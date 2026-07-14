# Shiva (TIRUNARA)

<p align="center">
  <img src="https://raw.githubusercontent.com/TIRUNARA/TIRUNARA/main/pixel_banner.svg" alt="pixel art banner" width="800"/>
</p>

<p align="center">
  <a href="https://github.com/TIRUNARA">
    <img src="https://readme-typing-svg.demolab.com?font=Outfit&size=22&duration=3000&pause=1000&color=47A1F2&center=true&vCenter=true&width=500&lines=Computer+Science+Student;Building+Agentic+Systems;Workflow+Automation+%26+DAG+Engines;Low-Level+Linux+%26+Systems+Programming" alt="Typing SVG" />
  </a>
</p>

---

## About Me

I'm a computer science student focused on building agentic systems, workflow automation engines, and interactive tools. I work close to the metal — Linux, async runtimes, process orchestration — and spend most of my time designing systems that can operate independently.

- **Currently building**: [Integris](https://github.com/TIRUNARA/integris) — an n8n-style visual DAG workflow engine with a TypeScript runtime, SQLite telemetry, and a React Flow canvas editor built inside a custom VSCodium shell.
- **AI & Agents**: Architecting multi-agent workflows using the Model Context Protocol (MCP), autonomous Jules bot CI pipelines, and a custom LLM routing service.
- **Platform**: Linux Mint — custom daemon automation, PipeWire audio, socket telemetry, and scripted dev workflows.
- **Games & Graphics**: Building shaders and 3D simulations in Godot 4.x as a side track.

---

## Tech Stack

<div align="center">

| Category | Badges |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat-square&logo=c%2B%2B&logoColor=white) ![GDScript](https://img.shields.io/badge/GDScript-478CBF?style=flat-square&logo=godot-engine&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black) ![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=flat-square&logo=gnu-bash&logoColor=white) |
| **AI & APIs** | ![Model Context Protocol](https://img.shields.io/badge/MCP-Protocol-orange?style=flat-square) ![Claude API](https://img.shields.io/badge/Claude-Anthropic-8a2be2?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI-SDK-brightgreen?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) |
| **Infrastructure** | ![Linux Mint](https://img.shields.io/badge/Linux_Mint-87CF3E?style=flat-square&logo=linux-mint&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat-square&logo=git&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=flat-square&logo=sqlite&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=flat-square&logo=vite&logoColor=white) |

</div>

---

## Active Projects

### ⚙️ Integris — Visual Workflow Automation Engine
A production-grade n8n-style DAG execution platform built from scratch.

- **Runtime**: TypeScript monorepo (`pnpm` workspaces) with a zone-partitioned hybrid scheduler — static zones run in topological order, dynamic zones (code sandbox, CLI, LLM) yield to the event loop for true concurrency.
- **Node Registry**: 9 built-in nodes — `start`, `json-transform`, `httpRequest`, `codeSandbox` (JS + Python sandboxed execution), `parallelSplit`, `router`, `loop`, `databaseQuery`, `legacyCli`.
- **Telemetry**: SQLite-backed `SQLiteLogger` capturing full run/step/log history with WAL journaling and a `ContextBus` for cross-node shared state with TTL.
- **Editor**: React Flow visual canvas compiled as a VSCodium webview extension with real-time WebSocket live-sync.
- **Test Coverage**: 18 engine unit tests + WebSocket/HTTP integration tests, all passing.

### 🤖 Integrity Vault & AI Workflow
A versioned engineering workspace managed with a session-aware AI co-engineer (Integrity) running on Gemini.

- Autonomous task delegation via Google Jules bot with GitHub Actions CI.
- Custom LLM routing service (`integrity_router_service.py`) for model selection and request interception.
- Session handover protocol for zero-memory-loss continuity across sessions.

### 🎮 Godot 3D & Graphics
Custom GLSL/GDScript shaders and physics-driven simulations in Godot 4.x.

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=TIRUNARA&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TIRUNARA&layout=compact&theme=radical&hide_border=true" alt="Top Languages" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=TIRUNARA&theme=radical&hide_border=true" alt="GitHub Streak" />
</p>

---

## Contact

- **Email**: [tiirruu@gmail.com](mailto:tiirruu@gmail.com)
- **GitHub**: [github.com/TIRUNARA](https://github.com/TIRUNARA)

<p align="center">
  <sub><i>"The best way to predict the future is to compile it."</i> — Integrity Terminal</sub>
</p>
