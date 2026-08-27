# Layal Jbara

Personal academic website, built with [al-folio](https://github.com/alshedivat/al-folio).

**Live URL (once GitHub Pages is on):** <https://layaljbara.github.io>

## What is here

| Page | What it is |
| --- | --- |
| `/` | Bio, news, selected papers, funders |
| `/research/` | Clinical LLMs, pathology, PhD fluids work |
| `/publications/` | Full bibliography |
| `/leadership/` | Students + funders/collaborators |
| `/cv/` | CV |

## First things to edit

1. Drop a square headshot at `assets/img/prof_pic.jpg` (or `.png` and change `_pages/about.md`).
2. Confirm email in `_data/socials.yml`.
3. Add or remove students in `_includes/students.liquid`.
4. If **Knight** is not the Knight Foundation, change the link in `_includes/funders.liquid`.
5. Replace the wordmark SVGs in `assets/img/funders/` with official logos if you have permission to use them.

## Put it on GitHub Pages

1. Create a repo named `layaljbara.github.io` (or your GitHub username + `.github.io`).
2. Push this folder to `main`.
3. Repo **Settings → Actions → General → Workflow permissions → Read and write**.
4. **Settings → Pages → Deploy from a branch → `gh-pages`**.
5. Wait for the **Deploy site** workflow.

If your GitHub username is not `layaljbara`, change `url:` in `_config.yml` to match.
