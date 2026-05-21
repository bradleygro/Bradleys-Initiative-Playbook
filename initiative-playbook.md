# Initiative Playbook

> **Version:** 1.0
> **Purpose:** A PM's north star for running product initiatives proactively — from kickoff through shipped and learning. Use this when you feel reactive, when you're not sure what to drive next, or when you're drifting into "waiting for the next question."
>
> This framework is grounded in the SVPG product model but designed to work across a range of real operating conditions — not just fully-empowered PM organizations.

---

## Step 1: Configure Your Operating Context

Answer these questions once before using the playbook. Your answers populate the "In your operating context" sections throughout — the only part of the framework that's company-specific.

### 1. Strategic direction setting

**Who decides what gets built, and how validated is that decision when it reaches you?**

- **A — Empowered:** I have genuine authority to examine and redirect strategic assumptions. "Should we build this?" is on my table.
- **B — Hybrid:** Some strategic directions are set above me and non-negotiable; others I own fully. I need to know which domain I'm in.
- **C — Feature factory:** Leadership sets direction based on unvalidated assumptions and absorbs accountability for those assumptions. "Should we build this?" is off my table; "how do we build this well?" is fully mine.

*Why it matters:* Determines how you apply the "strategic ceiling" principle. If A: use the full PM toolkit including strategic validation. If B: map which domains you own before starting discovery. If C: redirect energy from strategic validation to tactical discovery — what does the committed solution need to do, for which users, in what way, to actually achieve the outcome?

---

### 2. Customer access

**How accessible are your end users for open-ended research conversations (not demos, not feedback on mockups — just listening)?**

- **A — Open:** I can reach users directly without approval. No groundwork required.
- **B — Gated:** I need manager review of a discussion guide and/or a curated list of approved contacts before scheduling.
- **C — Restricted:** Direct user contact requires procurement, legal, or relationship coordination (e.g., RFP in flight, enterprise contract constraints, regulated outreach).

**Does your manager or leadership have a different definition of "customer discovery" than open-ended research?** (e.g., they expect you to show mockups and collect feedback on a committed solution, not ask open-ended questions)

- Yes / No

*Why it matters:* If yes, you need to explicitly name and frame your research method every time you propose a user conversation. "No mockups, no presenting — I'm listening to how they work today" addresses the concern without giving ground on real discovery.

---

### 3. Regulatory and compliance context

**Is your industry or your clients' industry regulated?** (healthcare, insurance, financial services, education, government contracting, legal, etc.)

- Yes — highly regulated (federal/state oversight, audit requirements, liability exposure)
- Partially — regulated in specific domains or for specific client types
- No — limited compliance constraints

*Why it matters:* In regulated domains, viability risk is not an edge case — it's a data model requirement that can invalidate scope if discovered mid-build. Weight it as urgent from day one.

---

### 4. Team structure

**Do you have dedicated design and engineering partners in discovery (not just delivery)?**

- Designer: Yes, embedded / Shared / None
- Engineering: Yes, embedded / Available for consultations / Joins at delivery

*Why it matters:* Shapes when to involve design (early, even without a dedicated resource) and how to run feasibility checks.

---

### 5. Outcome accountability

**How is success defined on your team — by outputs shipped or outcomes achieved?**

- Outcomes: success is defined by measurable user behavior or business metric change
- Outputs: success is defined by features shipped or deadlines met
- Mixed: ostensibly outcomes, but pressure defaults to outputs in practice

*Why it matters:* If outputs dominate in practice, the forcing questions around outcome framing in this playbook require more deliberate effort. The "how will we know this worked?" test is the most important habit to build.

---

## My Operating Context

*Fill this in based on your answers above. Keep it short — 5-8 bullets. This is the only section that's company-specific.*

```
Strategic model: [A / B / C — one sentence describing what this means for you]
Customer access: [what groundwork is required before a user conversation]
Discovery framing that works with leadership: [phrase that gets approval]
Discovery framing to avoid: [phrase that triggers pushback]
Regulatory context: [domain and key constraints]
Team: [designer situation / engineering situation]
Outcome accountability: [how success is actually measured on your team]
```

---

## Quick Reference: Where Am I Right Now?

If you're feeling reactive or stuck, locate yourself and identify the next proactive move.

