# Fast Food Restaurant Distribution Analysis Across the United States

## Team Members

Aakash Reddy
Parvez
Tarun
Shubham

## Introduction

Fast food restaurants are an important part of the food industry in the United States. Their distribution varies across different cities and states due to differences in population, economic activity, and consumer demand. This project analyzes fast food restaurant locations across the United States and investigates how restaurant availability differs across cities and states using both raw counts and per-capita metrics.

## Problem Statement

The distribution of fast food restaurants is not uniform across the United States. Understanding which cities and states have the highest and lowest concentration of fast food restaurants can provide insights into market presence and accessibility. This project aims to analyze restaurant distribution patterns and identify trends using location and population data.

## Dataset Description

Dataset 1: Fast Food Restaurants Dataset

* Restaurant name
* City
* State
* Latitude
* Longitude

Dataset 2: US Cities Population Dataset

* City
* State
* Population

Dataset 3: US State Population Dataset

* State
* Population

## Data Preparation

The datasets were cleaned and standardized before analysis. State abbreviations were converted into full state names, city names were standardized, and population data was merged with restaurant data. Records with missing population information were removed to ensure accurate per-capita calculations.

## Question 1: Cities with the Most and Least Fast Food Restaurants

### Objective

Identify the cities with the highest and lowest number of fast food restaurant locations.

### Methodology

Restaurant records were grouped by city and the total number of restaurants was calculated for each city.

### Results

Top Cities by Restaurant Count

| City          | Restaurant Count |
| ------------- | ---------------- |
| Cincinnati    | 119              |
| Las Vegas     | 72               |
| Houston       | 63               |
| Miami         | 58               |
| Denver        | 52               |
| Chicago       | 51               |
| Phoenix       | 42               |
| Atlanta       | 41               |
| Oklahoma City | 41               |
| Columbus      | 40               |

### Key Insights

* Cincinnati has the highest number of fast food restaurant locations in the dataset.
* Major metropolitan areas dominate the rankings.
* Fast food restaurants are concentrated in densely populated urban centers.
* Smaller cities generally contain fewer restaurant locations.

### Visualization

![Top 10 Cities by Number of Fast Food Restaurants](../charts/question1_top_cities.png)

Question 2: Cities with the Most and Least McDonald's per Capita

Objective

The objective of this analysis is to identify which cities have the highest and lowest concentration of McDonald's restaurants relative to their population size.

Methodology

The dataset was filtered to include only McDonald's locations. The number of McDonald's restaurants in each city was counted and divided by the city's population. The result was converted into the number of McDonald's locations per 100,000 residents to allow fair comparisons between cities of different sizes.

Key Findings

Hamilton, Ohio recorded the highest McDonald's concentration with approximately 7.88 locations per 100,000 residents. Williamsburg, Yakima, Pompano Beach, and Rapid City also ranked among the highest.

Large metropolitan areas such as Boston, San Francisco, New York, and Los Angeles showed the lowest McDonald's concentration per capita. Although these cities contain McDonald's locations, their very large populations reduce the number of restaurants per resident.

The results suggest that smaller and medium-sized cities may have a higher concentration of McDonald's locations relative to their population, while major metropolitan areas tend to have lower per-capita values.
