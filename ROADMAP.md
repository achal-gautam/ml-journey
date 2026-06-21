# ML Journey — Master Roadmap
### Started: 22 June 2026 | Target: Employable by end of 2026

---

## About Me

- Pure maths postgrad — very little applied study
- Intermediate Python — no numpy, pandas, pytorch, matplotlib etc.
- Need to relearn/learn statistics from an applied perspective
- Work 2 days a week — ample time available
- **ADHD** — need checklists, broken into weeks, clear phases, no drift
- Love maths deeply — tendency to over-theorise and procrastinate via depth
- Love handwriting — one physical notebook per phase
- GitHub repo: `ml-journey`
- Local folder: `~/ml-journey` with subfolders `phase1/` through `phase6/`
- Conda environment: `mljourney` (Python 3.11)
- VS Code kernel: "ML Journey"

---

## The Core Study Principle

**Theory earns its place by immediately serving a practical skill.**
Every maths concept has a direct, visible payoff in code that same week.
Maths is the reward, not the preamble.

Applied study loop: **read → do → check → reflect → repeat**
This is different from pure maths (read → think → prove). Moving on without
fully understanding something is allowed — the next thing often explains the previous.

---

## The 6-Phase Roadmap

| Phase | Weeks | Dates | Theme |
|-------|-------|-------|-------|
| 1 | 1–4 | 22 Jun – 19 Jul | Python Data Stack + Stats Foundations |
| 2 | 5–9 | 20 Jul – 23 Aug | Classical ML + Statistics Applied + SQL |
| 3 | 10–14 | 24 Aug – 27 Sep | Deep Learning Foundations |
| 4 | 15–19 | 28 Sep – 1 Nov | Deep Learning Applied (CNNs, NLP, Transformers) |
| 5 | 20–23 | 2 Nov – 29 Nov | MLOps + Production |
| 6 | 24–26 | 30 Nov – 21 Dec | Portfolio + Job Prep |

---

## Resources — When to Use Each

| Resource | Phase | How to use |
|---|---|---|
| **Python for Data Analysis** — McKinney | 1 | Code-along, every function typed not pasted. Primary practical spine for Phase 1. |
| **All of Statistics** — Wasserman | 1–2 | Ch. 1–6 in Phase 1 (probability, distributions, expectation). Ch. 7–13 in Phase 2 (inference, regression). Rigorous supplement — ration time on it. |
| **Andrew Ng ML Course** | 2–3 | Runs parallel with Hands-On ML. Ng = intuition + maths derivations. Géron = code. |
| **Mathematics for Machine Learning** — Deisenroth | 1–3 (reference) | Do NOT read linearly. Use as a lookup and deepener. Scheduled maths reward blocks only. |
| **Hands-On Machine Learning** — Géron | 2–4 | Main practical spine for classical ML and early deep learning. Chapter by chapter, code everything. |
| **ML with PyTorch and Scikit-Learn** — Raschka | 3–4 | Use alongside Géron for PyTorch. More code-heavy. Different perspective to reinforce concepts. |
| **Andrej Karpathy — Neural Networks: Zero to Hero** (YouTube) | 3–4 | Best resource for maths → code. Builds GPT from scratch. No hand-waving. |
| **SQLZoo or Mode SQL Tutorial** | 2 (Weeks 6–7) | Browser-based interactive SQL. ~6–8 hours covers everything needed. |
| **StrataScratch** | 6 | Real SQL interview questions from actual companies. Interview prep only. |
| **FastAI practical lessons** | 5 | Top-down practical approach for MLOps and deployment concepts. |
| **Designing ML Systems** — Huyen | 5 | Free chapters available. Production ML thinking. |

---

## Phase End Projects

| Phase | Project |
|---|---|
| 1 | Full EDA notebook — real dataset, plots, statistical commentary, pushed to GitHub |
| 2 | End-to-end ML pipeline — regression + classification on Kaggle dataset, full scikit-learn workflow |
| 3 | Neural net from scratch in PyTorch on MNIST/CIFAR-10 — maths written up in physical notebook |
| 4 | NLP project — sentiment analysis or text classifier using pretrained transformer (HuggingFace) |
| 5 | Deployed model as REST API (FastAPI or Flask) + model card + basic CI pipeline |
| 6 | 3 polished GitHub projects + resume + LinkedIn live + 5–10 job applications |