| You feel like... | You're probably in... | The move is... |
|---|---|---|
| "I'm waiting for someone to ask me a question" | Any phase | Look at your open questions — find the highest-risk unanswered one and close it this week |
| "I don't know what users actually need yet" | Phase 2 | You've been in internal discovery too long — get a user in front of you, even a proxy |
| "I'm writing requirements but don't know if they're right" | Phase 3 | You've skipped or compressed discovery — stop, run a prototype or interview, get a real signal |
| "I feel powerless / the real problem is higher up" | Any phase | You're pushing against the strategic ceiling — reframe to what IS answerable in your lane |
| "Engineering is asking me questions I can't answer" | Phase 3 or 4 | A discovery question is still open — it's not too late to close it before committing to build |
| "We shipped but I don't know if it worked" | Phase 5 | Instrumentation was an afterthought — pull whatever signal exists and define measurement now |
| "A stakeholder just asked why we built X" | Phase 5 | The outcome wasn't made explicit early enough — document it now, use it for the next initiative |

---

## Creating a Project Playbook

When starting a new initiative, create a project-specific playbook at `process/[project-name]-playbook.md` that applies this template to the project's actual state. The project playbook is the living driver for that initiative — updated frequently, self-contained, and the single source of "what to drive next."

**Before writing anything:** Read all existing project docs first. The playbook synthesizes; it does not invent. At minimum, read whatever exists of: a project context doc, any discovery docs, prior meeting notes, and any scope or process docs.

**Structure of a project playbook:**

1. **"Where we are now" opener** — current phase + 2-3 sentence state summary. Someone picking this up cold should immediately know where the project stands and what the most urgent gap is.

