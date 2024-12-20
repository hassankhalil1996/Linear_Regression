# Film Revenue Prediction using Linear Regression
![image alt](https://github.com/hassankhalil1996/Linear_Regression/blob/main/Capture.PNG?raw=true)

This project predicts the worldwide gross revenue of a film based on its production budget using **linear regression**.

## Files

- **cost_revenue_clean.csv**: Dataset with production budgets and worldwide gross revenues of films.
- **Film_Revenue_Prediction.ipynb**: Jupyter Notebook with the linear regression model and visualizations.

## Requirements

Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn
```

## Running the Code

1. Clone the repository:
```bash
    git clone https://github.com/yourusername/film-revenue-prediction.git
```

2.Open the notebook:
```bash
    jupyter notebook
```

Run the cells in Film_Revenue_Prediction.ipynb to:

3 . Visualize the relationship between production costs and worldwide revenue.
- Fit a linear regression model.
- Plot the regression line.

## Conclusion:
The slope we obtained is 3.11, which means that for every dollar invested in production, the revenue increases by 3.11 dollars.
This makes sense, as higher production budgets generally lead to higher revenues.

However, the intercept is -7 million USD, meaning that if no money is invested in the production, 
the predicted revenue would be a loss of 7 million USD. This doesn't make sense in a real-world context, 
as films with no production cost wouldn't generate any revenue.

**This suggests that using a simple linear regression model with only one feature (production budget)**
**may not be efficient for predicting film revenue. A more complex approach, incorporating additional factors,**
**may yield better and more accurate predictions.**  