# 100-Day Integration Plan Generator

A Claude AI skill that generates comprehensive 100-day post-merger integration plans for PE-backed roll-up operators.

Paste your deal details. Get a structured plan with milestones, KPIs, risk register, and governance — in minutes.

## What It Does

- Generates a **1-page executive brief** (board-ready) plus a **full detailed plan**
- Covers 7 workstreams: Finance, IT, HR, Operations, Sales, Legal, Communications
- Sequences system migrations correctly (Email → CRM → Finance → HR → Operational)
- Right-sizes plans based on deal type — bolt-ons get lighter treatment than platform builds
- Flags risks with likelihood, impact, mitigation, and owners
- Includes synergy estimates, KPI recommendations, and governance structure
- Produces playbook notes for compressing your next integration

## Who It's For

Operations teams at PE-backed roll-ups who need to integrate acquisitions fast. COOs, integration managers, operating partners — people who've done this before and want speed and consistency, not a tutorial.

## How to Install

### Option 1: Claude Cowork (easiest)

1. Open a Claude Cowork session
2. Paste this repo URL into the chat
3. Say: "Add this as a skill"
4. Done. The skill is now available in your Cowork sessions.

### Option 2: Manual Install

1. Clone or download this repo
2. Copy the `100-day-plan-generator/` folder into your `.claude/skills/` directory
3. The skill will be available in your next Claude session

## How to Use

Once installed, just describe your acquisition:

> "We just closed on a bolt-on — HVAC company in Spain, €1.3M revenue, 50 employees. They use Gestiona 3w and Microsoft 365. We're on NetSuite and Google Workspace. Back-office integration only. Generate a 100-day plan."

The skill will ask for any missing details, then generate:
1. A 1-page executive brief you can forward to your board
2. A full integration plan with phase-by-phase actions, owners, and dates

### Follow-Up Prompts

After the initial plan, try:
- "Deep-dive the IT workstream with weekly tasks"
- "Draft the Day 1 employee communication in Spanish"
- "Build a synergy tracking spreadsheet"
- "Generate a lighter version for our next bolt-on"
- "Assess integration risks for a deal we're in diligence on"

## Tips for Better Output

- **Be specific about systems** — "QuickBooks Desktop 2019" beats "accounting software"
- **State board priorities** — "The sponsor wants consolidated reporting within 60 days" shapes the entire plan
- **Mention deal history** — "This is our 5th bolt-on" activates the repeatable playbook logic
- **Include country/region** — triggers jurisdiction-specific legal and compliance guidance

## What It Can't Do

- Doesn't know your company politics or the personalities involved
- Can't assess data quality from a description alone
- Won't catch edge cases that only surface during execution
- Plans. Doesn't execute.

The plan gets you 80% there. The last 20% — judgment calls, stakeholder management, actual migrations — is where experience matters.

---

Built by [PMI Stack](https://pmistack.com) — post-merger integration execution for PE-backed roll-ups.

Questions? hello@pmistack.com
