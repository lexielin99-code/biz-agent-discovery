# biz-agent-discovery

A Claude Code skill for marketing and e-commerce professionals who want to explore AI agent capabilities but don't know where to start.

## What it does

Instead of listing what AI *can* do in the abstract, this skill runs a short consultation: it asks about your actual work, matches the most relevant use cases, and generates a live HTML demo on the spot — so you see something concrete, not a feature list.

The demo is always framed as a starting point, not a ceiling.

## Who it's for

Senior marketing strategists and e-commerce operators who:
- Already have Claude Code installed
- Have real business problems but aren't sure how AI agents fit
- Don't need hand-holding — they need a capable collaborator who takes initiative

## How it works

**Phase 1 — Quick positioning**
A few yes/no questions to zero in on your role and work patterns. No open-ended prompts.

**Phase 2 — Live demo**
Matches 1–2 scenarios from a capability library (22 scenarios across marketing, e-commerce, and universal use cases). Asks about your preferred dimension and granularity *before* building — the user drives the direction. Generates an interactive HTML file and opens it directly in the browser.

**Phase 3 — Remix framing**
Shows which dimensions can be changed: data source, output format, frequency, granularity. Helps you connect the demo to your own context.

**Phase 4 — Action suggestions**
3 light suggestions to try next. Directional, not prescriptive.

## Capability coverage

| Area | Scenarios |
|------|-----------|
| Marketing | Monthly reports, strategy archiving, content SOPs, multi-platform copy, competitor briefs, A/B copy, user feedback mining, ad performance, KOL pitches |
| E-commerce | Sales dashboards, ops SOP archiving, inventory health reports, promo planning, product copy batch, FAQ generation, SKU analysis, supplier emails |
| Universal | Interactive HTML reports (PPT replacement), workflow documentation, meeting → action items, data → exec narrative, competitor research |

## Installation

Copy `SKILL.md` and `capability-library.md` into your Claude skills directory:

```
~/.claude/skills/biz-agent-discovery/
├── SKILL.md
└── capability-library.md
```

Claude Code will detect it automatically. Trigger it by describing your role or asking about AI use cases in your work.

## Design principles

- **Demo is a probe, not a boundary** — always emphasizes it's one possibility among many
- **Treat users as smart** — shows the capability space, lets them make the connections
- **Ask before deciding** — never picks dimension or granularity on behalf of the user; the Q&A process is where discovery happens
- **Proactive, not reactive** — asks for your materials directly rather than waiting for you to describe problems
