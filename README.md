Understood the structure and characteristics of financial time-series data through exploratory analysis, summary statistics, and price/return visualizations generated in the notebook.
Learned the importance of establishing naïve baseline models and observed from the RMSE outputs that simple persistence-based forecasts provide a strong benchmark due to temporal autocorrelation in the data.
Implemented walk-forward evaluation and learned how it realistically simulates deployment by ensuring that training is performed strictly on past data and testing on future observations.
Observed that conventional random train–test splits are unsuitable for time-series data due to information leakage, which leads to overly optimistic performance metrics.
Applied RMSE as a primary evaluation metric and interpreted printed RMSE values to compare baseline and machine learning models consistently.
Used rolling RMSE plots to analyze time-varying model performance and identified periods of increased prediction error corresponding to higher volatility or regime shifts.
Learned that model performance is not uniform across time and that temporal stability is as important as aggregate accuracy.
Implemented and evaluated a Random Forest model and observed from rolling RMSE behavior that complex models can overfit historical patterns and degrade under changing market conditions.
Understood that similar overall RMSE values across models can hide significant differences in error distribution and timing.
Learned that model errors occurring predominantly during high-volatility periods may be less impactful in a portfolio context due to reduced exposure and risk management practices.
Developed an understanding of the need to combine quantitative metrics with visual diagnostics when evaluating time-series forecasting models.
