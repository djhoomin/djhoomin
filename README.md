## Hi, I'm DJ

AI research and product leader in Amsterdam. Currently Director of Research and Incubation at Raw Power Labs, where I run a research-to-product portfolio — and still write the code.

Most of my work lives in private repositories: a decade of it in banking, at two AI platform vendors, and now inside a research lab. This is what's in them.

### What I've been building

**Autonomous multi-agent platform** — built solo, 601 commits, ~56,500 lines across Python, Rust, TypeScript and Bash, over about five months alongside the day job. Orchestrates AI runner CLIs against markdown task specs with success-criteria review loops, retries, git-worktree isolation, and an orchestrator-managed PR flow for code tasks. Native desktop app, CI with lint and tests. Production record: 333 completed autonomous tasks across ~20 projects, ~800 generated reports, 122 consecutive automated daily briefs. Since generalised into the team-wide knowledge base, running on our own GPUs.

**Embeddable graph database in Rust** — ~31,000 lines, 231 commits. Library-first, broad Cypher support, graph algorithms, C FFI and Python APIs. Started as a personal project, graduated into a team project, and is now the embedded graph store inside a knowledge-graph engine for game-narrative consistency that the lab has in development.

**On-device language-model platform** — originated it, shipped the automated fine-tuning MVP, and built the evaluation stack: BLEU/ROUGE/METEOR, LLM-as-judge scoring, JSON-validity checks, prompt-version tracking. A 500MB CPU-only model beat a frontier API model on latency at matched quality. In September 2026 [Finans](https://finans.dk/tech/ECE19601152/naar-vandhanen-drypper-hjaelper-et-nyt-aivaerktoej-beboerne-uden-at-sende-data-til-usa/) reported on a Danish property administrator whose reply-drafting assistant runs on the lab's model, on a 40,000-kroner machine in their own office with a person finishing every reply, expected to save about 2,400 hours a year.

**Android app for on-device model evaluation** — ran and benchmarked the small language models we trained, with a full UI, in-app model download, and on-device execution. Roughly doubled the upstream open-source codebase it started from: llama.cpp integration, templated chat, and a complete on-device benchmark suite; later extended with CPU kernel optimisations.

**Two product lines I originated and staffed, both still in development** — a knowledge graph for game narrative (design documents become a graph with canon and rules subgraphs, embedded in the engine; conceived 2025, validated through designer interviews before building; industry talk accepted at IEEE CoG 2026; the Rust graph database above is its store) and a generative asset vault (every generated asset embedded into a vector index, similar requests served from the corpus instead of regenerated, the same index delivering assets at runtime, so cost per asset falls as the corpus grows; MVP in build). For the vault's storage layer the team contributed upstream to [Openinary](https://github.com/openinary/openinary): [3D and audio originals](https://github.com/openinary/openinary/pull/107) and [upload content validation](https://github.com/openinary/openinary/pull/116).

*How this was built: much of the code above was written with LLM assistance. I build agentic harnesses for a living and use them daily on my own work. The architecture, the reviews, and the judgement about what was worth building are mine; a good share of the keystrokes were not. That is what engineering looks like for me in 2026, and I would rather say so than have you assume otherwise.*

### On my own time

- [**jobsearch-agent**](https://github.com/djhoomin/jobsearch-agent) — a terminal app for a senior job search: public-ATS discovery, strategy scoring, grounded CV tailoring, and an ATS verifier that proves the PDF survives text extraction
- [**first-try**](https://github.com/djhoomin/first-try) — a usability benchmark for agent-facing APIs: does an agent get it right on the first try?
- [**local-system-one**](https://github.com/djhoomin/local-system-one) — typed, calibrated decisions from small local models, with a routing benchmark and a distilled 19 ms encoder
- [**bookly-agent**](https://github.com/djhoomin/bookly-agent) — a support agent where the model understands and code decides: policy as code, the clarifying question as a gate
- [**MAL-Graph**](https://github.com/djhoomin/MAL-Graph) — an anime list as an explorable graph in Memgraph, with a React and Cytoscape UI
- **Business-English rehearsal environment** (private) — an AI practice environment for business English, built with a language school in the Netherlands: actor and coach modes, trainer augmentation, GDPR by design

### Selected work

- **Patent (inventor)** — *A Method for Creating Specialized Language Models*, application PA/2025/30389, approved for PCT international filing (2026)
- **Talks** — AI Denmark Summit, DI Copenhagen (Dec 2024) · [AI Denmark podcast](https://podcasts.apple.com/dk/podcast/sm%C3%A5-sprogmodeller-til-spil-og-meget-mere/id1591937564?i=1000691103654) on small language models for games (Feb 2025) · Game Days AI Summit, Malmö (April 2026) · IEEE CoG 2026, industry talk accepted (Madrid)
- **Academic** — university research collaboration with a published paper on small-language-model content generation; authored a funded industry-track PhD proposal

### Background

A decade across all three sides of enterprise AI: buyer (First National Bank), vendor (DataRobot, Abacus.AI), and builder (Raw Power Labs). Started as a quantitative analyst building credit scorecards and terabyte-scale data pipelines, and never stopped shipping. Master's in Operations Research, *cum laude*, Stellenbosch University.

### Working with

`Python` `Rust` `TypeScript` `SQL` · agentic architectures · evaluation pipelines · on-device and small language models · knowledge graphs · observability and model monitoring · MLOps

---

📍 Amsterdam · [djhuman.net](https://djhuman.net) · [LinkedIn](https://linkedin.com/in/dj-human-nl)
