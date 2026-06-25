# rupeshpatil_-2511897_part3_regression_insights
# rohinipatil_2511898_part3_regression_insights
# Part 3: Regression-Based Business Insights & Model Interpretation

## Business Problem Summary

The retail leadership team wants to identify the factors that influence monthly sales performance across stores. Regression analysis is used to determine which business variables are most strongly associated with sales and to support data-driven decision making.

## Dataset Description

Dataset: business_regression_data.xlsx

Records: 320

Dependent Variable:

* monthly_sales

Independent Variables:

* marketing_spend
* footfall
* avg_discount_pct
* staff_count
* inventory_availability_pct
* competitor_distance_km
* holiday_flag
* customer_rating
* region
* store_type

## Numerical Variables

* marketing_spend
* footfall
* avg_discount_pct
* staff_count
* inventory_availability_pct
* competitor_distance_km
* customer_rating
* monthly_profit
* monthly_sales

## Categorical Variables

* region
* store_type

## Variables Requiring Transformation

Categorical variables were converted into dummy variables before regression modeling.

## Dummy Variable Approach

Region was converted into dummy variables.

Reference Category:

* East

Dummy Variables:

* North
* South
* West

East was excluded to avoid the Dummy Variable Trap.

## Regression Approach

The analysis includes:

1. Simple Regression Model 1

   * monthly_sales ~ marketing_spend

2. Simple Regression Model 2

   * monthly_sales ~ footfall

3. Multiple Regression Model

   * monthly_sales ~ marketing_spend + footfall + inventory_availability_pct + region dummies

## Model Comparison Summary

The multiple regression model provided the highest explanatory power and stronger business insight compared to individual simple regression models.

## Final Model Selected

Multiple Regression Model

Reason:

* Highest R-squared
* Includes multiple business drivers
* Better decision-support capability

## Business Recommendation

Leadership should prioritize:

* Increasing footfall
* Optimizing marketing spend
* Maintaining inventory availability

Regional effects should be considered, especially for South and West regions.

## Assumptions and Limitations

* Regression identifies association, not causation.
* External factors such as economic conditions are not included.
* Results depend on data quality and model assumptions.

## Screenshots Included

* simple_regression_output.png
* multiple_regression_output.png
* residuals_preview.png
* model_comparison_preview.png
