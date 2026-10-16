[![DOI](https://zenodo.org/badge/1420616755.svg)](https://doi.org/10.5281/zenodo.23415012)

# Self-enhancement and devaluation of others during belief formation are linked to narcissistic traits
This repository contains the code for reproducing the results of the manuscript:
"Self-enhancement and devaluation of others during belief formation are linked to narcissistic traits" by Matthiesen et al.

This version of the repository corresponds to the analyses reported in the
currently submitted version of the manuscript.

-----------------------------------------------
SOFTWARE AND PACKAGES
-----------------------------------------------

The analyses of this manuscript were conducted in R version 4.5.2 (R Core Team 2025), and the
following packages were utilized:

Package	Version	Citation
base	4.5.2	R Core Team (2025)
gt	1.3.0	Iannone et al. (2026)
Hmisc	5.2.5	Harrell Jr (2026)
lavaan	0.6.21	Rosseel (2012); Rosseel et al. (2025)
lme4	1.1.38	Bates et al. (2015)
lmerTest	3.2.0	Kuznetsova et al. (2017)
psych	2.6.3	William Revelle (2026)
rmarkdown	2.30	Xie et al. (2018); Xie et al. (2020); Allaire et al. (2025)
svglite	2.2.2	Wickham et al. (2025)
tidyverse	2.0.0	Wickham et al. (2019)

-----------------------------------------------
REPRODUCING THE ANALYSES
-----------------------------------------------

To reproduce the main analyses from the paper:

1) Download the full repository, including all files and subfolders.
2) Open the Quarto file "analyses_Narcissism_LOOP.qmd".
3) Run the relevant code chunks or render the full document.

This will generate an HTML file containing all results and plots.
A pre-rendered version is provided in the subfolder "03_rendered_report".

-----------------------------------------------
REPOSITORY STRUCTURE
-----------------------------------------------

01_data
    Contains datasets required to run the analyses.

02_plots
    Contains pre-rendered plots.

03_tables
	Contains pre-rendered tables.

03_rendered_report
    Contains the rendered HTML output of the analyses.

Main directory:
    - analyses_Narcissism_LOOP.qmd (main analysis script)
    - codebook.xlsx (overview of dataset variables)
    - grateful-refs.bib (BibTeX references for R packages)
    - grateful-report.html (summary of R package dependencies)