2. **One section per phase** — past phases are retrospective (what was done, artifacts produced, key decisions locked); the current phase is active tracking (what's been done well, what's still open organized by urgency); future phases are forward-looking (what they'll produce for this project, what to watch for, project-specific risks).

3. **Open items organized by urgency** — within the current phase's open items: scope-blocking first, then high, then medium. Each row has an explicit owner and a specific action — not a vague "follow up on X." Missing artifacts from the phase artifact list belong here as explicit rows, not left for the reader to infer by comparing against this template.

4. **"Phase is done when" checklist** — at the end of the current phase section; makes the exit criteria explicit so you know when to move rather than drift.

5. **Consolidated action items by owner** — a single table at the bottom, organized by who owns what. Eliminates "I have to read the whole doc to know what I owe."

6. **Key reference docs table** — links to all project docs with one-line descriptions. The project playbook links out to everything; everything else links back to the playbook.

**The core rule:** Anything that is needed but doesn't exist yet — whether it's an artifact, a decision, or an answered question — must appear as an explicit action item in the project playbook. Never leave a gap for the reader to discover by comparing against this template. The project playbook is self-contained.

**Keeping it current:** Update the project playbook whenever any other project doc is updated. New finding in the discovery log → update the phase status and open items in the playbook. New decision in the context doc → close the corresponding open item in the playbook.

---

## The Five Phases

### Phase 1 — Frame and Orient (Before Any Discovery Begins)

**Purpose:** Understand the landscape before you start learning. Know what question you're answering, what already exists, and what's decided vs. open.

**Duration signal:** Days, not weeks. This is setup, not progress.

**What done looks like:**
- You can state the outcome leadership wants (in their terms), and you can state the question that is actually in your lane to answer
- You know what already exists — existing tools, processes, prior research, adjacent projects — so you don't start from a blank canvas
- You have a project context doc with: business context, the problem being solved, what's already decided, open questions (even if many), key stakeholders, and a glossary
- You know who your end users are (or suspect are) and have not yet talked to them

**What to drive proactively:**
- Walk the current state before doing anything else — observe the existing tool, process, or workaround the way an outsider would; don't ask stakeholders to describe it, see it
- Write down the business context and the decisions that have already been made, in plain language, so you don't waste energy revisiting them as discovery questions
- Write down everything you don't know yet — organized by whether it's a user question, a data/system question, a viability/compliance question, or a strategic question that is above your ceiling
- Identify who the actual end users are; note whether internal stakeholders are proxies or real users, and be explicit about which ones you have easy access to vs. which ones require planning

**Forcing questions:**
- What outcome does leadership want? Have I written it down in those terms?
- What is the question I am actually being asked to answer — and is that the same as the question I want to ask?
- Who are the actual users of this thing I'm building, and have I observed them or just heard about them?
- What's already been decided, and what would I be wasting energy pushing against?
- Are there existing artifacts (internal tools, prior research, contracts, prototypes) I should walk before I start generating new questions?

**In your operating context:** If your strategic model is C (feature factory), write down the committed direction explicitly and mark it as decided. Then immediately write the question that IS in your lane: "What does [committed solution] need to do, for which users, in what way, to actually achieve the outcome?" That question is almost always fully discoverable regardless of the strategic constraint.

**Artifacts to create in this phase:**
- **Project context doc** (`PROJECT_CONTEXT.md`) — business context, the problem being solved, what's already decided, open questions, key stakeholders, glossary. More static than discovery artifacts; updated when major facts change.
- **Project playbook** (`process/[project-name]-playbook.md`) — the living initiative driver adapted from this template. Tracks phase status, what's done, what's open, and what to drive next. Updated frequently.
- **Meetings folder** (`meetings/`) — one note per meeting from day one.

**Blind spot check:** The impulse here is to start scheduling internal stakeholder meetings. That's fine — but notice if internal meetings are becoming a substitute for getting close to actual users. Name the users explicitly and write down when you plan to make contact with them.

---

### Phase 2 — Discovery (Building to Learn)

**Purpose:** Answer the four discovery risks before you commit anything to build. Find the combination of users, workflow, capability, and constraints that is actually worth building — not just the one that sounds right from the inside.

**Duration signal:** Weeks, not months. If discovery is running long, something is blocking it — name the blocker explicitly rather than letting it extend passively.

**What done looks like:**
- You can answer: "Will users actually use this, and why?" (value risk)
- You can answer: "Can users figure out how to use it without hand-holding?" (usability risk) — even if you only have a paper prototype
- Engineering has reviewed feasibility and given you a credible signal (not a precise estimate, just: "this is buildable" or "this is a problem") (feasibility risk)
- Legal, compliance, finance, or the relevant viability stakeholders have been asked the viability questions — their answers are documented, not pending (viability risk)
- You have talked to real users, not just proxies — even once, even briefly, even before you have something to show

**What to drive proactively:**
- Identify which of the four risks is most dangerous for this initiative — lead with that one; don't discover in sequence
- Get real users in front of you before you have a prototype — that first conversation is orientation, not validation; do it early
- When working from an internal tool as a starting point, validate that the internal workflow resembles the target user's workflow before treating simplification as a design strategy
- Close compliance and viability questions as dedicated conversations — they do not close themselves from an open questions list; assign an owner and a date
- Build rough prototypes or workflow sketches with your designer before writing anything that looks like a requirements document; the prototype surfaces what writing conceals

**In your operating context:**
- If customer access is gated (B): create your discussion guide before proposing any user conversations — not after approval is given. Frame the method explicitly to whoever reviews it: "no mockups, no presenting — listening to how they work today." This directly addresses the concern that client conversations create expectations.
- If customer access is restricted (C): use internal proxies (CS, sales, account managers who have direct user exposure) to close the gap while pursuing formal access in parallel. A proxy conversation is not a substitute for a user conversation, but it is better than nothing.
- Internal discovery is usually more accessible than user research — start there, but set a hard deadline for when internal work must be supplemented by direct user contact. Two weeks without a user conversation is a warning sign.

**Forcing questions:**
- Which of the four risks is most dangerous here — value, usability, feasibility, or viability? Am I leading with that one?
- When did I last talk to an actual end user — not a colleague who knows the user, but the user themselves?
- Have I explicitly identified which internal stakeholders are proxies vs. which ones are genuine users?
- Which viability/compliance questions are still listed as "open" with no owner and no date? That is not a plan.
- Is there a regulatory or compliance dimension to this initiative? If yes: who owns answering it, and have I told them it's urgent?
- Has engineering reviewed for feasibility — not a full estimate, just a "this is buildable / here is why this might be hard" signal?
- If I'm adapting an internal tool for a different user type: have I confirmed that the target user's workflow resembles the internal workflow, or am I assuming it does?

**Artifacts to create in this phase:**
- **Discovery log** (`discovery/discovery-log.md`) — all findings, open questions by theme (user, data/system, viability, strategic), decisions log. Updated continuously throughout discovery; the most frequently touched doc in this phase.
- **User flows / JTBD analysis** (`discovery/user-flows-jtbd.md`) — once you have identified two or more meaningfully distinct user types, document their jobs to be done, trigger → workflow → outcome flows, and anxieties. Start with inferred flows if needed, but flag them as unvalidated until user research confirms or corrects them.
- **Discussion guide** (`discovery/discussion-guide.md`) — a focused set of questions and protocols for user conversations. Create this before proposing any user sessions to stakeholders, not after approval is given.
- **Specialized research docs as needed** — data audits, competitive profiles, contract analyses, etc. (`discovery/`). Create a new doc when a research thread produces findings rich enough to live outside the discovery log.
- **Meeting notes** (`meetings/`) — one note per key discovery session.

**Blind spot check:** Two weeks of internal discovery without a user conversation is a warning sign, not a discovery phase. If you're in week three of internal research and no user is in sight, name that to yourself and create a plan to close the gap — even a proxy session is better than nothing.

---

### Phase 3 — Definition (What to Build, Not How)

**Purpose:** Translate discovery findings into a clear, outcome-anchored description of what needs to be built, so engineering can design and estimate with confidence — not a spec they execute against.

**Duration signal:** Definition is not a phase that runs in series with discovery; it runs alongside it and wraps up after the key discovery risks are closed. If you're writing definition before discovery is done, you're writing fiction.

**What done looks like:**
- There is a clear outcome statement: what user behavior change or business metric will change if this works? With a baseline (where it is now) and a target (where it needs to be)?
- There is a user problem statement — a description of the friction, the workflow gap, or the unmet need — that any engineer or designer on the team could read and understand without a briefing from you
- There is a set of requirements that describes what the solution needs to do (not how it does it), organized by must-have vs. nice-to-have, with open items clearly marked
- Compliance, security, accessibility, and regulatory constraints have been documented — not listed as future risks
- Fail states and error conditions are addressed — not deferred to engineering to figure out during build
- The designer and engineer have both reviewed and contributed to what's here — this is not a document you handed them

**What to drive proactively:**
- Write the outcome statement before you write any requirements — if you can't state the measurable outcome, you're not ready to define anything
- Organize requirements by user role, not by feature — "what does a [user type] need to be able to do?" rather than "the system shall have a [feature name]"
- Surface viability constraints explicitly in the requirements — not as a risk flag, but as a constraint that shapes the solution
- Write the "how will we know this worked?" test before you write the "what are we building?" spec
- Flag any requirement that was written before corresponding discovery was done — these are assumptions, not validated requirements, and should be marked as such

**In your operating context:**
- Requirements that originate from contract language, an RFP, or a leadership mandate need a discovery flag: "this is what [source] says; we have/haven't validated that this is how users actually experience the problem."
- Don't let the data model or technical architecture drive the requirements. The data model is a feasibility question engineering owns. Requirements describe what the solution must be capable of. Engineering translates that into architecture.
- If your outcome accountability model defaults to outputs in practice: the outcome statement is your most important protection against the feature factory trap. Write it first, share it visibly, and evaluate every scope change against it.

**Forcing questions:**
- What is the measurable outcome this work is supposed to produce, and have I written it down with a baseline and a target?
- Can I state the user problem in one paragraph, in user terms, without referencing internal system vocabulary?
- Are my requirements statements about what the solution needs to do, or about how the system works? If the latter, I've crossed into engineering territory.
- Which requirements came directly from contract, brief, or leadership direction without user validation? Have I flagged those?
- Have compliance, security, and regulatory constraints been confirmed — not just listed as open questions?
- Have my designer and engineer reviewed this? Have they pushed back on anything?

**Artifacts to create in this phase:**
- **MVP scope doc** (`process/mvp-scope-[project].md`) — minimum viable scope definition, what's in and out of MVP, success criteria with candidate outcomes, architecture direction. Write this early in Phase 3 and use it to evaluate every requirement that follows.
- **API contract doc** (`process/api-contract.md`) — for platform or infrastructure projects, the agreed specification of what questions the system answers and what form those answers take. This is a bilateral agreement between PM, engineering, and any consuming team — not a PM-authored reference doc.
- **Migration plan** (`process/migration-plan.md`) — for projects with data migration: scope, owner, timeline, QA process, accuracy audit gate. This is a launch-blocking dependency; it needs its own doc and a named owner before build starts.

**Blind spot check:** If your requirements section is a feature list with no outcome statement and no baseline metric, you are in feature factory mode. The test: "How will we know this worked six months after we shipped it?" If you can't answer that specifically, the definition isn't done.

---

### Phase 4 — Delivery (Building to Earn)

**Purpose:** Build the validated solution to commercial quality — not to spec, but to the outcome. The PM's job in delivery is not project management; it is protecting the outcome as tradeoffs surface and remaining accountable for the viability decisions that emerge during build.

**Duration signal:** Delivery is ongoing. The PM's active role in delivery is less than in discovery, but it is not passive.

**What to drive proactively:**
- Stay close to what's being built — not to approve decisions (that's the designer's and engineer's job), but to catch drift when the solution under construction is diverging from the validated problem
- Escalate viability issues as they surface — if a legal or compliance question emerges during build, treat it as high-urgency, not a parking lot item
- Track instrumentation as a delivery requirement, not a post-launch add-on — if the build doesn't include the logging or events that will tell you whether the outcome is moving, raise it before the feature ships
- Communicate what's being built and why to stakeholders — not to seek approval, but to prevent late surprises from people with the power to derail launch
- When tradeoffs surface, ask: "Does this tradeoff change whether the solution will achieve the outcome?" If yes, it's a PM decision. If it's about how to implement without affecting the outcome, it's engineering's call.

