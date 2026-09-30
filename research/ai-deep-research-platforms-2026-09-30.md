# AI deep-research platforms: which cite best

As at 30 September 2026. Prepared for professional and personal research use (strategy, market, cultural and relocation questions), covering consumer deep-research products and academic literature tools. Ranked on how concise, verifiable and well-cited the output is, with cost noted. Sources are numbered in square brackets and listed at the end, each marked with how it was accessed.

## The answer

### Consumer deep-research products, ranked

1. Perplexity Research (Pro, $20/month). Highest measured citation accuracy of any deep-research agent, at 90.2% on DeepResearch Bench's FACT test [1], best of eight tools in the Tow Center's news-citation audit [4], and inline numbered citations on every claim that reviewers single out for traceability [22][23]. Its reports are the shortest of the group. The weak spot is source quality. It repeated false claims 47% of the time in NewsGuard's August 2025 audit, the second-worst result, before improving to one of the three best by January 2026 [6][7], and it had the worst full-trajectory hallucination score among deep-research agents on DeepHalluBench [11].

2. Claude Research (Pro, $20/month). The lowest fabrication in every 2026 study that includes Claude: 3.0% to 3.2% hallucinated citation links, the lowest of ten systems tested [3]; 0% repeated false claims in NewsGuard's January 2026 audit, the only chatbot correct every time [7]; and the lowest hallucination rate with web search on HalluHard [12]. A dedicated citation agent checks that cited sources match the claims before the report is returned [18]. Reviewers rate its synthesis and prose highest [24]. The weak spot is evidence coverage. Claude Research as a product appears on none of the independent per-product tables, so the case rests on tests of Claude models with search rather than the Research feature itself.

3. ChatGPT Deep Research (Plus, $20/month; Pro, $200/month). The most precise references among the large agents, with 3.5% fabricated links [3] and reference precision of 0.385 against Gemini's 0.145 on ReportBench [10], and the best DeepHalluBench score [11]. Reviewers call its reports the most polished [24]. The weak spots are the lowest citation-accuracy score among agents on FACT (78.0%) [1], 10.1% dead links [3], and the longest reports, which reviewers say over-cite and dilute the findings [24][26]. A February 2026 update lets you restrict searches to trusted sites and interrupt a run to add sources [19].

4. Gemini Deep Research (Google AI Pro, $19.99/month; AI Ultra, $99.99 or $199.99/month). Reads the most sources by far, at 111 effective citations per report against 31 to 41 for rivals [1], and leads breadth-oriented rubric benchmarks [13]. It's the worst on verifiability. In the April 2026 study 13.3% of its citation links were fabricated and 18.5% didn't resolve, both the highest of any system tested [3]; 72% of its news answers had a significant sourcing problem in the EBU/BBC study, against under 25% for the other three assistants [5]; and its reference precision on ReportBench was the lowest [10]. Use it when you want coverage and will check the links yourself.

5. Microsoft 365 Copilot Researcher (about $30 per user per month on the work add-on; consumer Microsoft 365 Premium $19.99/month). Source-cited reports grounded in your own files and email, and Microsoft claims a 13.9-point lead over Perplexity on Perplexity's own DRACO benchmark [15]. No independent benchmark publishes an absolute score for it. Usage is capped at 25 Researcher queries per user per month, reports can't yet export to PDF or PowerPoint, admins can't allow-list specific websites, and one reviewer found reports run to 20 to 30 pages [20][27]. Copilot's consumer Deep Research mode was retired on 18 August 2026 [28].

6. Grok DeepSearch (SuperGrok, $30/month; SuperGrok Heavy, $300/month). Strong on real-time X data and a respectable 83.6% citation accuracy on FACT, but with only 8 effective citations per report [1]. It has the worst citation record in the audits: 94% wrong, with 154 of 200 links leading to error pages, in the Tow Center test [4], and the highest grounded-hallucination rates on Vectara's leaderboard [14]. No credible 2026 test of DeepSearch's citations was found.

### Academic and literature tools, ranked

