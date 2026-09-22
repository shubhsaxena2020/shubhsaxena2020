# Hi, I'm Shubh Saxena

**Full-Stack & AI Systems Developer** — React . TypeScript . Python . Node.js — RAG, LLM Agents & MCP

[![Portfolio](https://img.shields.io/badge/Portfolio-shubhbuilds.com-000000?style=for-the-badge)](https://shubhbuilds.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubh-saxena2020)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shubh.saxena2020@gmail.com)
![Open to Work](https://img.shields.io/badge/Open%20to%20Work-success?style=for-the-badge)

## About Me

I design and ship production-shaped software end to end, full-stack web applications and AI infrastructure alike, as an independent developer working with an AI-directed engineering workflow: I architect the system and write the specification, then direct coding agents to implement against it, reviewing and verifying every change before it ships. Based in Kanpur, India. Open to full-time, contract, and remote opportunities.

**Currently building:** multi-tenant RAG infrastructure, a local-first AI knowledge-graph desktop app, and developer-productivity tooling for AI-agent workflows.

🔭 **Focus areas:** Retrieval-Augmented Generation (RAG), LLM agent orchestration, and the Model Context Protocol (MCP)

🛠️ **Full-stack:** React, TypeScript, Node.js, Python, FastAPI, Electron

🧠 **AI/ML infrastructure:** vector search (Qdrant), hybrid retrieval and reranking, RBAC and encryption for multi-tenant systems

🎓 **Education:** BCA (Computer Science), PSIT Kanpur, affiliated to Kanpur University (CSJMU)

📥 **Reach me:** shubh.saxena2020@gmail.com

## Tech Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![NodeJS](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Featured Projects

### multi-tenant-rag — Production-Shaped Multi-Tenant RAG Service
Repository: https://github.com/shubhsaxena2020/multi-tenant-rag

A self-hostable Retrieval-Augmented Generation template built to run in production, not as a toy demo. Per-tenant Qdrant collection isolation makes cross-tenant reads impossible at the storage layer; retrieval is hybrid dense+sparse fused with Reciprocal Rank Fusion and re-scored by a cross-encoder reranker; data is sealed at rest with AES-GCM envelope encryption; access is governed by document-level RBAC; ingestion runs async with a pollable job queue; an offline evaluation harness reports hit-rate, MRR, and nDCG; and a Prometheus/Grafana stack gives full observability. The test suite runs the entire pipeline end to end deterministically offline with zero model downloads. 145+ commits, 5 tagged releases, Python and TypeScript client SDKs.

Stack: FastAPI, Qdrant, Redis, SQLAlchemy, Docker Compose, Prometheus, Grafana

### cortex — Local-First AI Knowledge Graph (Desktop App)
Repository: https://github.com/shubhsaxena2020/cortex

An Electron + React + TypeScript desktop app that turns notes and AI conversation history into a searchable, visual knowledge graph that never leaves the device. A WebGL renderer (Sigma.js + Graphology) handles large graphs smoothly; hybrid vector and full-text search (sqlite-vec + FTS5, local embeddings via Ollama) finds relevant memories fast; a three-signal system (tag overlap, keyword match, embedding similarity) auto-generates semantic edges between related memories; and a built-in MCP server exposes 11 tools so any MCP-compatible AI agent can read and write the graph directly. 465 passing tests across 6 shipped minor releases.

Stack: Electron, React, TypeScript, better-sqlite3, sqlite-vec, Ollama, Sigma.js

### furniture-3d-viewer — Photo-to-3D Pipeline for E-Commerce
Repository: https://github.com/shubhsaxena2020/furniture-3d-viewer

Turns a handful of ordinary furniture photos into an interactive, textured 3D model rendered in the browser. A multi-view photogrammetry pipeline (COLMAP + OpenCV) reconstructs 20K to 50K face meshes with PBR material estimation and multi-view texture transfer; a FastAPI backend automates upload and processing with real-time progress; and a Three.js frontend renders the result with live color and material customization plus GLB/OBJ export. Evaluated as a white-label commercial concept for furniture retailers.

Stack: Python, FastAPI, OpenCV, pycolmap, Three.js

### ai-tools-monitor — Windows Tray App for AI-Agent Fleets
Repository: https://github.com/shubhsaxena2020/ai-tools-monitor

A native Windows 11 tray application that gives live status and real usage data for five concurrent AI coding CLIs at once: Claude Code, Codex CLI, Hermes, OpenCode, and Antigravity. Built for developers running multiple autonomous coding agents in parallel who need a single at-a-glance operations view.

Stack: C#, WinForms

### multi-ai-framework — Verification-First Multi-Agent Delegation
Repository: https://github.com/shubhsaxena2020/multi-ai-framework

A Claude Code skill that delegates deep engineering work across four different coding agents, Codex, OpenCode, Hermes, and Antigravity, under a verification-first protocol, so work produced autonomously is checked before it is trusted rather than assumed correct.

Stack: TypeScript, CLI tooling

### llm-fallback-chains — Reliability Engineering for AI CLIs
Repository: https://github.com/shubhsaxena2020/llm-fallback-chains

Automatic multi-provider fallback for AI coding CLIs, Hermes, Qwen Code, OpenCode, and Goose, using native provider chains where the CLI supports them and wrapper scripts where it doesn't. Built and verified against a real production relay outage rather than a simulated one.

Stack: Shell

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=shubhsaxena2020&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shubhsaxena2020&layout=compact&theme=tokyonight&hide_border=true)

## Let's Connect

Portfolio: https://shubhbuilds.com  ·  LinkedIn: https://www.linkedin.com/in/shubh-saxena2020  ·  Email: shubh.saxena2020@gmail.com
