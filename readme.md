# Reproducibility Exercise – RR Assignment 11

This repository contains a simple reproducible R project created with `renv`.

The goal of the project is to demonstrate how package versions and dependencies can be managed and restored in a consistent environment.

## Used libraries

The project uses the following R packages:

* tidyverse
* pastecs

## Project files

* `analysis.R` – example R script with data analysis and visualization
* `renv.lock` – lockfile containing package versions
* `renv/` – project environment infrastructure
* `.gitignore` – ignored local/system files

## Example analysis

The script:

* creates a small sample dataset,
* calculates descriptive statistics using `pastecs`,
* visualizes the data using `ggplot2` from the `tidyverse`.

## How to reproduce the environment

1. Clone the repository:

```bash id="j6l5j3"
git clone YOUR_REPOSITORY_LINK
```

2. Open the project in RStudio.

3. Install `renv` if it is not installed:

```r id="rj6z0n"
install.packages("renv")
```

4. Restore all project dependencies:

```r id="v49r3z"
renv::restore()
```

5. Run the analysis script:

```r id="c3wo3q"
source("analysis.R")
```

## Author

Izabela Kosiec
