# Page Visits Funnel Analysis for Uniqoo Pte Ltd

![funnel-analysis-2 width-1500](https://github.com/user-attachments/assets/af48ee5b-55d9-4943-a76e-88efc9ed7e61)

This project aims to analyze user behavior on Uniqoo's website using funnel analysis techniques. The funnel follows users from their initial visit to making a purchase. This analysis helps identify drop-off points and suggests improvements to increase conversion rates.

## Overview
The funnel consists of four stages:
1. **Visit**: A user visits the website.
2. **Add to Cart**: A user adds a product to their cart.
3. **Checkout**: A user clicks on "checkout".
4. **Purchase**: A user completes the purchase.

The primary goal is to analyze the data to understand user behavior and optimize each stage of the funnel to improve conversion rates.

## Project Features
- **Data Acquisition and Cleaning**: Load data from CSV files and remove duplicates.
- **Data Merging**: Combine data from different stages (visits, cart, checkout, purchase) to create a unified dataset.
- **Funnel Analysis**: Calculate drop-off rates at each stage to identify where users are exiting the funnel.
- **Time Analysis**: Calculate the average time users take to move between stages.
- **Data Visualization**: Generate bar plots and line graphs to better understand the data and visualize key metrics.
- **Investigative Analysis**: Identify potential reasons for drop-off and provide insights for improvement.
- **Basic Predictive Analysis**: Identify users who may be likely to drop off based on time spent in each stage.

## Requirements
- Python 3.6+
- Pandas
- Matplotlib

You can install the required Python libraries using the following command:
```sh
pip install pandas matplotlib
```

## Running the Project
1. **Clone the Repository**:
   ```sh
   git clone <repository_url>
   cd uniqoo_funnel_analysis
   ```

2. **Prepare the Data**: Place the CSV files (`visits.csv`, `cart.csv`, `checkout.csv`, `purchase.csv`) in the project directory.

3. **Run the Script**: Execute the Python script to analyze the funnel:
   ```sh
   python uniqoo_funnel_analysis.py
   ```

## Key Insights
- **Drop-off at Add to Cart**: 82.6% of users did not add an item to their cart, suggesting a need for improvements in incentivizing users to add products.
- **Drop-off at Checkout**: 35.06% of users who added an item to the cart did not proceed to checkout. Enhancing checkout incentives and reducing friction could improve this.
- **Time to Purchase**: Average time to complete a purchase is approximately 43 minutes, which can be optimized through better engagement techniques.

## Visualizations
The project provides the following visualizations:
1. **Funnel Bar Plot**: Displays the number of users at each stage of the funnel.
2. **Conversion Rate by Hour of Visit**: Line plot showing the conversion rate based on the hour of the day, helping to identify peak and underperforming times.

## Recommendations
- **Enhance "Add to Cart" Button**: Improve its visibility and make it more attractive.
- **Reduce Friction in Checkout**: Simplify the checkout process, consider a one-page checkout, or add trust elements.
- **Time Optimization**: Implement targeted campaigns for users taking longer than average to make a purchase.

## Future Work
- **Machine Learning Model**: Implement a predictive model to identify users at risk of dropping off and target them with specific interventions.
- **A/B Testing**: Conduct A/B tests on various stages (e.g., different versions of "Add to Cart") to identify the best-performing changes.
