# ETC5513 Assignment 3 - International Education Cost Analysis

Topic: Is Master of Computer Science at Monash University affordable for U.S. student in 2025?

This repository contains the source files and reproducible code. Our project analyzes the affordability of international Master's programs in Computer Science, with a focus on Monash University.

## Group Members:

-   Nutchanok Saitin (nsai0012) - 35493011
-   Tzu-Hsuan Yang (tyan0082) - 35461586
-   Ruowei Li (rill0141) - 35693436

## Repository Structure

```         
├── data/ # Raw dataset (CSV)
├── bib/ # Bibliography or reference files
├── images/ # Images used in slides
├── renv/ # R package environment (auto-managed by renv)
├── assignment-3-gg.qmd # Main written report (.qmd format)
├── assignment-3-gg.pdf # Rendered PDF version of the report
├── assignment-3-gg-slides.qmd # Presentation slides (.qmd)
├── assignment-3-gg-slides.html # Rendered HTML presentation
├── assignment-3-reproducible-reporting-gg.Rproj # R project file
├── README.md # Overview of the project (this file)
├── .gitignore # Git ignore list (includes .Rhistory, renv/cache, etc.)
├── .Rprofile # Used by renv to load project environment
└── renv.lock # Lockfile for restoring package versions
```

## Scenario & Research Question

A U.S. student plans to study a Master of Computer Science at Monash University with an annual budget of **USD 42,355.90**.\
We aim to evaluate whether this budget is sufficient by analyzing tuition, rent and living cost expense across global universities.

## Reproducibility

This project uses the following tools for reproducibility: - `renv` to manage R package dependencies - `quarto` to generate PDF/HTML reports and slides - `git` and GitHub for version control and collaboration - `LaTex` for render the pdf file

### To reproduce this report:

1.  Clone the repository:

    ``` bash
    git clone git@github.com:ETC5513-2025/assignment-3-reproducible-reporting-gg.git
    ```

2.  Open the R project file (.Rproj) in RStudio.

3.  Restore the environment:

  ``` r
  renv::restore()
  ```

4.  Knit the main report:

  ``` r
  quarto::render("assignment-3-gg.qmd")
  ```

## Dataset

We used the public dataset from [Kaggle - Cost of International Education](https://www.kaggle.com/datasets/adilshamim8/cost-of-international-education), which includes tuition, living cost index, rent, visa fees, and program duration across multiple global universities.
