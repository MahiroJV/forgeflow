# 🚀 ForgeFlow

> A visual CI/CD workflow generator that creates ready-to-use GitHub Actions pipelines based on your project type, language, framework, and deployment targets.

---

# 🧠 What is ForgeFlow?

ForgeFlow is a developer tool that helps developers generate CI/CD workflows without manually writing YAML files.

Instead of learning GitHub Actions syntax, users can:

* Select a programming language
* Select a framework
* Choose CI/CD features
* Pick deployment targets
* Generate production-ready workflow files instantly

The goal of YAMLForge is to simplify DevOps workflow creation while remaining flexible and scalable.

---

# ⚙️ Tech Stack

## Frontend

* Next.js
* TypeScript
* TailwindCSS
* shadcn/ui

## Backend

* Rust
* Axum
* Tokio
* Serde
* Tera

---

# 📁 Project Structure

```text
forgeflow/
├── frontend/                 # Next.js frontend
│   ├── app/
│   ├── components/
│   ├── lib/
│   └── styles/
│
├── backend/                  # Rust backend
│   ├── src/
│   │   ├── routes/
│   │   ├── core/
│   │   ├── services/
│   │   └── models/
│   │
│   ├── templates/
│   │   ├── rust/
│   │   ├── node/
│   │   ├── python/
│   │   └── java/
│   │
│   └── Cargo.toml
│
├── shared/
├── docs/
├── scripts/
└── README.md
```

---

# 🧱 How ForgeFlow Works

```text
User Selection
      ↓
Frontend Wizard (Next.js)
      ↓
API Request
      ↓
Backend (Axum)
      ↓
Template Engine
      ↓
Merge YAML blocks
      ↓
Generated Workflow
```

---

# 📦 Template System

YAMLForge uses a modular template system.

Templates are reusable CI/CD workflow blocks.

Example:

```text
templates/rust/
├── ci.yml
├── cd.yml
├── linux.yml
└── windows.yml
```

The backend dynamically merges templates based on user selections.

---

# 🚀 MVP Goals

The first version of YAMLForge will support:

## Languages

* Rust

## Frameworks

* Dioxus
* Tauri
* Axum

## Platforms

* Linux
* Windows

## Linux Outputs

* Raw binary
* AppImage

## Windows Outputs

* EXE

---

# 🎨 Planned Features

* Step-by-step workflow builder
* Live YAML preview
* Download generated workflows as ZIP
* Workflow graph visualization
* Multi-language support
* GitHub integration
* Template presets

---


# 🚀 Roadmap

## Phase 1 — Core Setup
- Rust backend (Axum)
- Next.js frontend
- Basic API connection

## Phase 2 — Generator Engine
- Template system
- YAML generator
- First working CI pipeline

## Phase 3 — UI Builder
- Step-by-step wizard
- Live preview
- Better UX

## Phase 4 — Multi-language Support
- Node.js templates
- Python templates
- Java templates

## Phase 5 — Advanced Features
- GitHub OAuth
- Repo import
- Smart suggestions
- Export ZIP

---

# 💡 Future Vision

ForgeFlow will evolve into a full DevOps automation platform for developers.

---


# 🔥 Key Design Principles

* Modular architecture
* Template-driven generation
* Easy extensibility
* Multi-language support
* Scalable backend design
* Clean developer experience

---

# 📌 License

MIT License