---

## Employable Target Profile (End of 2026)

- Python fluency: numpy, pandas, scikit-learn, PyTorch
- End-to-end ML pipeline: data → model → evaluation → deployment
- Understanding of core algorithms — can explain AND derive them
- Deep learning fundamentals + at least one applied area (NLP or CV)
- Git/GitHub with real projects
- Basic MLOps: can serve a model, understands experiment tracking
- SQL: basic + intermediate (SELECT, JOIN, GROUP BY, subqueries, CASE WHEN)
- Portfolio of 3 non-trivial projects with good documentation

---

## ADHD Management System

### Core rules
- Every week has a **checklist of checkboxes** — not goals, checkboxes
- Projects are **mandatory** — you do not move to the next phase without shipping the project
- **One notebook per phase** — physical, Cornell layout, dated every page

### The Maths Deep Dive Queue
- Lives at the back of each physical notebook
- When a rabbit hole tempts you, write it there — do NOT follow it immediately
- **Scheduled reward block:** after completing the week's practical checklist
- One item per reward block, 45 minutes maximum, timer set
- This channels the rabbit-hole instinct productively rather than suppressing it

### Theory-first trap
- You are not allowed to read theory before attempting the practical
- Code before you're ready — write broken code, get errors, fix them
- Understanding why things work comes AFTER seeing that they work

### Session structure (Pomodoro)
- 25 min work → 5 min break (one Pomodoro)
- Typical session: 4 Pomodoros = ~2.5 hours real work
- Block 1–2: read + notebook
- Block 3: code
- Block 4: active recall + review + tomorrow's prep

### End of session ritual (non-negotiable)
1. `git add . && git commit -m "phase[N] week[N]: what you did" && git push`
2. Write tomorrow's first task at the top of a fresh notebook page
3. Check the week's checklist

---

## Notebook System

### Physical notebook — one per phase
- Label: `ML Journey — Phase N`
- Date every page
- Cornell layout on every page:
  - Left ~1/3: cue column (keywords, questions — filled AFTER main notes)
  - Right ~2/3: main notes area (derivations, diagrams, pseudocode, examples)
  - Bottom ~4 lines: summary bar (written last — "what does this mean?")

### Two notebooks per phase
- **Notebook A — Study notebook:** Cornell layout. Concepts, derivations, diagrams.
- **Notebook B — Project notebook:** Engineering logbook. Architecture sketches, bugs, decisions.

### What goes in the notebook
| Content | How |
|---|---|
| Concept explanation | Rewrite in your own words — never copy from the book |
| Derivations | By hand, step by step, with reasons |
| Diagrams | Draw everything — nets, curves, decision boundaries |
| Code | Pseudocode only — actual code lives in `.ipynb` files |
| Questions | Cue column with `?` — resolve later |
| "Wait, why?" moments | Circle, cue column, resolve in reward block if > 5 min |
| Intuitions | "This feels like eigenvectors..." — write these |
| Mistakes | Write them — "I thought X but actually Y because Z" |
| Summary | Bottom of every page — one or two sentences |

### What NOT to do
- No re-reading sections before attempting active recall
- No highlighting
- No copying text from books
- No needing to understand everything before moving on

---

## Active Recall System

After every section: close book/laptop, look at cue column only, try to explain each cue.
For code: close the example, retype from memory. Peek if stuck, then try again.
The struggle to remember IS the learning — not a sign of failure.

---

## Anki System

**Rule: understanding first, Anki second. Never the other way around.**

### Start: Week 2 onwards (not before)

### What to make cards for
- Key formula definitions
- NumPy/pandas function signatures you keep forgetting
- Statistical distributions — name, PDF, parameters
- ML algorithm names + one-line descriptions
- Terminology (precision vs recall, bias vs variance)
- Interview Q&A style facts

