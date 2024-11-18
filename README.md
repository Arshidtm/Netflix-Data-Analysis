# Netflix Data Analysis

This repository contains a comprehensive data analysis project focused on Netflix titles using Python. The project aims to explore data distribution, perform cleaning, and extract insights from a dataset with details about Netflix shows and movies.

## Project Overview

This project analyzes a Netflix dataset that includes information on titles, directors, cast members, release years, ratings, genres, and more. Through data analysis and visualization, it uncovers patterns, trends, and meaningful insights into Netflix's content library.

## Data Loading & Inspection

- Libraries Used: numpy, pandas, matplotlib, plotly.express

- Loaded the dataset to inspect entries, structure, and initial data exploration.

## Data Cleaning

The data cleaning process involved:

- Handling missing values in columns such as director, cast, country, and date_added.

- Displaying a summary of missing values using pandas and ensuring clean data for analysis.

## Data Exploration

### Content Distribution Analysis

- Distribution of content types: Movies vs. TV Shows.

- Analysis of genres and their popularity over the years.

### Temporal Trends

- Examined the year-wise addition of content.

- Explored patterns in Netflix's content releases over time.

### Country and Cast Analysis

- Analyzed content distribution across different countries.

- Insights into frequently cast actors/actresses in Netflix titles.

### Ratings & Categories

- Breakdown of content based on ratings (e.g., TV-MA, PG-13).

- Grouped content by categories and genres to reveal common themes.

## Dataset

The dataset consists of 7787 entries with 12 features:

- `show_id`: Unique identifier for each show.

- `type`: Type of content (Movie or TV Show).

- `title`: Title of the show or movie.

- `director`: Director(s) of the content.

- `cast`: Main cast members.

- `country`: Country of origin.

- `date_added`: Date the content was added to Netflix.

- `release_year`: Year of release.

- `rating`: Age rating of the content.

- `duration`: Movie duration or number of seasons for TV Shows.

- `listed_in`: Genres/categories.

- `description`: Brief description or synopsis.

## Insights

The analysis revealed key trends, including:

- Proportions of Movies vs. TV Shows in the Netflix catalog.

- Popular genres and their distribution by country.

- Trends in Netflix's content production and acquisition strategies over time.

## Visualizations

The project utilizes:

- Bar Plots, Pie Charts, and Histograms for visual distribution analysis.

- Interactive Plots using Plotly for enhanced data exploration.

## Usage

1. Clone the repository:

   ```bash

   git clone https://github.com/yourusername/netflix-data-analysis.git

   ```

2. Install required dependencies (if not already installed):

   ```bash

   pip install -r requirements.txt

   ```

3. Open the Jupyter Notebook and run the cells to reproduce the analysis:

   ```bash

   jupyter notebook "Netflix Data Analysis .ipynb"

   ```