1. Elicit (free; Plus $12/month; Pro $49/month). The most independently tested tool. Sentence-level citations link to the exact passage in the paper [29], it scored 1 of 11 on a reference-hallucination test where ChatGPT scored 11 of 11 [37], and its data extraction was close to human accuracy at 81.4% against 86.7% in a 602-data-point study [32]. Its search recall is poor for systematic reviews, averaging 39.5% against 94.5% for a librarian's search [33], so use it to explore a topic rather than to be exhaustive.

2. Consensus (free; Pro $20/month, or about $12 on annual billing; Deep $65/month). The best free tier and the largest index at over 220 million papers [30], with inline citations to real papers. One 2026 nursing study found its output matched only 21% of a human reference list [34], and the Consensus Meter counts papers rather than grading evidence, a limit the vendor states itself [30].

3. SciSpace (free; Premium $20/month). Scored 1 of 11 on the same reference-hallucination test as Elicit [37] and sits alongside Elicit and Ai2's Asta at about 85% on ScholarQA-CS2 [39].

4. Scite (Basic $20/month billed annually; Pro $50/month). The only tool that labels each citation as supporting, contrasting or mentioning, drawing on 1.6 billion citation statements [31]. The one independent test, from 2023, found the classifier weak: it labelled 96 of 98 citations as merely "mentioning" where reviewers found 42 supporting and 17 contrasting [35].

5. Ai2 Asta and OpenScholar (free). Open, retrieval-grounded, and the subject of a Nature paper in February 2026 showing GPT-4o hallucinated 78% to 90% of citations where OpenScholar didn't [38]. A June 2026 study found Asta's cited references unstable across identical queries [40].

6. Undermind (about $16 to $20/month). Claims 85% recall of the top papers on a topic, but the claim is the vendor's own, with no peer-reviewed recall test found [41].

### Synthesis

For concise, checkable, well-cited research, Perplexity Research and Claude Research are the two to use, and they fail in different ways. Perplexity is the most traceable and the shortest but pulls in lower-quality pages, while Claude fabricates the least and writes the best synthesis but has the thinnest independent product-level benchmarking. ChatGPT and Gemini Deep Research win on depth and breadth and lose on concision and dead links, so read their reports as a list of sources to check. For literature, Elicit is the only tool with a body of independent validation behind it, and every academic tool tested is fine for exploration and unfit for systematic search.

## How this was judged

Criteria, in order of weight: citation accuracy (does the cited source support the claim), link reliability (does the citation resolve to a real page), truthfulness (does the tool repeat false claims), concision (report length and signal density), and traceability (how easy it is to click through and check). Breadth was recorded but not rewarded. Price is the tier where the research mode lives.

Evidence, in order of weight: peer-reviewed and preprint studies that measured citation behaviour (2025 to 2026), independent benchmarks with per-product tables, journalist-run audits (Tow Center, EBU/BBC, NewsGuard), vendor pages for pricing and features, and hands-on reviews from mainstream outlets. Per-product citation-accuracy tables on the independent benchmarks all date from mid-2025; the 2026 leaderboards mostly score API models inside a harness rather than the consumer products.

