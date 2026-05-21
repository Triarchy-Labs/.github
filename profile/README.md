<!-- Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:151515,100:005C8A&height=220&section=header&text=Triarchy%20Labs&fontSize=65&fontColor=ffffff&fontAlignY=38&desc=Protocol%20Engineering%20%C2%B7%20Web3%20Security%20%C2%B7%20Autonomous%20Agents&descAlignY=58&descAlign=50" />
</div>

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Tauri_v2-FFC131?style=for-the-badge&logo=tauri&logoColor=black" />
  <img src="https://img.shields.io/badge/WebGPU-005C8A?style=for-the-badge&logo=webgl&logoColor=white" />
  <img src="https://img.shields.io/badge/WASM_WASI_0.2-1F2328?style=for-the-badge&logo=webassembly&logoColor=white" />
  <img src="https://img.shields.io/badge/Soroban-000000?style=for-the-badge&logo=stellar&logoColor=white" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" />
</p>

---

### What we do

We build infrastructure for autonomous agent networks on Stellar. The kind where agents discover tasks, execute them inside WASM sandboxes, get paid via Soroban smart contracts, and nobody has to trust anybody.

Our current focus areas:
- **Zero-trust execution** via Extism WASI 0.2 sandboxing (microsecond cold starts, no filesystem/network access)
- **x402 agentic payments** on Stellar/Soroban with replay protection and budget enforcement
- **Native desktop agents** on Tauri v2 with WebGPU rendering (zero Chromium overhead)
- **Agent reputation and quarantine** systems for mesh networks

---

### Active projects

| Project | What it does | Status |
| :--- | :--- | :--- |
| **x402 Arbitrage Mesh** | Sovereign gateway for x402 agent payments. Live dashboard, agent registry, bounty board, WASM quarantine. | [Live](https://x402-arbitrage-mesh.vercel.app) |
| **ExoSuit Mark 53** | Tauri v2 native desktop agent with WebGPU Liquid Glass rendering and local WASI 0.2 runtime. | In development |
| **Autonomous Node** | Standalone Rust agent with OpenRouter LLM routing and sentinel-level process isolation. | In development |
| **Health Monitor** | Node telemetry, heartbeat checks, and systemd-level watchdog for agent uptime. | In development |

> Most repos are currently private while we harden the security layer. Reach out if you want access.

---

### Architecture

<div align="center">
  <img src="./architecture.svg" width="100%" alt="Triarchy Architecture" />
</div>

---

### Links

- [Live Platform](https://x402-arbitrage-mesh.vercel.app) — sovereign agent gateway with real-time dashboard
- [Architecture Demo](https://youtube.com/watch?v=tA33OansnaQ) — 2-min walkthrough
- [@mod_minimal](https://x.com/mod_minimal) on X

<!-- Footer -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:005C8A,100:151515&height=80&section=footer" />
</div>
