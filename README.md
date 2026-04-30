# LOD No Food Analysis

R Markdown analysis of Limit of Detection (LOD) data comparing food vs. no food conditions for Salmonella detection with 2 strains.

## Project Description

This project analyzes LOD data for food vs. no food conditions with 2 strains for comparison. Food and no food trials were run on separate days with separate inoculum for each strain.

## Files

- `lod_no_food_github_human.Rmd` - Main R Markdown analysis file
- `lod_no_food_github.Rmd` - Additional analysis file
- `two_column_no_food.csv` - Data file (no food condition)
- `two_column.csv` - Data file (with food)
- `lod_trials_food_only.csv` - Food-only trial data
- `decpoint_nofood.csv` - Decision Point device data

## Requirements

- R (version 4.0+)
- RStudio
- Required R packages:
  - rstatix
  - ggpubr
  - broom
  - skimr
  - dplyr
  - scales
  - MASS
  - ggplot2
  - cowplot
  - gtable
  - knitr
  - tidyverse

## Usage

1. Open `lod_no_food_github_human.Rmd` in RStudio
2. Knit the document to generate the analysis
3. Or run individual code chunks as needed

## Author

Guadalupe Lulu Bernal
Date: 2023-10-06