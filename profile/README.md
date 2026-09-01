<div align="center">

<img src="https://avatars.githubusercontent.com/u/315273465?v=4" width="112" alt="Argus AI Team logo">

# ARGUS AI TEAM

### Building persistent AI systems that extend human capability

[![Website](https://img.shields.io/badge/Website-argusbot.cn-111111?style=for-the-badge)](https://argusbot.cn/)
[![Projects](https://img.shields.io/badge/Explore-Projects-2f6feb?style=for-the-badge)](https://argusbot.cn/projects/)
[![Technical Report](https://img.shields.io/badge/Read-Technical_Report-b8860b?style=for-the-badge)](https://arxiv.org/abs/2608.05144)

**Long-horizon agents · AI systems in silicon · Model deployment · Mathematical research**

</div>

---

## About Argus

Argus AI Team is an independent research and engineering team building AI
systems that can pursue substantial work beyond a single model response.

Our work spans the full path from autonomous agent runtimes to verified RTL,
practical deployment of frontier multimodal models, and inspectable
mathematical research. Across these domains, we focus on one principle:
**capability should be accompanied by evidence**.

We believe AI should not diminish human agency. It should expand what
researchers, engineers, and creators are able to understand, build, and
verify.

## Research and engineering

| Domain | What we build | Explore |
|---|---|---|
| **Agent systems** | Persistent multi-agent runtimes with durable state, explicit roles, reusable skills, and evidence-based review for long-horizon research and engineering. | [Argus](https://github.com/lbx154/Argus) · [Official release](https://github.com/microsoft/ArgusAgent) · [Report](https://arxiv.org/abs/2608.05144) |
| **Chips and RTL** | Model-faithful quantized inference architectures that connect software references, cycle-level validation, RTL, synthesis, and physical evidence. | [ACE-2](https://github.com/Argus-AiTeam/ace-2) · [ACE-3](https://github.com/Argus-AiTeam/ace-3) |
| **Model deployment** | Adaptation and acceleration of demanding multimodal models for Apple Silicon, desktop GPUs, and visual workflows. | [MiniMax-H3 for Mac](https://github.com/Argus-AiTeam/minimax-h3-mac) · [Desktop](https://github.com/Argus-AiTeam/minimax-h3-desktop) · [ComfyUI](https://github.com/Argus-AiTeam/ComfyUI-MiniMax-H3-MLX) |
| **Mathematics** | Public mathematical result packages with precise claim boundaries, technical reports, certificates, formal or computational checks, and reproducible evidence. | [Result archive](https://github.com/Argus-AiTeam/argus-mathematics) · [Argus Open](https://open.argusbot.cn/) · [Hilbert16 Observatory](https://github.com/Argus-AiTeam/Hilbert16-Dual-Argus-Observatory) |

## Selected work

### Argus · Persistent reviewed autonomy

[Argus](https://github.com/lbx154/Argus) separates campaign control, planning,
execution, and acceptance across distinct agent roles. Durable project state
preserves tasks, checkpoints, decisions, skills, and evidence across sessions
and runtime changes.

The accompanying [technical report](https://arxiv.org/abs/2608.05144) records
approximately **78% on SWE-Bench Pro**, compared with **59% for Direct
Copilot**, at **1.41× aggregate token use**. Six paper pipelines completed
**254 missions**, including **16 evidence-driven stage rollbacks**.

### ACE · AI execution in silicon

[ACE-2](https://github.com/Argus-AiTeam/ace-2) is an evidence-first
Qwen2.5-0.5B W4A8 accelerator. Its public record includes:

- **18/18** validated Layer-0 fixed-point operator boundaries;
- **13,914/13,914** runtime commands across a demonstrated 24-layer,
  two-token path;
- a mapped SKY130 result of **62,283 cells** and **0.614 mm²** non-SRAM area;
- a **100 MHz** target with positive setup slack.

[ACE-3](https://github.com/Argus-AiTeam/ace-3) advances the architecture toward
native asymmetric AWQ W4A16 execution. The accepted 24-layer fixture consumes
all **624/624 official decoder tensors**. Its current public scope is
pre-synthesis RTL evidence; measured silicon, FPGA, area, power, and latency
claims are deliberately left outside that boundary.

### MiniMax-H3 · Frontier multimodal models on practical hardware

Our MiniMax-H3 projects make complete video-and-stereo-audio generation
available on hardware outside datacenter-scale deployments:

- [MiniMax-H3 for Mac](https://github.com/Argus-AiTeam/minimax-h3-mac) runs the
  documented generation path on an Apple M4 Pro with 24 GB unified memory
  through streamed model execution.
- [MiniMax-H3 Desktop](https://github.com/Argus-AiTeam/minimax-h3-desktop)
  runs the full FL2VA stack on one RTX A6000 and publishes prompts, outputs,
  matched benchmarks, structural audio/video checks, and system telemetry.
- [ComfyUI MiniMax-H3 MLX](https://github.com/Argus-AiTeam/ComfyUI-MiniMax-H3-MLX)
  exposes model loading, generation, conversion, and direct MP4 output through
  a visual node workflow on Apple Silicon.

### Argus Mathematics · Claims connected to evidence

[Argus Mathematics](https://github.com/Argus-AiTeam/argus-mathematics)
currently preserves **12 public result packages** across low-dimensional
topology and foliations, Riemannian and algebraic geometry, complex analysis
and harmonic measure, graph theory, convex geometry, beta-transformations
and Salem numbers, arithmetic dynamics, and braid-group algebra.

The archive includes **seven independently runnable verification paths**, one
Lean-checked logical composition, technical reports, review packages,
certificates, and checksums for **70 public artifacts**. It explicitly
distinguishes original constructions from literature reconstructions,
historical negative results, scope corrections, and claims whose novelty has
not yet been certified.

## How we publish

We aim to make ambitious work easy to inspect and difficult to overstate.

- **Evidence before headline.** Results are linked to reports, commands,
  certificates, measurements, or reproducible artifacts.
- **Scope before scale.** We state what a result demonstrates and what it does
  not yet establish.
- **Review separate from execution.** Acceptance is based on artifacts and
  checks rather than the producing agent's confidence.
- **Negative results remain visible.** Failed routes and bounded evidence help
  prevent repeated mistakes and unsupported claims.
- **Corrections are part of the record.** Public work should become more
  precise as stronger evidence arrives.

## Start exploring

| Destination | Description |
|---|---|
| [argusbot.cn](https://argusbot.cn/) | The public home of Argus AI Team |
| [Projects](https://argusbot.cn/projects/) | Systems, evidence, and project-level results |
| [Get Started](https://argusbot.cn/get-started/) | Install and begin using Argus |
| [Technical report](https://arxiv.org/abs/2608.05144) | Architecture, evaluations, and long-horizon case studies |
| [Argus Open](https://open.argusbot.cn/) | Live mathematical research, open-problem audit, and published results |
| [Contact](https://argusbot.cn/contact/) | Team profiles and public community channels |

---

<div align="center">

### AI should make people more capable, not less important.

[Website](https://argusbot.cn/) ·
[GitHub](https://github.com/Argus-AiTeam) ·
[Report](https://arxiv.org/abs/2608.05144) ·
[Contact](https://argusbot.cn/contact/)

</div>
