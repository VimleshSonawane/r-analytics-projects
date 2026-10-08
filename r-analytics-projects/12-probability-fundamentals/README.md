# Probability fundamentals

Joint, conditional, and union probability worked through in R.

**Type:** Probability · **Completed:** May 2025 · Northeastern University (ALY 6000)

[← All projects](../)

## What this project is about

This project practices the core rules of probability in R, using a dataset of colored, labeled balls along with coin-flip and soccer-game problems.

## Why it matters

Every statistical method rests on the basic rules of probability. Working them out in code makes each step checkable and repeatable, instead of a calculation on paper that can't be verified.

## Dataset

**Ball dataset** (`ball-dataset.csv`): each row is a ball with a color and a letter label.

## What I did

I completed this project on my own, from cleaning the data through to the final report.

1. Built frequency tables of colors and labels, and charted them.
2. Calculated simple, joint, conditional, and union probabilities from the frequency tables.
3. Solved a two-step drawing problem by splitting it into cases.
4. Wrote a custom factorial function and used it for coin-flip and soccer-game probability problems.

## Results

- Worked through each probability rule with code, so every answer can be checked and rerun.

## Takeaways

- Breaking a multi-step probability problem into separate cases makes it much easier to get right.

## Skills demonstrated

Frequency tables, joint, conditional, and union probability, writing custom functions in R

## Files

- [`probability_fundamentals.R`](probability_fundamentals.R): R script

## How to run it

Packages: `readr`, `dplyr`, `ggplot2`, `tidyr`, `tibble`

Place `ball-dataset.csv` in this folder and run the script in R or RStudio. This project was submitted as a script only, so there is no separate report.
