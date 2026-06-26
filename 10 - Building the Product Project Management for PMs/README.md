# 10 - Building the Product Project Management for PMs

> **Core Principle:** *"The job of a product manager is to translate vision into execution — from the abstract 'why' down to the concrete 'what,' and then get out of the way of the 'how.'"*

---

## The Hierarchy: From Vision to User Story

The instructor presents a clear hierarchy that connects company-level vision to day-to-day engineering work.

```
Vision (CEO/Founder — 3-5 year horizon)
    ↓
Goals (Executive — defined into metrics like "+5% new users")
    ↓
Initiatives (Company-wide efforts like "translate product into 3 languages")
    ↓
Releases (Grouping of features shipped on a specific date)
    ↓
Epics (Major bodies of work, multiple sprints, ~3-5 per quarter)
    ↓
User Stories (Specific pieces of functionality, fit in one sprint)
```

### The Principle
> *"Vision without execution is hallucination. Execution without vision is activity. The hierarchy connects them."*

---

## Epics

An epic is a large body of work taking longer than one sprint. Typical team: 3-5 epics per quarter. Contains features, functionalities, and user stories.

Examples: "Translate the app to Spanish", "Implement photo sharing in DMs", "Migrate database" (technical, not user-facing).

### Why "Epic" Instead of "Feature"
Not everything a team builds is user-facing. Infrastructure, tech debt, and migrations are not features but are significant work. "Epic" covers both.

### Epic Spec Sheet (Requirements Document)

| Section | Who Owns It | What It Contains |
|---------|------------|------------------|
| Introduction | PM | Summary of what and why. Metrics targeted. Supporting docs. |
| Product Requirements | PM | User stories, user flows, feature phasing. |
| Design Requirements | PM + Designer | Mockups, wireframes, prototypes. |
| Engineering Requirements | Engineers | Database requirements, APIs, tech decisions, dependencies. |

**The principle:** *The spec sheet should be accessible to anyone in the company. It's a communication tool, not a bureaucratic artifact.*


---

## User Stories and Acceptance Criteria

### User Stories
A short description of functionality from the end user's perspective.

**Format:** *"As an X, I want to do Y, so that I can Z."*

Example: *"As a user, I want to send pictures in a direct message to my friends, so that I can share my favorite photos with them."*

**Why this format:** The PM owns the **what** and the **why** — leaving the **how** to engineers and designers. This format prevents PMs from dictating technical implementation.

### Acceptance Criteria
Conditions that software must satisfy to be considered complete.

**Format:** Given/When/Then
- *Given* I am a user
- *When* I click the add picture button in the direct message
- *Then* I am presented with a pop-up window to choose the file

**Purpose:** A testable checklist. Engineers know when they're done. PMs verify before approving release.

**The principle:** *User stories describe what the user should be able to do. Acceptance criteria spell out exactly how it should work. Together, they give engineers enough specificity to build without being told how to build.*

---

## The Backlog and Sprint Workflow

### The Backlog
A holding area for all work planned but not yet being worked on. The PM is responsible for prioritizing the backlog.

### Sprint Workflow (JIRA or similar)
1. **Backlog** — All planned work, prioritized by PM
2. **Sprint Planning** — Team pulls items based on capacity
3. **To Do** — Not started
4. **In Progress** — Engineer actively working
5. **QA / Testing** — PM or QA verifies against acceptance criteria
6. **Done** — Approved and complete

**The principle:** *The tool doesn't matter. The workflow of defining, prioritizing, committing, building, and verifying is what matters.*

---

## Estimations and Velocity

### Why Estimation Is Hard
The instructor's **custom car mechanic analogy**: If every car were unique, no mechanic could estimate repairs accurately. Software is the same — every project is novel with unique unknowns.

A BMW mechanic who has done the same job 1,000 times → accurate. A mechanic facing a custom-built car → impossible.

**The principle:** *The only reliable estimate comes from having done the same thing before. In software, almost everything is unique.*

### Story Points vs. Hours
Teams estimate in **story points** (relative effort) rather than hours. This avoids false precision and accounts for complexity and uncertainty.

### Velocity
Average story points completed per sprint, measured over multiple sprints.

```
Sprint 1: 12 pts   Sprint 2: 16 pts   Sprint 3: 14 pts   Sprint 4: 10 pts
Average velocity: 13 pts/sprint
```

With velocity, you can predict: "Epic estimated at 40 points → ~3 sprints."

**Why Scrum enables prediction:** Timeboxed sprints create consistent measurement periods. Kanban makes prediction harder without standardized time windows.



---

## Roadmapping

### The Fundamental Tension
Roadmaps are always inaccurate because Agile. If you're truly Agile (responding to change over following a plan), you cannot predict what you'll be building three months from now.

The instructor: *"If you have a roadmap that's accurate down to the date, you are not being Agile."*

### Two Approaches

| Approach | Best For | Risk |
|----------|----------|------|
| **Quarterly Roadmap** (Q1: X, Q2: Y) | Stakeholders, investors | Creates false commitment; changes feel like failure |
| **Three-Bucket Model** (Now, Next, Later) | Agile teams | Less commitment, harder for stakeholders to plan around |

### The Three-Bucket Model
- **Now** — Working on immediately (next few weeks)
- **Next** — Plan to work on after that (mid-term)
- **Later** — Want to get to eventually (long-term, vague)

Intentionally avoids specific dates. Keeps everyone aligned without false expectations.

**The principle:** *Roadmaps are communication tools, not commitment devices. The further out an item is, the less certain it should appear.*

---

## Prioritization

### The Problem
Prioritization is not just about user stories. A PM prioritizes epics, marketing campaigns, technical debt, cross-team dependencies — while accounting for competitors, market shifts, new technologies, and org constraints.

### Three Methods

#### 1. Assumption Testing
Prioritize by the **riskiest assumption**. Assign a value (1-10). Tackle highest-risk items first to de-risk the project early.

**The principle:** *Prioritize what reduces the most uncertainty per unit of effort.*

#### 2. RICE (Reach, Impact, Confidence, Effort)

| Component | What It Measures |
|-----------|-----------------|
| Reach | How many users will this affect? |
| Impact | How much will this move the needle? (e.g., 3 = massive, 1 = minimal) |
| Confidence | How sure are we? (%) |
| Effort | Person-months required |

**Formula:** `RICE Score = (Reach × Impact × Confidence) / Effort`

Highest score gets prioritized first.

#### 3. MoSCoW

| Category | Meaning |
|----------|---------|
| **M**ust have | Non-negotiable for this release |
| **S**hould have | Important but not critical |
| **C**ould have | Nice to have if time permits |
| **W**on't have | Explicitly out of scope this time |

### The Caveat
The instructor: *"Some of the biggest successes were not decided on fancy quantitative frameworks — they came from companies that engender risk-taking. Use the frameworks, but also think for yourself."*

**The principle:** *Frameworks organize your thinking. They don't replace judgment. The best prioritization combines structured analysis with the intuition from deep understanding of your users and market.*
**The principle:** *Single-item estimation is unreliable. Averaged over time, velocity becomes remarkably useful for planning.*
