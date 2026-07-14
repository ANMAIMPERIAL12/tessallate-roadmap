# Tessellate — Interactive Development Roadmap & Learning Guide

> **Privacy by mathematics. Trust by design.**
>
> An elegant, interactive engineering handbook and timeline detailing how to build Tessellate: a privacy-preserving collaborative analytics platform that runs SQL-like queries over combined datasets without ever exposing raw databases.

This web application serves as the **official interactive roadmap** for developers and security analysts to learn how Tessellate is engineered from research to production across 11 key phases.

---

## 🌟 Key Features

- **11 Modular Engineering Phases**: Traces progress from Phase 0 (Foundations and Threat Modeling) all the way to Phase 10 (Kubernetes telemetry stream visualizer).
- **Interactive SQL Simulator**: Compile and execute SQL queries (SUM, COUNT, AVG) inside a virtual compiler console, tracing the compilation DAG, mTLS routing, encryption (Microsoft SEAL), secure aggregation, and Differential Privacy noise addition.
- **Progress Tracking & Persistence**: Check off tasks in the interactive *Definition of Done* list. Toggles update progress bars globally and are stored persistently in the browser's `localStorage` (refreshes will not lose your progress).
- **Global Search Index**: Search instantly across phase titles, taglines, goals, tech stacks, or academic reading materials.
- **Interactive Architectural Diagrams**: Fluid inline vector SVGs showing dataflow and cryptographic boundaries for every single phase.
- **Curated Reading Library**: Includes links, reading times, and difficulty indicators for essential cryptographic papers, books, and official documentation.
- **Premium CyFocus Aesthetics**: Designed with responsive layouts, an active network-particle canvas background, glassmorphism cards, and subtle micro-animations.

---

## 🚀 How to Run

Because this project is built as a single, compiled, and self-contained static file, **no installations or build tools are required**.

### Option A: Local Execution (Offline)
1. Download the repository folder.
2. Double-click [index.html](index.html) to open it directly in any modern web browser.

### Option B: Hosting on GitHub Pages
You can host this roadmap instantly for free:
1. Push `index.html` to a public GitHub repository.
2. Go to **Settings > Pages**.
3. Under *Build and deployment*, set the branch to `main` and the folder to `/ (root)`.
4. Click **Save**. Within 1 minute, your site will be live at `https://<your-username>.github.io/<repo-name>/`.

---

## 📂 File Directory

- `index.html` - The complete interactive roadmap application (Vanilla JS + CSS).
- `description.txt` - Core Tessellate product architecture specification.
- `design.txt` - Graphic guidelines and brand personality documentation.
- `development-instructions.txt` - Step-by-step roadmap structure instructions.
- `README.md` - Project documentation.

---

## ⚙️ Technical Foundations Detailed in Roadmap

If you complete every phase in this roadmap, you will gain hands-on knowledge in:
- **Rust System Programming** (using Tokio, Axum, and SQLx)
- **gRPC Services & Mutual TLS (mTLS)** (using Tonic)
- **Homomorphic Encryption (HE)** (context parameter sets for Microsoft SEAL and OpenFHE)
- **Secure Multi-Party Computation (MPC)** (Additive secret sharing and MP-SPDZ evaluator structures)
- **Differential Privacy (DP)** (Laplace/Gaussian noise scaling algorithms)
- **Cryptographic Auditing** (Merkle Trees and Ed25519 signatures)
- **Cloud Orchestration** (multi-stage Docker containerization and Kubernetes namespaces)
