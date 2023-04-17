# Seattle's Airbnb Analysis

## Overview

The purpose of this project is to conduct an exploratory analysis of Seattle's Airbnb Data, focusing on finding the answers for the below questions:

- Which neighborhoods in Seattle are more expensive?
- What does the price trend look like throughout the year, and when is the busiest time to visit the city?
- Which types of properties are most likely to welcome pets?

The Seattle's Airbnb data is available on [Kaggle](https://www.kaggle.com/datasets/airbnb/seattle>) or [Airbnb](http://insideairbnb.com/get-the-data/)

## Files
 
```bash
├── raw_files
│   ├── listings.csv: including descriptions, amenities and average review score of 3.818 Airbnb listings.
│   ├── calendar.csv: including listing id, price and availability for that day. The period is from Jan/16 to Jan/17.
│   └── reviews.csv: including unique id for each reviewer and detailed comments
├── nb_analysis.ipynb
├── README.md

```
## Instructions

You can run the code (nb_analysis.ipynb) using Anaconda distribution. These are the libraries required:
- pandas
- numpy
- matplotlib
- seaborn

The code should run with no issues using Python versions 3.*.

## Results

The main findings of this analysis can be found at this Medium post.
 
## Acknowledgments

I would like to thank Airbnb for releasing these datasets to the public domain.
