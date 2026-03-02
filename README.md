# CareerProof Skills for Claude Code

## What is CareerProof?

CareerProof is an AI-powered career and workforce intelligence platform built for two audiences navigating the same disruption from opposite sides: **professionals** rethinking their careers in the age of AI, and **organizations** redesigning their workforce to stay competitive.

The platform operates in two modes:

- **CeeVee** (Personal Career Intelligence) — Helps individuals understand how their experience translates in a rapidly shifting market, optimize their positioning, and make data-backed career decisions.
- **Atlas** (Workforce & Org Intelligence) — Gives HR leaders, talent acquisition teams, and consultants the analytical firepower to evaluate candidates, benchmark compensation, plan workforce transitions, and generate research-grade reports on org design, skills gaps, and talent strategy.

Both modes are powered by the same intelligence engine: a curated RAG (Retrieval-Augmented Generation) knowledge base drawn from 50+ premium sources — including HBR, McKinsey, BCG, Bain, Deloitte, PwC, Gartner, Forrester, WEF, MIT, and Stanford — combined with live web research via Tavily for real-time market data.

## Why It Matters

The workforce is being restructured by AI at every level. Job roles are morphing, entire functions are being automated, and organizations need to redesign around capabilities that didn't exist two years ago. CareerProof bridges the gap between individual career navigation and organizational workforce strategy by grounding both in the same deep research:

- **For professionals**: Move beyond generic career advice. Get intelligence calibrated to your actual experience, industry, and seniority — drawn from the same sources that inform executive strategy.
- **For organizations**: Replace gut-feel hiring and ad-hoc workforce planning with structured analysis. Evaluate talent against competency frameworks, benchmark against market data, and generate the kind of research reports that previously required expensive consulting engagements.

## The Intelligence Engine

Every CareerProof skill is backed by a three-layer intelligence stack:

1. **Expert-Curated RAG** — A knowledge base of career, compensation, and workforce intelligence aggregated from premium research sources (McKinsey, BCG, HBR, Gartner, Forrester, WEF, and 50+ others). Updated 3x daily with executive-focused queries spanning 25+ industries.
2. **Live Web Research** — Real-time search and extraction via Tavily APIs, grounded in current market conditions rather than stale training data. Search results are automatically stored back into the knowledge base, making it smarter over time.
3. **CV/Candidate Context** — When available, analysis is calibrated to actual experience: role, seniority, industry, function, skills, and career trajectory. This transforms generic insights into personalized intelligence.

## Skills Overview

### Atlas Skills (Workforce & Org Intelligence)

| Skill | Purpose | Cost |
|-------|---------|------|
| **atlas-onboard** | Set up a hiring context — company profile, candidate CVs, job descriptions | Free |
| **atlas-shortlist** | Batch evaluate and rank candidates against a JD with competency scoring and fit matching | 8-13 credits/candidate |
| **atlas-deep-eval** | 360-degree single candidate evaluation — competency analysis, JD-FIT matching, and tailored interview questions | ~26 credits |
| **atlas-report** | Generate research-grade PDF reports across 16 types (see below) | 15 credits/report |

#### Report Types (16)

**Recruitment:** Talent market landscape, salary benchmarking, competitor talent analysis, sourcing strategy

**Workforce Planning:** Skills gap analysis, succession planning, workforce demographics, attrition risk

**Strategic HR:** DEI assessment, employer branding, L&D strategy, org design, employee engagement, total rewards, HR technology, change management

### CeeVee Skills (Personal Career Intelligence)

| Skill | Purpose | Cost |
|-------|---------|------|
| **ceevee-optimize** | Full CV positioning pipeline — market analysis, career opportunities, targeted edits with trade-off analysis | 13 credits (3-step) or 10 credits (quick review) |
| **ceevee-career-intel** | Career intelligence chat with live web research, RAG knowledge base, and CV-aware personalization | 2 credits/message |

## Installation

Install the CareerProof skills plugin in Claude Code:

```bash
claude skills install careerproof
```

## Usage

Once installed, invoke any skill by name:

```
/atlas-onboard          # Set up a new hiring context
/atlas-shortlist        # Batch evaluate candidates
/atlas-deep-eval        # Deep-dive on a single candidate
/atlas-report           # Generate a workforce research report
/ceevee-optimize        # Optimize your CV positioning
/ceevee-career-intel    # Start a career intelligence chat
```

Skills accept optional arguments:

```
/atlas-report org design           # Jump straight to org design report
/ceevee-career-intel salary trends # Start with a salary trends question
```

## Requirements

- An active CareerProof account with available credits
- CareerProof MCP server connected to your Claude Code session

## Links

- [CareerProof Platform](https://careerproof.ai)
- [Support](mailto:support@careerproof.ai)
