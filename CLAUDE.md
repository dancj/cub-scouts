# CLAUDE.md — context for AI sessions

## What this is

Den planning + advancement tracking for a Cub Scout den. Dan is an **assistant
den leader** for a **Tiger den** (1st grade). His kid will advance one rank per
year, so this repo is built to grow: one rank at a time.

## Program facts (BSA / Scouting America, 2024+ update)

- Ranks by grade: Lion (K), **Tiger (1st)**, Wolf (2nd), Bear (3rd),
  Webelos (4th), Arrow of Light (5th).
- Each rank = **6 required + 2 elective adventures**.
- **Bobcat** is not a standalone badge anymore — it is the *first required
  adventure* of each rank, age-appropriate per year.
- Lion and Tiger are **adult-partner** ranks: each scout attends with a Tiger
  adult partner (parent/guardian).
- **Scoutbook** (scoutbook.scouting.org) is the official system of record. This
  repo is the working copy; the tracker CSV gets copied into Scoutbook.

## Repo conventions

- `adventures/<rank>.md` — required + elective adventures, with requirement text.
- `meetings/YYYY-MM-DD-<topic>.md` — one dated file per meeting.
- `tracking/<rank>-tracker.csv` — rows = scouts, columns = adventures (completion
  date). Requirement-level detail lives in the meeting/adventure files.
- Dates ISO (`YYYY-MM-DD`). Real scout names go only in `tracking/` (keep PII out
  of committed docs if this ever goes to a shared/remote repo).

## Adding a rank

Pull the new rank's adventures from
https://www.scouting.org/programs/cub-scouts/adventures/ → add
`adventures/<rank>.md` + `tracking/<rank>-tracker.csv`. Requirement text changes
over time — re-check scouting.org, don't trust old files.

## Sources

- https://www.scouting.org/programs/cub-scouts/adventures/
- https://www.scouting.org/cub-scout-adventures/bobcat-tiger/
