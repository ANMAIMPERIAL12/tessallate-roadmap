# Tessellate — Interactive Development Roadmap & Learning Guide

👉 **[Launch the Live Interactive Web App](https://anmaimperial12.github.io/tessallate-roadmap/)**

Tessellate is a privacy-preserving collaborative analytics platform that enables organizations to execute analytical queries over combined datasets without sharing their raw records.

This repository hosts the **Interactive Development Roadmap & Engineering Handbook** for Tessellate. It is designed to walk you through the end-to-end development of the platform across 11 key engineering phases—from mathematical modeling to production deployment.

---

## 🚀 Live Link
You can open and interact with the guide directly in your browser:
**[https://anmaimperial12.github.io/tessallate-roadmap/](https://anmaimperial12.github.io/tessallate-roadmap/)**

---

## 🌟 Interactive Features to Explore

When you launch the web application, you can interact with several educational modules:

### 1. The 11-Phase Roadmap Timeline
- Scroll through the project lifecycle from **Phase 0** (foundations & threat models) to **Phase 10** (visualizers & Kubernetes).
- Click any phase card to open its **Chapter Guide**.

### 2. Detailed Chapter Panels
Each phase detail view features:
- **Central Question & Goal**: The core challenge and primary engineering outcome of that phase.
- **Workflow Steps**: Expandable accordion steps detailing the coding tasks.
- **Dataflow Diagrams**: Custom inline SVG charts representing the architectural layout.
- **Definition of Done Checklists**: Checkboxes that let you mark tasks complete. Your progress is synced to `localStorage` and dynamically updates the progress bar on the dashboard.
- **Learning Resources**: Direct link cards to official manuals, books, and scientific research papers.
- **Gantt Charts**: Estimated timeline breakdowns for research, coding, testing, and documentation.

### 3. Query Compilation Simulator
- Select from preset PostgreSQL dialect queries (SUM, COUNT, AVG).
- Click **Execute Secure Computation Plan** to watch the simulator run.
- Trace how queries are validated, compiled into an execution DAG, encrypted, homomorphically combined, and perturbed using **Differential Privacy** to yield a secure output.

### 4. Global Search
- Use the search bar in the top navigation to instantly query phases, technologies (e.g. *Rust*, *mTLS*, *SEAL*), reading resources, or deliverables.

---

## 📂 Repository Structure

- `index.html` - The complete, self-contained single-page application.
- `description.txt` - Architectural definitions of the Tessellate core engine.
- `design.txt` - Brand visual identity and aesthetic guidelines.
- `development-instructions.txt` - Roadmap content guidelines.
- `README.md` - This user guide.
