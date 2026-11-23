# Advanced Ecological Modeling in R

Coursework from **Quantitative Biology**, Universidad de los Andes (2026), showcasing statistical modeling of ecological and environmental data using R.

## Contents

| Analysis | Methods and questions | Authorship |
| --- | --- | --- |
| [Workshop 6](analysis/workshop-06-gams-mixed-models.Rmd) | Generalized additive models (GAMs) and linear mixed-effects models (LMMs) for vegetation and environmental data from the middle Magdalena River basin | Juanita Guerrero and María José Camacho |
| [Exam 2](analysis/exam-02-ecological-modeling.Rmd) | Modeling parasite counts in reef fish and analyzing plant ecophysiology along environmental gradients | Juanita Guerrero |

## Data

The `data/` directory contains the four datasets provided with the coursework:

- `magdalena_gams.csv` — Workshop 6, GAM analysis
- `magdalena_lmm.csv` — Workshop 6, mixed-model analysis
- `df_epidemiologia_arrecifal.csv` — Exam 2, reef fish epidemiology
- `df_ecofisiologia_gradiente.csv` — Exam 2, plant ecophysiology

## Reproducing the analyses

1. Download or clone this repository, keeping the `analysis/` and `data/` folders together.
2. Open either `.Rmd` file from `analysis/` in RStudio.
3. Install any missing R packages referenced by that document, and use **Knit** to render it. The data paths are relative to the `analysis/` folder (e.g., `../data/magdalena_gams.csv`).
4. The source documents use `pdf_document` with XeLaTeX and may require a LaTeX installation (e.g., TinyTeX) to knit to PDF.

**Note:** The original analysis and interpretations are preserved; only input file paths were adjusted to match the repository layout. The analyses have not been independently executed or validated in this packaging step. These are course assignments, not peer-reviewed research results.

## Attribution

Workshop 6 was completed jointly by **Juanita Guerrero and María José Camacho**. Exam 2 is attributed to **Juanita Guerrero**. The original Spanish-language course reports remain in the `analysis/` folder.
