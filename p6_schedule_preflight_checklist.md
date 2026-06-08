# P6 Schedule Pre-Flight Checklist

> Run this on your own before sending a schedule for review. It's a plain-language version of the **DCMA 14-Point Assessment** — the schedule-health standard used in real project controls. If you can tick most of these, your schedule is genuinely "on track" and worth a deeper review. The thresholds in brackets are the industry benchmarks; treat them as targets, not pass/fail laws on a practice project.

---

## A. Structure & completeness

- [ ] **One true start, one true finish.** The whole project has a single open start and a single open finish — nothing else dangles.
- [ ] **No open ends** anywhere else. Every other activity has at least one predecessor AND one successor. *(DCMA: missing logic ≤ 5%)*
  - *How to check in P6:* add columns for Predecessor and Successor counts, or filter for activities with no predecessor / no successor.
- [ ] **Activity count is sensible** for the scope — not 15 mega-activities, not 3,000 micro-ones.
- [ ] **No orphan activities** sitting outside the WBS.

## B. Logic quality

- [ ] **Mostly Finish-to-Start.** FS relationships make up the large majority. *(DCMA: FS ≥ 90%)*
- [ ] **SS / FF used only where real**, and you can explain each one out loud.
- [ ] **No leads (negative lags).** Negative lag is a red flag — rework the logic instead. *(DCMA: leads = 0)*
- [ ] **Lags are rare and justified.** *(DCMA: lags ≤ 5% of relationships)*
- [ ] **No redundant logic** (an activity tied both directly and indirectly to the same successor without reason).

## C. Constraints

- [ ] **Hard constraints are minimal.** Prefer "Start On or After" / "Finish On or Before" over "Mandatory Start/Finish". *(DCMA: hard constraints ≤ 5%)*
- [ ] **Every constraint has a reason** you've written down (ideally in the Basis of Schedule).
- [ ] **No Mandatory constraints** unless contractually forced — they break the network logic.

## D. Critical path & float

- [ ] **The critical path is continuous and traceable** from start to finish — you can follow it activity by activity.
- [ ] **The critical path makes physical sense** (it runs through the work that genuinely controls completion, not through an admin task).
- [ ] **No negative total float** on a baseline schedule. *(DCMA: negative float = 0)*
- [ ] **No absurdly high float.** Few activities should have total float above ~44 working days; if many do, your logic is probably too loose. *(DCMA: high float ≤ 5%)*

## E. Durations & calendars

- [ ] **Calendars are assigned** to every activity, with the right work pattern and holidays.
- [ ] **No long "black box" durations.** Few activities should exceed ~44 working days; long ones usually need breaking down. *(DCMA: high duration ≤ 5%)*
- [ ] **No zero-duration activities** except real milestones.
- [ ] **You can state the basis** of each major duration (rate, crew, quantity, or experience).

## F. Baseline & updating *(from Project 3 onward)*

- [ ] **Baseline set before progressing.** A primary baseline is assigned.
- [ ] **Data date is correct** for the update period.
- [ ] **% complete type is deliberate** (duration / physical / units) — you know which you used and why.
- [ ] **No invalid dates.** No actual dates in the future; no forecast dates in the past. *(DCMA check)*
- [ ] **Variance is explainable** — for anything that slipped, you can say why.

## G. Resources *(for resource-loaded schedules)*

- [ ] **Resources/costs loaded** where the project calls for it.
- [ ] **No unexplained over-allocation spikes** in the histogram.
- [ ] **The S-curve shape is realistic** (slow start, steep middle, tapering finish).

## H. The thinking (Basis of Schedule)

- [ ] **Sections 8 & 9 are written in full** — basis of durations and sequencing logic. These are the ones reviewers read first.
- [ ] **Assumptions, constraints, and exclusions are explicit.**
- [ ] **A stranger could read the narrative and understand why the schedule looks the way it does** without you in the room.

## I. Review packet — what to send

When the above is ticked, send me:

- [ ] **Tracker backup JSON** (the 💾 export) — covers learning progress + all Basis narratives
- [ ] **The XER file** — so I can run an automated health check on the points above
- [ ] **Gantt screenshot with a critical-path filter on**
- [ ] **Activity table screenshot showing predecessor/successor columns**
- [ ] **Resource histogram + S-curve** (resource-loaded projects)
- [ ] **For updates:** before/after data-date views and your variance notes

---

### Quick "is it clean?" gut check (the 4 that matter most)
1. One open start, one open finish — nothing else dangling.
2. Hard constraints close to zero.
3. Mostly Finish-to-Start logic.
4. A critical path you can trace and explain.

If those four hold, you're in good shape. The rest is polish.
