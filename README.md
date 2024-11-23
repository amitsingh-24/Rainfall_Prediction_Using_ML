# Rainfall_Prediction_Using_ML

## Project Overview
This project focuses on the comprehensive analysis and predictive modeling of weather data to forecast rainfall. The dataset used is `weatherAUS.csv`, which includes various meteorological measurements recorded over time.

## Key Steps and Achievements

1. **Data Preprocessing:**
   - Loaded the weather dataset using pandas and conducted an initial exploration.
   - Replaced categorical values in the `RainToday` and `RainTomorrow` columns with numerical equivalents for ease of analysis.

2. **Data Visualization:**
   - Created visual representations of the imbalanced and balanced dataset regarding the `RainTomorrow` indicator.
   - Utilized heatmaps to identify missing data patterns within the dataset.

3. **Data Imputation:**
   - Filled missing values in categorical features with their mode values.
   - Applied Multiple Imputation by Chained Equations (MICE) to handle missing data in numerical features.
   
4. **Outlier Detection and Removal:**
   - Identified outliers using the Interquartile Range (IQR) method and removed them to refine the dataset.

5. **Feature Engineering:**
   - Standardized the dataset for consistency.
   - Performed feature selection using methods such as Chi-Square test and Random Forest feature importance.
   
6. **Model Building:**
   - Developed and evaluated multiple machine learning models, including Logistic Regression, Decision Trees, Neural Networks, Random Forests, LightGBM, CatBoost, and XGBoost.
   - Assessed model performance based on accuracy, ROC-AUC, and Cohen's Kappa metrics.

7. **Model Evaluation:**
   - Used ROC curves and confusion matrices to visualize and compare model performance.
   - Presented comprehensive classification reports for each model, detailing precision, recall, and F1-score.

8. **Project Outcomes:**
   - Achieved a balanced dataset through oversampling techniques.
   - Successfully identified significant features influencing the prediction of rainfall.
   - Demonstrated high-performing models capable of accurately predicting rainfall.

## Future Work
Future enhancements for this project could include:
- Exploring additional feature engineering techniques to further improve model performance.
- Incorporating more sophisticated imputation methods to handle missing data.
- Experimenting with advanced models such as Gradient Boosting Machines and ensemble learning techniques.
- Extending the analysis to other weather-related phenomena and datasets.
- Automating the entire pipeline using tools like Apache Airflow or Prefect for real-time data processing and model deployment.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute this code as long as the original author is credited.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements, bug fixes, or documentation updates.