Verification limit. This work ran in a cloud environment whose network policy blocked direct fetches from most primary hosts, including arxiv.org, cjr.org, newsguardtech.com, allenai.org, openai.com, one.google.com, perplexity.ai, x.ai and deepresearch-bench.github.io. Pages on claude.com, support.claude.com and microsoft.com were reachable and were read directly. Every other figure was confirmed from search-result excerpts of the named page, and the five figures that carry the ranking (the Tow Center error rates, the EBU/BBC sourcing rates, NewsGuard's January 2026 audit, the DeepResearch Bench citation-accuracy column and the DRACO scores) were second-sourced through separate searches. Figures that rest on one excerpt or a third-party mirror are marked [single source]. Nothing is from memory. The FutureSearch Deep Research Bench figures could not be corroborated and are left out.

Two sources of bias to know about. DRACO is Perplexity's own benchmark, BrowseComp is OpenAI's, and system-card scores are vendor-reported. And the author of this document is Claude, one of the products ranked. The ranking was built from the cited evidence, and the sources are listed so it can be checked.

## Consumer products: the evidence

### Citation and truthfulness measures

| Product | Citation accuracy, FACT [1] | Fabricated links [3] | Dead links [3] | Significant sourcing issue, EBU/BBC [5] | False claims repeated, NewsGuard [6][7] |
|---|---|---|---|---|---|
| Perplexity Deep Research | 90.2% (31 effective citations) | not tested | not tested | 15% [single source] | 47% (Aug 2025); top three (Jan 2026) |
| Claude with search | 93.7% (Claude 3.7 Sonnet with search, not the Research agent) | 3.0% to 3.2% | 7.8% to 8.5% | not tested | 10% (Aug 2025); 0% (Jan 2026) |
| OpenAI Deep Research | 78.0% (41 effective citations) | 3.5% | 10.1% | 24% (ChatGPT) [single source] | 40% (Aug 2025) |
| Gemini Deep Research | 81.4% (111 effective citations) | 13.3% | 18.5% | 72% | 17% (Aug 2025) |
| Grok DeeperSearch | 83.6% (8 effective citations) | not tested | 154 of 200 dead, Tow Center [4] | not tested | not captured |
| Copilot Researcher | not tested | not tested | not tested | 15% (Copilot) [single source] | about 35% (Aug 2025) |

FACT figures are from the June 2025 paper runs, judged by Gemini 2.5 Pro; the benchmark switched judges in May 2026 and its live leaderboard could not be read from here [1][2]. The fabricated and dead link figures are from Rao, Wong and Callison-Burch (April 2026), who checked 53,090 citation URLs across ten systems; the Gemini agent tested was the 2.5 Pro version, and no 2026 test of the Gemini 3.x-era agent was found [3].

### Other measures

- ReportBench (August 2025) compared the two largest agents on survey-writing tasks. OpenAI Deep Research had reference precision of 0.385 and a citation-match rate of 78.9%; Gemini Deep Research had 0.145 and 72.9%, and produced about three times as many cited statements without better recall [10].
- DeepHalluBench (January 2026) scored whole research trajectories for hallucination, lower being better: OpenAI 0.155, Gemini 0.175, Perplexity 0.208 [11].
- HalluHard (February 2026) tested 950 multi-turn questions with a web-search judge. Claude Opus 4.5 fell from 60.0% hallucination to 30.2% with web search; GPT-5.2 thinking with search was 38.2%; Gemini 3 Pro had no search variant tested [12] [single source].
- DRACO (February 2026), Perplexity's benchmark with Harvard, scored Perplexity Deep Research on Opus 4.6 at 70.5%, Claude Opus 4.6 with web and code at 59.8%, Gemini Deep Research at 59.0% [single source] and OpenAI Deep Research on o3 at 52.1% [9]. Microsoft reported its Researcher agent with the Critique feature at 13.88 points above Perplexity on the same benchmark [15] [single source].
- Breadth benchmarks, vendor-reported. On BrowseComp, OpenAI's hard-fact-finding test, GPT-5.6 and GPT-6 report 91% to 92%, Claude Opus 5 90.8%, Gemini 3.1 Pro 85.9% and Grok 4.6 about 84% [16]. On Humanity's Last Exam with tools, Anthropic reports Claude Opus 5.5 at 67.7% and GPT-6 Astra at 57.2% [17]; Google reported Gemini Deep Research Max at 54.6% and Perplexity reported 50.5% for Deep Research in Computer [single source]. Independent reruns of these tests come in 10 to 20 points below vendor figures [16].
- Tow Center, March 2025. 1,600 tests across eight tools asked each to identify the article behind a quoted excerpt. More than 60% of answers were wrong. Perplexity was wrong 37% of the time, ChatGPT Search 67%, and Grok-3 94%; Gemini returned more fabricated links than correct ones, and Copilot declined 104 of 200 queries [4]. No 2026 repeat was found.
- EBU/BBC, October 2025. Journalists at 22 public broadcasters in 18 countries rated more than 3,000 answers from ChatGPT, Copilot, Gemini and Perplexity. 45% had at least one significant issue, 31% a sourcing problem and 20% an accuracy problem; Gemini had a significant sourcing issue in 72% of answers [5]. A 2026 follow-up is reported but its per-assistant figures could not be read.
- NewsGuard. In the August 2025 audit ten chatbots repeated false claims 35% of the time on average, with Perplexity at 47%, ChatGPT 40%, Copilot about 35%, Gemini 17% and Claude 10% [6]. In January 2026, across 330 prompts to eleven chatbots, the average was 28.8%; Claude was at 0%, Mistral's Le Chat at 50%, and Claude, Pi and Perplexity were named the best three [7]. The May 2026 quarterly exists but its per-bot rates could not be read.

### Pricing and research limits

| Product | Free | Entry paid tier | Top tier | Research-mode limit | Access |
|---|---|---|---|---|---|
| Perplexity | limited Research; sources disagree on the daily cap | Pro $20 | Max $200 (unlimited Research); Enterprise Max $325 | Pro "extended", Max unlimited | third-party and help-centre excerpts [21] |
| Claude | no Research | Pro $20 ($17 on annual) | Max $100 (5x) or $200 (20x); Team $25 or $125 per seat | same five-hour limits as normal chat, used faster | read directly [18][42] |
| ChatGPT | limited deep research | Go $8; Plus $20 | Pro $200; Pro 500 at $500; Business $25 per user | monthly allowance, count unconfirmed | help-centre excerpts [19] |
| Gemini | Deep Research available, may be unavailable at high demand | AI Plus $7.99; AI Pro $19.99 | AI Ultra $99.99 or $199.99 | AI Pro reported at 20 sessions a day [single source] | Google Help and third-party excerpts [43] |
| Grok | limited | SuperGrok $30 | SuperGrok Heavy $300 | unconfirmed | x.ai and third-party excerpts [44] |
| Copilot Researcher | none | Microsoft 365 Premium $19.99 (consumer) | Microsoft 365 Copilot add-on, about $30 per user | 25 queries per user per month | Microsoft Learn read directly [20]; pricing page read directly [45] |

No EUR pricing could be confirmed for any product.

## Academic tools: the evidence

| Tool | Corpus | Citation style | Free tier | Paid (USD/month) | Best independent evidence |
|---|---|---|---|---|---|
| Elicit | 138M+ papers via Semantic Scholar, PubMed, OpenAlex [29] | sentence-level, linked to the exact quote | yes | Plus $12; Pro $49; Team $79 | extraction 81.4% vs human 86.7% [32]; recall 39.5% vs 94.5% [33]; 1 of 11 fabricated-reference score [37] |
| Consensus | 220M+ papers [30] | inline paper citations, plus the Meter tally | yes, generous | Pro $20 ($12 annual); Deep $65 | 21.3% match with human reference lists [34] |
| SciSpace | 280M+ papers, 50M open PDFs | cited synthesis with an execution report | yes | Premium $20; Advanced $90; Max $200 | 1 of 11 fabricated-reference score [37]; about 85% ScholarQA-CS2 [39] |
| Scite | 1.6B citation statements [31] | supporting, contrasting or mentioning context | limited | Basic $20; Pro $50 (annual billing) | classifier F-measures 0.0 to 0.58 [35] |
| Ai2 Asta, OpenScholar | Semantic Scholar, about 214M | inline citations to retrieved passages | yes | none | Nature paper [38]; AstaBench [39]; citation instability [40] |
| Undermind | Semantic Scholar | ranked report with a completeness estimate | rate-limited | about $16 to $20 [single source] | vendor whitepaper only [41] |
| Google Scholar Labs | Google Scholar, top 300 results screened | papers with an explanation of fit | yes, limited rollout | none | one library test: 6 of 10 and 8 of 10 results relevant [46] |

Three cross-tool findings matter more than any single score. Retrieval-grounded academic tools rarely invent papers, but they mis-extract details (Elicit and ChatGPT each fabricated 3% to 4% of extracted values in one Cochrane test [36]) and they miss most of what a proper search finds. A May 2026 review of literature tools found low reproducibility, limited transparency about which databases were searched, and highlighted passages that often failed to support the answer, and judged them unsuitable for systematic reviews [47]. And a May 2026 Arthroplasty Today study found ChatGPT-5 Deep Research recovered 47.5% of a gold-standard paper set against 85.2% for clinical fellows [48]. One widely shared article comparing Elicit, SciSpace and Consensus has been retracted and shouldn't be cited [49].

## Concision

Every measure points the same way. More citations do not mean better support, and the longer the report, the more of its citations fail to check out.

- Gemini Deep Research produced about 113 URLs per query, the most of any system, alongside the highest fabrication rate; the authors found the relationship between citation volume and reliability "is, if anything, inverse" [3].
- Gemini emitted three times as many cited statements as OpenAI on ReportBench with no gain in recall [10].
- In "Cited but Not Verified" (May 2026), frontier agents' links worked more than 94% of the time and were relevant more than 80% of the time, but only 39% to 77% of citations factually supported the claim, and accuracy fell about 42% as retrieval depth rose from 2 to 150 tool calls [8] [single source].
- Reviewers describe OpenAI's reports as the longest and prone to over-citing, Gemini's breadth as diluting focus, Perplexity's output as shorter, and Copilot Researcher's as 20 to 30 pages and hard to skim [24][26][27].

Practical defaults that follow: ask for a brief before a full report, restrict the search to trusted sites where the tool allows it, and click every link you intend to rely on.

## What would change this ranking

- A 2026 per-product FACT table. DeepResearch Bench's live board moved to Hugging Face in March 2026 and a mirror shows its citation columns blank for the top entries [2].
- An independent link-reliability test of the Gemini 3.x-era Deep Research agent. The 13.3% figure is from the 2.5 Pro era.
- An independent test of Claude Research as a product rather than Claude models with search.
- NewsGuard's May 2026 per-bot rates, and any 2026 repeat of the Tow Center test.
- Full text of the 2026 Zapier, Tom's Guide and TechRadar comparisons, which were read here only as search excerpts.

## Sources

Access key: "read directly" means the page was opened from this environment; "excerpt" means the figures come from search-result excerpts of that page because the host was blocked; "mirror" means a GitHub copy of the paper or table was read.

Benchmarks and studies

1. Du et al., "DeepResearch Bench: A Comprehensive Benchmark for Deep Research Agents", arXiv 2506.11763, June 2025 (ICLR 2026). https://arxiv.org/abs/2506.11763 and https://deepresearch-bench.github.io/ (excerpt; site table read from its GitHub Pages source).
2. DeepResearch Bench repository news, updated 22 September 2026. https://github.com/Ayanami0730/deep_research_bench (read directly).
3. Rao, Wong and Callison-Burch, "Detecting and Correcting Reference Hallucinations in Commercial LLMs and Deep Research Agents", arXiv 2604.03173, 3 April 2026. https://arxiv.org/abs/2604.03173 (excerpt; table read from a mirror).
4. Tow Center for Digital Journalism, "AI Search Has a Citation Problem", Columbia Journalism Review, 6 March 2025. https://www.cjr.org/tow_center/we-compared-eight-ai-search-engines-theyre-all-bad-at-citing-news.php (excerpt; per-tool counts also via Nieman Lab, https://www.niemanlab.org/2025/03/ai-search-engines-fail-to-produce-accurate-citations-in-over-60-of-tests-according-to-new-tow-center-study/).
5. EBU and BBC, "News Integrity in AI Assistants", 22 October 2025. https://www.ebu.ch/research/open/report/news-integrity-in-ai-assistants (excerpt; also NPR, https://www.npr.org/sections/npr-extra/2025/10/21/g-s1-94424/global-study-on-news-integrity-in-ai-assistants-shows-need-for-safeguards-and-improved-accuracy).
6. NewsGuard, AI False Claims Monitor, August 2025 audit (published September 2025). https://www.newsguardtech.com/ai-monitor/august-2025-ai-false-claim-monitor/ (excerpt; per-bot rates via Euronews, https://euronews.com/next/2025/09/05/which-ai-chatbot-spews-the-most-false-information-1-in-3-ai-answers-are-false-study-says).
7. NewsGuard, AI False Claims Monitor, January 2026 quarterly. https://www.newsguardtech.com/ai-monitor/january-2026/ (excerpt).
8. Onweller et al., "Cited but Not Verified", arXiv 2605.06635, May 2026. https://arxiv.org/abs/2605.06635 (excerpt).
9. DRACO: "a Cross-Domain Benchmark for Deep Research Accuracy, Completeness, and Objectivity", Perplexity and Harvard, arXiv 2602.11685, 12 February 2026. https://arxiv.org/abs/2602.11685 (excerpt).
10. Li et al., "ReportBench: Evaluating Deep Research Agents via Academic Survey Tasks", arXiv 2508.15804, August 2025. https://github.com/ByteDance-BandAI/ReportBench (mirror, read directly).
11. Zhan et al., "DeepHalluBench", arXiv 2601.22984, January 2026. https://github.com/yuhao-zhan/DeepHalluBench (mirror, read directly).
12. Fan et al., "HalluHard", EPFL, arXiv 2602.01031, February 2026. https://arxiv.org/abs/2602.01031 (excerpt; table from a mirror).
13. Scale AI, "ResearchRubrics", arXiv 2511.07685, November 2025. https://github.com/scaleapi/researchrubrics (read directly; scores from excerpt).
14. Vectara Hallucination Leaderboard, updated 22 September 2026. https://github.com/vectara/hallucination-leaderboard/ (read directly).
15. Microsoft 365 Copilot blog, "Introducing multi-model intelligence in Researcher", 30 March 2026. https://techcommunity.microsoft.com/blog/microsoft365copilotblog/introducing-multi-model-intelligence-in-researcher/4506011 (excerpt).
16. steel-dev source-linked benchmark leaderboard (BrowseComp rows with vendor source dates), reviewed 22 September 2026. https://github.com/steel-dev/leaderboard (read directly).
17. Anthropic, "Introducing Claude Opus 5.5", 22 September 2026. https://www.anthropic.com/news/claude-opus-5-5 (read directly).

Vendor pages, consumer products

18. Anthropic, "Using Research on Claude", support article updated 2 June 2026. https://support.claude.com/en/articles/11088861-using-research-on-claude (read directly). Anthropic, "How we built our multi-agent research system", 13 June 2025. https://www.anthropic.com/engineering/built-multi-agent-research-system (read directly).
19. OpenAI Help, "Deep research in ChatGPT" and ChatGPT release notes. https://help.openai.com/en/articles/10500283-deep-research-in-chatgpt and https://help.openai.com/en/articles/6825453-chatgpt-release-notes (excerpt).
20. Microsoft Learn, "Researcher agent FAQ" and "Get started with Researcher agent". https://learn.microsoft.com/microsoft-365/copilot/faq-researcher and https://learn.microsoft.com/microsoft-365/copilot/researcher-agent (read directly).
21. Perplexity Help Centre, "What is Research mode?" and "Perplexity Max". https://www.perplexity.ai/help-center/en/articles/10738684-what-is-research-mode and https://www.perplexity.ai/help-center/en/articles/11680686-perplexity-max (excerpt); pricing tiers via https://felloai.com/perplexity-pricing/ (third party).

Reviews

22. Zapier, "Perplexity vs. ChatGPT: Which AI tool is better? [2026]". https://zapier.com/blog/perplexity-vs-chatgpt/ (excerpt).
23. Tom's Guide, "I tested ChatGPT vs. Perplexity for research, and this is the one I recommend". https://www.tomsguide.com/ai/i-tested-chatgpt-vs-perplexity-for-research-and-this-is-the-one-i-recommend (excerpt, undated).
24. Zapier, "Gemini vs. ChatGPT: What's the difference? [2026]", https://zapier.com/blog/gemini-vs-chatgpt/, and Superkind, "The Best AI Deep Research Tools in 2026", https://superkind.ai/blog/ai-deep-research-tools (excerpt; the second is a lower-credibility comparison site).
25. Van Slyke, "Deep Research isn't really deep research". https://aigoestocollege.substack.com/p/deep-research-isnt-really-deep-research (excerpt).
26. aimultiple, deep-research benchmark and length findings. https://aimultiple.com/ai-deep-research (excerpt).
27. Office-Watch, Copilot Deep Research review. https://office-watch.com/2025/copilot-deep-research-review-results/ (excerpt).
28. Notebookcheck, "Microsoft Copilot: Deep Research ends, successor is paid only", 2026. https://www.notebookcheck.net/Microsoft-Copilot-Deep-Research-ends-successor-is-paid-only.1371446.0.html (excerpt).

Academic tools

29. Elicit pricing and sources. https://elicit.com/pricing and https://support.elicit.com/en/articles/553025 (excerpt).
30. Consensus subscription plans, research database and Meter guardrails. https://help.consensus.app/en/articles/10087865-subscription-plans, https://help.consensus.app/en/articles/10055108-consensus-research-database and https://consensus.app/home/blog/consensus-meter/ (excerpt).
31. Scite pricing and features. https://scite.ai/pricing and https://scite.ai/features (excerpt).
32. Hilkenmeier et al., Social Science Computer Review, 2025. https://journals.sagepub.com/doi/10.1177/08944393251404052 (excerpt).
33. Lau et al., Cochrane Evidence Synthesis and Methods, 2025. https://onlinelibrary.wiley.com/doi/full/10.1002/cesm.70050 (excerpt).
34. O'Rourke et al., Western Journal of Nursing Research, August 2026. https://doi.org/10.1177/01939459261451723 (excerpt).
35. Bakker, Theis-Mahon and Brown, Hypothesis, 2023. https://journals.indianapolis.iu.edu/index.php/hypothesis/article/view/26528 (excerpt).
36. Helms Andersen et al., Cochrane Evidence Synthesis and Methods, 2025. https://onlinelibrary.wiley.com/doi/full/10.1002/cesm.70036 (excerpt).
37. Reference Hallucination Score, JMIR Medical Informatics, 2024. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11325115/ (excerpt).
38. OpenScholar, Nature, 4 February 2026. https://www.nature.com/articles/s41586-025-10072-4 (excerpt).
39. Ai2, AstaBench spring 2026 update, 30 April 2026. https://allenai.org/blog/astabench-update-spring-2026 (excerpt).
40. Asta citation system study, arXiv 2606.08301, June 2026. https://arxiv.org/abs/2606.08301 (excerpt).
41. Undermind whitepaper. https://www.undermind.ai/whitepaper.pdf (excerpt); pricing via https://www.buildfastwithai.com/ai-tools/undermind (third party).
42. Claude plans and pricing. https://claude.com/pricing (read directly, 30 September 2026).
43. Google Help, "Use Deep Research in Gemini Apps", https://support.google.com/gemini/answer/15719111 (excerpt); Google AI Pro price and session limit via https://www.datastudios.org/post/gemini-pro-subscription-breakdown-with-pricing-usage-and-hidden-advantages and https://felloai.com/gemini-pricing/ (third party).
44. xAI pricing, https://x.ai/pricing (excerpt); tiers via https://costbench.com/software/ai-chatbots/grok/ (third party).
45. Microsoft 365 Copilot pricing. https://www.microsoft.com/en-us/microsoft-365-copilot/pricing (read directly; the Business add-on showed $25.20 per user per month, against about $30 quoted on Microsoft Learn Q&A).
46. Villanova University Falvey Library on Google Scholar Labs, 15 April 2026. https://blog.library.villanova.edu/2026/04/15/scholar-labs-ai-search-from-google-scholar-for-business-research/ (excerpt).
47. "Useful for Exploration, Risky for Precision", arXiv 2605.10125, May 2026. https://arxiv.org/abs/2605.10125 (excerpt).
48. Arthroplasty Today, deep-research agents against clinical fellows, 2026. https://pmc.ncbi.nlm.nih.gov/articles/PMC13194160/ (excerpt).
49. Retracted: "Assessing the Effectiveness of AI Tools (Elicit, SciSpace, and Consensus)", Canadian Journal of Information and Library Science. https://ojs.lib.uwo.ca/index.php/cjils/article/view/23075 (excerpt; listed only so it isn't cited).
