# World Population Density Map

This project demonstrates how to create an interactive map displaying the population density of countries worldwide. Using Python, `geopandas`, and `folium`, we calculate population density based on country polygons and visualize the results on an interactive map with a color-coded scale for easy interpretation.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Methodology](#methodology)
  - [Area Calculation](#area-calculation)
  - [Population Density Calculation](#population-density-calculation)
  - [Color Scale](#color-scale)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

This map project uses the `geopandas` dataset on world countries to calculate and visualize population density. By leveraging country polygon shapes and known population data, we calculate the population density (people per square kilometer) and display it on an interactive map. This visualization can provide insights into the distribution of population density across different countries.

## Dataset

The dataset used in this project is the built-in `naturalearth_lowres` dataset from `geopandas`, which provides world country boundaries and estimated population data. We calculate the area of each country and then use it to determine population density.

## Requirements

To run this project, you need:

- **Python 3.10** or higher
- **Geopandas** for geospatial data handling
- **Folium** for creating the interactive map
- **Branca** for generating a color scale bar

### Installation

You can install the necessary packages using:

```bash
pip install geopandas folium branca
