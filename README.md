# Steam Games EDA (STAT 545 mini data analysis)

A small exploratory data analysis of the **Steam games dataset** in R. I did it as a two-part course project for STAT 545 (Data Analysis with R) at UBC. I looked at game prices, discounts, genres, release dates, review counts and missing data.

## A note on what's mine

This is coursework. The two `.Rmd` notebooks started as templates from the course, with the instructions, task prompts and structure already written. **My work is the code, plots, model and written answers** in the sections marked "start your work below". The instructions and course text around them are not mine.

The templates carry this credit from the course: *"Thanks to Icíar Fernández Boyano for mostly putting this together, and Vincenzo Coia for launching."*

## The data

The `steam_games` dataset (40,833 games, 21 columns) comes from the [`datateachr`](https://github.com/UBC-MDS/datateachr) R package, which got it from Kaggle. The dataset isn't stored in this repo.

## What's in here

| Folder | What it is |
|---|---|
| [`Milestone 1/`](Milestone%201/) | Picking a dataset, exploring it, and choosing four research questions |
| [`Milestone 2/`](Milestone%202/) | Answering those questions: summaries and plots, tidying, a simple model, and saving results |
| [`output/`](output/) | Files saved by Milestone 2 (a model and a summary table) |

## The four research questions

1. How do discount percentages vary across genres?
2. Is there a relationship between a game's original price and how many reviews it gets?
3. How does release date relate to discounts and review counts?
4. What affects whether a game has missing data in key variables?

## How to run it

You need R and RStudio.

1. Clone the repo (change the URL if the repo name is different):
   ```
   git clone https://github.com/thedrna/steam-games-eda.git
   ```
2. Install the packages:
   ```r
   install.packages(c("devtools", "tidyverse", "broom", "here"))
   devtools::install_github("UBC-MDS/datateachr")
   ```
3. Open the `.Rmd` file you want in RStudio and knit it. Each milestone also has a `.md` version you can just read on GitHub.