# Cub Scouts — Den Planning & Advancement Tracking

Planning meetings and tracking advancement for our Cub Scout den. Currently a
**Tiger** den (1st grade). Built to grow with the scout: add a rank each year.

## How the program works (2024+ update)

- Ranks by grade: **Lion** (K) → **Tiger** (1st) → **Wolf** (2nd) → **Bear**
  (3rd) → **Webelos** (4th) → **Arrow of Light** (5th).
- Each rank = **6 required + 2 elective adventures**.
- **Bobcat** is no longer a standalone badge — it's the *first required
  adventure* of every rank, redone age-appropriately each year.

## Layout

```
adventures/   one file per rank — required + elective adventures and requirement text
meetings/     one file per meeting — dated plan with agenda + requirement checklist
```

> **Public repo — no PII.** No scout names, contact info, or rosters go in here.
> Track who completed what in [Scoutbook](https://scoutbook.scouting.org), the
> official system of record. See `CLAUDE.md` for the rules.

## Workflow

1. **Plan** — copy a meeting file, pick the adventure + requirements to hit.
2. **Run** the meeting.
3. **Record** completions in [Scoutbook](https://scoutbook.scouting.org) (official
   system of record) — not in this repo.

## Growing to the next rank

When the den advances (e.g. Wolf next year): add `adventures/wolf.md` from
[scouting.org/programs/cub-scouts/adventures](https://www.scouting.org/programs/cub-scouts/adventures/),
keep going. Nothing here needs restructuring.

## Start here

- Tomorrow's meeting: [`meetings/2026-09-20-tiger-bobcat.md`](meetings/2026-09-20-tiger-bobcat.md)
- Tiger adventures + Bobcat requirements: [`adventures/tiger.md`](adventures/tiger.md)
