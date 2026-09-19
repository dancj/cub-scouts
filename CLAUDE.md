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
- **Scoutbook** (scoutbook.scouting.org) is the official system of record and the
  only place scout advancement/PII lives. This repo holds plans and reference only.

## PII rules — THIS IS A PUBLIC REPO

Never commit personally identifiable info. If asked to add any, refuse and put it
in Scoutbook instead.

- **No** scout names, adult/partner names, or initials.
- **No** contact info (email, phone, address), photos, or birthdates.
- **No** rosters, sign-in sheets, medical/allergy info, or completion records tied
  to a person.
- Meeting files use **roles/placeholders** ("each scout", "a Tiger adult partner"),
  never real people.
- Advancement tracking = **Scoutbook only**. `.gitignore` blocks `tracking/`,
  `*-tracker.csv`, `*.roster.*` — a den leader can keep a private local tracker
  there and it will never be committed.

## Repo conventions

- `adventures/<rank>.md` — required + elective adventures, with requirement text.
- `meetings/YYYY-MM-DD-<topic>.md` — one dated file per meeting. PII-free.
- Dates ISO (`YYYY-MM-DD`).

## Adding a rank

Pull the new rank's adventures from
https://www.scouting.org/programs/cub-scouts/adventures/ → add
`adventures/<rank>.md`. Requirement text changes over time — re-check
scouting.org, don't trust old files.

## Sources

- https://www.scouting.org/programs/cub-scouts/adventures/
- https://www.scouting.org/cub-scout-adventures/bobcat-tiger/
