# Model Comparison

| Model | Variables Used | R-Squared | Significant Variables | Business Usefulness | Limitations |
|---------|---------|---------|---------|---------|---------|
| Simple Regression 1 | monthly_sales ~ marketing_spend | 0.167 | marketing_spend | Useful for understanding marketing impact | Ignores other business drivers |
| Simple Regression 2 | monthly_sales ~ footfall | 0.736 | footfall | Strong predictor of sales | Single variable view |
| Multiple Regression | monthly_sales ~ marketing_spend + footfall + inventory_availability_pct + region dummies | 0.811 | marketing_spend, footfall, inventory availability, South, West | Best decision-making model | Does not capture all external factors |

## Conclusion

The multiple regression model explains approximately **81.1%** of the variation in monthly sales and provides the strongest business insight among all models evaluated. Due to its higher explanatory power and inclusion of multiple business drivers, it is the recommended model for supporting business decisions and sales forecasting.

Save the file as:
