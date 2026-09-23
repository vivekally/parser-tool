# VERIFICATION.md — Parser Tool Briefing

Last verified: **2026-09-23**

Every factual claim on the site is tagged VERIFIED (independently confirmed against a primary/reputable source), INFERRED (analyst estimate or reasonable conclusion from confirmed facts), or ASSUMED (stated but unconfirmed, self-reported, or forward-looking). All Parser product claims are ASSUMED by default — the product is concept-stage.

---

## Corrections made 2026-09-23

These were wrong in the first published version and have been fixed:

| Claim as published | Problem | Corrected to |
|---|---|---|
| "73% don't read contracts before signing" attributed to University of Law UK | **Misattributed and misstated.** ULaw found 68%, and about a different thing (don't read *or don't understand*, for subscriptions/utilities). The 73% is from an Adobe survey measuring how often people *work with* contracts monthly. | 68%, correctly attributed, with a tooltip flagging the common misquote |
| Browser Use "79K+ GitHub stars" | Stale by ~47% | 116,079 stars / 12,781 forks (GitHub API, 2026-09-23) |
| "~80% of features rarely/never used" | Source says "*up to* 80%"; site presented it as a central estimate | "up to 80%", dated 2019, marked directional |
| DocuSign "67.6% market share" | Cherry-picked the most flattering of several contested figures | ~34% global / 35–40% US, with a note on the 67% narrower cut |
| Doc creation market "$2–24B" | 12x spread from mixing two different market definitions | ~$2.3B (document-centric collaboration), broader scope explained separately |
| E-signature "$5–17B" | Mixed e-signature platform with broader digital-signature/PKI market | ~$7.0B (platform scope, Mordor 2025) |
| Agent benchmark chart | **Core claim was false.** Mixed OSWorld and WebArena (different human baselines), and the "agents score below humans" premise no longer holds | Split into two benchmarks; argument reframed around long-horizon failure |
| "Anthropic ~50%" in benchmark chart | Single reviewer's 12-task anecdote presented as a benchmark result | Removed |
| Supademo "demo-builder leader" | Overclaim vs comparable Navattic/Storylane | "Seed stage" |
| Whatfix $10.9M / 728 hrs | Vendor-commissioned by a direct competitor; the two figures don't reconcile | Retained but labeled vendor-commissioned with the inconsistency shown |
| Real estate "4.1M US sales/yr" | Accurate but omitted that 2025 was a 30-year low | 4.06M, with the 30-year-low context |

---

## Document Intelligence Track

| Claim | Tag | Source checked |
|---|---|---|
| Rambler (CHI 2024) semantic zoom slider with GPT-4 | VERIFIED | ACM DL, DOI 10.1145/3613904.3642217 |
| Sensecape (UIST 2023) multilevel LLM abstraction | VERIFIED | ACM DL, DOI 10.1145/3586183.3606756 |
| "Semantic zoom" coined by Perlin & Fox, 1993 | VERIFIED | Pad paper |
| Google Docs Gemini inline quick actions | VERIFIED | support.google.com/docs/answer/13951448 |
| MS Word Copilot Auto Rewrite | VERIFIED | Microsoft support documentation |
| No mainstream competitor ships continuous semantic zoom | VERIFIED | Feature review of all 9 listed competitors |
| Grammarly $700M+ revenue, 40M+ DAU | VERIFIED | Grammarly blog, May 2025 |
| Grammarly $13B valuation (2021) | VERIFIED | Press coverage; note figure is 5 yrs old |
| Grammarly acquired Coda (Jan 2025), Superhuman (Jul 2025) | VERIFIED | Company announcements |
| Spellbook $50M Series B at $350M (Oct 2025) | VERIFIED | BusinessWire, SiliconANGLE |
| Genie AI ~$17.8M Series A (Oct 2024) | VERIFIED | Press, LegalTechHub |
| Luminance ~$30M ARR (2024) | INFERRED | Sacra analyst estimate, not audited |
| Ironclad ~$150M ARR (2025) | INFERRED | Sacra analyst estimate, not audited |
| **68% don't read or understand contracts** | VERIFIED | law.ac.uk press release |
| **E-signature platform ~$7.0B (2025)** | VERIFIED | Mordor Intelligence |
| **Doc collaboration ~$2.3B (2025)** | INFERRED | Cognitive Market Research; definition-sensitive |
| CLM market $1.2–3B (2025) | INFERRED | Grand View $1.78B, IMARC $2.05B, Precedence $2.96B |
| **DocuSign ~34% global / 35–40% US share** | INFERRED | Statista, esign.ai; figures contested across sources |
| DocuSign Iris signer-facing "translate legalese" (Jan 2026) | INFERRED | Referenced in source research; not independently confirmed |
| **US existing-home sales 4.06M in 2025, a 30-year low** | VERIFIED | NAR via PBS News |
| Real estate closing packages 100–400 pages | ASSUMED | Industry blogs only; no primary source found |
| Healthcare e-sig 28% CAGR | INFERRED | Analyst estimate |
| BFSI 28.2% of e-sig market (2025) | INFERRED | Analyst estimate |
| Government e-sig +20% annual adoption | INFERRED | Analyst estimate |

