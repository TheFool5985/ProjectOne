# Contributing [Placeholder]

Thanks for your interest in contributing! This guide explains how to set up the project locally, make changes, and open a pull request.

## Code of Conduct
By participating, you agree to follow our Code of Conduct: see `CODE_OF_CONDUCT.md` (or be respectful, collaborative, and professional).

---

## Project Structure
This repo is a monorepo with two main apps:

- `frontend/` — Vite-based web UI
- `backend/` — FastAPI API (uses `uv` for Python package management)

> If your folders are named differently, update this section to match your repo.

---

## Getting Started

### Prerequisites
- Git
- Node.js (LTS recommended) + npm (or pnpm/yarn if the repo uses it)
- Python 3.11+ (or whatever `backend` targets)
- `uv` installed for backend dependency management

### Clone
```bash
git clone <your-fork-url>
cd <repo>
