# Model Equations

## Simple Regression Model 1

### Equation

Monthly Sales = 560777.35 + 2.13 × Marketing Spend

### Interpretation

* Intercept (560777.35): Estimated sales when marketing spend is zero.
* Marketing Spend Coefficient (2.13): For every additional unit of marketing spend, monthly sales increase by approximately 2.13 units.

### Model Performance

R² = 0.167

This model explains approximately 16.7% of the variation in monthly sales.


## Simple Regression Model 2

### Equation

Monthly Sales = 446410.58 + 35.68 × Footfall

### Interpretation

* Intercept (446410.58): Estimated sales when footfall is zero.
* Footfall Coefficient (35.68): Each additional customer visit is associated with an increase of approximately 35.68 units in monthly sales.

### Model Performance

R² = 0.736

This model explains approximately 73.6% of the variation in monthly sales.


## Multiple Regression Model

### Equation

Monthly Sales =
131460.31

* 1.19(Marketing Spend)
* 33.87(Footfall)
* 2818.21(Inventory Availability %)
* 10547.38(North)
* 21940.49(South)
* 17491.37(West)

### Coefficient Interpretation

* Marketing Spend: Positive impact on monthly sales.
* Footfall: Strong positive impact on monthly sales.
* Inventory Availability %: Higher inventory availability is associated with increased sales.
* North: Sales are higher than the reference category by approximately 10,547 units.
* South: Sales are higher than the reference category by approximately 21,940 units.
* West: Sales are higher than the reference category by approximately 17,491 units.



## Dummy Variable Explanation

Categorical variable used:

Region

Dummy Variables Created:

* North
* South
* West

Reference Category:

East

East was excluded from the model to avoid the dummy variable trap and serves as the baseline for comparison.



## Final Model Selection

Selected Model:

Multiple Regression Model

### Reason for Selection

* Highest R² value (0.811)
* Includes multiple business drivers
* Better forecasting capability
* Provides stronger business insight than simple regression models

  Simple Regression Model 2

Equation:

Monthly Sales = 446410.58 + 35.68(Footfall)

Interpretation:

Intercept = 446410.58

Footfall Coefficient = 35.68

For every additional customer visit, monthly sales increase by approximately 35.68 units.

R² = 0.736

P-value = 4.75E-94

Conclusion:

Footfall is statistically significant and is a strong predictor of monthly sales.

### Business Interpretation

The model demonstrates that customer footfall, marketing investment, inventory availability, and regional factors are important contributors to monthly sales performance. The model is therefore suitable for supporting strategic business decisions and resource allocation.
