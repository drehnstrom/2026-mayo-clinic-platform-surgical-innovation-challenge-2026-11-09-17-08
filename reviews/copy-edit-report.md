# Copy Edit Report: 2026 Mayo Clinic Platform Surgical Innovation Challenge

## Pass: 2026-11-09

| Field | Value |
| :--- | :--- |
| Editor model | Claude 3.5 Sonnet (Copy Editor Agent) |
| Session | Fresh (yes) |
| Scope | Slides only (`course/00-introduction.md`, `course/01-run-of-show.md`; no lab files exist) |

### Glossary

| Term | Form used | Notes |
| :--- | :--- | :--- |
| Behind Glass | `Behind Glass` | Standardized capitalized form for the secure Mayo Clinic Platform analytical enclave |
| Export Template | `Export Template` | Standardized Title Case for the official export request document |
| Antigravity CLI | `Antigravity CLI` | Left as official Google hackathon CLI tool name |
| TSMs | `TSMs` | Technical Solutions Managers (Mayo Clinic Platform support role) |
| Dr. Gelareh Zadeh | `Dr. Gelareh Zadeh` | Opening keynote speaker name verified |
| Dr. Kyle Ettinger | `Dr. Kyle Ettinger` | Challenge topic briefings speaker name verified |
| Build Sprint N | `Build Sprint 1` through `5` | Standardized naming across all three days |
| gcloud / bq | `gcloud`, `bq` | Left as command-style names inside code fences |

### Fix counts

| Type | Count |
| :--- | :--- |
| Spelling | 0 |
| Grammar | 1 |
| Smart quotes | 0 |
| Em-dashes / ampersands | 5 |
| Consistency | 4 |

### Representative fixes

- `course/00-introduction.md` / Who Should Attend: Standardized casing from `AI and ML engineers` to `AI and ML Engineers` to match parallel role titles (`Data Scientists`, `Healthcare Researchers`).
- `course/01-run-of-show.md` / Navigation slides (5 slides): Standardized `Data and Workspace Introduction (Mayo Clinic Platform TSMs, 10:00–11:20)` to `Data and Workspace Introduction (Mayo Clinic Platform TSMs, 10:00 to 11:20 AM)` to match slide 7 title format and eliminate en-dash inconsistency.
- `course/01-run-of-show.md` / Saturday Morning Kickoff: Changed hyphen to colon in `Opening Keynote: *Mayo Clinic Platform and the Power of Data*`.
- `course/01-run-of-show.md` / Google Tools Introduction: Standardized time in title from `(11:20 to 12:00)` to `(11:20 AM to 12:00 PM)`.
- `course/01-run-of-show.md` / Monday Morning Build Sprints: Fixed missing article in callout prose: `Do not wait until afternoon` → `Do not wait until the afternoon`.
- `course/01-run-of-show.md` / Quiz 3 Discussion Points: Fixed inconsistent casing: `Monday Afternoon Sprint 5` → `Monday afternoon Sprint 5`.

### Left unchanged

- `gcloud config list`, `bq ls`, and `antigravity --help` kept as literal CLI syntax inside bash code block.
- `images/roi-logo-with-name.png`, `welcome.png`, `agenda.png`, `who-should-attend.png`, `prerequisites.png`, `ch01-behind-glass-export-boundary.svg`, and `ch01-sprint-progression-arc.svg` paths and alt texts preserved.
- Event structure, timetable, speaker assignments, and quiz formats kept intact.
