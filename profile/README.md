### VexelQuant Research Foundry
**Sub-25ms Specialized Small Language Models (1.5B–7B) & Deterministic JSON Execution Engines for Quantitative Crypto & Prediction Market Systems.**

VexelQuant designs, fine-tunes, and quantizes task-specific SLMs engineered to replace high-latency (~900ms+) external LLM APIs inside automated trading pipelines, Polymarket CLOB arbitrage bots, and autonomous on-chain agents.

#### Core Architecture Standards
| Metric / Layer | VexelQuant Standard | External Frontier APIs |
| :--- | :--- | :--- |
| **Inference Latency (Local GGUF / vLLM)** | **14ms – 28ms** | 850ms – 2,100ms |
| **JSON Schema Compliance** | **99.4%+ (GRPO Enforced)** | 91% – 96% |
| **Data Privacy & Strategy Leakage** | **100% Air-Gapped / Local** | Shared with third-party API hosts |
| **Marginal Cost per 1M Calls** | **$0.00 (Self-Hosted)** | $150 – $1,500+ |

#### Active Model Tracks (v1 Suite)
* **`Vexel-Catalyst-1.5B-v1`** — High-frequency breaking news & Telegram/X catalyst extraction to deterministic ticker JSON.
* **`Vexel-PolyArb-3B-v1`** — Polymarket resolution rule parsing & real-time probability delta estimation.
* **`Vexel-DeFiCaller-3B-v1`** — Zero-hallucination EVM (Base/Arbitrum) & Solana (Jupiter) RPC transaction payload generation.
* **`Vexel-RugShield-3B-v1`** — Sub-30ms Solidity/Rust smart contract honeypot & fee-manipulation triage.

#### Engineering & Evaluation Stack
Unsloth • PyTorch • TRL (GRPO/DPO) • llama.cpp (GGUF Q4_K_M / Q8_0) • vLLM • Outlines / Grammar-Constrained Decoding

*For bespoke LoRA/GRPO fine-tuning on proprietary trading logs and custom bot schemas: `founder@vexelquant.me`*
