<h1 align="center">Abdel</h1>
<p align="center"><strong>Head of Applied AI &amp; Verifiable Intelligence — StarkWare</strong></p>
<p align="center">World models · AI safety · verifiable computation.<br/>
Closing the gap between what autonomous systems <em>claim</em> and what can be <em>proven</em>.</p>

<p align="center">
  <a href="https://x.com/AbdelStark"><img src="https://img.shields.io/badge/@AbdelStark-000000?style=for-the-badge&logo=x&logoColor=white" alt="X / Twitter"></a>
  <a href="https://huggingface.co/abdelstark"><img src="https://img.shields.io/badge/🤗-Hugging%20Face-000000?style=for-the-badge" alt="Hugging Face"></a>
  <a href="https://www.linkedin.com/in/0xabdelstark/"><img src="https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://orcid.org/0009-0006-9640-9194"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://hackmd.io/@AbdelStark"><img src="https://img.shields.io/badge/Writing-HackMD-111111?style=for-the-badge" alt="Writing"></a>
</p>

<p align="center">
  <a href="https://starkware.co"><img src="https://img.shields.io/badge/StarkWare-Current-4C6FFF?style=for-the-badge" alt="StarkWare"></a>
  <a href="https://eips.ethereum.org/EIPS/eip-1559"><img src="https://img.shields.io/badge/EIP--1559-Co--author-6C47FF?style=for-the-badge" alt="EIP-1559"></a>
</p>

---

## What I do

