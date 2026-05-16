# Predictive Oil Well Selection & Financial Risk Analysis

## Objective
The strategic objective of this project was to select the optimal geographical regions for drilling 200 new oil wells for OilyGiant. The business challenge required integrating technical volume forecasting with a comprehensive financial ROI (Return on Investment) analysis and strict risk mitigation controls.

## Key Results
By combining predictive modeling with a **Bootstrapping** statistical simulation (1,000 samples), **Region 0** was identified as the ideal location for expansion. It demonstrated the highest expected average profit and a completely positive 95% confidence interval, successfully keeping the risk of financial loss below the company's strict threshold of 2.5%.

## Tools & Technologies Used
- **Python** (Pandas, NumPy, Matplotlib)
- **Scikit-Learn** (Linear Regression)
- **Statistical Simulation** (Bootstrapping, 95% Confidence Interval)

## What I Learned
- Developing continuous predictive models using Linear Regression to estimate physical asset reserves.
- Applying practical financial concepts such as profit margins and break-even analysis within a data science context.
- Managing corporate risk through rigorous statistical simulations of uncertainty under real business constraints.

## Future Improvements
- Test non-linear regression algorithms or ensemble methods (e.g., XGBoost, Random Forest) to refine oil volume prediction accuracy.
- Incorporate dynamic operational and logistical cost variables unique to each geographic region.

---

## Methodology
1. **Data Preparation:** Evaluated geological characteristics across three independent regional datasets.
2. **Training & Validation:** Built independent predictive models for each region and calculated the RMSE.
3. **Profit Calculation:** Defined revenue logic based on the forecasted volumes of the top-performing wells.
4. **Risk Analysis (Bootstrapping):** Simulated sub-samplings to map profit distributions and calculate the exact probability of losses.

## How to Run
1. Clone this repository.
2. Install the required dependencies: `pip install pandas numpy scikit-learn matplotlib`
3. Execute the notebook to view the consolidated risk-reward comparison for the three regions.
