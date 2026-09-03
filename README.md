# Git Workflow Project

A simple personal portfolio landing page, built to practice a real Git branching workflow as part of the DevOps internship (Task 4).

## Tech
Plain HTML, CSS, and JavaScript — no build tools needed. Just open `index.html` in a browser.

## Git Workflow Used
- `main` — stable, production-ready branch
- `dev` — integration branch where features are merged before going to main
- `feature/*` — short-lived branches for individual pieces of work, merged into `dev` via Pull Request

## Steps Followed
1. Initialized the repo and pushed the base project to `main`.
2. Created a `dev` branch off `main`.
3. Created a `feature/update-script` branch off `dev` to add new functionality.
4. Opened a Pull Request to merge the feature branch into `dev`.
5. Tagged a release once `main` was updated (`v1.0`).

See `docs/task-log.md` for a day-by-day log of what was done.
