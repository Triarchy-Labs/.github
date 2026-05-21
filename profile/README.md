<!-- Header -->
<div align="center">
  <img src="./header.svg" width="100%" alt="Triarchy Labs" />
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000?style=flat-square&logo=rust&logoColor=fff" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=fff" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=fff" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=fff" />
  <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=fff" />
  <img src="https://img.shields.io/badge/Tauri_v2-FFC131?style=flat-square&logo=tauri&logoColor=000" />
  <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=fff" />
  <img src="https://img.shields.io/badge/Three.js-000?style=flat-square&logo=three.js&logoColor=fff" />
  <img src="https://img.shields.io/badge/WebGPU-005C8A?style=flat-square&logo=webgl&logoColor=fff" />
  <img src="https://img.shields.io/badge/WASM-654FF0?style=flat-square&logo=webassembly&logoColor=fff" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Soroban-000?style=flat-square&logo=stellar&logoColor=fff" />
  <img src="https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=fff" />
  <img src="https://img.shields.io/badge/Cosmos_SDK-2E3148?style=flat-square&logo=cosmos&logoColor=fff" />
  <img src="https://img.shields.io/badge/Foundry-1C1C1C?style=flat-square&logo=ethereum&logoColor=fff" />
  <img src="https://img.shields.io/badge/Extism-1a1a2e?style=flat-square&logo=webassembly&logoColor=fff" />
  <img src="https://img.shields.io/badge/Ollama-000?style=flat-square&logo=ollama&logoColor=fff" />
  <img src="https://img.shields.io/badge/ROCm-ed1c24?style=flat-square&logo=amd&logoColor=fff" />
  <img src="https://img.shields.io/badge/Tree--sitter-4B9CD3?style=flat-square&logo=treehouse&logoColor=fff" />
  <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=fff" />
  <img src="https://img.shields.io/badge/Hyprland-58E1FF?style=flat-square&logo=wayland&logoColor=000" />
</p>

---

### [ WHO WE ARE ]

Small team of engineers who operate across the full spectrum — protocol security, native desktop apps, WebGL frontends, knowledge graphs, and low-level Linux infrastructure. We audit DeFi protocols for a living, build research tooling because nothing off-the-shelf fits our workflow, and ship native Rust binaries because Electron is bloat.

We run Arch btw.

---

### [ WHAT WE BUILD ]

<br>

#### /// CORE — Security, Infrastructure, Payments

**Security Research** — We audit smart contracts across Solana, Stellar/Soroban, EVM, Cosmos, and XRP Ledger. Active on Cantina, Code4rena, Sherlock, and Immunefi. Our custom SAST tooling (ABLS) runs a 13-phase pipeline with 27 integrated scanners — Mythril, Echidna, Slither, and LLM-powered business logic analysis. Findings submitted against protocols managing $50M+ in TVL.

**Native Desktop & Sovereign Infrastructure** — Our main platform ships as a Tauri v2 binary with WebGPU rendering, local WASI 0.2 runtime, and zero Chromium overhead. Execution model built around Extism WASM sandboxing for task isolation — microsecond cold starts instead of Docker containers. We write our own systemd watchdogs.

**x402 Agentic Payments on Stellar** — Sovereign gateway for autonomous micropayments on Soroban. Live agent registry with reputation scoring, zero-trust payload quarantine, replay protection, and budget enforcement. Currently the only implementation with a WASM-based trust layer between payment verification and task execution.

<br>

#### /// RESEARCH — AI, Graphs, Reconnaissance

**AI & Local Inference** — Self-hosted LLM infrastructure on AMD ROCm (no CUDA dependency). Custom quantization pipelines, vLLM serving, Ollama orchestration, multi-model routing through OpenRouter. GLiNER for zero-hallucination entity extraction on industrial and scientific documents. Built an ARC-AGI solver prototype because we wanted to understand the benchmark instead of just throwing compute at it.

**Knowledge Graphs & Research Tooling** — Custom graph engine (Crucible) for codebase intelligence, NER extraction via GLiNER, hypergraph synthesis for cross-domain pattern recognition. We built our own OSINT reconnaissance toolkit, bounty radar, and code review pipeline because we got tired of context-switching between 15 different tabs.

**Multi-Agent Task Orchestration** — Custom orchestration framework with persistent cross-session memory, skill-based routing across 97 domain modules, and interrupt-resume checkpointing. Three specialized execution modes (strategy, implementation, research) coordinated through a shared knowledge graph and SQLite-backed message broker. CI/CD pipeline for cognitive work instead of builds.

