## Predictive Analytics for Electricity Consumption Forecasting ##
### Overview
This project explores the effectiveness of various traditional and machine learning models in accurately forecasting future electricity consumption, particularly in the presence of challenging exogenous factors. We demonstrate how models like SARIMAX, Support Vector Machine (SVM), and Random Forest can effectively capture complex relationships and generalize well with data influenced by external variables such as weather conditions and electricity prices.

### Project Goal
The primary goal of this project was to forecast electricity sales, leveraging temperature, electricity price, and unemployment rate as key exogenous variables. We aimed to identify which models and variable combinations yield the most accurate predictions under different scenarios.

### Methodology
I employed the following models for forecasting:

* SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors): A statistical model widely used for time series forecasting, capable of incorporating external factors.

* Support Vector Machine (SVM): A powerful supervised learning model used for classification and regression tasks, known for its ability to handle high-dimensional data.

* Random Forest: An ensemble learning method that constructs a multitude of decision trees at training time and outputs the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.

### Key Findings
Our analysis revealed insightful performance differences:

* Individual Exogenous Variables: When temperature, electricity price, and unemployment rate were applied separately to the SARIMAX model, SARIMAX consistently demonstrated strong prediction performance. Temperature, in particular, proved to be the most influential single exogenous variable, leading to the best prediction accuracy for SARIMAX.

* Combined Exogenous Variables: When all exogenous variables (temperature, electricity price, and unemployment rate) were applied simultaneously to the electricity sales data, the Random Forest model emerged as the superior performer, yielding the most accurate predictions.

### Conclusion
The study highlights the importance of selecting appropriate models based on the nature and combination of exogenous variables. While SARIMAX excels with individual exogenous factors (especially temperature), Random Forest demonstrates greater robustness and predictive power when multiple complex exogenous influences are at play. These findings provide valuable insights for developing more accurate and resilient electricity consumption forecasting models.

### Future Work (Optional)
Explore deep learning models (e.g., LSTMs) for time series forecasting with exogenous variables.

Incorporate additional exogenous factors such as holidays, economic indicators, or population changes.

Develop a real-time prediction dashboard
