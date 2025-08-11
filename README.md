# Posters
# Project Poster Repo

## Team
- Alice — Project Lead / Designer
- Bob — Frontend / Poster Designer
- Carol — Backend / Reviewer
(Replace with actual team names & roles)

## Poster tools used
- Alice — Canva
- Bob — Figma
- Carol — Photoshop

## Folder structure
- `posters/` — poster images (one file per branch/person). Naming convention:
  `poster-<name>-<tool>.<ext>`

## Branching & PR rules
- Each member creates a branch: `poster/<your-name>`
- Add poster to `posters/` and push branch
- Open Pull Request to `main` with title `Add poster — <Your Name>`
- Create at least one GitHub Issue related to the poster (design/feedback)

## CI / Workflow
We have a GitHub Actions workflow that runs on push to `posters/` and prints:
`Poster Uploaded Successfully`.
Workflow file: `.github/workflows/poster-upload.yml`

## Quick checklist for contributors
- [ ] Create branch `poster/<your-name>`
- [ ] Add exported poster to `posters/`
- [ ] Commit & push branch
- [ ] Open PR to `main`
- [ ] Create at least 1 Issue (e.g., color change, font change)
- [ ] Request at least one reviewer
