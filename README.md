<h1 align="center">Awesome Claude Corporate Skills</h1>

<p align="center">
  <strong>The largest curated collection of Claude AI skills organized by corporate role</strong>
</p>

<p align="center">
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge-flat2.svg" alt="Awesome" />
  </a>
  <img src="https://img.shields.io/badge/Skills-166-blue?style=flat-square" alt="166 Skills"/>
  <img src="https://img.shields.io/badge/Roles-14-green?style=flat-square" alt="14 Categories"/>
  <img src="https://img.shields.io/badge/Claude-Code%20%7C%20Cowork%20%7C%20API-purple?style=flat-square" alt="Claude Platforms"/>
  <a href="https://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome" />
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="License: MIT" />
  </a>
</p>

<p align="center">
  166 production-ready skills across 14 categories &mdash; from executive strategy and investment banking to procurement and document processing.
  <br />
  Built for <a href="https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview">Claude Code</a>, <a href="https://claude.ai">Claude Cowork</a>, and any tool supporting the open <code>SKILL.md</code> format.
</p>

---

## Contents

- [What Are Claude Skills?](#what-are-claude-skills)
- [Quick Start](#quick-start)
- [Skills by Role](#skills-by-role)
  - [Meta Tools](#00--meta-tools)
  - [Executive Leadership](#01--executive-leadership)
  - [Finance & Accounting](#02--finance--accounting)
  - [Human Resources](#03--human-resources)
  - [Marketing](#04--marketing)
  - [Sales](#05--sales)
  - [Legal & Compliance](#06--legal--compliance)
  - [Operations](#07--operations)
  - [IT & Engineering](#08--it--engineering)
  - [Product Management](#09--product-management)
  - [Data & Analytics](#10--data--analytics)
  - [Customer Success](#11--customer-success)
  - [Procurement & Supply Chain](#12--procurement--supply-chain)
  - [Document Processing](#13--document-processing)
- [Folder Structure](#folder-structure)
- [Sources](#sources)
- [Contributing](#contributing)
- [Resources](#resources)
- [License](#license)

## What Are Claude Skills?

Claude Skills are reusable instruction sets (`.md` files) that teach Claude how to perform specific tasks in a repeatable, standardized manner. Think of them as **expert playbooks** — each skill encodes domain knowledge, best-practice workflows, templates, and edge-case handling so that Claude can deliver consistent, high-quality output across any platform.

Skills work everywhere Claude does: **Claude Code** (CLI), **Claude Cowork** (web), and the **Claude API**.

## Quick Start

### Claude Code (CLI)

```bash
# Clone the full collection
git clone https://github.com/w95/awesome-claude-corporate-skills.git

# Copy a whole role to your project
cp -r awesome-claude-corporate-skills/02-finance-accounting/.  ~/.claude/skills/

# Or cherry-pick individual skills
cp -r awesome-claude-corporate-skills/02-finance-accounting/dcf-model ~/.claude/skills/

# Start Claude Code — skills load automatically
claude
```

### Claude Cowork (Web)

Select this repo folder as your workspace — all skills in scope become automatically available.

### Manual / API

Open any `SKILL.md` and use the instructions directly as a system prompt or reference material in API calls.

## Skills by Role

### 00 — Meta Tools

> *Skills about skills — tooling for creating and managing your skill collection.*

| Skill | Description |
|-------|-------------|
| [skill-creator](00-meta/skill-creator/) | Guidance for creating effective Claude Skills with specialized knowledge, workflows, and tool integrations |
| [CrakSEO/skills](https://github.com/CrakSEO/skills) | Connect Claude/Cursor/Codex to CrakSEO remote MCP servers for keyword research, SERP, backlinks, rank tracking, site audit, local SEO, AI visibility, Search Console and URL indexing | Claude Code, Cursor, Codex | MIT |

### 01 — Executive Leadership

> *Strategic planning, board prep, M&A, KPIs, and crisis communications.*

| Skill | Source | Description |
|-------|--------|-------------|
| [strategic-planning](01-executive-leadership/strategic-planning/) | Custom | OKRs, SWOT, vision docs, strategic frameworks |
| [board-meeting-prep](01-executive-leadership/board-meeting-prep/) | Custom | Board decks, agendas, governance materials |
| [executive-communication](01-executive-leadership/executive-communication/) | Custom | All-hands, investor updates, crisis comms |
| [kpi-dashboard](01-executive-leadership/kpi-dashboard/) | Custom | Executive scorecards, metric tracking |
| [ma-due-diligence](01-executive-leadership/ma-due-diligence/) | Custom | M&A evaluation, integration planning |
| [competitive-analysis](01-executive-leadership/competitive-analysis/) | Anthropic FSP | Competitive landscape analysis |
| [change-management](01-executive-leadership/change-management/) | Anthropic KWP | Organizational change planning |
| [risk-assessment](01-executive-leadership/risk-assessment/) | Anthropic KWP | Enterprise risk evaluation |
| [knowledge-synthesis](01-executive-leadership/knowledge-synthesis/) | Anthropic KWP | Cross-source knowledge consolidation |
| [task-management](01-executive-leadership/task-management/) | Anthropic KWP | Productivity and task tracking |
| [internal-comms](01-executive-leadership/internal-comms/) | Anthropic Skills | Internal communications |
| [deep-research](01-executive-leadership/deep-research/) | Community | Autonomous multi-step research using Gemini Deep Research Agent |

### 02 — Finance & Accounting

> *The deepest section — 42 skills covering DCF, LBO, 3-statement models, equity research, PE, wealth management, and IB pitch decks.*

<details>
<summary><strong>View all 42 skills</strong></summary>

| Skill | Source | Description |
|-------|--------|-------------|
| [3-statements](02-finance-accounting/3-statements/) | Anthropic FSP | Three-statement financial models |
| [dcf-model](02-finance-accounting/dcf-model/) | Anthropic FSP | Discounted cash flow valuation |
| [lbo-model](02-finance-accounting/lbo-model/) | Anthropic FSP | Leveraged buyout modeling |
| [comps-analysis](02-finance-accounting/comps-analysis/) | Anthropic FSP | Comparable company analysis |
| [check-model](02-finance-accounting/check-model/) | Anthropic FSP | Financial model auditing |
| [merger-model](02-finance-accounting/merger-model/) | Anthropic FSP | Merger & acquisition modeling |
| [pitch-deck](02-finance-accounting/pitch-deck/) | Anthropic FSP | Investment banking pitch decks |
| [deal-tracker](02-finance-accounting/deal-tracker/) | Anthropic FSP | Deal pipeline management |
| [datapack-builder](02-finance-accounting/datapack-builder/) | Anthropic FSP | Data package assembly |
| [cim-builder](02-finance-accounting/cim-builder/) | Anthropic FSP | Confidential Information Memorandums |
| [buyer-list](02-finance-accounting/buyer-list/) | Anthropic FSP | Potential buyer identification |
| [teaser](02-finance-accounting/teaser/) | Anthropic FSP | Deal teaser documents |
| [process-letter](02-finance-accounting/process-letter/) | Anthropic FSP | M&A process letters |
| [strip-profile](02-finance-accounting/strip-profile/) | Anthropic FSP | Financial strip profiles |
| [earnings-analysis](02-finance-accounting/earnings-analysis/) | Anthropic FSP | Post-earnings analysis |
| [earnings-preview](02-finance-accounting/earnings-preview/) | Anthropic FSP | Pre-earnings estimates |
| [sector-overview](02-finance-accounting/sector-overview/) | Anthropic FSP | Industry sector reports |
| [morning-note](02-finance-accounting/morning-note/) | Anthropic FSP | Daily market briefings |
| [initiating-coverage](02-finance-accounting/initiating-coverage/) | Anthropic FSP | Research initiation reports |
| [model-update](02-finance-accounting/model-update/) | Anthropic FSP | Financial model updates |
| [catalyst-calendar](02-finance-accounting/catalyst-calendar/) | Anthropic FSP | Event catalyst tracking |
| [thesis-tracker](02-finance-accounting/thesis-tracker/) | Anthropic FSP | Investment thesis monitoring |
| [idea-generation](02-finance-accounting/idea-generation/) | Anthropic FSP | Investment idea generation |
| [dd-checklist](02-finance-accounting/dd-checklist/) | Anthropic FSP | Due diligence checklists |
| [dd-meeting-prep](02-finance-accounting/dd-meeting-prep/) | Anthropic FSP | DD meeting preparation |
| [deal-sourcing](02-finance-accounting/deal-sourcing/) | Anthropic FSP | Deal origination |
| [deal-screening](02-finance-accounting/deal-screening/) | Anthropic FSP | Deal evaluation criteria |
| [unit-economics](02-finance-accounting/unit-economics/) | Anthropic FSP | Unit economics analysis |
| [portfolio-monitoring](02-finance-accounting/portfolio-monitoring/) | Anthropic FSP | Portfolio company tracking |
| [value-creation-plan](02-finance-accounting/value-creation-plan/) | Anthropic FSP | PE value creation plans |
| [ic-memo](02-finance-accounting/ic-memo/) | Anthropic FSP | Investment committee memos |
| [returns-analysis](02-finance-accounting/returns-analysis/) | Anthropic FSP | Investment returns analysis |
| [tax-loss-harvesting](02-finance-accounting/tax-loss-harvesting/) | Anthropic FSP | Tax-loss harvesting strategies |
| [financial-plan](02-finance-accounting/financial-plan/) | Anthropic FSP | Comprehensive financial planning |
| [investment-proposal](02-finance-accounting/investment-proposal/) | Anthropic FSP | Investment proposals |
| [client-review](02-finance-accounting/client-review/) | Anthropic FSP | Client portfolio reviews |
| [portfolio-rebalance](02-finance-accounting/portfolio-rebalance/) | Anthropic FSP | Portfolio rebalancing |
| [client-report](02-finance-accounting/client-report/) | Anthropic FSP | Wealth management reports |
| [spglobal-earnings-preview](02-finance-accounting/spglobal-earnings-preview/) | S&P Global | S&P earnings previews |
| [spglobal-tear-sheet](02-finance-accounting/spglobal-tear-sheet/) | S&P Global | Company tear sheets |
| [spglobal-funding-digest](02-finance-accounting/spglobal-funding-digest/) | S&P Global | Funding round digests |
| [invoice-organizer](02-finance-accounting/invoice-organizer/) | Community | Invoice management |

</details>

### 03 — Human Resources

> *Job descriptions, interview kits, onboarding, performance reviews, DEI strategy, and compensation benchmarking.*

| Skill | Source | Description |
|-------|--------|-------------|
| [job-description-writer](03-human-resources/job-description-writer/) | Custom | Inclusive, compelling JDs |
| [interview-kit-builder](03-human-resources/interview-kit-builder/) | Custom | Structured interview processes |
| [onboarding-planner](03-human-resources/onboarding-planner/) | Custom | 30-60-90 day onboarding plans |
| [performance-review-assistant](03-human-resources/performance-review-assistant/) | Custom | Reviews, PIPs, feedback |
| [compensation-benchmarking](03-human-resources/compensation-benchmarking/) | Custom | Salary bands, pay equity |
| [employee-handbook-builder](03-human-resources/employee-handbook-builder/) | Custom | Policy handbooks |
| [dei-strategy](03-human-resources/dei-strategy/) | Custom | Diversity & inclusion programs |
| [employee-engagement-survey](03-human-resources/employee-engagement-survey/) | Custom | Survey design & analysis |
| [resume-generator](03-human-resources/resume-generator/) | Community | Tailored resume creation |

### 04 — Marketing

> *Campaign planning, SEO, email marketing, social media, brand voice, visual design, and competitive ads.*

| Skill | Source | Description |
|-------|--------|-------------|
| [campaign-planner](04-marketing/campaign-planner/) | Custom | End-to-end campaign planning |
| [seo-content-optimizer](04-marketing/seo-content-optimizer/) | Custom | SEO optimization workflows |
| [email-marketing](04-marketing/email-marketing/) | Custom | Email campaigns & sequences |
| [social-media-strategy](04-marketing/social-media-strategy/) | Custom | Multi-platform social strategy |
| [market-research](04-marketing/market-research/) | Custom | Market sizing, personas, trends |
| [brand-guidelines](04-marketing/brand-guidelines/) | Anthropic Skills | Brand identity standards |
| [brand-voice-enforcement](04-marketing/brand-voice-enforcement/) | Anthropic KWP | Voice consistency |
| [guideline-generation](04-marketing/guideline-generation/) | Anthropic KWP | Brand guideline creation |
| [discover-brand](04-marketing/discover-brand/) | Anthropic KWP | Brand discovery |
| [competitive-ads-extractor](04-marketing/competitive-ads-extractor/) | Community | Competitor ad analysis |
| [content-research-writer](04-marketing/content-research-writer/) | Community | Research-driven content |
| [domain-name-brainstormer](04-marketing/domain-name-brainstormer/) | Community | Domain name ideation |
| [twitter-algorithm-optimizer](04-marketing/twitter-algorithm-optimizer/) | Community | X/Twitter optimization |
| [canvas-design](04-marketing/canvas-design/) | Community | Beautiful visual art in PNG/PDF with design philosophy |
| [theme-factory](04-marketing/theme-factory/) | Community | Professional font & color themes for artifacts and reports |

### 05 — Sales

> *Call prep, outreach drafting, lead enrichment, competitive intel, account research, and prospecting.*

| Skill | Source | Description |
|-------|--------|-------------|
| [call-prep](05-sales/call-prep/) | Anthropic KWP | Sales call preparation |
| [account-research](05-sales/account-research/) | Anthropic KWP | Account intelligence |
| [daily-briefing](05-sales/daily-briefing/) | Anthropic KWP | Daily sales briefings |
| [draft-outreach](05-sales/draft-outreach/) | Anthropic KWP | Outreach email drafting |
| [competitive-intelligence](05-sales/competitive-intelligence/) | Anthropic KWP | Competitive battlecards |
| [create-an-asset](05-sales/create-an-asset/) | Anthropic KWP | Sales collateral creation |
| [enrich-lead](05-sales/enrich-lead/) | Apollo | Lead enrichment |
| [prospect-apollo](05-sales/prospect-apollo/) | Apollo | Prospecting via Apollo |
| [sequence-load](05-sales/sequence-load/) | Apollo | Outreach sequences |
| [weekly-prep-brief](05-sales/weekly-prep-brief/) | Common Room | Weekly prep briefs |
| [contact-research](05-sales/contact-research/) | Common Room | Contact intelligence |
| [compose-outreach](05-sales/compose-outreach/) | Common Room | Outreach composition |
| [prospect-common-room](05-sales/prospect-common-room/) | Common Room | Signal-based prospecting |
| [call-prep-common-room](05-sales/call-prep-common-room/) | Common Room | Signal-based call prep |
| [account-research-common-room](05-sales/account-research-common-room/) | Common Room | Account signals |
| [lead-research-assistant](05-sales/lead-research-assistant/) | Community | Lead qualification |

### 06 — Legal & Compliance

> *Contract review, NDA triage, legal risk assessment, and compliance tracking.*

| Skill | Source | Description |
|-------|--------|-------------|
| [contract-review](06-legal-compliance/contract-review/) | Anthropic KWP | Clause-by-clause review |
| [nda-triage](06-legal-compliance/nda-triage/) | Anthropic KWP | NDA automated triage |
| [legal-risk-assessment](06-legal-compliance/legal-risk-assessment/) | Anthropic KWP | Legal risk evaluation |
| [compliance](06-legal-compliance/compliance/) | Anthropic KWP | Regulatory compliance |
| [compliance-tracking](06-legal-compliance/compliance-tracking/) | Anthropic KWP | Compliance monitoring |
| [canned-responses](06-legal-compliance/canned-responses/) | Anthropic KWP | Standard legal responses |
| [meeting-briefing](06-legal-compliance/meeting-briefing/) | Anthropic KWP | Legal meeting prep |

### 07 — Operations

> *SOPs, project status reports, business cases, postmortems, process optimization, and continuous improvement.*

| Skill | Source | Description |
|-------|--------|-------------|
| [sop-builder](07-operations/sop-builder/) | Custom | Standard Operating Procedures |
| [project-status-report](07-operations/project-status-report/) | Custom | RAG status reports |
| [business-case-builder](07-operations/business-case-builder/) | Custom | ROI and business cases |
| [incident-postmortem](07-operations/incident-postmortem/) | Custom | Blameless postmortems |
| [process-optimization](07-operations/process-optimization/) | Anthropic KWP | Process improvement |
| [resource-planning](07-operations/resource-planning/) | Anthropic KWP | Resource allocation |
| [vendor-management](07-operations/vendor-management/) | Anthropic KWP | Vendor relationships |
| [memory-management](07-operations/memory-management/) | Anthropic KWP | Context management |
| [file-organizer](07-operations/file-organizer/) | Community | File organization |
| [meeting-insights-analyzer](07-operations/meeting-insights-analyzer/) | Community | Meeting analysis |
| [kaizen](07-operations/kaizen/) | Community | Continuous improvement using Japanese Kaizen & Lean methodology |

### 08 — IT & Engineering

> *Code review, system design, incident response, testing, architecture, TDD, and tech debt management.*

| Skill | Source | Description |
|-------|--------|-------------|
| [code-review](08-it-engineering/code-review/) | Anthropic KWP | Code review workflows |
| [system-design](08-it-engineering/system-design/) | Anthropic KWP | Architecture design |
| [incident-response](08-it-engineering/incident-response/) | Anthropic KWP | Incident management |
| [testing-strategy](08-it-engineering/testing-strategy/) | Anthropic KWP | Test planning |
| [tech-debt](08-it-engineering/tech-debt/) | Anthropic KWP | Technical debt management |
| [documentation](08-it-engineering/documentation/) | Anthropic KWP | Technical documentation |
| [mcp-builder](08-it-engineering/mcp-builder/) | Anthropic Skills | MCP server creation |
| [webapp-testing](08-it-engineering/webapp-testing/) | Anthropic Skills | Web app testing |
| [frontend-design](08-it-engineering/frontend-design/) | Anthropic Skills | Frontend UI design |
| [changelog-generator](08-it-engineering/changelog-generator/) | Community | Release changelogs |
| [developer-growth-analysis](08-it-engineering/developer-growth-analysis/) | Community | Dev metrics |
| [langsmith-fetch](08-it-engineering/langsmith-fetch/) | Community | LangSmith integration |
| [software-architecture](08-it-engineering/software-architecture/) | Community | Clean Architecture, SOLID, and design patterns |
| [test-driven-development](08-it-engineering/test-driven-development/) | Community | TDD methodology for features and bugfixes |

### 09 — Product Management

> *PRDs, roadmaps, sprint planning, user research synthesis, and product launch playbooks.*

| Skill | Source | Description |
|-------|--------|-------------|
| [prd-writer](09-product-management/prd-writer/) | Custom | Product requirements docs |
| [roadmap-builder](09-product-management/roadmap-builder/) | Custom | Product roadmaps |
| [user-research-synthesizer](09-product-management/user-research-synthesizer/) | Custom | Research synthesis |
| [sprint-planning](09-product-management/sprint-planning/) | Custom | Agile sprint planning |
| [product-launch-playbook](09-product-management/product-launch-playbook/) | Custom | Launch planning |
| [feature-spec](09-product-management/feature-spec/) | Custom | Feature specifications |
| [doc-coauthoring](09-product-management/doc-coauthoring/) | Anthropic Skills | Collaborative writing |
| [search-strategy](09-product-management/search-strategy/) | Anthropic KWP | Information search |
| [source-management](09-product-management/source-management/) | Anthropic KWP | Source tracking |
| [brainstorming](09-product-management/brainstorming/) | Community | Transform rough ideas into fully-formed designs |

### 10 — Data & Analytics

> *Dashboards, SQL queries, statistical analysis, data visualization, CSV analysis, and PostgreSQL.*

| Skill | Source | Description |
|-------|--------|-------------|
| [data-validation](10-data-analytics/data-validation/) | Anthropic KWP | Data quality checks |
| [interactive-dashboard-builder](10-data-analytics/interactive-dashboard-builder/) | Anthropic KWP | Dashboard creation |
| [statistical-analysis](10-data-analytics/statistical-analysis/) | Anthropic KWP | Statistical methods |
| [data-visualization](10-data-analytics/data-visualization/) | Anthropic KWP | Charts & visualizations |
| [data-context-extractor](10-data-analytics/data-context-extractor/) | Anthropic KWP | Data context extraction |
| [sql-queries](10-data-analytics/sql-queries/) | Anthropic KWP | SQL query generation |
| [data-exploration](10-data-analytics/data-exploration/) | Anthropic KWP | Exploratory data analysis |
| [csv-data-summarizer](10-data-analytics/csv-data-summarizer/) | Community | Auto-analyze CSV files with insights & visualizations |
| [postgres](10-data-analytics/postgres/) | Community | Safe read-only PostgreSQL queries with multi-connection support |

### 11 — Customer Success

> *QBRs, churn analysis, ticket triage, customer onboarding, and escalation management.*

| Skill | Source | Description |
|-------|--------|-------------|
| [qbr-builder](11-customer-success/qbr-builder/) | Custom | Quarterly Business Reviews |
| [churn-analysis](11-customer-success/churn-analysis/) | Custom | Churn prediction & retention |
| [onboarding-playbook](11-customer-success/onboarding-playbook/) | Custom | Customer onboarding |
| [ticket-triage](11-customer-success/ticket-triage/) | Anthropic KWP | Support ticket routing |
| [escalation](11-customer-success/escalation/) | Anthropic KWP | Escalation management |
| [customer-research](11-customer-success/customer-research/) | Anthropic KWP | Customer intelligence |
| [response-drafting](11-customer-success/response-drafting/) | Anthropic KWP | Response templates |
| [knowledge-management](11-customer-success/knowledge-management/) | Anthropic KWP | Knowledge base management |
| [slack-messaging](11-customer-success/slack-messaging/) | Anthropic KWP | Slack communication |
| [slack-search](11-customer-success/slack-search/) | Anthropic KWP | Slack search |

### 12 — Procurement & Supply Chain

> *RFP builder, vendor evaluation, contract negotiation, and inventory forecasting.*

| Skill | Source | Description |
|-------|--------|-------------|
| [rfp-builder](12-procurement-supply-chain/rfp-builder/) | Custom | Request for Proposals |
| [vendor-evaluation](12-procurement-supply-chain/vendor-evaluation/) | Custom | Vendor comparison |
| [contract-negotiation](12-procurement-supply-chain/contract-negotiation/) | Custom | Negotiation prep |
| [inventory-forecasting](12-procurement-supply-chain/inventory-forecasting/) | Custom | Demand forecasting |
| [supplier-scorecard](12-procurement-supply-chain/supplier-scorecard/) | Custom | Supplier performance |
| [vendor-management](12-procurement-supply-chain/vendor-management/) | Anthropic KWP | Vendor relationships |

### 13 — Document Processing

> *Create, edit, and analyze Word docs, PDFs, slides, and spreadsheets directly in Claude.*

| Skill | Source | Description |
|-------|--------|-------------|
| [docx](13-document-processing/docx/) | Anthropic Skills | Create, edit, analyze Word docs with tracked changes, comments, formatting |
| [pdf](13-document-processing/pdf/) | Anthropic Skills | Extract text, tables, metadata, merge & annotate PDFs |
| [pptx](13-document-processing/pptx/) | Anthropic Skills | Read, generate, and adjust slides, layouts, templates |
| [xlsx](13-document-processing/xlsx/) | Anthropic Skills | Spreadsheet manipulation: formulas, charts, data transformations |

## Folder Structure

```
awesome-claude-corporate-skills/
├── 00-meta/                          # Meta tools (skill creation)
├── 01-executive-leadership/          # 12 skills
│   ├── strategic-planning/SKILL.md
│   ├── board-meeting-prep/SKILL.md
│   ├── deep-research/SKILL.md        # NEW
│   └── ...
├── 02-finance-accounting/            # 42 skills
│   ├── dcf-model/SKILL.md
│   ├── 3-statements/SKILL.md
│   └── ...
├── 03-human-resources/               # 9 skills
├── 04-marketing/                     # 15 skills
│   ├── canvas-design/SKILL.md        # NEW
│   ├── theme-factory/SKILL.md        # NEW
│   └── ...
├── 05-sales/                         # 16 skills
├── 06-legal-compliance/              # 7 skills
├── 07-operations/                    # 11 skills
│   ├── kaizen/SKILL.md               # NEW
│   └── ...
├── 08-it-engineering/                # 14 skills
│   ├── software-architecture/SKILL.md # NEW
│   ├── test-driven-development/SKILL.md # NEW
│   └── ...
├── 09-product-management/            # 10 skills
│   ├── brainstorming/SKILL.md        # NEW
│   └── ...
├── 10-data-analytics/                # 9 skills
│   ├── csv-data-summarizer/SKILL.md  # NEW
│   ├── postgres/SKILL.md             # NEW
│   └── ...
├── 11-customer-success/              # 10 skills
├── 12-procurement-supply-chain/      # 6 skills
├── 13-document-processing/           # 4 skills — NEW CATEGORY
│   ├── docx/SKILL.md
│   ├── pdf/SKILL.md
│   ├── pptx/SKILL.md
│   └── xlsx/SKILL.md
├── INDEX.md                          # Full inventory with sources
├── LICENSE
└── README.md
```

Each skill folder contains a `SKILL.md` with:
- **YAML frontmatter** — name and trigger description
- **Detailed instructions** — step-by-step workflows
- **Templates & examples** — ready-to-use formats
- **Best practices** — domain-specific guidance

## Contributing

Contributions welcome! To add a skill:

1. **Fork** this repo
2. **Create** a new folder under the appropriate role directory
3. **Add** a `SKILL.md` following the format below
4. **Submit** a PR with a description of what the skill does

### Skill Template

```markdown
---
name: my-skill-name
description: "When and why to use this skill. Be specific about triggers."
---

# Skill Title

## Overview
What this skill does and when to use it.

## Workflow
Step-by-step instructions for Claude to follow.

## Templates
Ready-to-use output templates.

## Best Practices
Domain-specific guidance and edge cases.
```

### Quality Checklist

- [ ] Skill is based on a real corporate use case
- [ ] No duplicate of an existing skill
- [ ] Follows the `SKILL.md` format with YAML frontmatter
- [ ] Includes clear instructions, not just a description
- [ ] Placed in the correct role directory

## Resources

### Official Documentation

- [Claude Skills Overview](https://www.anthropic.com/news/skills) — What skills are and how they work
- [Creating Custom Skills](https://support.claude.com/en/articles/12512198-creating-custom-skills) — Skill development guide
- [Claude Code Docs](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) — CLI reference
- [Anthropic Skills Repo](https://github.com/anthropics/skills) — Official example skills

## License

This repository is licensed under the [MIT License](LICENSE).

Individual skills sourced from external repositories may carry their own licenses — check each skill's source for details.

---

<p align="center">
  <sub>Built with Claude &mdash; Curated for the corporate world</sub>
  <br />
  <sub>If this collection helps your team, consider giving it a <strong>star</strong> — it helps others find it too.</sub>
</p>
