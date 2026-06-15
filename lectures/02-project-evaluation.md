# Lecture 2: Project Evaluation and Programme Management
**Source:** Hughes & Cotterell, 5th ed., Chapter 2 (pp. 21–48)
**Duration:** ~105 min — two distinct halves (Part A is calculation-heavy/worked-examples,
Part B is conceptual/discussion). Natural split point for a two-session week marked below.

## Learning Objectives (from the book's own chapter objectives)
- Describe the contents of a typical business case
- Explain project portfolio management
- Carry out evaluation/selection of projects against strategic, technical and economic criteria
- Use cost-benefit evaluation techniques for comparing competing project proposals
- Evaluate the business risk involved in a project
- Explain how individual projects can be grouped into programmes
- Explain how programmes/projects are managed so planned benefits are achieved

---

## PART A: Project Evaluation (§2.1–§2.6) — ~60 min

### A1. The business case document (§2.1–2.2) — 10 min
- Recap from Lecture 1: every project needs a justification before a team is even assembled
- The book's 10-part business case structure: Introduction/background, Proposed project,
  Market, Organizational/operational infrastructure, Benefits, Outline implementation plan,
  Costs, Financial case, Risks, Management plan
- **Framing for students:** this 10-part structure is what their capstone teams will produce
  as their first deliverable — pairs naturally with the Annex 1 project-plan contents from
  Lecture 1

### A2. Project portfolio management (§2.3) — 10 min
- Definition: an overview of all projects an org is running/considering, used to prioritize
  resource allocation
- Three aspects: portfolio **definition**, portfolio **management**, portfolio **optimization**
- New product development (NPD, e.g. a game sold to customers) vs **renewal** projects
  (improving how the org operates) — a healthy portfolio balances both
- The "below the line" problem: informal ad-hoc work that doesn't appear in the official
  portfolio but still consumes effort

### A3. Evaluating individual projects (§2.4) — 10 min
- **Technical assessment**: can the required functionality be achieved with current,
  affordable technology?
- **Cost-benefit analysis**: identify costs (development, setup, operational) and benefits,
  express both in money
- **Cash flow forecasting** — Figure 2.1: the typical product-lifecycle cash flow curve
  (negative during development, positive during operation, possibly negative again at
  decommissioning)

**In-class activity — Exercise 2.1 (Brightmouth College):** Students list costs (development/
setup/operational) and benefits (quantified & valued / quantified but not valued / identified
but not easily valued) for replacing the college's payroll service.

### A4. Cost-benefit evaluation techniques — worked examples (§2.5) — 20 min
This is the core quantitative section — work through **Table 2.1** (four IOE project cash
flows) live, ideally on a spreadsheet/projector so students can follow the arithmetic:

| Technique | What it measures | Key worked example |
|---|---|---|
| **Net profit** | Total income − total costs over project life | Projects 1 & 3 both = £50,000 net profit — but very differently timed (Exercise 2.2) |
| **Payback period** | Time to break even | Exercise 2.3 — simple, but ignores everything after breakeven |
| **ROI** (= ARR) | `(average annual profit / total investment) × 100` | Exercise 2.4 — Project 1 = 10% |
| **NPV** | Discounts future cash flows to present value using `PV = value / (1+r)^t` | Table 2.3 — Project 1 NPV @ 10% = £618; Exercises 2.5–2.6 show NPV can **re-rank** projects differently than net profit/ROI because it accounts for timing |
| **IRR** | The discount rate that makes NPV = 0; a % return comparable to interest rates | Limitations: doesn't show absolute size of return; can have multiple solutions |

**Key takeaway to land explicitly:** no single technique is sufficient on its own —
real evaluation combines several, because each captures a different blind spot (timing,
scale, comparability with bank interest rates).

