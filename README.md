## Hi, I'm DJ

AI research and product leader in Amsterdam. Currently Director of Research and Incubation at Raw Power Labs, where I run a research-to-product portfolio — and still write the code.

Most of my work lives in private repositories: a decade of it in banking, at two AI platform vendors, and now inside a research lab. This is what's in them.

### What I've been building

**Autonomous multi-agent platform** — built solo, 601 commits, ~56,500 lines across Python, Rust, TypeScript and Bash, over about five months alongside the day job. Orchestrates AI runner CLIs against markdown task specs with success-criteria review loops, retries, git-worktree isolation, and an orchestrator-managed PR flow for code tasks. Native desktop app, CI with lint and tests. Production record: 333 completed autonomous tasks across ~20 projects, ~800 generated reports, 122 consecutive automated daily briefs. Since generalised into the team-wide knowledge base, running on our own GPUs.

**Embeddable graph database in Rust** — ~31,000 lines, 231 commits. Library-first, broad Cypher support, graph algorithms, C FFI and Python APIs. Started as a personal project, graduated into a team project, and is now the embedded graph store inside a knowledge-graph engine for game-narrative consistency that the lab has in development.

**On-device language-model platform** — originated it, shipped the automated fine-tuning MVP, and built the evaluation stack: BLEU/ROUGE/METEOR, LLM-as-judge scoring, JSON-validity checks, prompt-version tracking. A 500MB CPU-only model beat a frontier API model on latency at matched quality.

**Android app for on-device model evaluation** — ran and benchmarked the small language models we trained, with a full UI, in-app model download, and on-device execution. Roughly doubled the upstream open-source codebase it started from: llama.cpp integration, templated chat, and a complete on-device benchmark suite; later extended with CPU kernel optimisations.

*How this was built: much of the code above was written with LLM assistance. I build agentic harnesses for a living and use them daily on my own work. The architecture, the reviews, and the judgement about what was worth building are mine; a good share of the keystrokes were not. That is what engineering looks like for me in 2026, and I would rather say so than have you assume otherwise.*

### Selected work

- **Patent (inventor)** — *A Method for Creating Specialized Language Models*, application PA/2025/30389, approved for PCT international filing (2026)
- **Talks** — AI Denmark Summit, DI Copenhagen (Dec 2024) · [AI Denmark podcast](https://podcasts.apple.com/dk/podcast/sm%C3%A5-sprogmodeller-til-spil-og-meget-mere/id1591937564?i=1000691103654) on small language models for games (Feb 2025) · Game Days AI Summit, Malmö (April 2026) · IEEE CoG 2026, industry talk accepted (Madrid)
- **Academic** — university research collaboration with a published paper on small-language-model content generation; authored a funded industry-track PhD proposal

### Background

A decade across all three sides of enterprise AI: buyer (First National Bank), vendor (DataRobot, Abacus.AI), and builder (Raw Power Labs). Started as a quantitative analyst building credit scorecards and terabyte-scale data pipelines, and never stopped shipping. Master's in Operations Research, *cum laude*, Stellenbosch University.

### Working with

`Python` `Rust` `TypeScript` `SQL` · agentic architectures · evaluation pipelines · on-device and small language models · knowledge graphs · OpenTelemetry · MLOps

---

📍 Amsterdam · [djhuman.net](https://djhuman.net) · [LinkedIn](https://linkedin.com/in/dj-human-nl)
