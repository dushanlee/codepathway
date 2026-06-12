# CodePathway

CodePathway is a complete self-paced software engineering learning platform built as a single HTML file. It combines a structured 7-phase curriculum, a daily scheduling engine, an in-browser code playground, progress tracking, and interview prep tools into one place — no accounts, no backend, no install required.

**Live site:** https://dushanlee.github.io/codepathway/

---

## Purpose

Built for:

- Beginner software engineers
- Coding bootcamp graduates
- Self-taught developers
- Career changers transitioning into tech
- Anyone who needs a structured, opinionated path into software engineering

---

## Pages

The app has eight pages, each reachable from the top nav bar or by pressing its number key.

| Key | Page | Description |
|-----|------|-------------|
| `1` | Home | Progress snapshot, phase overview, quick navigation |
| `2` | Daily | Today's lesson, streak bar, focus timer, calendar, schedule settings |
| `3` | Roadmap | Phase table, cost/time breakdown, interactive knowledge graph |
| `4` | Curriculum | All 67 lessons by phase — objectives, resources, practice tasks |
| `5` | Checklist | Same lessons as a checkbox skill list, synced with Daily |
| `6` | Practice | In-browser multi-language playground + per-lesson practice links |
| `7` | Tracker | Project log, DSA log, STAR stories, system design notes |
| `8` | Help | Keyboard shortcuts, schedule guide, backup/restore instructions |

---

## Curriculum

67 lessons across 7 phases, ordered from foundational Python to interview readiness.

| Phase | Name | Lessons | Outcome |
|-------|------|---------|---------|
| 1 | Python Fundamentals | 11 | Write Python programs: scripts, OOP, file I/O, error handling, async basics |
| 2 | CS Fundamentals & DSA | 12 | Analyze Big-O and solve 50+ LeetCode problems by pattern |
| 3 | Languages & Tooling | 10 | Build frontends with HTML/CSS/JS, use Git professionally, configure a dev environment |
| 4 | Full Stack Frameworks | 9 | Build a full-stack app: React + FastAPI + PostgreSQL + JWT auth |
| 5 | DevOps & Deployment | 8 | Containerize with Docker, deploy to AWS/Render, set up CI/CD, write tests |
| 6 | Engineering Depth | 9 | Design scalable systems, audit for security vulnerabilities, profile and optimize |
| 7 | Job-Ready Polish | 8 | Polished resume, portfolio, 150+ LeetCode problems, 10+ STAR stories, 5+ mock interviews |

<details>
<summary>View all 67 lessons</summary>

**Phase 1 — Python Fundamentals**
1. Syntax & Variables
2. Control Flow
3. Functions
4. Built-in Data Structures
5. OOP
6. Modules & Packages
7. Error Handling
8. Type Hints
9. File I/O & Context Managers
10. Async & Concurrency
11. Small Python Projects

**Phase 2 — CS Fundamentals & DSA**
12. Big O Notation
13. Arrays & Hashing
14. Two Pointers & Sliding Window
15. Linked Lists
16. Stacks & Queues
17. Trees & BSTs
18. Heaps & Priority Queues
19. Graphs
20. Sorting & Searching
21. Recursion & Backtracking
22. Dynamic Programming
23. OS & Networking Theory

**Phase 3 — Languages & Tooling**
24. JavaScript
25. TypeScript
26. HTML
27. CSS
28. Git
29. Linux & Terminal
30. Env Vars & Secrets
31. Package Managers
32. AI-Assisted Development
67. Tailwind CSS

**Phase 4 — Full Stack Frameworks**
33. React
34. State Management
35. FastAPI
36. PostgreSQL & SQL
37. SQLAlchemy ORM
38. REST API Design
39. Authentication
40. Third-Party APIs
41. API Consumption

**Phase 5 — DevOps & Deployment**
42. Docker
43. AWS Core Services
44. Deploying to Production
45. CI/CD Pipelines
46. Testing
47. Debugging
48. Code Quality
49. Secrets Management

**Phase 6 — Engineering Depth**
50. System Design
51. Distributed Systems
52. Security (OWASP)
53. Performance
54. Monitoring & Observability
55. Advanced API Patterns
56. Agile & Team Workflow
57. Technical Writing
58. Caching with Redis

**Phase 7 — Job-Ready Polish**
59. Resume
60. GitHub Profile
61. Portfolio Site
62. DSA Interview Prep
63. Behavioral Prep
64. System Design Prep
65. Mock Interviews
66. LinkedIn & Networking

</details>

---

## Features

### Daily Dashboard