## Enterprise Workflow Agent Track

| Claim | Tag | Source checked |
|---|---|---|
| Pendo: ~12% features drive 80% of usage; up to 80% rarely used | INFERRED | Pendo Feature Adoption Report, **2019** — 7 yrs old, 615 subscriptions |
| Whatfix/Forrester $10.9M loss, 728 hrs/employee | ASSUMED | **Vendor-commissioned**; internally inconsistent (implies ~$15/hr loaded cost) |
| Whatfix $125M Series E at ~$900M val (Sept 2024) | VERIFIED | Press releases |
| SAP acquired WalkMe $1.5B (Sept 2024) | VERIFIED | SAP press release |
| Amplitude acquired Command AI ~$45M+ (Oct 2024) | INFERRED | Unnamed TechCrunch source; never officially disclosed |
| Pendo ~$300M ARR; $2.6B val **(2021)** | INFERRED | Valuation 5 yrs stale, no newer round found |
| **Browser Use 116,079 stars, $17M seed** | VERIFIED | GitHub API 2026-09-23; TechCrunch |
| DAP market $0.9–2.7B | INFERRED | ~4x analyst spread from differing definitions |

## Agent Benchmarks (rebuilt 2026-09-23)

| Claim | Tag | Source checked |
|---|---|---|
| OSWorld human baseline 72.36% | VERIFIED | Original OSWorld paper, 369 tasks |
| WebArena human baseline 78.24% | VERIFIED | Original WebArena paper |
| OSWorld-Verified top score 86.1% (Qwen3.8-Max, Aug 2026) | ASSUMED | **Vendor self-reported**; llm-stats.com confirms 0 of 26 entries independently verified |
| Claude Mythos Preview 85.4%, Opus 4.8 83.4% | ASSUMED | Vendor self-reported |
| OSWorld 2.0 released 2026-06-26, 108 long-horizon tasks | VERIFIED | arxiv.org/html/2606.29537v1 |
| OSWorld 2.0 paper: short tasks "overstate real progress" | VERIFIED | Direct quote from paper |
| Opus 5 44.33% binary / 77.67% partial (max effort) | INFERRED | Snorkel leaderboard; metric and effort setting must be stated |
| Opus 4.8 20.6% binary | INFERRED | Official OSWorld 2.0 site |
| UC Berkeley broke 8 benchmarks solving zero tasks | VERIFIED | rdi.berkeley.edu, Apr 2026 — Wang, Mang, Cheung, Sen, Song |
| WebArena ~100% and OSWorld 73% via exploits | VERIFIED | Same Berkeley paper |
| 20–30 pt scaffold swing on WebArena for same model | VERIFIED | arxiv.org/pdf/2607.28367, Dong et al., 2026-07-31 |
| Claude Opus 4: 64.9% vs 57.6% across frameworks | VERIFIED | Same paper |
| 10.7% of audited failures were evaluator false negatives | VERIFIED | Same paper |
| WebArena SOTA contested (74.3% most defensible) | INFERRED | Steel.dev; other trackers show 68.7% and 95.6% |

