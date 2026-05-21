# [Project Name] — Project Playbook

> **Last updated:** [DATE]
> **Owner:** [NAME]
> **Related docs:** [PROJECT_CONTEXT.md](../PROJECT_CONTEXT.md) · [discovery/discovery-log.md](../discovery/discovery-log.md)

---

## Where We Are Now

**Current phase:** Phase [X] — [Phase Name]

[2-3 sentences: what has been done, what is the most critical open gap right now, and what is immediately blocking forward progress. Someone picking this up cold should understand the project's state without reading anything else.]

---

## Phase 1 — Frame and Orient

> **Status:** [Complete — DATE / In progress / Not started]

### What was done

- [x] [Artifact or action completed]
- [x] [Artifact or action completed]

### Decisions locked in this phase

| Decision | Rationale | Source |
|---|---|---|
| [Decision 1] | [Why] | [Meeting / doc / stakeholder] |
| [Decision 2] | [Why] | [Meeting / doc / stakeholder] |

### Artifacts produced

| Artifact | Path | Status |
|---|---|---|
| Project context doc | [PROJECT_CONTEXT.md](../PROJECT_CONTEXT.md) | [Complete / Draft] |
| Project playbook | [process/[project]-playbook.md](../process/[project]-playbook.md) | [Complete / Draft] |
| Meetings folder | [meetings/](../meetings/) | [Active] |

---

## Phase 2 — Discovery

> **Status:** [Complete — DATE / In progress / Not started]

### What has been done well

- [Track or research thread that is solid and can be built on]
- [Track or research thread that is solid and can be built on]

### Open items

*Scope-blocking first, then high urgency, then medium. Each row has an owner and a specific next action.*

#### Scope-blocking

| Item | Owner | Next action |
|---|---|---|
| [What's unresolved that prevents scope from being locked] | [Name] | [Specific action, not "follow up"] |

#### High urgency

| Item | Owner | Next action |
|---|---|---|
| [Compliance or viability question with no owner] | [Name — assign one; do not leave this blank] | [Specific action] |
| [User research not yet started or incomplete] | [Name] | [Specific action] |

#### Medium urgency

| Item | Owner | Next action |
|---|---|---|
| [Engineering feasibility check pending] | [Name] | [Specific action] |
| [Internal process or operational question open] | [Name] | [Specific action] |

### Discovery tracks

| Track | Output | Primary Sources | Status |
|---|---|---|---|
| [Data / system audit] | [What this track produces] | [Who / what] | [Not started / In progress / Complete — date] |
| [Current-state process] | [What this track produces] | [Who / what] | [Not started / In progress / Complete — date] |
| [User research] | [How users think about X; workflow; blockers] | [Which user types / how you'll reach them] | [Not started / In progress / Complete — date] |
| [Viability / compliance] | [Regulatory constraints, audit requirements, legal boundaries] | [Legal, compliance, contracts team] | [Not started / In progress / Complete — date] |
| [Engineering feasibility] | [What's buildable, what's risky, what's expensive to change later] | [Engineering leads] | [Not started / In progress / Complete — date] |

### Artifacts to produce before exiting Phase 2

| Artifact | Path | Status |
|---|---|---|
| Discovery log | [discovery/discovery-log.md](../discovery/discovery-log.md) | [Complete / In progress / Not started] |
| User flows / JTBD analysis | [discovery/user-flows-jtbd.md](../discovery/user-flows-jtbd.md) | [Complete / In progress / Not started] |
| Discussion guide (for user conversations) | [discovery/discussion-guide.md](../discovery/discussion-guide.md) | [Complete / In progress / Not started] |
| [Additional research doc, if applicable] | [discovery/[doc-name].md](../discovery/[doc-name].md) | [Complete / In progress / Not started] |

### Phase 2 is done when

- [ ] All four discovery risks are closed: value, usability, feasibility, viability
- [ ] At least one direct user conversation has happened (not a proxy)
- [ ] Viability / compliance questions have a named owner and documented answers — not pending
- [ ] Engineering has given a credible feasibility signal (not a full estimate — just "this is buildable" or "here's what's hard")
- [ ] The discovery log reflects current findings and has no open questions without an owner
- [ ] All Phase 2 artifacts exist and are populated

---

## Phase 3 — Definition

> **Status:** [Complete — DATE / In progress / Not started]

### What this phase will produce for this project

[2-3 sentences: what the definition phase needs to lock down specifically for this initiative — what questions will be closed, what scope decisions will be made, what the MVP scope doc will capture.]

### Forward-looking open items

| Item | Owner | When needed |
|---|---|---|
| [Requirement that is still under discovery] | [Name] | [Before this phase can close] |
| [Viability constraint that needs confirming before writing requirements] | [Name] | [Before this phase can close] |

### Artifacts to produce in this phase

| Artifact | Path | Status |
|---|---|---|
| MVP scope doc | [process/mvp-scope-[project].md](../process/mvp-scope-[project].md) | [Not started] |
| API contract (if platform/infrastructure project) | [process/api-contract.md](../process/api-contract.md) | [Not started / N/A] |
| Migration plan (if data migration involved) | [process/migration-plan.md](../process/migration-plan.md) | [Not started / N/A] |

### Risks to watch in this phase

- [e.g., Requirements being written before corresponding discovery is done — mark those as assumptions until validated]
- [e.g., Viability constraints discovered during definition that invalidate scope already written]
- [Project-specific risk]

### Phase 3 is done when

- [ ] Outcome statement written: "[metric] changes from [baseline] to [target] within [timeframe]"
- [ ] User problem statement written in user terms — any engineer could read it without a briefing
- [ ] Requirements organized by user role (what each user type needs to do), not by feature
- [ ] Must-have vs. nice-to-have explicitly separated
- [ ] Compliance, security, and regulatory constraints documented — not listed as open questions
- [ ] Designer and engineering lead have reviewed and contributed
- [ ] MVP scope doc complete

---

## Phase 4 — Delivery

> **Status:** [Complete — DATE / In progress / Not started]

### What this phase will produce for this project

[1-2 sentences: what "built" looks like for this initiative — what will be deployed, who will use it, and what the go-live criteria are.]

### Risks to watch in this phase

- [e.g., Solution drifting from the validated problem as engineering makes tradeoffs]
- [e.g., Viability issue surfacing mid-build that wasn't closed in discovery]
- [Project-specific risk]

### Artifacts to produce in this phase

| Artifact | Path | Status |
|---|---|---|
| Instrumentation / measurement plan | [process/instrumentation-plan.md](../process/instrumentation-plan.md) | [Not started] |
| Launch readiness checklist | [process/launch-readiness-checklist.md](../process/launch-readiness-checklist.md) | [Not started] |

### Phase 4 is done when

- [ ] Instrumentation is in place — events and logging that will tell you whether the outcome is moving
- [ ] Launch readiness checklist complete — every "MVP is done when" item has a sign-off
- [ ] No viability questions still open
- [ ] Stakeholders who need to know about launch have been briefed

---

## Phase 5 — Shipped and Learning

> **Status:** [Complete — DATE / In progress / Not started]

### What this phase will produce for this project

[1-2 sentences: what learning will look like — what data to pull, what user conversations to have post-launch, what the retrospective will cover.]

### Artifacts to produce in this phase

| Artifact | Path | Status |
|---|---|---|
| Post-launch review | [process/post-launch-review.md](../process/post-launch-review.md) | [Not started] |

### Phase 5 is done when

- [ ] Outcome data pulled — is the metric moving?
- [ ] At least one post-launch user conversation completed
- [ ] Post-launch review written: outcomes vs. targets, what was wrong, what to do differently
- [ ] 90-day update scheduled

---

## Consolidated Action Items by Owner

*Update this table whenever any other section changes. Each owner should be able to read only this table and know exactly what they owe.*

### [Owner Name]

| Action | Urgency | Linked to |
|---|---|---|
| [Specific action] | Scope-blocking / High / Medium | [Phase / track] |

### [Owner Name]

| Action | Urgency | Linked to |
|---|---|---|
| [Specific action] | Scope-blocking / High / Medium | [Phase / track] |

---

## Key Reference Docs

| Document | Description |
|---|---|
| [PROJECT_CONTEXT.md](../PROJECT_CONTEXT.md) | Business context, problem statement, stakeholders, open questions, key decisions |
| [discovery/discovery-log.md](../discovery/discovery-log.md) | All findings, open questions by theme, decisions log |
| [discovery/discussion-guide.md](../discovery/discussion-guide.md) | Questions and protocol for user conversations |
| [process/mvp-scope-[project].md](../process/mvp-scope-[project].md) | MVP scope definition, what's in and out, success criteria |
| [meetings/](../meetings/) | All meeting notes, one file per session |