<br>

#### /// CREATIVE — WebGL, Commerce, Immersive Interfaces

**Creative Engineering** — Lusion-grade WebGL pipelines. GPGPU particle systems, custom GLSL fluid dynamics shaders, React Three Fiber scene graphs, Theatre.js animation rigs. We build immersive 3D interfaces for protocol dashboards because terminals shouldn't be the only option.

**Industrial Intelligence & E-commerce** — TMiK Intelligence Suite for Rosatom — graph-based industrial product analytics with 8-dimension data ingestion from patents, academic papers, and material databases. Polundra seafood marketplace. Tangiers HoReCa AI pipeline. We don't limit ourselves to crypto — if it needs an engineering team, we're interested.

**Prediction Markets & Quantitative Infrastructure** — Polymarket CLOB integration with delta-neutral grid strategies. Custom extractors for market discovery, order book parsing, and position management. Prediction markets as another protocol to audit and build on top of.

<br>

#### /// TOOLING — Automation, MCP, Browser Ops

**Custom MCP Protocol Servers** — Model Context Protocol servers from scratch: AST-based code intelligence with Tree-Sitter parsing, persistent knowledge graph memory with FTS5 search, and cross-session state management. Not wrappers around existing APIs — standalone Rust/TypeScript services we use daily.

**Stealth Browser Automation** — Custom DOM-to-Tree ingestion engine with iframe-piercing, anti-fingerprint headers, and headless Chromium orchestration. Built for reconnaissance and data extraction at scale without triggering bot detection. Faster than Playwright, more configurable than Puppeteer.

**Automation & Internal Tooling** — Bounty radar scraping Cantina, Code4rena, Sherlock, Immunefi, and OnlyDust in real-time. n8n workflow orchestration for CI/CD, Telegram alerting, and automated triage. Everything runs on Arch Linux with Hyprland and custom Lua configs.

**Hackathon Track Record** — Active on DoraHacks, Stellar Hacks (x402 Agents), FlagOS Open Computing (Auto Data Annotation), AI Trading Agents ($55K pool). Hackathons as forcing functions for shipping production-grade prototypes under pressure, not weekend toys.

---

### [ ACTIVE PROJECTS ]

| Project | Stack | Status |
| :--- | :--- | :--- |
| **x402 Arbitrage Mesh** | TypeScript, Next.js, Soroban, WASM | [Live](https://x402-arbitrage-mesh.vercel.app) |
| **ExoSuit Mark 53** | Rust, Tauri v2, WebGPU | In development |
| **ABLS** | Python, Rust — 13-phase audit pipeline, 27 tools | In development |
| **Crucible Graph** | Rust, KuzuDB — codebase intelligence engine | In development |
| **Bounty Radar** | TypeScript, n8n — real-time bounty triage | Internal |
| **TMiK Intelligence Suite** | Next.js, KuzuDB, GLiNER — industrial 8D analytics | Deployed |
| **OmniVault** | TypeScript — multi-chain wallet aggregator | In development |
| **Autonomous Node** | Rust — multi-model LLM routing, sentinel isolation | In development |

> Most repos are currently private while we harden the security layer. Reach out if you want access.

---

### [ AUDIT COVERAGE ]

```
ECOSYSTEM              TOOLS                           PROTOCOLS REVIEWED
-------                -----                           ------------------
Solana / Anchor        Mythril, Slither, Echidna       Perena, Pump.fun
Stellar / Soroban      Foundry, Heimdall, custom       K2 Lending, Monetrix
EVM / Uniswap V4      CodeQL, AFL++, Semgrep          Revert Finance, Morpho
Cosmos / CometBFT      Go vet, custom Go analyzer      QBTC Bridge
XRP Ledger             rippled source audit            SponsorshipSet
```

---

### [ ARCHITECTURE ]

<div align="center">
  <img src="./architecture.svg" width="100%" alt="Triarchy Architecture" />
</div>

---

### [ LINKS ]

- [x402 Sovereign Gateway](https://x402-arbitrage-mesh.vercel.app) — live agent mesh with real-time dashboard
- [Architecture Demo](https://youtube.com/watch?v=tA33OansnaQ) — 2-min walkthrough
- [@mod_minimal](https://x.com/mod_minimal) on X

<!-- Footer -->
<div align="center">
  <img src="./footer.svg" width="100%" alt="" />
</div>
