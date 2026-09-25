# DSCI 521 Milestone 3

## Project Overview

This repository contains my DSCI 521 Milestone  2 and 3 Quarto website. It includes my personal journey and two data analysis posts using the Palmer Penguins dataset:

- An R analysis using `tidyverse` and `palmerpenguins`
- A Python analysis using `pandas`, `matplotlib`, and `palmerpenguins`

## Data

Both posts use the Palmer Penguins dataset.

Data source:

https://allisonhorst.github.io/palmerpenguins/

## Requirements

The following software is required to build the website:

- Quarto
- R
- Python
- `uv`

## Setup

### Clone the repository

```bash
git clone https://github.com/Lindalab/lindalab.github.io.git
cd lindalab.github.io
```

## Set up the R environment

Restore the R packages using renv:

```bash
R -e "renv::restore()"
``` 

## Set up the Python environment

Synchronize the Python environment using uv:

```bash 
uv sync
```

## Render the Website

From the project root, run:

```bash
quarto render
```

This renders the Quarto website and generates the website files in the docs/ directory.

## Preview the Website

To preview the website locally, run:

```bash
quarto preview
```

## Posts

## R: Palmer Penguins

The R post explores the Palmer Penguins dataset using dplyr and tidyverse. The analysis identifies the penguin with the highest bill length, compares the number of penguins across islands, and creates a nested dataset grouped by species and island.

## Python: Palmer Penguins

The Python post explores the Palmer Penguins dataset using pandas and matplotlib. The analysis identifies the penguin with the highest bill length, compares penguin counts across islands and species, examines body mass by species, and explores the relationship between bill length and body mass.

## Reproducible Environments

The R environment is recorded using:

renv.lock
.Rprofile
renv/activate.R

The Python environment is recorded using:

pyproject.toml
uv.lock
.python-version

These files are included in the repository to support reproducibility.

Author

Linda Arthur
