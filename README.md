# Do Women Politicians Face More Interruptions? An Analysis of Interjections in the Australian Parliamentary Debates (1998-2025)

This project analyzes interruptions in Australian Parliamentary debates from 1998-2025, focusing on gender and party dynamics.

## Overview

Interruptions are a routine component of parliamentary debate, 
but also reveal underlying power dynamics and behavioural norms within political institutions. 
Using a dataset of digitized Australian Hansard transcripts from 1998 to 2025, 
this paper examines the frequency of interruptions in the House of Representatives debates, 
focusing on the effects of gender and political party affiliation. 
In particular we consider 1,651 sitting days, with 391 unique speakers, 
across nine parliaments, who made a combined 535,961 statements. 
There were 95,522 interruptions. 
We build a Negative Binomial regression model, offset for speeches, 
and find that women Members of Parliament (MPs) and MPs from centre and centre-left leaning parties are less likely to be interrupted, 
and that the overall frequency of interruptions declined as the number of women in parliament increased. 
These findings provide new empirical evidence on the relationship between institutional norms and representation, 
demonstrating how quantitative analysis of parliamentary speech can detect subtle, gendered patterns of discursive inequality over time.

## Key findings

- Women MPs and MPs from centre and centre-left parties may be less likely to be interrupted
- Overall interruption frequency declined as the number of women in parliament increased
- Interruption patterns vary across different parliamentary periods

## Project Structure

- `data/` - Dataset containing women MPs statistics
- `paper/` - Quarto manuscript, bibliography, and analysis outputs
  - `paper.qmd` - Main manuscript file
  - `paper.pdf` - Compiled paper
  - `images/` - Visualizations
  - `tables/` - Statistical tables
  - `model/` - Regression model outputs