**What you are not doing in delivery:**
- Approving design decisions — that is your designer's domain; your role is to flag when a design choice conflicts with a validated user need
- Micromanaging engineering sequencing — that is engineering's call; your role is to be clear about what must ship together vs. what can be decoupled
- Acting as a shield between the team and stakeholders — your job is to make sure the solution being built works for the business; that requires engagement with stakeholders, not insulation from them

**In your operating context:**
- If a compliance or regulatory question surfaces during build and you can't get a quick internal answer, escalate it immediately — do not carry it as an open question while build continues.
- If timeline pressure produces a scope reduction proposal, evaluate it against the outcome: "If we cut this, will the outcome still be achievable?" If yes, make the cut. If no, surface the conflict explicitly rather than accepting the cut silently.

**Forcing questions:**
- Is the thing being built still addressing the problem we validated, or has it drifted toward a different problem?
- What instrumentation is in place to measure whether the outcome moves after launch? Is it in the build?
- Are there viability questions still open from discovery that haven't been closed? This is the last chance before launch.
- Are there stakeholders who will be surprised at launch? If yes, get ahead of it now.

**Artifacts to create in this phase:**
- **Instrumentation/measurement plan** (`process/instrumentation-plan.md`) — what gets logged, how, and what thresholds will surface whether the outcome is moving. This is a delivery requirement, not a post-launch add-on; create it before the first sprint starts.
- **Launch readiness checklist** (`process/launch-readiness-checklist.md`) — the go/no-go gate before the solution is exposed to real users. Each "MVP is done when" item from the scope doc becomes a checklist item with an owner and sign-off. No user exposure until every item is checked.

