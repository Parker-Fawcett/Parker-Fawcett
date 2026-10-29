# Parker Fawcett

I'm Parker. I run a small lab with one rule: publish the red ink too. Every project here keeps score honestly, passes and failures alike. Most of my time goes to AI evaluation, how you tell whether a system does what you claim, and to open-source infrastructure that makes that check reproducible.

## Selected engineering work

- **AI Skills Engineer — CHG Healthcare.** Build enterprise MCP tooling and agent workflows, including automated validation and developer tooling.
- **Rebuild Dossier — coding-agent evaluation research.** In a deliberately constructed control, an HTTP-200 stub passed **20/20 visible and 12/12 held-out test files** but matched **0/77 checks** in a separate, author-written behavioral fidelity oracle. [Reproduce the baseline](https://github.com/Parker-Fawcett/rebuild-dossier/tree/main/evidence/baselines/constant-200) · [Scoring protocol and limits](https://github.com/Parker-Fawcett/rebuild-dossier/blob/main/evidence/fidelity-oracle/PROTOCOL.md)
- **OpenClaw — three merged upstream fixes.** [Clamp Responses output tokens](https://github.com/openclaw/openclaw/pull/128282) · [Preserve tool-result whitespace](https://github.com/openclaw/openclaw/pull/128266) · [Prevent duplicate Telegram progress output](https://github.com/openclaw/openclaw/pull/128259)

## Research

Rebuild-Dossier: https://github.com/Parker-Fawcett/rebuild-dossier
A tool that reverse engineers a rebuild spec from a running app. It generates a locked CLAUDE.md and tests you can run to see if a rebuild matches the original.
Paper: https://arxiv.org/abs/2608.23616 | DOI: https://doi.org/10.5281/zenodo.22036801 | SSRN: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7468682

Stock audit lab: a private quant lab auditing a community-documented AI stock predictor with its methodology intact. Every strategy runs against monkey baselines and sealed holdouts, and every failure stays on the record. Manuscript in progress. The repo goes public on acceptance.

## Products

Keepsake: https://github.com/Parker-Fawcett/Keepsake
A relationship-aware notes app. Paste or speak messy notes and it organizes the people, dates, memories, and reminders inside them. Express, Postgres, Docker.

CatchAndTrade: https://github.com/Parker-Fawcett/catchandtrade (live at https://catchandtrade.com)
Trading card marketplace and portfolio. Full stack, TypeScript monorepo.

Totally-Normal: https://github.com/Parker-Fawcett/Totally-Normal
A site built entirely in Whitespace. The source file has no visible characters.

## How I build

Mostly Python and TypeScript. React and Next.js on the front end, Postgres and Docker underneath. I've also used Kotlin and JavaScript a lot.

## Elsewhere

https://www.parkerfawcett.com
ORCID: https://orcid.org/0009-0003-9699-7422
Skora: https://skoraadmit.com AI college counseling platform (live product, repo private)
