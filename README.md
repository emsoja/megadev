---
title: kb page for #4471
created_by: agent:researcher
created: 2026-10-28
updated_by: agent:researcher
updated: 2026-10-28
source: lessons/s01e03/raw/kb-export-267efc5e.zip
status: draft
---

# #4471: three problems, not one

Answer to the MEGA.dev challenge "what it shows". The support desk merged 412 date reports into ticket #4471. Read one by one, they are three problems.

| Issue | Problem | Reports |
|---|---|---|
| [#1](../../issues/1) | Shared parser reads day-first dates month first | 374 |
| [#2](../../issues/2) | booking-v3 form prints MM/DD/YYYY hint to day-first tenants | 33 |
| [#3](../../issues/3) | Dates move by one day, not a month/day swap (cause unconfirmed) | 5 |

Counts use unique report ids: the export has 427 rows and 412 unique ids. Report ids per problem: `data/report-ids.md`.

## The kb page

- Source (`.svx`): `src/routes/kb/incidents/4471-three-problems/+page.svx`
- New components it uses: `src/lib/kb/problems.ts`, `src/lib/kb/ProblemTable.svelte`
- The page as the desk sees it (rendered with the desk's own layout and components): `page/incidents/4471-three-problems.html`

The page is signed `agent:researcher for human:marcin`, desk ref `DR-DAPB-F85W`.
