# LearnR Sports Data Tutorials

Interactive R tutorials for SPMC350 at the University of Nebraska-Lincoln's College of Journalism and Mass Communications. These 37 lessons teach R programming, data analysis, and data visualization using real sports data.

## What You'll Learn

**R Fundamentals (Lessons 1–12)**
Working with data in R, filtering, mutating, aggregating, and joining datasets. Statistical concepts including significance testing, correlation, linear and multiple regression, residuals, and z-scores.

**Data Visualization (Lessons 13–27)**
Creating and customizing charts with ggplot2: bar charts, stacked bars, waffle charts, line and step charts, slope charts, scatterplots, bubble charts, beeswarm plots, bump charts, dumbbell charts, tables, faceting, and arranging multiple plots.

**Advanced Topics (Lessons 28–37)**
Finishing and publishing work: annotations, headlines, color, and finishing touches. Web scraping with `rvest`, text cleaning, clustering, simulations, and data joins.

## Installation

You will need [R](https://cran.r-project.org/) and [RStudio](https://posit.co/download/rstudio-desktop/) installed first.

**Step 1** — Install required packages:

```r
install.packages(c("tidyverse", "rmarkdown", "lubridate", "janitor", "cowplot", "learnr", "wehoop", "remotes", "devtools", "ggrepel", "ggbeeswarm", "ggtext", "rvest", "Hmisc", "cluster"))
```

**Step 2** — Install ggbump:

```r
devtools::install_github("mattwaite/ggbump")
```

**Step 3** — Install the tutorials package:

```r
devtools::install_github("mattwaite/SportsDataTutorials")
```

If prompted about installing newer versions of dependencies, decline.

## Running a Tutorial

In the RStudio console, run:

```r
learnr::run_tutorial("01-basics", package = "SportsDataTutorials")
```

Replace `"01-basics"` with the tutorial you want to open. Tutorials are numbered `01` through `37`.
