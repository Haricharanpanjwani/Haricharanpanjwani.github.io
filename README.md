# Research Homepage Draft

This is a GitHub Pages-ready static site for positioning Hari Panjwani as an active, credible researcher and reviewer with strong production ML experience.

## Why this structure works

- It leads with credibility signals instead of a generic biography.
- It highlights a clear niche: production ML systems, LLM evaluation, retrieval, and research service.
- It is intentionally short enough that busy researchers can scan it in under two minutes.
- It is plain HTML and CSS, which makes GitHub Pages deployment simple and low-maintenance.

## Before publishing

- Add a `resume.pdf` file and change the Resume card in `index.html` to link to it.
- Replace any wording you want softened around "established" or "frontier" if you want a more understated academic tone.
- Add one short section for:
  - education
  - patents, talks, or awards
  - a few older representative publications

## GitHub Pages setup

1. Create a repository named `<username>.github.io` if you want this to live at the root of your GitHub Pages site.
2. Copy the contents of this folder into that repository.
3. Commit and push to the `main` branch.
4. In GitHub repo settings, confirm GitHub Pages is serving from the root of `main`.

## Recommended next iteration

The strongest follow-up would be to convert the hero metrics and publication list into structured data pulled from your Scholar/OpenReview/hand-maintained JSON so the site stays current without manual editing.
