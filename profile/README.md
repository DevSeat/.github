<div align="center">

# DevSeat

**Building practical systems for AI agents, developer infrastructure, and automation.**

Tools that make software and AI systems more capable, observable, persistent, and easier to operate.

</div>

---

## What we build

DevSeat is an engineering organization focused on practical software systems around AI agents, developer tooling, automation, and local-first infrastructure.

Our work currently spans:

- **Agent infrastructure** — persistent runtimes, memory, capability layers, and model-independent systems
- **MCP tooling** — measurement, compute offloading, tool infrastructure, and agent-facing services
- **Developer infrastructure** — fast local utilities, diagnostics, automation, and reusable service layers
- **Systems research** — networking, resilient software, local AI, simulation, and experimental architectures

## Selected projects

> Projects are currently being consolidated under the DevSeat organization. Some repositories still live under the original maintainer account during migration.

| Project | What it does |
| --- | --- |
| [**MCPMeter**](https://github.com/stickleetoto/MCPMeter) | Local-first measurement proxy for MCP traffic, tokenized payload, latency, and tool overhead. |
| [**YiSang**](https://github.com/stickleetoto/YiSang) | Model-independent persistent-agent runtime where memory and capability survive model replacement. |
| [**Yekaterina**](https://github.com/stickleetoto/Yekaterina) | Deterministic compute engine for LLM agents with a deliberately small MCP tool surface. |
| [**Smart Kernel Brain**](https://github.com/stickleetoto/Smart-Kernel-Brain) | High-performance local file discovery for humans and AI agents through CLI, daemon, and MCP. |
| [**Nuntius**](https://github.com/stickleetoto/Nuntius) | Cross-platform network inspection, snapshot/diff, live watch, path diagnostics, and MCP access. |
| [**Maverick**](https://github.com/stickleetoto/Maverick) | Flight simulation testbed for AI pilot and unmanned-aircraft research. |

## Engineering principles

We prefer systems that are:

**Local-first when practical**  
Critical workflows should remain useful without depending on a remote service.

**Measurable**  
Performance, cost, behavior, and regressions should be observable rather than guessed.

**Modular**  
Models, runtimes, tools, storage, and interfaces should be replaceable without rebuilding everything.

**Verification-oriented**  
Tests, reproducible checks, stable interfaces, and explicit boundaries matter more than impressive demos.

**Built for reuse**  
Infrastructure should become a foundation for the next project instead of being rewritten every time.

## Direction

DevSeat is gradually bringing its projects into a shared ecosystem: common infrastructure, consistent interfaces, reusable services, and stronger automation between tools.

The goal is not to build one monolithic platform. It is to build a collection of interoperable systems that can evolve independently while working better together.

---

<div align="center">

**DevSeat · AI Systems · Developer Infrastructure · Automation**

</div>