- Shows today's assigned lesson with phase, difficulty rating, and learning objectives
- Streak bar with cards for current streak, total lessons done, and estimated finish date
- Lesson navigator — step forward and back through any lesson with `J` / `K`
- Mark a lesson as learned with one click or by pressing `M`
- Rest day detection — shows the next upcoming lesson on days off
- Built-in focus timer
- Undo any schedule change with `Ctrl/Cmd+Z` — stack holds 30 actions

### Schedule Controls

- Set a study start date, rest days of the week, and a target finish date
- Scheduling engine auto-assigns lessons to calendar dates weighted by difficulty
- Skip any lesson without losing progress; skipped lessons are flagged in the Calendar view
- Export full progress as a `.json` backup and restore from the same menu

### In-Browser Playground

Write and run code without leaving the app. Code auto-saves per language.

| Environment | Runtime |
|------------|---------|
| JavaScript | Native browser execution |
| HTML / CSS | Live iframe preview |
| TypeScript | Browser-based transpilation |
| Python | Pyodide — runs fully in-browser |
| React | Browser-based JSX transpilation |
| SQL | In-browser SQLite |
| Tailwind CSS | CDN-backed live preview |

### Engineering Tracker

- **Projects** — log real projects with stack, status, and links
- **DSA Log** — record LeetCode/NeetCode problems with pattern, difficulty, and notes
- **STAR Stories** — write behavioral interview answers in Situation/Task/Action/Result format
- **System Design** — record practice sessions per topic

### Knowledge Graph

An interactive, draggable SVG graph on the Roadmap page showing all 67 lessons as nodes with prerequisite edges. Color-coded by phase. Click any node to view lesson details and jump to it in the Daily view. Supports pan, zoom, and fullscreen.

### Search

Press `/` from any page to search across lesson names, objectives, resource names, and your own personal notes.

### Command Palette

`Ctrl+K` opens a command palette for quick actions — jump to any page, mark the current lesson done, open your notes, export progress, and more.

### Notes

Every lesson has a freeform notes field included in search. The Review All panel collects every note in curriculum order, lets you filter and jump to any lesson, and exports the full set as Markdown. Import a Markdown file back in to sync edits made in an external editor.

### Achievements

| Tier | Examples |
|------|---------|
| Bronze | First Step, Momentum Builder (5 lessons) |
| Silver | Foundation Builder (10 lessons), Quarter Way (25%), Pythonista (P1), Algorithmic (P2) |
| Gold | Halfway Hero (50%), Home Stretch (75%), Full Stack (P4), Shipped It (P5), Architect (P6) |
| Legend | Graduate (all 67 lessons), Job Ready (P7) |

---

## Keyboard Shortcuts

### Global

| Key | Action |
|-----|--------|
| `/` | Open search |
| `?` | Open Help page |
| `Esc` | Close any overlay or modal |

### Page Navigation

| Key | Page |
|-----|------|
| `1` | Home |
| `2` | Daily |
| `3` | Roadmap |
| `4` | Curriculum |
| `5` | Checklist |
| `6` | Practice |
| `7` | Tracker |
| `8` | Help |

### Daily Page

| Key | Action |
|-----|--------|
| `J` | Next lesson |
| `K` | Previous lesson |
| `M` | Mark / unmark current lesson as learned |
| `Ctrl/Cmd+Z` | Undo last schedule change |

### Playground

| Key | Action |
|-----|--------|
| `Ctrl/Cmd+Enter` | Run code |
| `Tab` | Indent |
| `Shift+Tab` | De-indent |

---

## Technologies Used

- HTML5
- CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (ES2020+)
- Pyodide (in-browser Python via WebAssembly)
- Local browser storage (`localStorage`)
- GitHub Pages

No frameworks. No npm. No build step.

---

## Getting Started

**Option 1 — Use the live site**

https://dushanlee.github.io/codepathway/

Progress saves to your browser automatically.

**Option 2 — Run locally**

```bash
git clone https://github.com/dushanlee/codepathway.git
cd codepathway
open index.html
```

No install required.

---

## Data & Privacy

All progress is stored in your browser's `localStorage`. Nothing is sent to any server.

To back up your progress: Daily → Schedule → Settings → **Export progress**

This downloads a `.json` file. It is the only way to restore your data if you clear browser storage. To restore: Daily → Schedule → Settings → **Import progress**.

---

## Development Process

This project was developed with the assistance of AI tools including ChatGPT and Claude for brainstorming, UI/UX refinement, code structure, and debugging. Project direction, curriculum design, roadmap structure, feature selection, and final implementation were personally guided and reviewed throughout.

---

## Author

Created by Dushan Lee

- GitHub: https://github.com/dushanlee
- LinkedIn: https://linkedin.com/in/dushanlee