### A5. Risk evaluation (§2.6) — 10 min
- Recap: **project risk** (threatens successful execution) vs **business risk** (delivered
  product isn't profitable) — business risk is the focus here
- **Risk matrix** (Table 2.5): importance (H/M/L) × likelihood (H/M/L) for business risks
  like "competitors undercut prices" or "online payment has security problems"
- Risk premium: add 2–5% to the discount rate for risky projects
- **Cost-benefit with probabilities — Exercise 2.7 (BuyRight):** expected income =
  Σ(income × probability) — walk through Table 2.6 (expected income = £500,000) and ask
  students whether to proceed given £750,000 development cost + £200,000/year ongoing costs
- **Decision trees — Figure 2.2:** worked example of "extend vs. replace" a sales order
  system under market-expansion uncertainty; compute expected value of each branch
  (Extend = £40,000 vs Replace = £10,000 → choose Extend)

---
**— Natural split point for a two-session week —**
---

## PART B: Programme Management (§2.7–§2.14) — ~45 min

### B1. What is a programme? (§2.7) — 10 min
- Ferns' definition: *"a group of projects that are managed in a coordinated way to gain
  benefits that would not be possible were the projects to be managed independently"*
- Five types: business cycle programmes, strategic programmes, infrastructure programmes,
  R&D programmes, innovative partnerships — give one concrete example of each

### B2. Programme manager vs. project manager (§2.8–2.9) — 10 min
- **Table 2.7** contrast:

| Programme manager | Project manager |
|---|---|
| Many simultaneous projects | One project at a time |
| Personal relationship with skilled resources | Impersonal relationship with resource *type* |
| Needs to maximize resource utilization | Needs to minimize resource demand |
| Projects tend to be similar | Projects tend to be dissimilar |

- Strategic programme management — brief OGC/PRINCE2 background (sets up Appendix A
  for later if covered)

### B3. Creating a programme (§2.10) — 10 min
Walk through the pipeline using the book's "merging two organizations" example:
**programme mandate** → programme director appointed → **programme brief** (vision
statement, benefits, risks, costs/timescales) → **blueprint** (business models, org
structure, info systems, costs) → **benefit profiles** → **programme portfolio** →
preliminary plan → financial plan

### B4. Aids to programme management (§2.11) — 10 min
- **Dependency diagrams** — Figure 2.3: the 7-project merge example (A: systems study →
  C: build common systems → ... → G: implement corporate interface) — note how C and D
  both depend on A completing first
- **Delivery planning / tranches** — Figure 2.4: grouping the portfolio into tranches that
  each deliver a coherent set of benefits

### B5. Reservations & benefits management (§2.12–2.14) — 5 min
- Reservations: a programme isn't a "super-project" — over-structuring risks bureaucratic
  obstruction; programmes need to evolve as the business environment changes
- **Benefits management** — types of benefit: mandatory compliance, quality of service,
  productivity, risk reduction, economy, revenue enhancement/acceleration, strategic fit
- Quantifying benefits: quantified & valued / quantified but not valued / identified but
  not easily valued — plus **disbenefits** (e.g. more sales → more overtime cost)
- **Business change managers** — own benefit realization *after* the project closes
  (benefits can't be tracked within a project's own lifetime)

## Wrap-up (§2.14 Conclusion)
Recap the chapter's 4 key points:
- Projects must be evaluated on strategic, technical and economic grounds
- Many projects are only justifiable as part of a broader programme
- Not all benefits can be precisely quantified in financial terms
- Economic assessment requires identifying *all* costs and income over the system's
  full lifetime, not just development

---

## Homework / Follow-up
- Read Ch.2 in full (pp. 21–48)
- Problem set: Exercises 2.1–2.7 (cost-benefit calculations) — strong candidate for a
  spreadsheet-based tutorial/lab session, ties into the "Tools for Hands-on Labs" section
  of the teaching plan
- Further Exercises §2.15
- Capstone teams: draft the **business case** section (§2.2's 10-part structure) for their
  chosen project, including at least a payback-period and NPV estimate for their proposal
