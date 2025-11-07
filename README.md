# Hansard interruptions

This project analyzes interruptions in Australian Parliamentary debates from 1998-2025, 
focusing on gender and party dynamics.

## Overview

Using digitized Hansard transcripts from the Australian House of Representatives, 
this research examines whether women MPs face different interruption patterns than their male counterparts. 
The analysis covers 1,651 sitting days across nine parliaments, 
with 391 unique speakers and 95,522 recorded interruptions.

## Key findings

-   Women MPs and MPs from centre and centre-left parties may be less likely to be interrupted
-   Overall interruption frequency declined as the number of women in parliament increased
-   Interruption patterns vary across different parliamentary periods

## Project structure

-   `data/` - Dataset containing women MPs statistics, and sample dataset
-   `paper/` - Quarto manuscript, bibliography, and analysis outputs
    -   `paper.qmd` - Main manuscript file
    -   `paper.pdf` - Compiled paper
    -   `images/` - Visualizations
    -   `tables/` - Statistical tables
    -   `model/` - Regression model outputs

## Data

The full dataset that we use is available from <https://zenodo.org/records/17351233>. 
You should download that and save it in `data`, as `corpus_1998_to_2025.parquet`. 
For the purpose of being self-contained, we provide a reduced sample in this repo `sample_corpus_1998_to_2025.parquet`.
