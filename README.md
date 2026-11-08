# Awesome-AI-Contract-Execution-Operations-Copilot

# Awesome-AI-Contract-Execution-Operations-Copilot

**Top AI Contract Execution Operations Copilot (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Post-Signature Obligation Tracking, Agentic Contract Reasoning, Source-Linked Extraction & Self-Hosted CLM*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Contract Execution & Operations Copilot**. These tools enable legal and contract operations teams to move beyond static contract storage—extracting obligations, tracking renewals, answering portfolio questions in natural language, and executing post-signature workflows with AI agents at every step.



**Examples** include Icertis Vera Copilot, Ironclad AI, Robin AI, Spellbook, Casetext CoCounsel, Harvey AI, ContractPodAi Leah, Luminance, Evisort AI, and Lexion AI (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted contract AI, obligation extraction, and open CLM infrastructure. **Critical note**: The open-source landscape has matured to the point where a viable self-hosted CLM exists—**draftLegal** is the most complete open-source Ironclad + Harvey alternative, with eight specialist agents, hybrid retrieval over your portfolio, and full lifecycle from drafting to obligation tracking . **Aakd** takes the opposite approach—deliberately narrow, human-controlled post-signature operations with source-linked citations and optional AI . No open-source project matches Icertis Vera's contract data lake or Harvey's legal reasoning depth, but for teams wanting data sovereignty and no six-figure SaaS costs, the options are production-capable.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Contract Lifecycle Management (CLM) and contract AI market is valued at approximately **$1.8B to $2.1B** and projected to grow at a **~12% CAGR** to surpass **$5B+ by the mid-2030s**. The sector remains **moderately fragmented**—with over 150+ regional and specialized providers alongside a low top-5 vendor concentration (~28–35%)—though aggressive consolidation and mega-rounds from AI leaders continue to reshape enterprise adoption.

## SaaS/Hosted Platforms

| Platform | Company Scale (Valuation / Revenue) | Pricing | Free Tier / Trial Limits | Description & Best For | Trade-offs |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Harvey AI** | **$15.5B valuation** (~$400M+ ARR) | ~$1,000–$1,200 / user / month (min. 20–25 seats; entry ~$288K–$360K / year) | No free tier; demo / sales-assisted PoC only upon qualification | Generative AI platform for deep contract reasoning, clause drafting, and portfolio search; best for top law firms and legal teams | No native execution/CLM layer (approvals, e-sign); requires pairing with tools like Ironclad |
| **Icertis Vera Copilot** | **$5.0B valuation** (~$300M–$350M ARR) | ~$48,000–$100,000+ / year base subscription (typically $150–$350 / user / month equivalent) | No free tier or public free trial; sales-assisted enterprise demo/PoC only | Enterprise contract intelligence control plane with agentic obligation execution (Vera Operate); deeply embedded in SAP, Microsoft, and Salesforce | Steep six-figure initial commitments; complex implementation and onboarding cycles |
| **Ironclad AI** | **$3.2B valuation** (~$200M+ ARR) | ~$50,000–$60,000+ / year starting tier (approx. $200–$600 / user / month equivalent) | No free tier or self-serve trial; custom sales-led demo/PoC only | Workflow-first CLM with AI assistance, obligation tracking, and Harvey integration; best for scalable legal ops approval chains | AI reasoning is less native compared to Harvey; dependency on external partnerships |
| **Casetext CoCounsel** | **$650M acquisition** (Thomson Reuters) | ~$340–$630+ / user / month (Essentials tier; Legal suite upwards of $1,600+ / month) | No permanent free tier; time-limited sales-provisioned evaluation trial upon request | AI legal research, contract review, and document analysis integrated into Westlaw / Practical Law ecosystems | Transitioned into Thomson Reuters enterprise bundles; standalone product no longer available |
| **ContractPodAi Leah** | **~$250M–$700M valuation** (~$40M–$57M ARR) | ~$50,000–$65,000 / year starting platform fee (unlimited user tier + AI add-on) | No free tier or public trial; sales consultation and custom enterprise demo only | AI-native CLM with intake portal ("Legal Front Door"), automated redlining, and obligation tracking | Substantial first-year setup and workflow configuration investment |
| **Luminance** | **~$400M valuation** (~$30M ARR, $165M raised) | ~$40,000–$60,000+ / year starting tier (volume/capacity-based document licensing) | No free tier or self-serve trial; request-only corporate demonstration and trial | Proprietary legal LLM specializing in portfolio-wide contract analysis, due diligence, and automated negotiation | Pricing scales quickly with contract repository size; less focused on mid-market self-serve teams |
| **Spellbook** | **$350M valuation** (~$100M ARR) | ~$50–$350+ / user / month (tailored quote by team seat count & add-on agents) | **7-day free trial** (access to Word add-in drafting, redlining, and playbooks; no credit card required) | AI contract drafting, review, and playbook benchmarking directly inside Microsoft Word | Primarily focused on drafting and pre-signature review; not a comprehensive post-signature CLM |
| **Evisort AI** | **$311M acquisition** (Workday) | ~$30,000–$60,000 / year starting tier (covering 500–2,000 contracts) | No free tier or self-serve trial; demo and enterprise proof-of-concept through sales | AI contract intelligence and post-signature obligation tracking with analytics; integrated into Workday CLM | Primarily analytics- and extraction-driven; requires Workday ecosystem alignment post-acquisition |
| **Lexion AI** | **$165M acquisition** (DocuSign) | ~$15,000–$25,000 / year starting tier (approx. $1,500–$2,100 / month equivalent) | No free tier or self-serve trial; sales demo and guided evaluation only | Lightweight, accessible AI contract repository and workflow management for mid-market teams | Now part of DocuSign; advanced enterprise features require higher DocuSign tiers |
| **Robin AI** | **~$70M+ raised / ~$10M ARR** | Free plan available; paid tiers quote-based (custom volume/seat pricing) | **Free Forever Plan** (capped at 1 user and ~10 AI messages/queries per day) | AI contract review and redlining assistant powered by custom legal models; best for rapid clause checks | Free tier limited to basic exploratory queries; advanced playbook automation requires paid plans |



## Open-Source GitHub Projects



- **draftLegal**

  **Open-source alternative to Ironclad + Harvey** (license per repo) — **the most complete open-source AI-native CLM**, with full lifecycle from drafting to obligation tracking and a chat assistant with ~30 tools over your contracts . **Features**: **Agent-first architecture**—chat assistant with ~30 tools (search, cite, compare, draft, redline, route approvals); every write proposed on a confirm card first, most undoable; **eight specialist agents** (review, draft, redline, approval summary, playbook review, assist, ask, portfolio) running as background jobs . **Extract + cite**—clauses, dates, and values extracted, risk-scored, and cited to the clause and section; PDF citations open the original at its page . **Portfolio intelligence**—hybrid retrieval (pgvector + Elasticsearch + RRF fusion) for cross-portfolio questions about exposure, counterparties, renewals, and notice deadlines . **Full lifecycle**—approval workflows, in-platform e-signature, and post-signature obligation tracking . **Bring your own model**—Anthropic, OpenAI, or Google Gemini; no vendor lock-in . **Self-hosted & private**—`docker compose up` on your own infra; contracts never touch a third-party SaaS . **Tech stack**: Node.js, Python, React, PostgreSQL, Elasticsearch, pgvector . **Deploy**: Self-hosted (`pnpm dev:setup` then `pnpm dev`) or hosted demo at app.draft-legal.com . **Trade-off**: **Early-stage project**—some agents (ask, portfolio) lack UI; complex setup (Docker, Node 22+, Python 3.11+) . **Best for**: legal and contract operations teams wanting self-hosted AI-native CLM that reasons over the entire portfolio—with full data sovereignty and no six-figure SaaS costs.



- **Aakd**

  **Open-source, self-hostable CLM for reviewed, source-linked contract operations** (AGPL-3.0) — **the most focused open-source tool for post-signature obligation management**, deliberately narrow and human-controlled . **Features**: **Source-linked extraction**—upload executed PDF/DOCX, review extracted fields and obligations with **exact page-level citations**, correct anything wrong, assign owners and due dates . **Obligation and renewal views** with owners, deadlines, reminders, and audit history; **organization-scoped approvals**, comments, notifications, and activity logs . **AI is optional**—extraction, questions, and risk signals are reviewable and **never the canonical source of truth**; local Ollama support for privacy . **Contract repository** with OCR, folders, tags, search, and version history; REST API and scoped MCP endpoint for agent-assisted, human-controlled workflows . **Tech stack**: TypeScript, PostgreSQL, Redis, MinIO . **Deploy**: Self-hosted (Docker Compose for local; production installer for Ubuntu VM) . **Trade-off**: **Early release (Phase 0)**—customer validation in progress; authoring, template management, and autonomous agents are explicitly out of scope for the first release; new e-signature sends are temporarily paused . **Best for**: contract operations teams wanting to turn executed contracts into reviewed, owned actions with source-linked evidence—without autonomous AI taking over legal judgment.



### Additional Strong Open-Source Options



- **contract-vault** — Post-signature management CLI for executed contracts (PyPI, zero dependencies). Git-backed vault, obligation tracking, renewal/notice/payment deadlines as `.ics` calendar, deterministic field provenance with confidence scores . **Note**: **CLI tool, not a full CLM**—no AI agent, no approval workflows, no e-signature; pairs with `extract-cli` for ingestion . **Best for**: developers and legal ops wanting a lightweight, auditable contract register with deadline tracking.

- **OpenContracts** — Open-source contract analysis with citation network (MIT). Converts contract libraries into searchable knowledge graphs; built-in MCP server for Claude Code; each answer carries source citations . **Note**: **Analysis and RAG layer**—not a full CLM with approvals or obligation workflows . **Best for**: teams wanting portfolio-wide contract search and reasoning with citations.

- **signcraft** — Open-source AI contract review & e-signature platform (open source). Free alternative to DocuSign, Adobe Sign, and PandaDoc; draft, review, and sign with AI-powered clause analysis . **Note**: **E-signature and review focus**—less depth in post-signature obligation tracking than Aakd . **Best for**: teams wanting open-source contract signing with AI review.

- **ContractSpark** — Open-source AI contract generator (open source). AI smart builder, real-time preview, customizable templates, one-click PDF export; works offline . **Note**: **Generation only**—no lifecycle, approvals, or obligation tracking . **Best for**: teams wanting AI-assisted contract drafting without SaaS costs.



**Frameworks for building custom systems**: Combine **draftLegal** for AI-native lifecycle management and portfolio intelligence with **Aakd** for source-linked obligation tracking, **contract-vault** for CLI-based deadline management, and **OpenContracts** for citation-network search—creating a composable open-source contract AI stack. **None of these match Icertis Vera's contract data lake or Harvey's legal reasoning depth**, but for teams prioritizing data sovereignty and AI-agent workflows, the options are production-capable.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Contract AI platforms handling privileged legal documents must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls and confidentiality safeguards.

- **The "full CLM with AI agents" vs. "post-signature operations" vs. "analysis/RAG" vs. "e-signature" vs. "generation" distinction is critical.** **draftLegal** is a **full CLM with AI agents**—drafting, review, redline, approval, e-sign, and obligation tracking with agents at every step . **Aakd** is **post-signature operations**—it focuses on turning executed contracts into reviewed, owned obligations with citations; authoring is out of scope . **contract-vault** is a **CLI register**—deadline tracking and field provenance, not a platform . **OpenContracts** is **analysis/RAG**—citation-network search over a portfolio . **signcraft** is **e-signature + review**—signing with AI clause analysis . **ContractSpark** is **generation**—drafting contracts, not managing them . **Choose based on whether you need full lifecycle, post-signature tracking, portfolio search, signing, or drafting.**

- **draftLegal is the most complete open-source CLM attempt**, combining Ironclad's execution layer with Harvey-style contract intelligence in one self-hosted platform . **The trade-off**: early-stage with complex setup; some agents lack UI. **For teams wanting AI-native CLM with data sovereignty, it is the most ambitious option.**

- **Aakd takes the opposite philosophy**—deliberately narrow and human-controlled, with AI as an optional assistant that is **never the canonical source of contract truth** . **The trade-off**: Phase 0 release with authoring out of scope; e-signature sends paused. **For contract operations teams wanting source-linked obligation tracking without autonomous AI risk, it is the more conservative choice.**

- **Icertis Vera is the enterprise benchmark**—a conversational control plane that understands query intent, searches the repository, and invokes agents for creation, review, and reconciliation . **Vera Operate** turns commitments into fulfilled actions, tracking obligations and triggering downstream events . **The trade-off**: six-figure enterprise commitment; deep SAP/Microsoft/Salesforce integration is the value driver.

- **Harvey and Ironclad's partnership reflects the market split**—Harvey has intelligence but no execution layer; Ironclad has execution but weak intelligence . **No single commercial vendor covers both natively** except Icertis with Vera.

- Self-hosted open-source solutions require proper infrastructure (PostgreSQL, Elasticsearch for draftLegal; MinIO, Redis for Aakd), security hardening, and ongoing maintenance. **Contracts contain privileged and confidential information**—ensure your deployment meets your organization's security and compliance requirements before migrating production legal documents.



---



**Made for legal operations teams, contract managers, and organizations building transparent contract AI solutions.**

Let's make AI Contract Execution & Operations Copilots more open, data-driven, and obligation-aware.
