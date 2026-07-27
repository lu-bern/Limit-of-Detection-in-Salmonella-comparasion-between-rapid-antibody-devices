## Project Description
This repository contains an R Markdown workflow for analyzing limit of detection (LOD) data to compare the performance of two antibody-based rapid tests for the detection of Salmonella. The analysis evaluates the sensitivity of each device using samples with and without food matrices across two Salmonella strains.

LOD data from both devices were analyzed using a side by side experimental design. Each strain was tested in samples containing no food and then in food matrices (chicken rinsate and ground beef). Food and no-food experiments were conducted on separate days using independent inoculum and sample preparations for each strain to ensure experimental consistency. 

<img width="548" height="1158" alt="thesis flowchart-Copy of LOD workflow drawio (1)" src="https://github.com/user-attachments/assets/1c0dc99a-6512-49e0-a847-031baef0aa42" />



## Files

- `lod_no_food_github_human.Rmd` - Main R Markdown analysis file
- `lod_no_food_github.Rmd` - Additional analysis file

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
