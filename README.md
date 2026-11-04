# Aidan Karas

I build AI agents and measure whether they can be trusted.

Data Science + Mathematics at Boston University (May 2028). Machine learning research in the Barnes Group; previously Research Software Engineer (DOE SULI) at Argonne National Laboratory.

### Evaluating AI systems
- **[mcp-risk-census](https://github.com/aidankaras/mcp-risk-census)**: what can the tool servers that agents connect to actually do? A static scan of 109 public MCP servers: 65% can run shell commands, only 37% restrict file paths. Scanner validated on 20 LLM-reviewed repos (precision 0.75-0.81). Rescans monthly.
- **[model-lab](https://github.com/aidankaras/model-lab)**: does fine-tuning a small LLM beat simple baselines on a real task? LoRA on Qwen2.5-0.5B beat production rules for email triage (70% vs 53%, McNemar p = 0.003), and a TF-IDF baseline tied it at ~90x lower latency.
- **[sec-filings-e6](https://github.com/aidankaras/sec-filings-e6)**: can an LLM agent beat a conventional model at forecasting from SEC filings when both see byte-identical evidence? The conventional arm shows no measurable skill over 60 walk-forward days.

### Building agents and tools
- **[callback](https://github.com/aidankaras/callback)**: Claude Code plugin that tailors resumes from a provenance-tracked fact store, then checks every claim deterministically, with no LLM in the checker.
- **[agent-readiness-scanner](https://github.com/aidankaras/agent-readiness-scanner)**: scores how readable a store is to AI shopping agents; first study of 75 stores.
- I also run a self-hosted multi-agent system (Hermes Agent, Claude Code, MCP tools, scheduled jobs) with approval gates on any action that sends, spends or publishes.

### Research
- **Argonne / DOE PyGREET**: built impact dominance analysis and an upstream contribution tree, merged into the Python platform for DOE's R&D GREET model with a REST API, 84 tests and CI.
- **Barnes Group**: testing whether post-processing can fix the spatial-dependence errors of a diffusion-model forecast ensemble on chaotic Lorenz-96, scored with CRPS and variogram score.
- **[signal-lab-public](https://github.com/aidankaras/signal-lab-public)**: ~20 pre-registered trading experiments against SPY and a random-entry control; every concluded one loses out of sample, and the write-ups say so.

[aidankaras.dev](https://aidankaras.dev) · [LinkedIn](https://linkedin.com/in/aidankaras)
