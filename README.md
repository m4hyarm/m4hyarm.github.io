# m4hyarm.github.io

Personal academic website of Mahyar Maleki, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.

## Where things live

| To change | Edit |
| --- | --- |
| Bio on the home page | `_pages/about.md` |
| Publications | `_bibliography/papers.bib` (add `selected = {true}` to show a paper on the home page) |
| Web CV | `_data/cv.yml` |
| CV PDF | upload `assets/pdf/Mahyar_Maleki_CV.pdf` |
| Teaching | `_pages/teaching.md` |
| Project cards | `_projects/*.md` |
| Social links | `_data/socials.yml` |
| Profile photo | `assets/img/prof_pic.jpg` |
| Name, site settings | `_config.yml` |

Every push to `main` rebuilds the site through GitHub Actions (`.github/workflows/deploy.yml`) and publishes it to the `gh-pages` branch.
