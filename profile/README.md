<div align="center">

# DevSeat

**Building practical AI systems and developer infrastructure.**

DevSeat develops focused software products for persistent AI, verified computation, and fast local tooling.

</div>

---

## Core products

DevSeat's primary product line currently consists of three systems.

### BIO

**A persistent AI system built around durable user-owned memory and context.**

BIO is designed so the user's memory and long-lived context remain independent from any single model or client. Its architecture separates the user-facing client from the Core that owns and governs persistent state.

> BIO Core is developed privately.

### Yekaterina

**Deterministic computation for LLM agents with a minimal MCP surface.**

[Yekaterina](https://github.com/stickleetoto/Yekaterina) exposes a large verified operation registry through a deliberately small interface, allowing agents to offload computation without inflating their visible tool surface.

The public v1.4 line serves as the free baseline, while later commercial development is maintained separately.

### Smart Kernel Brain

**High-performance local file discovery for humans and AI agents.**

[Smart Kernel Brain](https://github.com/stickleetoto/Smart-Kernel-Brain) provides fast local file lookup through a CLI, resident daemon, and MCP interface while keeping the search path local and lightweight.

---

## Research & engineering tools

DevSeat also develops supporting infrastructure and experimental systems. These projects are not the primary product line, but they contribute technology, tooling, and research to the wider DevSeat ecosystem.

Examples include:

- [MCPMeter](https://github.com/stickleetoto/MCPMeter) — MCP cost, latency, payload, and tool-overhead measurement
- [YiSang](https://github.com/stickleetoto/YiSang) — model-independent persistent-agent runtime research
- [Nuntius](https://github.com/stickleetoto/Nuntius) — cross-platform network inspection and diagnostics
- [Maverick](https://github.com/stickleetoto/Maverick) — AI pilot and unmanned-aircraft simulation research

## Engineering principles

We prefer systems that are:

**Local-first when practical**  
Critical workflows should remain useful without depending on a remote service.

**Measurable**  
Performance, cost, behavior, and regressions should be observable rather than guessed.

**Modular**  
Models, runtimes, tools, storage, and interfaces should remain replaceable.

**Verification-oriented**  
Stable interfaces, reproducible checks, and explicit system boundaries matter.

**Built for reuse**  
Shared infrastructure should strengthen future DevSeat products instead of being rebuilt repeatedly.

## Direction

DevSeat is building an ecosystem around three core products — **BIO, Yekaterina, and Smart Kernel Brain** — supported by reusable internal infrastructure and ongoing systems research.

Repositories are gradually being consolidated under the DevSeat organization.

---

<div align="center">

**DevSeat · BIO · Yekaterina · Smart Kernel Brain**

</div>
