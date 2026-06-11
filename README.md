# Hey there, I'm Martin 👋

I'm a full-stack Software Engineer based in New York, building production web and mobile products in **TypeScript/React** and **Node.js**, with a focus on **AI integration** — LLM APIs behind real guardrails, plus self-hosted model infrastructure. Before going independent, I spent 6+ years at a Fortune 500 insurer working on Python services powering AI-driven OCR at scale.

I'm currently leading development on **KODA**, an LMS platform for scholastic esports, and **Ledes**, a category-selective mobile microblogging app.

---

### Programming Languages and Technologies 💻

| Category | Tools |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript (ES6+), Python, SQL, PHP |
| **Mobile & Frontend** | React 19, React Native (Expo), Tailwind CSS, Vite |
| **Backend & DB** | Node.js (Express 5), PostgreSQL, Firebase (Firestore/Auth/Functions) |
| **AI** | Anthropic Claude & Google Gemini APIs, LLM guardrails (auth gating, rate limiting, prompt-injection sanitization), self-hosted LLMs (Ollama), MCP |
| **DevOps & Security** | GitHub Actions (CI/CD), Docker, NVIDIA CUDA, Tailscale, JWT, bcrypt, Vercel |

---

### Key Projects 🚀

#### 🎮 KODA — Scholastic Esports LMS
*React 19, TypeScript, Firebase, Google Gemini*
An LMS for K–12 scholastic esports programs, designed for an addressable market of 700+ Title I schools in NYC.
- **🤖 KODA Coach:** an in-app AI assistant on the Gemini API via a Firebase callable function — with auth gating, rate limiting, prompt-injection input sanitization, and per-user context injection
- **⚙️ Features:** real-time bracket engine (single/double elimination + round-robin), role-based access control (Student/Coach/Recruiter)
- **🔒 Compliance:** built to FERPA and COPPA standards, with guardian-review gates for student-recruiter messaging

#### 📱 Ledes — Category-Selective Microblogging
*React Native (Expo), TypeScript, Node.js, PostgreSQL*
A social mobile app with a novel "lede" system: followers subscribe to specific content buckets (e.g., Tech vs. Sports) per creator.
- **📚 Stack:** React Native 0.81 (Expo), TypeScript 5.9, Express 5, PostgreSQL
- **🎀 Features:** category-selective following, gesture-driven UI (Reanimated), JWT auth with silent token refresh
- **🛠️ Engineering:** 18-endpoint REST API, comprehensive validation, optimistic UI updates, full-text search

#### 🖥️ Hermes — Self-Hosted LLM Stack (Deployment & Ops)
*Ollama, Docker, NVIDIA CUDA, Tailscale*
Deployed and operate a self-hosted Qwen3-8B (64k context) via Ollama, alongside a Dockerized ComfyUI/SDXL image-generation service with CUDA GPU passthrough on a remote box.
- **⚡ GPU ops:** shared-VRAM management (model eviction before image gen) and per-request latency budgets
- **🚀 Deploys:** idempotent phased deploys (preflight → build → smoke → integrate) with automatic rollback
- **🔐 Access:** Tailscale (WireGuard) mesh VPN — zero port-forwarding — wired into a Discord bot via an `/imagine` command

---

### Engineering Impact 📈

> [!IMPORTANT]
> My primary current work (KODA and Ledes) lives in private repositories — happy to walk through the projects anytime.

* **KODA:** 110+ PRs merged with CI/CD via GitHub Actions + Firebase, including zero-downtime preview environments
* **Ledes:** 18-endpoint REST API with JWT auth, silent token refresh, and category-selective subscriptions
* **Previously:** 6+ years at a Fortune 500 insurer — optimized the Python services powering Hyperscience (AI-driven OCR), eliminating 75% of manual data entry

---

### Contact Me 📬

- **Location:** New York, NY
- **LinkedIn:** [mr-martinsosa](https://www.linkedin.com/in/mr-martinsosa/)

---

### Tech Stack & Tools 🛠️

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
![Google Gemini](https://img.shields.io/badge/google_gemini-8E75B2?style=for-the-badge&logo=google-gemini&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
