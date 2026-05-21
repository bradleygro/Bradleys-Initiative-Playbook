# Initiative Playbook

A practical PM framework for running product initiatives proactively — from kickoff through shipped and learning. Grounded in the SVPG product model, adapted to work across real operating conditions including feature factory environments, gated customer access, and regulated industries.

---

## Who this is for

Product managers who want a structured way to run initiatives — especially when feeling reactive, stuck, or unsure what to drive next. The framework is designed to work regardless of whether you have full strategic autonomy or operate under top-down direction. A setup questionnaire at the top of the playbook configures the guidance to your actual conditions.

---

## What's in this repo

| File | What it is | When to use it |
|---|---|---|
| [initiative-playbook.md](initiative-playbook.md) | The core framework — five phases, cross-phase principles, operating context questionnaire, quick reference table | Read once to orient; keep as a reference throughout |
| [project-context-template.md](project-context-template.md) | Structured template for documenting a project's business context, problem, requirements, decisions, risks, and stakeholders | Create one per initiative at the start of Phase 1 |
| [discovery-log-template.md](discovery-log-template.md) | Living log of discovery findings, open questions (by theme), decisions, and review notes | Create at the start of Phase 2; update continuously through discovery |
| [project-playbook-template.md](project-playbook-template.md) | Project-specific driver — tracks phase status, open items by urgency, action items by owner, and key reference docs | Create one per initiative at the start of Phase 1; update whenever any other project doc changes |

---

## Recommended folder structure

```
your-project/
├── PROJECT_CONTEXT.md          <- project-context-template.md, filled in
├── process/
│   ├── [project]-playbook.md   <- project-playbook-template.md, filled in
│   ├── mvp-scope-[project].md  <- created in Phase 3
│   └── post-launch-review.md   <- created in Phase 5
├── discovery/
│   ├── discovery-log.md        <- discovery-log-template.md, filled in
│   └── discussion-guide.md     <- created in Phase 2 before user conversations
└── meetings/
    └── YYYY-MM-DD-[topic].md   <- one file per meeting, from day one
```

---

## Getting started (first 48 hours)

1. **Read the initiative playbook.** Answer the five operating context questions at the top. Fill in the "My Operating Context" block. This is the only company-specific configuration you need.

2. **Copy and fill in the project context template.** Don't invent answers — write down what you actually know, mark unknowns explicitly, and leave questions open rather than forcing premature answers.

3. **Copy and fill in the project playbook template.** Mark your current phase. If you're in Phase 1, most of Phase 2 onward will say "Not started" — that's correct. The playbook is a living driver, not a finished document.

4. **Create your meetings folder.** Start a meeting note for every conversation that happens from day one. Trying to reconstruct project history from memory is expensive and inaccurate.

---

## How to use this (the four-doc system)

| Doc | Role | Update cadence |
|---|---|---|
| **Project context** | Captures the stable facts: business context, problem, stakeholders, decisions | When major facts or decisions change |
| **Discovery log** | Captures the evolving learning: findings, open questions, new decisions | Continuously during discovery |
| **Project playbook** | Drives action: what's done, what's open, who owns what | Every time any other doc is updated |
| **Meeting notes** | The raw record: what was said, what was decided, what was assigned | After every relevant meeting |

The playbook is the hub. Every other document links to it; it links to everything else. When something gets resolved in the discovery log, close the corresponding item in the playbook. When a new question surfaces in a meeting, add it to the discovery log and the playbook open items in the same session.

---

## The five phases

| Phase | Purpose | Duration signal |
|---|---|---|
| **1 — Frame and Orient** | Understand the landscape before starting to learn | Days, not weeks |
| **2 — Discovery** | Answer the four risks before committing to build | Weeks, not months |
| **3 — Definition** | Translate findings into a clear, outcome-anchored description of what to build | Runs alongside late discovery |
| **4 — Delivery** | Build the validated solution to commercial quality | Ongoing; PM role is active, not passive |
| **5 — Shipped and Learning** | Determine whether the outcome moved; feed learning into the next initiative | First signal within 4-6 weeks of launch |

---

## The four discovery risks

Every initiative carries four risks that must be closed before committing to build. The two that most commonly get dropped are noted.

| Risk | The question | Commonly dropped? |
|---|---|---|
| **Value** | Will users actually use this? Will it change their behavior? | Sometimes |
| **Usability** | Can users figure out how to use it without help? | Yes — when there's no designer engaged early |
| **Feasibility** | Can engineering build this with available time, skills, and tech? | Rarely |
| **Viability** | Is it compliant, affordable to support, legally sound? | Yes — when compliance feels like someone else's problem |

---

## Philosophy

This framework borrows heavily from Marty Cagan's SVPG product model but is designed to work in real conditions — including organizations where strategic direction is set above the PM level, customer access is gated, and compliance constraints are real. The setup questionnaire at the top of the playbook is how the generic framework adapts to your specific constraints.

The core idea is simple: discovery is not optional, outcomes matter more than outputs, and the best time to learn something is always before you build it. The playbook just makes that discipline systematic.

---

*Free to use and adapt — attribution appreciated.*
