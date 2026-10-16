# ⚡ Systems, Cryptography & Computational Geometry Engineer

**Rust • Python (FastAPI / Asyncio) • TypeScript (2D/3D CAD & Spatial Solvers) • Solana / Stellar / ZK-SNARKs**

[![Hire Me](https://img.shields.io/badge/Hire_Me-$10--$150_Fast_Turnaround-00C853?style=for-the-badge)](mailto:duongynhi000001@gmail.com)
[![Flagship Tool](https://img.shields.io/badge/Flagship_Release-Crypto_%26_Bounty_Tax_OS_v1.0-3B82F6?style=for-the-badge)](https://github.com/duongynhi000005-oss/deeptech-crypto-tax-and-pnl-engine/releases/tag/v1.0.0)

---

## 🛠️ Available for Rapid Engineering & Consulting ($10 – $150 Fixed Scope)

I specialize in **hard systems & algorithmic engineering problems** with deterministic unit/regression test coverage and 1–24 hour turnaround:

- **⚡ Flash Bug Fixes & CI Test Rescue ($10 – $25, 1–3h Turnaround):** Fixing race conditions in Python `asyncio`/FastAPI WebSockets, TypeScript/Node.js pipelines, Docker/Helm builds, or failing `pytest` / `bun test` / `cargo test` suites.
- **🕸️ Anti-Bot Web Scraping & Data Pipelines ($15 – $50):** High-concurrency Playwright / Python `httpx` scrapers, webhook fanout, and automated multi-sheet Dark-Mode Excel (`openpyxl`) + JSON/CSV reporting.
- **🦀 Deep-Tech Systems, CAD/Geometry & Web3 ($50 – $150):** 2D/3D spatial indexing, A* pathfinding, KiCad/Gerber CAD compilers, Rust Groth16/R1CS zero-knowledge circuits, and Solana/Stellar smart contracts.

📫 **Direct Contact:** [`duongynhi000001@gmail.com`](mailto:duongynhi000001@gmail.com) — *PayPal, Stripe, or USDC / USDT / SOL / XLM accepted (pay after seeing working proof/test output).*

---

## 🏆 Featured Open-Source Pull Requests (25+ Live Deep-Tech PRs)

### 1. High-Concurrency Python & Real-Time AI Audio Backends (`BasedHardware/omi` — 13.7k+ ⭐, YC-Backed)
- **[BasedHardware/omi#21813](https://github.com/BasedHardware/omi/pull/21813):** `fix(listen): isolate reconnect and prepare rollover finalizations` — Fixed WebSocket listen-session coroutine lifecycle and transcript rollover race conditions.
- **[BasedHardware/omi#21810](https://github.com/BasedHardware/omi/pull/21810):** `fix(integrations): guard nested context filters and non-string webhook fields` — Hardened real-time webhook fanout and vector memory filtering pipelines.

### 2. 2D/3D Computational Geometry, A* Autorouting & CAD Compilers (`tscircuit` — YC-Backed)
- **[tscircuit/core#4677](https://github.com/tscircuit/core/pull/4677):** `fix(autorouting): prevent MultilayerIjump overshoot when wallDistance is Infinity (#4585)` — Fixed open-corridor goal overshoot in multilayer A* jump-point pathfinding.
- **[tscircuit/core#4676](https://github.com/tscircuit/core/pull/4676):** `fix(obstacles): keep small polygon and circular cutouts in routing obstacles` — Preserved sub-millimeter polygon and circular board cutouts during spatial obstacle generation.
- **[tscircuit/core#4675](https://github.com/tscircuit/core/pull/4675):** `fix(autorouting): prevent escaped pads from retaining remote connection point IDs in withFixedTraces` — Fixed `TopologyMergingSolver` crash when combining saved fanout paths with `routeRemaining`.
- **[tscircuit/core#4674](https://github.com/tscircuit/core/pull/4674):** `fix(autorouting): avoid duplicating breakout-covered ports as plane-terminated traces` — Fixed dogbone fanout solver crash on copper-poured nets.
- **[tscircuit/circuit-json-to-kicad#657](https://github.com/tscircuit/circuit-json-to-kicad/pull/657):** `fix(pcb): support rounded rect pcb_cutout corner_radius and standalone cutouts on Edge.Cuts` — Added rounded-rectangle corner arc approximation and standalone `Edge.Cuts` export.
- **[tscircuit/circuit-json-to-kicad#656](https://github.com/tscircuit/circuit-json-to-kicad/pull/656):** `fix: use KiCad 9 layer ordinals and populate placed symbol Footprint (#633)` — Fixed EasyEDA Pro S-expression import compatibility for KiCad 9 exports.
- **[tscircuit/circuit-json-to-kicad#655](https://github.com/tscircuit/circuit-json-to-kicad/pull/655):** `fix(pcb): derive SMD pad paste and mask layers from circuit-json (#638)` — Derived accurate `F.Paste`/`B.Paste` and `F.Mask`/`B.Mask` layers from `pcb_solder_paste` records.
- **[tscircuit/circuit-json-util#242](https://github.com/tscircuit/circuit-json-util/pull/242):** `fix: include PCB note and fabrication note stroke and label geometry in range selection` — Added stroke-width and rotated text bounding-box math for spatial range queries.
- **[tscircuit/circuit-json-schematic-placement-analysis#297](https://github.com/tscircuit/circuit-json-schematic-placement-analysis/pull/297):** `fix: detect component reference and value text crossing schematic section dividers` — Implemented label bounding-box intersection checks against schematic section dividers.

### 3. Rust Cryptography, ZK-SNARKs (`Groth16` / `R1CS`) & Distributed Bridges (`paraloom-labs`)
- **[paraloom-labs/paraloom-core#942](https://github.com/paraloom-labs/paraloom-core/pull/942):** `fix(privacy): enforce R1CS C-matrix satisfaction in CircomReduction/prover and harden circuit/tx bounds` — Patched critical Groth16 R1CS soundness hole (`A(z) ∘ B(z) = u · C(z) + h(z)t(z)`), enforced booleanity gates, and bound public inputs to transaction proofs.
- **[paraloom-labs/paraloom-core#945](https://github.com/paraloom-labs/paraloom-core/pull/945):** `fix(bridge): enforce canonical migrated validator/registry layouts and harden co-sign assembly` — Enforced $2/3+1$ quorum checks, distinct validator pubkey verification, and non-zero withdrawal destination guards.
- **[paraloom-labs/paraloom-core#947](https://github.com/paraloom-labs/paraloom-core/pull/947):** `fix(program): atomic Merkle pair append, vault self-withdrawal guard, slash event and unbonding checks` — Hardened Solana BPF withdrawal/deposit Merkle tree state transitions.
- **[paraloom-labs/paraloom-wallet#79](https://github.com/paraloom-labs/paraloom-wallet/pull/79):** `fix(transact): persist and reconcile pending spends and handle deposit leaf-index lag` — Implemented atomic crash-safe WAL persistence for privacy wallet nullifiers.

### 4. Compilers, Static Analysis & Cloud Infrastructure
- **[limitlessprojects/Go-Hybrid#306](https://github.com/limitlessprojects/Go-Hybrid/pull/306) & [#254](https://github.com/limitlessprojects/Go-Hybrid/pull/254):** Linear/affine ownership borrow-checker (`hy-check`) control-flow and loop back-edge analysis.
- **[OphirPay/OphirPay#1567](https://github.com/OphirPay/OphirPay/pull/1567) & [#1566](https://github.com/OphirPay/OphirPay/pull/1566):** Multi-stage Docker build-arg injection and Helm chart secret template hardening.

---

## 📦 Flagship Open-Core Tool: [Deep-Tech Crypto, DeFi & Freelance Tax Engine](https://github.com/duongynhi000005-oss/deeptech-crypto-tax-and-pnl-engine)

- **Zero-Dependency Python 3 CLI (`reconcile_cli.py`):** Ingests multi-platform CSV exports (PayPal, Stripe, Algora, Solana, Stellar, EVM), deduplicates via SHA-256 fingerprinting, computes **FIFO & LIFO** realized capital gains, and generates Markdown/JSON/CSV audit reports in `<50ms`.
- **5-Sheet Obsidian Dark-Mode Excel OS (`Freelance_Bounty_Crypto_Tax_OS_Pro.xlsx`):** Automated formulas, KPI cards, and embedded charts.
- 👉 **[Download Release v1.0.0 (.zip & .xlsx)](https://github.com/duongynhi000005-oss/deeptech-crypto-tax-and-pnl-engine/releases/tag/v1.0.0)**
