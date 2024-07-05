# Flight Price Prediction

## Overview
This project focuses on predicting flight prices based on various parameters such as airline, departure time, duration, stops, and more. Predicting flight prices accurately helps travelers plan their journeys effectively by anticipating fare changes.

## Tech Stack
- **Python**: Programming language used for data preprocessing, model building, and analysis.
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn for data manipulation, numerical computing, and data visualization.
- **Machine Learning**: Scikit-learn for implementing machine learning algorithms like Random Forest Regressor.
- **Jupyter Notebook**: Environment for interactive development and visualization of data and models.
- **Google Colab**: Cloud-based platform used for running Python code in Jupyter notebooks.

## Data Preprocessing
The dataset used for this project contains various features including airline, source, destination, departure and arrival times, duration, and total stops. Here’s a brief overview of the preprocessing steps:

1. **Data Cleaning**: 
   - Removed null values to ensure data integrity.
   - Cleaned and formatted date-time fields (departure and arrival times) for consistency.

2. **Feature Engineering**:
   - Extracted features such as journey day, month, departure hour, minute, arrival hour, minute, and duration from date-time strings.
   - Normalized the 'Total Stops' feature to numeric values for better model compatibility.

3. **Encoding Categorical Variables**:
   - Applied One-Hot Encoding to categorical variables like airline, source, and destination to convert them into numerical form suitable for machine learning models.

4. **Data Visualization**:
   - Utilized seaborn and matplotlib for visualizing price distributions across different airlines and other categorical variables.
   - Plotted correlation matrices to understand feature relationships and their impact on flight prices.

## Model Building and Evaluation
- **Random Forest Regressor**: Chosen for its ability to handle complex datasets and provide robust predictions.
- **Evaluation Metrics**: Evaluated models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) to assess prediction accuracy.

## Future Enhancements
- **Hyperparameter Tuning**: Optimize model performance through techniques like Grid Search or Randomized Search.
- **Feature Selection**: Identify the most influential features affecting flight prices to improve model efficiency.
- **Deployment**: Explore deployment options using Flask or other frameworks for making predictions accessible via a web interface.

## Conclusion
This project demonstrates the application of machine learning techniques to predict flight prices based on historical data. By leveraging data preprocessing techniques and a robust machine learning model, the goal is to provide accurate and timely predictions for better travel planning.