**Blind spot check:** If you've stopped looking at the product during delivery, you're functioning as a project manager. Your job during delivery is to remain accountable for value and viability — that requires staying close enough to catch drift.

---

### Phase 5 — Shipped and Learning

**Purpose:** Determine whether the solution actually produced the outcome, and feed that learning into the next initiative.

**Duration signal:** Ongoing, but the first meaningful signal should be available within 4-6 weeks of launch for most initiatives.

**What done looks like:**
- You have pulled data on whether the expected outcome is moving
- You have had at least one conversation with actual users post-launch — not to collect praise, but to understand what's working, what isn't, and what they're doing instead of using what you built
- You have documented what you learned — including what you got wrong — in a form that can inform the next initiative

**What to drive proactively:**
- Define success criteria before launch, not after — if you're defining "did this work?" after the fact, you're working backwards
- Pull the first data signal within the first two weeks — even if it's inconclusive, it forces the instrumentation to be validated and surfaces gaps
- Schedule a post-launch user conversation before launch happens — make it a commitment, not an intention
- Run a retrospective on the discovery process, not just the delivery: "What did we learn that we wish we'd known in Phase 2? What did we over-discover? What viability risk showed up in delivery that should have been surfaced in Phase 1?"

**In your operating context:**
- "We shipped [feature name]" is not a success metric. "[User behavior or business metric] changed by [X]" is.
- If you can't measure the outcome because instrumentation was skipped, document that explicitly and make it a prerequisite for the next initiative in this area.