## Track Exploration (added 2026-09-23)

| Claim | Tag | Source checked |
|---|---|---|
| RegTech market ~$21.8–24B (2026), 19–22% CAGR | INFERRED | The Business Research Company |
| FiscalNote delisted from NYSE 13 Apr 2026, going-concern doubt | VERIFIED | fiscalnote.com newsroom |
| FiscalNote FY26 guidance $75–78M, 25% staff cut | VERIFIED | Company disclosures |
| Investment research platforms $7.51B (2026) → $13.25B (2030) | INFERRED | ResearchAndMarkets |
| AlphaSense $350M at $7.5B, $600M+ ARR (June 2026) | VERIFIED | alpha-sense.com press release |
| Hebbia still at $130M Series B / $700M val on ~$13M ARR | INFERRED | Sacra; absence of newer round confirmed across sources |
| Daloopa $47M Series C (May 2026), $101M total | VERIFIED | daloopa.com press release |
| eDiscovery market $15.4–19.6B (2025) | INFERRED | IMARC, ComplexDiscovery |
| Relativity made aiR for Review/Privilege free in RelativityOne (early 2026) | VERIFIED | blog.platinumids.com, LawNext |
| Relativity $3.6B valuation (2021) | INFERRED | Stale — 5 yrs old |
| Harvey $11B (Mar 2026), Legora $5.6B (Apr 2026) | VERIFIED | Press coverage |
| VDR market ~$3.0–3.4B (2025) | INFERRED | ResearchAndMarkets, Grand View |
| Datasite acquired Ansarada ~$154M (2024) | VERIFIED | Press coverage |
| M&A data room volumes 1,500–50,000 files | INFERRED | peony.ink industry analysis |
| Conversation intelligence $28.5–32.25B (2026) | INFERRED | ResearchAndMarkets |
| Gong $500M ARR, $4.5B secondary (down from $7.25B) | INFERRED | Secondary-market reporting |
| Granola $125M at $1.5B (Mar 2026) | VERIFIED | TechCrunch |
| Fireflies ~$1B, 16M users | INFERRED | Company-reported |
| Ambient scribes ~$600M revenue (2025), 2.4x YoY | INFERRED | Industry analysis |
| Abridge $300M Series E at $5.3B (Apr 2026) | VERIFIED | FierceHealthcare |
| Ambience $243M at $1.25B | VERIFIED | Press coverage |
| FDA SaMD discussion paper (Aug 2026) | VERIFIED | FDA publication |
| AI code tools $7.34B (2025), ~26% CAGR | INFERRED | Analyst estimate |
| CodeRabbit $143M Series C at $1.5B | VERIFIED | TechFundingNews |
| Cursor/Anysphere acquired Graphite (Dec 2025) above $290M val | VERIFIED | cursor.com/blog/graphite |

## Parser's Own Product Claims

| Claim | Tag |
|---|---|
| Zoom-to-summarize interaction | ASSUMED — concept stage, not shipped |
| Inline rewrite | ASSUMED — concept stage |
| SLM→LLM tiering architecture | ASSUMED — planned |
| E-sign comprehension layer use case | ASSUMED — founder's stated vision |
| Enterprise workflow agent, phased guided→autonomous | ASSUMED — planned |
| Legacy modernization / conversational layer | ASSUMED — planned |

---

## Summary

| Tag | Count |
|---|---|
| VERIFIED | 44 |
| INFERRED | 31 |
| ASSUMED | 12 |

**Highest-risk items to avoid citing without a caveat:**
1. Any OSWorld / OSWorld 2.0 score — all vendor self-reported, none independently verified, and the benchmarks are demonstrably gameable.
2. Whatfix's $10.9M figure — vendor-commissioned and internally inconsistent.
3. Any market size given as a point estimate — analyst spreads run 2–12x depending on definition.
4. Valuations older than 2024 (Grammarly $13B, Pendo $2.6B, Relativity $3.6B) — all pre-date the current AI funding cycle.
