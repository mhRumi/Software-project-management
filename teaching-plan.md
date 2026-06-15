# Software Project Management — Teaching Plan

## Primary Textbook

**"Software Project Management" by Bob Hughes & Mike Cotterell, 5th Edition (McGraw-Hill, 2009)**
Best fit for an SPM course specifically (not a generic PM book). Covers WBS, estimation
(COCOMO, function points), PERT/CPM scheduling, risk, quality, and has solid agile
chapters. Widely used as the core text in CS/SE programs.

> Available locally at:
> `/run/media/rumi/b/documents/SPM/Software_Proiect_Management_F_fth_Editio.pdf`
> (Note: `16_EBOOK-7th_ed_..._pressman_.pdf` in the same folder is a mislabeled
> duplicate of this same book, not Pressman — both files contain Hughes & Cotterell 5e.)

### Alternatives depending on course slant
- **"Information Technology Project Management" by Kathy Schwalbe** — if leaning toward
  PMBOK/PMI-style IT project management (broader than just software, comes with
  planning templates).
- **"Agile Estimating and Planning" by Mike Cohn** + the official **Scrum Guide** — if
  the course is agile-heavy.

### Supplementary reading (for discussion/seminars)
- *The Mythical Man-Month* — Fred Brooks (classic essays on why adding people doesn't
  speed up late projects)
- *Peopleware* — DeMarco & Lister (team dynamics, productivity)
- Sommerville's *Software Engineering* — concise PM chapter for SE-context grounding

## Better Explanations Per Topic

Hughes/Cotterell/Ince is a good *topic map and reference* (and useful for exam-style
content), but its explanations are dry/dense. Use it for the syllabus skeleton, but
draw lecture explanations from these more engaging sources:

| Topic | Better-explained source |
|---|---|
| Overall PM narrative / intro to project management | *The Art of Project Management* — Scott Berkun (practical, story-based) |
| Estimation (COCOMO, function points, story points) | *Software Estimation: Demystifying the Black Art* — Steve McConnell |
| Risk management | *Waltzing with Bears* — Tom DeMarco & Timothy Lister (story-driven) |
| Agile / Scrum | *Scrum: The Art of Doing Twice the Work in Half the Time* — Jeff Sutherland |
| Team organization & people management | *Peopleware* — DeMarco & Lister; *The Mythical Man-Month* — Fred Brooks |

**Free video lectures for students:**
- NPTEL "Software Project Management" course — clear, structured lecture videos covering the same topics
- Coursera "Software Processes and Agile Practices" specialization (University of Alberta)

## Tools for Hands-on Labs
- **Jira or Trello** — sprint planning, backlogs, kanban boards
- **MS Project / GanttProject (free)** — Gantt charts, CPM/PERT scheduling
- **COCOMO II online calculator** — effort estimation exercises

## Syllabus — Mapped to Hughes & Cotterell 5e Chapters

15-week mapping, one chapter per week (Ch.5 split across two weeks since it has
14 subsections). Page numbers refer to the 5th edition PDF.

| Week | Chapter | Title (pp.) |
|---|---|---|
| 1 | Ch.1 | Introduction to software project management (1–20) |
| 2 | Ch.2 | Project evaluation and programme management (21–48) |
| 3 | Ch.3 | An overview of project planning — Step Wise (49–72) |
| 4 | Ch.4 | Selection of an appropriate project approach — waterfall, spiral, agile, XP (73–102) |
| 5 | Ch.5a | Software effort estimation — concepts & techniques, §5.1–5.9 (103–113) |
| 6 | Ch.5b | Software effort estimation — algorithmic models: FPA, COSMIC, COCOMO II, §5.10–5.14 (114–128) |
| 7 | Ch.6 | Activity planning — networks, CPM (129–161) |
| 8 | Ch.7 | Risk management (162–191) |
| 9 | Ch.8 | Resource allocation (192–211) |
| 10 | Ch.9 | Monitoring and control — earned value (212–235) |
| 11 | Ch.10 | Managing contracts (236–253) |
| 12 | Ch.11 | Managing people in software environments (254–270) |
| 13 | Ch.12 | Working in teams (271–292) |
| 14 | Ch.13 | Software quality (293–324) |
| 15 | — | Review + capstone project presentations (optional: Appendix A — PRINCE2 overview, 325–336) |

## Assessment Idea
A team-based "plan and run a mini software project" assignment running across the
semester (using Jira + a Gantt tool) tends to be the most effective way to make the
concepts stick.
