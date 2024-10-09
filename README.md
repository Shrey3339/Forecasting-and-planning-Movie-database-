# Demand Forecasting and Planning

Comprehensive analysis of demand forecasting and box office performance drivers for movies using Excel-based regression models. The project explores key influencers like screens, critics, and seasonal factors to predict first-week box office revenues.

## Overview

This repository presents a comprehensive analysis and model development for **Demand Forecasting** and **Planning** using a dataset from the movie industry. The project focuses on identifying key drivers influencing the box office performance of movies based on the number of screens and critic reviews. The objective is to accurately predict first-week box office revenues for different types of movies using advanced statistical and analytical techniques.

## Project Structure

The repository contains the following key files:

- **Data**: The dataset used for the analysis.
- **Reports**: Detailed documentation of the forecasting methodology and results.
- **Visualizations**: Graphs and charts demonstrating the performance of the predictive models.

## Key Features

### 1. **Movies with Less Than 2,500 Screens:**
   - **Main Influencers**: Number of critics plays a significant role in determining box office performance. Each additional critic is associated with an average increase of **$22,921.57** in first-week revenue.
   - **Other Factors**: Ratings and seasonal influences are less significant.
   - **Model Performance**: The R-square value is **0.627**, with an adjusted R-square of **0.586**.

### 2. **Movies with More Than 2,500 Screens:**
   - **Key Drivers**:
     - Additional screens add an average of **$22,544.40** to box office earnings.
     - Each additional critic contributes an impressive **$160,749.95**.
     - Summer releases add approximately **$11,951,274.12**, while family-oriented movies gain **$26,925,724.55**.
     - PG-13 and R-rated movies show significant revenue gains, with **$24,752,413.94** and **$23,608,710.98**, respectively.
   - **Model Performance**: The R-square value is **0.587**, with an adjusted R-square of **0.491**.

### 3. **Predictive Modeling for Avatar**:
   - Using the piecewise model for movies with at least 2,500 screens, the model predicted a first-week box office of **$100,625,754.06** for **Avatar**, showcasing the accuracy of the forecasting model.

## Model Evaluation

The models were evaluated using **R-Square**, **Adjusted R-Square**, and residual plots, which helped assess the accuracy and goodness-of-fit. Predictive performance was cross-validated using test data, and the model's ability to generalize was ensured by robust statistical validation techniques.

## Visualization

The project includes various visualizations such as:
- **Predicted vs Actual Box Office Performance** for both categories of movies (under 2,500 screens and over 2,500 screens).
- **Residual Plots** to understand model bias and variance.

## Technical Stack

- **Data Analysis Tools**: Excel for data analysis and visualization.
- **Techniques**: Linear regression and statistical analysis to identify key drivers.

## Usage

You can review the demand forecasting model and results in the `Reports` and `Visualizations` folders, which provide detailed insights into the model's performance and key findings.

## Results

The results of the forecasting models demonstrate significant predictive power, especially for movies with a large number of screens and critics. Detailed performance metrics and insights can be found in the `Reports` folder.

## Conclusion

This project provides a practical application of demand forecasting using real-world data. The results showcase the effectiveness of the models in predicting box office performance based on key influencers like screens, critics, and ratings. It also serves as a foundation for more advanced forecasting techniques that can be applied to other industries.

## Future Work

Potential enhancements include:
- Incorporating external factors like social media buzz or marketing spend.
- Expanding the model to include non-movie-related datasets for cross-industry forecasting.
- Implementing time-series forecasting methods to improve long-term predictions.
