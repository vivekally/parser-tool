# Parser — AI-Native Document Interaction Layer

Product briefing and competitive landscape for Parser, an in-development AI document tool by Unmodal Research.

**Live site:** https://vivekally.github.io/parser-tool/

## What's here

- `index.html` — Dark-themed landing page with interactive zoom demo, rewrite panel, competitive tables, and market sizing
- `VERIFICATION.md` — Claim-by-claim confidence audit with sources
- `/research/` — Source research documents and infographic

## Three tracks covered

1. **Document Intelligence** — Zoom-to-summarize with SLM/LLM tiering, inline rewrite. Competitive landscape vs Google Docs, MS Word, Notion, Spellbook, Luminance, Genie AI, DocuSign Iris.
2. **Enterprise Workflow Agent** — DAP/copilot for complex enterprise software. Benchmarked against WalkMe, Whatfix, Pendo, Command AI, Browser Use, OpenAI Operator, Supademo.
3. **Legacy Modernization** — Conversational AI layer that makes legacy software feel modern.

Plus **Track Exploration**: seven adjacent markets evaluated with skeptical verdicts (five are already closed).

## Confidence system

Every factual claim carries a colored dot:
- 🟢 **Verified** — confirmed against primary sources
- 🟡 **Inferred** — analyst estimates or logical conclusions from confirmed facts
- ⚫ **Assumed** — all Parser product claims (concept stage), plus unconfirmed data points

## Note on the agent benchmark section

The first published version claimed "agents score below human reliability." **That is no longer true** — on OSWorld-Verified, top agents now exceed the 72.4% human baseline. The section was rebuilt around the defensible argument instead: agents collapse on long-horizon tasks (20.6–44.3% binary completion on OSWorld 2.0), and the reported scores are themselves unreliable — UC Berkeley hit ~100% on WebArena while solving zero tasks, and scaffold changes alone swing results 20–30 points.

See [VERIFICATION.md](VERIFICATION.md) for the full correction log.
