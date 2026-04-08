**If you want to change the world, don't protest. Write code.**

I've been writing production software for 15+ years. Payments, banking, blockchain, cryptography. Industries where security is not an afterthought, mission critical software at scale. 

Head of Ecosystem at [StarkWare](https://starkware.co). Co-authored [EIP-1559](https://eips.ethereum.org/EIPS/eip-1559). Started [Kakarot](https://github.com/kkrt-labs/kakarot) and [Madara](https://github.com/keep-starknet-strange/madara) from nothing, both now run by independent teams. Lately most of my time goes to one question: how do you verify what an autonomous system actually did?

---

### AI safety

Deployment is moving faster than the verification layer. That's the gap I work on: cryptographic proofs, governance tooling, and agent harness engineering for auditable autonomous systems.

| Project | What it does |
|---------|-------------|
| [claude-md-compiler](https://github.com/AbdelStark/claude-md-compiler) | Compiles CLAUDE.md into a versioned policy lockfile. Enforces it against diffs, hooks, and CI. No LLM in the runtime path. |
| [awesome-ai-safety](https://github.com/AbdelStark/awesome-ai-safety) | Curated list of tools and resources for AI safety. Alignment, interpretability, red teaming, formal verification, ZKML, governance. Things you can actually use, not just papers. |
| [eu-ai-act-toolkit](https://github.com/AbdelStark/eu-ai-act-toolkit) | Open source toolkit for EU AI Act compliance. SDK, CLI, and web app for classifying AI systems and generating compliance docs. |
| [llm-provable-computer](https://github.com/AbdelStark/llm-provable-computer) | Can you prove an LLM produced a specific output without running it again? Exploring verifiable inference with STARKs. |

Writing on this:

| | |
|---|---|
| [Math Is Humanity's Last Bastion Against Skynet](https://hackmd.io/@AbdelStark/math-humanity-last-bastion-skynet) | Why ZK proofs are the foundation for AI safety at scale |
| [Can LLMs Be Provable Computers?](https://hackmd.io/@AbdelStark/llm-provable-computers) | Verifiable AI inference via STARKs |

---

### Machine learning

I implement frontier ML papers in Rust. If you can build it from scratch, you understand it.

| Project | What it does |
|---------|-------------|
| [latent-inspector](https://github.com/AbdelStark/latent-inspector) | Numbers, not vibes. Compare DINOv2, I-JEPA, V-JEPA 2, EUPE representation geometry on the same image — CKA, k-NN overlap, PCA projections, intrinsic dimensionality. In Rust, via ONNX. |
| [jepa-rs](https://github.com/AbdelStark/jepa-rs) | First Rust implementation of JEPA primitives (I-JEPA, V-JEPA, C-JEPA, VICReg, EMA) |
| [gpc_rs](https://github.com/AbdelStark/gpc_rs) | Generative robot policies. Diffusion policy + world model + evaluator, in Rust. |
| [mosaicmem](https://github.com/AbdelStark/mosaicmem) | Geometry-aware spatial memory for camera-controlled video generation |
| [attnres](https://github.com/AbdelStark/attnres) | Attention Residuals (Kimi/MoonshotAI). Softmax attention over all preceding layer outputs. |
| [turboquant](https://github.com/AbdelStark/turboquant) | Google's TurboQuant. Vector quantization of LLM KV caches, in Rust. |
| [jepa-notebooks](https://github.com/AbdelStark/jepa-notebooks) | Interactive notebooks exploring JEPA architectures |

---

### Ethereum

Co-authored [EIP-1559](https://eips.ethereum.org/EIPS/eip-1559), the fee market reform. Shipped to mainnet August 2021.

---

### Starknet / ZK proofs

Built the open source ecosystem around Starknet. Started Kakarot and Madara, both now have their own teams and communities.

| Project | What it does |
|---------|-------------|
| [Kakarot](https://github.com/kkrt-labs/kakarot) | EVM interpreter written in Cairo. Ethereum compatibility on Starknet via ZK proofs. |
| [Madara](https://github.com/keep-starknet-strange/madara) | Starknet sequencer for sovereign appchains |
| [Raito](https://github.com/starkware-bitcoin/raito) | Bitcoin ZK client in Cairo. Verifies Bitcoin consensus inside a STARK proof. |
| [Askeladd](https://github.com/starkware-bitcoin/askeladd) | Verifiable computation for Nostr Data Vending Machines via STARKs |
| [Cashu ZK Engine](https://github.com/AbdelStark/cashu-zk-engine) | Blind Diffie-Hellmann Key Exchange in Cairo for Cashu ecash |

---

### Bitcoin / freedom tech

| Project | What it does |
|---------|-------------|
| [bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) | Bitcoin & Lightning Network MCP server |
| [nostringer-rs](https://github.com/AbdelStark/nostringer-rs) | Ring signatures (SAG, BLSAG) for Nostr, in Rust |
| [nostr-mcp](https://github.com/AbdelStark/nostr-mcp) | Nostr MCP server |
| [bitcoin-honeybadger](https://github.com/AbdelStark/bitcoin-honeybadger) | Bitcoin Honeybadger |

---

### Writing

| | |
|---|---|
| [Before Fighting Banks, Let's Understand How They Actually Work](https://hackmd.io/@AbdelStark/BeforeFightingBanks) | A cypherpunk's guide to the financial system |
| [Time to Take the Nostr Pill](https://hackmd.io/@AbdelStark/time-to-take-the-nostr-pill) | Why Nostr matters for freedom of speech |
| [Nostr DVMs Meet Verifiable Computation](https://hackmd.io/@AbdelStark/nostr-dvm-verifiable-computation) | STARKs powering trustless Nostr services |
| [Cashu Meets STARKs](https://hackmd.io/@AbdelStark/cashu-starks) | Zero-knowledge proofs for the Cashu protocol |

---

If there's a thread, it's this: the gap between what individuals can verify and what institutions can hide should be closed by math, not by trusting people to behave. Bitcoin showed money doesn't need banks. Ethereum showed computation doesn't need servers. ZK proofs are how we'll know an AI actually did what it claimed.

Billions of autonomous agents are coming. Hospitals, roads, financial systems. The trust model we have assumes a small number of known actors. That assumption is about to break.

Becoming a dad changed my view of the world, my perspectives, my interests. The question shifted from "what's interesting" to "what world will they grow up in." Clarifying and terrifying in equal measure.

There's a video of a Unitree humanoid robot running and playing with kids in New York. The kids don't hesitate, no learned suspicion, no fear of something different. They just play. Kids apply "no enemies" (Thors mantra, from Vinland Saga) by default. And it's not because they're naive, rather because they haven't been taught yet to draw the lines we draw as "adults".

That's the world worth working toward. Not "no AI", but AI where integrity can be made by design, power that's distributed, trust that's verifiable. A world where kids don't have to unlearn anything to feel safe in it.

Math scales. Goodwill doesn't.

---

<p align="center">
  <a href="https://x.com/AbdelStark">X</a> · 
  <a href="https://primal.net/abdel">Nostr</a> · 
  <a href="https://hackmd.io/@AbdelStark">Writing</a>
</p>
