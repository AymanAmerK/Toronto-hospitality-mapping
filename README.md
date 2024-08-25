# Toronto Postal Code Analysis Project

This project analyzes postal codes in Canada, focusing on the Toronto area, particularly the Etobicoke neighborhood. It uses various data science techniques to explore and visualize geographical and venue data.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dependencies](#dependencies)
3. [Data Sources](#data-sources)
4. [Project Structure](#project-structure)
5. [Key Features](#key-features)
6. [Results](#results)

## Project Overview

This project is divided into three main parts:
1. Data collection and preprocessing of Canadian postal codes
2. Geospatial analysis of the Toronto area
3. Venue analysis and clustering of the Etobicoke neighborhood

## Dependencies

This project requires the following Python libraries:
- numpy
- pandas
- requests
- BeautifulSoup
- geocoder
- folium
- sklearn
- matplotlib
- geopy

You can install these dependencies using pip:

```
pip install numpy pandas requests beautifulsoup4 geocoder folium scikit-learn matplotlib geopy
```

## Data Sources

- Wikipedia: List of postal codes of Canada
- Foursquare API: Venue data

## Project Structure

The project is structured as follows:

1. Data Collection and Preprocessing
   - Scraping postal code data from Wikipedia
   - Cleaning and formatting the data

2. Geospatial Analysis
   - Merging postal code data with geospatial coordinates
   - Visualizing data on interactive maps

3. Venue Analysis and Clustering
   - Fetching venue data using Foursquare API
   - Analyzing common venues in neighborhoods
   - Clustering neighborhoods based on venue types

## Key Features

- Web scraping using BeautifulSoup
- Data cleaning and preprocessing with pandas
- Geospatial visualization with folium
- API integration (Foursquare)
- K-means clustering
- Data analysis and visualization


## Results

The project provides insights into:
- Distribution of postal codes in Canada
- Geographical layout of Toronto neighborhoods
- Popular venue types in Etobicoke
- Clusters of similar neighborhoods based on venue data

The results are visualized using interactive maps and charts throughout the notebook.

---

For more detailed information, please refer to the Jupyter notebook in this repository.