- Co-author and technical champion of **[EIP-1559](https://eips.ethereum.org/EIPS/eip-1559)** — the fee-market mechanism now securing Ethereum mainnet.
- **Head of Applied AI & Verifiable Intelligence at [StarkWare](https://starkware.co)** — applying STARK proofs to AI integrity, inference, and settlement.
- Former **Ethereum protocol engineer** (ConsenSys / PegaSys). 15+ years shipping production systems across payments, embedded security, cryptography, and blockchain.
- Originated **[Kakarot](https://github.com/kkrt-labs/kakarot)** (zkEVM in Cairo) and **[Madara](https://github.com/keep-starknet-strange/madara)** (Starknet sequencer) from zero; both now run with independent teams. Bootstrapped 15+ open-source projects and grew the Starknet developer ecosystem to thousands.
- Co-inventor, French patent **FR 2 996 663 A1**.

The question that drives the current work:

> **How do you verify what an autonomous system actually did?**

---

## Research

Peer-reproducible reports and preprints. Full record on **[ORCID](https://orcid.org/0009-0006-9640-9194)**.

- **Toward High-Assurance AI: Safety by Design for Autonomous Systems** (2026) — A framework for treating verification as a first-class system property rather than a post-hoc add-on. → [`10.5281/zenodo.20512718`](https://doi.org/10.5281/zenodo.20512718)
- **CodeLeWM: A Reproducible, Claim-Gated Code World-Model Study with Negative Action-Use Results and a Narrow Downstream Reranking Slice** (2026) — We study whether a JEPA-style latent code world-model can rerank candidate program edits without executing them, scoring candidates by predicted latent transitions rather than by generating patches. → [`10.5281/zenodo.20630120`](https://zenodo.org/records/20630120) · code: [`CodeLeWM`](https://github.com/AbdelStark/CodeLeWM)
- **Frozen-Backbone JEPA-Style Probes on HAM10000** (2026) — A nine-experiment ablation testing whether a latent predictor over a *frozen* vision encoder generalises on a leakage-controlled dermoscopy proxy; published with a full pretraining-contamination audit and an explicit "what is not yet claimed" boundary. → [`10.5281/zenodo.20556968`](https://doi.org/10.5281/zenodo.20556968) · code: [`derma-jepa`](https://github.com/AbdelStark/derma-jepa)
- **Patch-Token Geometry of Four Released Vision Encoders** (2026) — A multi-dataset artifact study comparing the patch-token representation geometry of DINOv2, I-JEPA, V-JEPA 2, and EUPE. → [`10.5281/zenodo.20048509`](https://doi.org/10.5281/zenodo.20048509) · code: [`latent-inspector`](https://github.com/AbdelStark/latent-inspector)
- **The Half-Life of Trust** (2026) — Why durable AI verification needs mathematics-rooted, post-quantum foundations rather than hardware-rooted trust (TEEs). → [`10.5281/zenodo.19682195`](https://doi.org/10.5281/zenodo.19682195)

---

## Selected work

### World models & physical AI

| Project | What it is |
|---|---|
| [worldforge](https://github.com/AbdelStark/worldforge) | Testable world-model workflows for physical-AI systems: providers, planning, evaluation, benchmarking, and diagnostics. |
| [Lensemble](https://github.com/AbdelStark/Lensemble) | Federated, end-to-end JEPA world models trained across mutually-distrusting data silos — with a roadmap to STARK-based proof of each participant's contribution. |
| [GenoLeWM](https://github.com/AbdelStark/GenoLeWM) | Action-conditioned JEPA world model for genomic edits: treat a DNA edit as an *action* over a frozen DNA encoder and predict the latent outcome. |
| [CodeLeWM](https://github.com/AbdelStark/CodeLeWM) | Latent transition models over code edits — a scorer/reranker for candidate patches, not a generator. Published as infrastructure plus an honest negative result. |
| [derma-jepa](https://github.com/AbdelStark/derma-jepa) | Frozen-backbone JEPA-style probes on HAM10000: can a latent predictor distinguish stable lesions from changing ones under nuisance variation? Contamination-audited. |
| [gpc_rs](https://github.com/AbdelStark/gpc_rs) | Generative robot policies in Rust: diffusion policy + world model + evaluator. |
| [asimov-sim-lab](https://github.com/AbdelStark/asimov-sim-lab) | Schema-backed inspection, validation, and deterministic evidence packaging for the Asimov v1 MuJoCo humanoid model. |
| [mosaicmem](https://github.com/AbdelStark/mosaicmem) | Geometry-aware spatial memory for camera-controlled video generation. |

### Representation learning & ML systems

| Project | What it is |
|---|---|
| [jepa-rs](https://github.com/AbdelStark/jepa-rs) | Rust implementation of JEPA primitives: I-JEPA, V-JEPA, C-JEPA, VICReg, EMA. |
| [latent-inspector](https://github.com/AbdelStark/latent-inspector) | Compare DINOv2, I-JEPA, V-JEPA 2, and EUPE representation geometry on the same image. Rust + ONNX. |
| [latent-inspector-py](https://github.com/AbdelStark/latent-inspector-py) | Patch-token geometry benchmarks for released vision encoders (DINOv2, I-JEPA, V-JEPA 2, EUPE). |
| [attnres](https://github.com/AbdelStark/attnres) | Attention residual stream experiments inspired by Kimi / MoonshotAI. |
| [turboquant](https://github.com/AbdelStark/turboquant) | Rust implementation of Google's TurboQuant for KV-cache quantization. |
| [nostrain](https://github.com/AbdelStark/nostrain) | Coordinator-free distributed ML training over Nostr relays using DiLoCo. |
| [jepa-notebooks](https://github.com/AbdelStark/jepa-notebooks) | Interactive notebooks for JEPA architectures. |

### AI safety & verifiable inference

Deployment is moving faster than the verification layer. That gap is the work.

| Project | What it is |
|---|---|
| [llm-provable-computer](https://github.com/AbdelStark/llm-provable-computer) | Verifiable LLM inference with STARKs. |
| [awesome-ai-safety](https://github.com/AbdelStark/awesome-ai-safety) | Curated map of AI safety tooling: alignment, interpretability, red teaming, formal verification, zkML, governance. |
| [eu-ai-act-toolkit](https://github.com/AbdelStark/eu-ai-act-toolkit) | Open-source toolkit for EU AI Act compliance. |
| [claude-md-compiler](https://github.com/AbdelStark/claude-md-compiler) | Compiles `CLAUDE.md` into a versioned policy lockfile and enforces it against diffs, hooks, and CI. |

### Zero-knowledge & Starknet infrastructure

| Project | What it is |
|---|---|
| [Kakarot](https://github.com/kkrt-labs/kakarot) | EVM interpreter in Cairo. Ethereum compatibility on Starknet via ZK proofs. |
| [Madara](https://github.com/keep-starknet-strange/madara) | Starknet sequencer for sovereign appchains. |
| [Raito](https://github.com/starkware-bitcoin/raito) | Bitcoin ZK client in Cairo. Verifies Bitcoin consensus inside a STARK proof. |
| [Askeladd](https://github.com/starkware-bitcoin/askeladd) | Verifiable computation for Nostr Data Vending Machines via STARKs. |
| [Cashu ZK Engine](https://github.com/AbdelStark/cashu-zk-engine) | Blind Diffie-Hellman key exchange in Cairo for Cashu ecash. |

### Bitcoin & freedom tech

| Project | What it is |
|---|---|
| [collidervm](https://github.com/AbdelStark/collidervm) | ColliderVM: stateful computation on Bitcoin without fraud proofs. |
| [bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) | Bitcoin and Lightning MCP server. |
| [nostringer-rs](https://github.com/AbdelStark/nostringer-rs) | Ring signatures for Nostr, in Rust. |
| [nostr-mcp](https://github.com/AbdelStark/nostr-mcp) | Nostr MCP server. |
| [bitcoin-honeybadger](https://github.com/AbdelStark/bitcoin-honeybadger) | Agent-based modeling for Bitcoin network resilience. |

### Applied AI tooling

| Project | What it is |
|---|---|
| [parler](https://github.com/AbdelStark/parler) | Multilingual voice intelligence on Mistral Voxtral — structured decision logs from French/English meetings. |

---

## Writing

| Title | What it is |
|---|---|
| [Provable World Model](https://hackmd.io/@AbdelStark/provable-world-model) | World models, the integrity gap, and the fork in the road. |
| [World Models, From Zero to Hero](https://hackmd.io/@AbdelStark/world-model-from-zero-to-hero) | A field guide to one of the most overloaded terms in AI. |
| [The Half-Life of Trust](https://hackmd.io/@AbdelStark/the-half-life-of-trust) | Why verifiable AI needs post-quantum foundations. |
| [Math Is Humanity's Last Bastion Against Skynet](https://hackmd.io/@AbdelStark/math-humanity-last-bastion-skynet) | Why ZK proofs are the foundation for AI safety at scale. |
| [Can LLMs Be Provable Computers?](https://hackmd.io/@AbdelStark/llm-provable-computers) | Verifiable AI inference via STARKs. |
| [Before Fighting Banks, Let's Understand How They Actually Work](https://hackmd.io/@AbdelStark/BeforeFightingBanks) | A cypherpunk's guide to the financial system. |
| [Time to Take the Nostr Pill](https://hackmd.io/@AbdelStark/time-to-take-the-nostr-pill) | Why Nostr matters for freedom of speech. |
| [Nostr DVMs Meet Verifiable Computation](https://hackmd.io/@AbdelStark/nostr-dvm-verifiable-computation) | STARKs for trustless Nostr services. |
| [Cashu Meets STARKs](https://hackmd.io/@AbdelStark/cashu-starks) | Zero-knowledge proofs for the Cashu protocol. |

---

## Earlier work

<details>
<summary><strong>Hellhound</strong> — applied cryptography / blind computation (2018)</summary>
<br>

I co-founded [Hellhound](https://github.com/ConsenSys/hellhound) inside ConsenSys R&D: a decentralized blind-computation platform for running programs over homomorphically encrypted inputs without exposing the data to the network.

I built the HHVM register-based bytecode VM, the Paillier homomorphic-encryption pipeline, the Kubernetes/GKE infrastructure, the Ethereum smart contracts for on-chain computation proofs, and the consensus logic for detecting malicious nodes. I was also first author of the [Red Paper](https://github.com/ConsenSys/hellhound/blob/master/hellhound-red-paper.pdf).

We shipped a live demo at [DevCon4 Prague](https://youtu.be/mztQHrRXEXs).

</details>

---

## Principle

**Close the gap between what systems claim and what can be verified.**

Math scales. Goodwill doesn't.

---

<p align="center">
  <a href="https://x.com/AbdelStark"><img src="https://img.shields.io/badge/@AbdelStark-000000?style=for-the-badge&logo=x&logoColor=white" alt="X / Twitter"></a>
  <a href="https://huggingface.co/abdelstark"><img src="https://img.shields.io/badge/🤗-Hugging%20Face-000000?style=for-the-badge" alt="Hugging Face"></a>
  <a href="https://www.linkedin.com/in/0xabdelstark/"><img src="https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://orcid.org/0009-0006-9640-9194"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://hackmd.io/@AbdelStark"><img src="https://img.shields.io/badge/Writing-HackMD-111111?style=for-the-badge" alt="Writing"></a>
</p>
