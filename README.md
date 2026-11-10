# Female Touring Artists: Earnings and Performance Analysis

## Overview

An exploratory analysis of historical concert-tour data for female artists. The project uses Python to clean a tour dataset and examine differences in tour gross revenue and the number of performances across artists.

## Questions explored

- How does average gross revenue per tour vary across the artists represented in the dataset?
- How many shows have artists performed across their listed tours?
- What patterns are visible when comparing gross revenue and performance counts?

## Data

The notebook works with a 20-row tour dataset containing fields such as artist, tour title, year, number of shows, actual gross, adjusted gross (2022 dollars), and average gross. The dataset includes multiple tours for some artists.

## Methods

1. Inspect the dataset and review column types and missing values.
2. Remove duplicate records and clean text fields.
3. Prepare the data for analysis.
4. Create horizontal bar charts to explore average gross revenue by tour and average number of shows by artist.

## Tools

- Python
- pandas
- Matplotlib
- Jupyter Notebook

## Interpretation

The notebook's visualizations are exploratory comparisons within the tours included in the dataset. The dataset is not a complete record of every tour or every artist, so the results should not be interpreted as rankings of all female artists or as evidence of broader industry-wide differences.

## Limitations and next steps

- The dataset contains a limited selection of tours and artists.
- Gross revenue and show counts are different measures and should be interpreted separately.
- The current notebook's text-cleaning step removes punctuation and non-ASCII characters, which can alter artist names. A future revision should preserve original labels and convert currency fields explicitly to numeric values before plotting.
- Adding a clear source citation and documenting the dataset's selection criteria would improve reproducibility.

