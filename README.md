# Brisbane AirBnB Property Analysis

This project analyzes public AirBnB property listings in Brisbane, sourced from [Inside Airbnb](https://data.insideairbnb.com/australia/qld/brisbane/2024-04-12/data/listings.csv.gz).

## Table of Contents

- [Aim](#aim)
- [Data Source](#data-source)
- [Data Dictionary](#data-dictionary)
- [Data Extraction Steps](#data-extraction-steps)
- [Analysis](#analysis)
- [Summary of Insights](#summary-of-insights)

## Aim

To extract insights from Brisbane AirBnB listings.

## Data Source

Data can be found [here](https://data.insideairbnb.com/australia/qld/brisbane/2024-04-12/data/listings.csv.gz).

## Data Dictionary

Access the data dictionary [here](https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit).

## Data Extraction Steps

1. Inspected the file in Notepad and Excel.
2. Identified necessary columns and their data types.
3. Imported the data into R using `read_csv()`, converting the 'price' column appropriately.

## Analysis

- **Count Listings**: Analyze listings containing "Airport" and "CBD".
- **Top Neighborhoods**: Identify neighborhoods with the highest review numbers.
- **Superhost Comparison**: Compare review scores between Superhosts and non-Superhosts.
- **Wynnum Properties**: Calculate average prices and ratings for properties in sample neighbourhood.
- **West End Listings**: Filter listings based on specific criteria (max price, property type).
- **Bar Chart**: Visualize the number of listings by property type.
- **Review Scores**: Analyze review scores across different categories using box plots.

## Summary of Insights

The analysis shows that entire rental units dominate the market, and provides insights into pricing, review scores, and property types. Further research could explore correlations between booking popularity and listing numbers.


## Running the R Markdown project

### Prerequisites

- R and RStudio
- Necessary R package: `tidyverse`

### How to Run

1. Clone the repository.
2. Copy 'Listings.csv' file to same location.
3. Open `BrisbaneAirbnbPropertyAnalysis.Rmd` in RStudio.
4. Render the document to see the analysis.
