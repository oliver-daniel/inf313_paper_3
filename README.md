This repository contains the full source code for my joint submission with Tiago Martins for Paper 1, the third major paper assignment in the 2022 edition of INF 312 taught by Rohan Alexander.

## File Structure
- `/` (project root)
  - `paper_3.Rmd`: A stand-alone R Markdown script that, when knit using `knitr`, runs all the required code to prepare and format the paper.
  - `paper3_lgbtq_identity.RProj`: An RStudio configuration file that assists with using the integrated R environment while exploring and developing data for this paper. It is recommended to load this file into RStudio when knitting `paper_3.Rmd`, for best reproducibility.
  - `LICENSE`: A copy of the Do What The Fuck You Want To Public License (WTFPL), which fully liberates you to view, modify, and replicate the contents of this repository as desired.
- `in/`
  - `references.bib`: A Bibtex file, containing all of the references to R packages and literature that we used in this project. This is consumed by `paper_3.Rmd` to automatically generate a References section, in APA formatting, along with in-text citations.
- `out/`
  - `paper_3.pdf`: The generated PDF version of the paper, with all text and figures included.
- `scripts/`
  - `scratch.rmd`: An R markdown document filled with miscellaneous exploratory visualizations and cross-sections of the data, as well as preliminary commentary in the form of text and code comments. We chose to include this document in its present, rough state, in case it contains any insights for those interested in future study.