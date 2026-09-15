# Text Analysis Workshop
UVA StatLab workshop on text analysis in R: scraping, cleaning, and analyzing a Charlottesville City Council meeting transcript.

## Workshop Overview
This workshop introduces a practical text-analysis workflow in R using a Charlottesville City Council meeting transcript as an example.
We will work through the process from collecting text data from the web to preparing and analyzing the text.

The workshop is divided into two parts:

### Part 1: Data Collection and Preparation
- Check whether a website can be scraped
- Inspect HTML structure
- Scrape a meeting transcript using `rvest`
- Extract speakers, roles, timestamps, and text
- Restructure and clean the scraped data
- Prepare the data for text analysis

### Part 2: Text Analysis
- Explore word frequencies
- Compare language across stakeholder groups
- Apply five text analysis methods: relative word frequency, n-grams, keyness, KWIC, and sentiment analysis
- Visualize and interpret text-analysis results

## Workshop Files

- `01_Text_Analysis_2026.qmd` — Part 1 source file (Quarto)
- `01_Text_Analysis_2026.html` — Part 1 rendered workshop material
- `02_Text_Analysis_2026.Rmd` — Part 2 source file (R Markdown)
- `02_Text_Analysis_2026.html` — Part 2 rendered workshop material
- `Text_Analysis_Workshop.pdf` — Workshop slides, including the overview and AI-assisted workflow
- `ordinance.csv` — Processed meeting transcript used for the text analysis
- `speaker_roster.csv` — Speaker information used to identify and group speakers

If you only want to read the workshop materials, open the `.html` files.

If you want to run the code yourself, use the `.qmd` and `.Rmd` files in RStudio.

## Getting the Materials

To download all workshop files:

1. Click the green **Code** button at the top of this repository.
2. Select **Download ZIP**.
3. Unzip the downloaded folder.
4. Open the workshop folder in RStudio.

## Software

You will need:

- R
- RStudio
- Quarto for Part 1

The workshop uses several R packages, including:

- `rvest`
- `dplyr`
- `purrr`
- `stringr`
- `ggplot2`
- `hms`
- `tidytext`
- `quanteda`
- `quanteda.textstats`
- `syuzhet`

If a required package is not already installed, you can install it with:

`install.packages("package_name")`

You generally need to install a package only once, but you need to load it with `library()` each time you start a new R session.

## About the Example

The workshop uses a publicly available Charlottesville City Council meeting transcript. We begin with one meeting so that we can closely examine the workflow, but the same approach can be extended to larger collections of text.

## Authors

**Hyeseon Seo**  
**Lucy Hong**

UVA StatLab  
Research Data Services  
University of Virginia Library
