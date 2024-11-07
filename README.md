# Instagram Reach Analysis

## Overview

This project explores Instagram post reach through data analysis and visualization. It aims to uncover insights about the performance of Instagram posts by analyzing various metrics such as impressions, likes, comments, and hashtags. Additionally, the project includes building a predictive model to forecast Instagram post reach.

## Features

- **Data Exploration**: Analyze the distribution of impressions from different sources.
- **Content Analysis**: Generate word clouds to visualize the most frequent captions and hashtags.
- **Relationship Analysis**: Explore relationships between key metrics (e.g., likes, comments, impressions).
- **Conversion Rate Analysis**: Calculate the conversion rate from profile visits to followers.
- **Prediction Model**: Use a machine learning model to predict Instagram post reach.

## Dataset

The dataset contains the following columns:

- `Impressions`: Total impressions on a post.
- `From Home`, `From Hashtags`, `From Explore`, `From Other`: Breakdown of impressions by source.
- `Saves`, `Comments`, `Shares`, `Likes`: Engagement metrics.
- `Profile Visits`, `Follows`: Conversion metrics.
- `Caption`, `Hashtags`: Post content.

## Install dependencies:
  ```pip install -r requirements.txt```

## Analysis Highlights:
  1. Impressions Distribution
  Visualized the distribution of impressions from various sources using Seaborn and Plotly.
  2. Content Insights
  Word clouds show the most frequent captions and hashtags.
  3. Metric Relationships
  Scatter plots and trendlines reveal relationships between impressions, likes, comments, and more.
  4. Conversion Rate
  Calculated the percentage of profile visits that converted to followers.
  5. Prediction Model
     Built a machine learning model using PassiveAggressiveRegressor to predict post reach.
## Visualizations:
  Distribution plots of impressions by source.
  Scatter plots showcasing relationships between engagement metrics.
  Word clouds for captions and hashtags.
## Future Work:
  Enhance the predictive model by testing other algorithms.
  Include more diverse datasets to generalize insights.
  Automate analysis for real-time Instagram data.
