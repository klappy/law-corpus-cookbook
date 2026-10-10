# ⚖️ law-corpus-cookbook

Law as a walkable fractal — a pinned, content-addressed jurisdiction stack (U.S. Code → CFR → Florida Statutes → Florida Administrative Code → Osceola County → Saint Cloud) with pre-registered questions, sealed ground truth, and receipts, so an agent can find the rule two layers up without reading the library. 🧭📜

**Public on purpose.** The corpus is public-domain law referenced by pointers (pinned by retrieval date, content-addressed); no ordinance text is republished here. The question set, scoring rule and freeze commits are public from day one. Each run's **answer key is held back** until that run's RESULTS land, then published with the receipts.

## What lives here
- `corpus/` — `DATASETS.md` (every source: URL, license, bulk format, size, retrieval date, pinned id) and per-layer pointer files. Never the text itself.
- `work/` — this project's rail: `queued/ active/ review/ done/`. One folder per unit: `TICKET.md`, receipts beside it.
- `journal/` — kirigami rows (`k####`), twelve-field floor, append-only.
- `PREREG.md` (when frozen) — the question set and scoring rule, frozen by the captain's taste; the freeze commit sha is the registration.

## Why
The NSF Project Pitch on the kitchen rail (`klappy/kitchen rail/1-ordered/2026-10-07-nsf-seed-fund-project-pitch/`) describes governance as a fractal of inherited layers. Law is that fractal in public, with the inheritance written into doctrine (preemption, conflict rules). This cookbook is the walker's second corpus and the candidate second Project Pitch: lawyers, citizens, judges, clerks.

## Ordering ticket
`klappy/kitchen rail/1-ordered/2026-10-10-legal-corpus-and-sealed-questions/TICKET.md` — read it first; `ANGLE-LEGAL.md` beside the pitch is the plan.

## Rules (short)
- Verify a dataset's license live before it is cited anywhere. No row in `DATASETS.md`, no citation.
- Question authors and walkers are separate seats. Sealed before any walk.
- Pointers, never slurps. Large sources live at their origin or a pinned mirror.
- Same four modes, same milestone ladder (30/300K → 20/200K → 10/100K → stretch 5/50K), same three controls as the parent pitch.
