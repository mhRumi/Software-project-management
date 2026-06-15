# Lecture 1: Introduction to Software Project Management
**Source:** Hughes & Cotterell, 5th ed., Chapter 1 (pp. 1–20)
**Duration:** ~100 min (splittable into two ~50-min sessions — split point marked below)

## Learning Objectives (from the book's own chapter objectives)
- Define the scope of "software project management"
- Understand the problems and concerns of software project managers
- Define the usual stages of a software project
- Explain the main elements of the role of management
- Appreciate the need for planning, monitoring and control
- Identify the stakeholders of a project and their objectives
- Define the success criteria for a project

---

### 1. Hook: Why does this matter? (§1.2) — 10 min
Open with the book's own numbers — no need to import outside material here:
- UK government (2002–03) spent **£2.3bn on ICT contracts vs £1.4bn on roads**
- Standish Group (2003): of 13,322 projects, only a minority succeeded — **82% were late, 43% over budget**
- National Audit Office: failures traced to "**lack of skills and proven approach to project management and risk management**"

Discussion prompt: *"Why do IT projects fail so often, even with smart people and big budgets?"*

### 2. What is a project? (§1.1, §1.3) — 15 min
- §1.1: all projects are about **meeting objectives**; SPM = ensuring stakeholder objectives are met
- Dictionary definition: a project is a **planned activity**
- **Figure 1.1** — spectrum: *Routine jobs ↔ Projects ↔ Exploration* (uncertainty of outcome increases left→right)
- 8 characteristics that distinguish projects (non-routine, planning required, specific objectives, fixed time span, work for someone else, multiple specialisms, temporary team, constrained resources, size/complexity)

**In-class activity — Exercise 1.1:** Students rank a list (producing a newspaper, Mars rover mission, getting married, second-year programming assignment, installing a word processor update, etc.) along the routine→exploration spectrum and justify their ordering. Good for getting discussion going early.

### 3. What makes SOFTWARE projects different? (§1.4–1.5) — 15 min
Brooks' four characteristics (§1.4):
- **Invisibility** — physical progress (a bridge) is visible; software progress isn't
- **Complexity** — more complexity per £/$ than other engineered products
- **Conformity** — software must conform to human/organizational requirements, which are inconsistent
- **Flexibility** — software is expected to change to accommodate everything else

§1.5: **Contract management vs. technical PM** — in-house vs. outsourced development; client-side PM (manages budget/contract) vs. supplier-side PM (manages technical delivery). This book focuses on the latter.

### 4. The software project lifecycle (§1.6) — 15 min
- **Figure 1.2**: Feasibility study → Plan → Project execution (the "is it worth doing? / how do we do it? / do it!" cycle)
- **Figure 1.3**: ISO 12207 lifecycle — requirements analysis → architecture design → detailed design → code & test → integration → qualification testing → installation → acceptance support

**Introduce the running case study — Exercise 1.2: Brightmouth College.**
*Brightmouth College currently has its payroll run by a local authority computer centre and wants to replace it with an off-the-shelf package run in-house. What are the main stages of this project, and how would it differ if the software were written from scratch?*

This case recurs through §1.8–1.16 — worth carrying it forward as a running example for the whole semester (capstone teams can pick a similar "build vs buy / replace a legacy system" scenario).

---
**— Natural split point for a two-session week —**
---

### 5. Plans, methods, methodologies & categorizing projects (§1.7–1.8) — 10 min
- **Method** (how to do a type of task) vs **plan** (method applied to real activities, with dates/owners/resources) vs **methodology** (a grouped set of methods, e.g. object-oriented design)
- Categorization dimensions: compulsory vs. voluntary users; information systems vs. embedded/real-time systems; **objective-driven vs. product-driven** projects

**Quick exercise:** Apply these categories to Brightmouth College (Exercises 1.4–1.5) — is it objective-driven or product-driven? Information system or embedded?

### 6. Stakeholders & setting objectives (§1.9–1.10) — 15 min
- Three stakeholder categories: internal to the project team / external to team but inside the organization / external to both
- **Theory W** (Boehm & Ross) — manager's job is to create win-win situations for all stakeholders
- **SMART objectives**: Specific, Measurable, Achievable, Relevant, Time-constrained
- Project authority / steering committee — who actually "owns" the project

**In-class activity — Exercises 1.6–1.8:** In groups, identify the stakeholders for Brightmouth College, then draft SMART objectives and sub-objectives for the project.

### 7. The business case & project success/failure (§1.11–1.12) — 10 min
- Cost-benefit analysis and the "business model" behind a project
- Critical distinction: **project objectives** (functionality, quality, on time, on budget) vs **business objectives** (does it actually deliver value?)
- Key insight worth dwelling on: *a project can hit all four project-objective targets and still be a business failure* (e.g., a game shipped on time and budget that nobody buys)

Discussion prompt: *"Can you think of a product that was delivered on time, on budget, to spec — but still failed?"* (Encourage students to bring their own examples — this is where a bit of outside discussion naturally fits without needing prepared case studies.)

### 8. What is management? Management control (§1.13–1.14) — 10 min
- 8 management activities: planning, organizing, staffing, directing, monitoring, controlling, innovating, representing
- **Figure 1.4** — the project control cycle: data collection → data processing → decisions/plans (informed by modelling) → implementation → back to the real world

**In-class activity — Exercise 1.9 (Paul Duggan case):** A short narrative about a section manager's day (staffing meeting, a team member's accident, arranging a replacement, managing a client conversation). Students map each of his actions to one of the 8 management activities — a nice concrete grounding for an otherwise abstract list.

### 9. Wrap-up (§1.15–1.16 + Annex 1) — 5 min
- Recap the chapter's 5 conclusions (projects are inherently uncertain; software has particular difficulties like invisibility; clear objectives are central to success; objectives need measurable tests; communication channels must be established)
- **Preview Annex 1 — "Contents list for a project plan"** (Introduction, Background/business case, Objectives, Constraints, Methods, Products, Activities, Resources, Risks, Management). This becomes the **template for the semester capstone project plan deliverable** — worth pointing this out explicitly now.

---

## Homework / Follow-up
- Read Ch.1 in full (pp. 1–20)
- Further Exercises 1.16, #1–3 (personal ICT project reflection; IS department roles; public library stakeholder/objectives exercise)
- Form capstone project teams; each team picks a "build vs. buy / replace a legacy system" scenario similar to Brightmouth College
- Optional: bring one real-world example of a "delivered on spec/time/budget but still failed" product for next session's discussion