### What NOT to make cards for
- Understanding of concepts (cards can't teach understanding)
- How algorithms work (too complex for a single card)
- Anything you don't yet understand

### Card rules
- **Atomic** — one fact per card, as small as possible
- **Make your own** — don't download pre-made decks as a substitute for understanding
- LaTeX works in Anki — use it for maths cards
- 15 minutes per day maximum — morning before study session or end of session
- 15–20 new cards per day maximum

---

## SQL Placement (Updated from original roadmap)

**SQL moves to Phase 2 — not Phase 5.**

Rationale: pandas and SQL are complementary. `GROUP BY` = `groupby()`.
`JOIN` = `merge()`. Learning them close together means mutual reinforcement.

### Target SQL level
| Level | Topics | Status |
|---|---|---|
| Basic | SELECT, WHERE, ORDER BY, LIMIT, GROUP BY, COUNT, SUM, AVG | ✅ Required |
| Intermediate | JOINs (INNER/LEFT/RIGHT), subqueries, HAVING, CASE WHEN | ✅ Required |
| Advanced | Window functions, CTEs | ⚠️ Nice to have |
| Expert | DB design, stored procedures | ❌ Not needed |

### Resources
- **Learn:** SQLZoo (sqlzoo.net) or Mode SQL Tutorial — browser-based, no setup, ~6–8 hours
- **Interview prep (Phase 6):** StrataScratch — real questions from real companies

---

## Git Workflow

### Daily commit message format
`phase[N] week[N]: what you did`
Example: `phase1 week1 day2: python basics, data structures, functions`

### Daily commands
```bash
git add .
git commit -m &quot;phase1 week1: description&quot;
git push
```

### Useful commands
```bash
git status          # what has changed
git log --oneline   # commit history
git diff            # exact changes
git pull            # sync from GitHub
```

---

## Folder Structure

```
ml-journey/
├── ROADMAP.md              ← this file
├── phase1/
│   ├── notebooks/          ← .ipynb files
│   ├── data/               ← datasets
│   ├── scripts/            ← .py files
│   └── notes/              ← photos of handwritten notebook pages
├── phase2/
│   └── ...
├── phase3/
│   └── ...
├── phase4/
│   └── ...
├── phase5/
│   └── ...
└── phase6/
    └── ...
```

---

## How to Use This Document with AI Assistants

When starting a new conversation, paste the relevant section(s) as context.
At minimum, paste:
- "About Me"
- "The 6-Phase Roadmap" table
- The current phase's section from the weekly plan

The assistant will then have full context and can pick up exactly where you left off.

---

## Weekly Plan Log
*(Update this as each week is completed)*

| Week | Dates | Status | Notes |
|---|---|---|---|
| Week 1 | 22–28 Jun | 🔄 In progress | Day 1 complete. Day 2 in progress. |
| Week 2 | 29 Jun–5 Jul | ⬜ Not started | |
| Week 3 | 6–12 Jul | ⬜ Not started | |
| Week 4 | 13–19 Jul | ⬜ Not started | Phase 1 project week |
| Week 5 | 20–26 Jul | ⬜ Not started | Phase 2 begins |
| Week 6 | 27 Jul–2 Aug | ⬜ Not started | SQL starts here |
| Week 7 | 3–9 Aug | ⬜ Not started | SQL continues |
| Week 8 | 10–16 Aug | ⬜ Not started | |
| Week 9 | 17–23 Aug | ⬜ Not started | Phase 2 project week |
| Week 10 | 24–30 Aug | ⬜ Not started | Phase 3 begins |
| Week 11 | 31 Aug–6 Sep | ⬜ Not started | |
| Week 12 | 7–13 Sep | ⬜ Not started | |
| Week 13 | 14–20 Sep | ⬜ Not started | |
| Week 14 | 21–27 Sep | ⬜ Not started | Phase 3 project week |
| Week 15 | 28 Sep–4 Oct | ⬜ Not started | Phase 4 begins |
| Week 16 | 5–11 Oct | ⬜ Not started | |
| Week 17 | 12–18 Oct | ⬜ Not started | |
| Week 18 | 19–25 Oct | ⬜ Not started | |
| Week 19 | 26 Oct–1 Nov | ⬜ Not started | Phase 4 project week |
| Week 20 | 2–8 Nov | ⬜ Not started | Phase 5 begins |
| Week 21 | 9–15 Nov | ⬜ Not started | |
| Week 22 | 16–22 Nov | ⬜ Not started | |
| Week 23 | 23–29 Nov | ⬜ Not started | Phase 5 project week |
| Week 24 | 30 Nov–6 Dec | ⬜ Not started | Phase 6 begins |
| Week 25 | 7–13 Dec | ⬜ Not started | |
| Week 26 | 14–21 Dec | ⬜ Not started | Portfolio complete. Apply. |

---

*Last updated: 22 June 2026*