**Artifacts to create in this phase:**
- **Post-launch review** (`process/post-launch-review.md`) — outcome metrics vs. targets, first user conversations post-launch, what you got wrong, what to do differently. Write the first version within 4-6 weeks of launch. Update at 90 days.

**Forcing questions:**
- What was the measurable outcome target? Is it moving?
- What are users actually doing — are they using what we built, or are they finding workarounds?
- What did we learn in delivery that we should have learned in discovery? How do we catch it earlier next time?
- What assumptions did we carry from Phase 1 that turned out to be wrong?

---

## Cross-Phase Principles

These apply at every phase. They're here because they tend to erode under pressure.

### On the four risks: address all of them, not the convenient ones

Every initiative has four risks that must be closed before committing to build:

1. **Value** — Will users actually use this? Will it change their behavior?
2. **Usability** — Can users figure out how to use it without help?
3. **Feasibility** — Can engineering build this with available time, skills, and tech?
4. **Viability** — Is it compliant, affordable to sell and support, legally sound?

The two that tend to get dropped are usability (when there's no designer engaged early) and viability (when compliance feels like someone else's problem). Both produce post-launch problems that are expensive to fix.

### On customer access: set a deadline, don't drift

Internal discovery is necessary. It is not sufficient. If you are more than two weeks into a discovery phase and have not had a conversation with an actual end user — not a colleague who knows the user, but the user themselves — you have a problem.

Set a specific deadline for first user contact at the start of every initiative. If the path to that contact requires groundwork (a discussion guide, manager review, a curated contact list), start that groundwork on day one.

### On viability and compliance: treat it as urgent, not pending

Viability risks that live in the "open questions" list with no owner are not being managed — they are being deferred. In regulated industries, for enterprise clients with their own compliance obligations, or any time requirements touch data ownership or audit trails: compliance constraints discovered during delivery invalidate scope. Finding out in week one of discovery is always cheaper than finding out mid-build.

For every initiative, identify the viability dimension explicitly within the first week. Assign it to a named person by the end of Phase 2. Do not enter Phase 3 with viability questions still open.

### On outcome framing: write it first, or don't write requirements at all

The test for whether you are in feature factory mode: can you complete this sentence specifically and measurably?

> "We will know this initiative worked when [measurable behavior or metric] changes from [baseline] to [target] within [timeframe]."

If you cannot complete that sentence, you are not ready to write requirements. Write the outcome statement first. Use it to evaluate every requirement that follows.

### On the strategic ceiling: redirect, don't push

When leadership has absorbed a strategic assumption and made it non-negotiable, pushing against it is a use of energy that produces nothing. The reframe: "What does [committed solution] need to do, for which users, in what way, that would actually achieve the outcome leadership wants?" That question is almost always fully discoverable and within your lane.

When you feel powerless or deflated after a conversation where a strategic question got shut down, that feeling is the signal. It means you are pushing against the ceiling. Name it to yourself, then redirect immediately to the lane you own.

### On timeline pressure: faster discovery, not less discovery

Contract timelines, brief windows, and engineering capacity constraints are real. They are reasons to run faster discovery — shorter interview cycles, lower-fidelity prototypes, more focused questions — not reasons to skip discovery. The post-launch redesign that comes from skipped discovery always costs more than the discovery would have.

When you hear yourself thinking "we already know what they need — it's in the brief / contract / stakeholder notes," that is the rationalization pattern activating. Name it and go get one real user conversation before committing to build.

---

*This document is a living reference. Update the "My Operating Context" section when your organizational constraints shift meaningfully. Update the framework itself when a new recurring blind spot pattern emerges that isn't captured here.*
