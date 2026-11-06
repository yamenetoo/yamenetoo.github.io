# yamenetoo.github.io

Personal website of **Mohamad Yamen Al-Mohamad** (محمد يامن المحمد), Department of Statistics, University of Tabriz.

**Live site:** https://yamenetoo.github.io

## What is on the site

- A short profile with links to [GitHub](https://github.com/yamenetoo), [Google Scholar](https://scholar.google.com/citations?user=un_6SQwAAAAJ&hl=en) and [ORCID](https://orcid.org/0009-0009-1665-7203)
- Research areas: statistics, deep learning and remote sensing
- A searchable index of public repositories, filterable by topic and language

## Structure

The site is a single static page with no build step:

| File | Purpose |
|---|---|
| `index.html` | The whole site: markup, styles and script (light and dark themes) |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Updating the repository list

The repository cards are generated from the `REPOS` array inside the `<script>` block of `index.html`. Each entry has:

| Key | Meaning |
|---|---|
| `n` | Repository name on GitHub |
| `t` | Topic tags, e.g. `['Statistics','Deep learning']` |
| `l` | Main language |
| `s` | Star count |
| `d` | Short description |
| `f` | `1` to pin the repository at the top |

Edit an entry, commit and push to `main`; GitHub Pages republishes the site within a minute or two.

## Contact

yamenmohamad@tabrizu.ac.ir
