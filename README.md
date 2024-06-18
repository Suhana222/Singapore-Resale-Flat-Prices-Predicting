# Singapore-Resale-Flat-Prices-Predicting

![Screenshot_18-6-2024_15222_localhost](https://github.com/Suhana222/Singapore-Resale-Flat-Prices-Predicting/assets/167739067/801c48db-3ac4-4729-a548-473eb016796b)

# Overview

This project is designed to predict the resale prices of flats in Singapore using various machine learning models.
The project encompasses data loading, exploratory data analysis (EDA), data preprocessing, model training, evaluation, and saving the best model using pickle. Additionally, a Streamlit web application provides an interactive interface for exploring the data, training models, and making predictions.

# Libraries Used

1.pandas: For data manipulation and analysis.

2.numpy: For numerical computations.

3.scipy: For statistical functions.

4.seaborn: For data visualization.

5.matplotlib: For plotting graphs.

6.scikit-learn: For machine learning algorithms and model evaluation.

7.pickle: For saving and loading machine learning models.

8.streamlit: For creating the interactive web application.

9.streamlit-option-menu: For creating sidebar navigation in Streamlit.

# Step By Step Procedure

## 1. Import Libraries
   
Necessary libraries are imported to perform data manipulation, visualization, and machine learning tasks.

## 2. Load Data

The dataset is loaded using pandas. It contains information on resale flat prices in Singapore.

## 3. Exploratory Data Analysis (EDA)

EDA involves analyzing the dataset to understand its structure, main characteristics, and data distributions. Key steps include:

1.Viewing the first few rows of the dataset.

2.Generating summary statistics.

3.Checking data types and missing values.

4.Visualizing relationships between variables using pair plots.

## 4. Data Preprocessing

Data preprocessing involves preparing the data for machine learning models. Key steps include:

1.Handling missing values.

2.Feature engineering (if necessary), such as extracting date components.

## 5. Model Training

Multiple regression models are trained to predict the resale flat prices. Models include:

1.Linear Regression

2.Decision Tree Regressor

3.Random Forest Regressor

4.Extra Trees Regressor

5.The models are evaluated using the R2 score to determine their performance.

## 6. Model Evaluation

The best-performing model is selected and further evaluated using:

1.R2 Score

2.Mean Absolute Error (MAE)

3.Mean Squared Error (MSE)

4.Root Mean Squared Error (RMSE)

## 7. Saving the Best Model

The best model is saved using pickle for future use.

## Streamlit Web Application
The Streamlit web application provides an interactive interface for:

1.Performing EDA

2.Preprocessing the data

3.Training models

4.Evaluating model performance

5.Predicting resale prices

## Sidebar Menu

The sidebar menu allows navigation between different sections:

1.Home

2.Prediction Dashboard

## Home Section

Provides information about the Housing & Development Board (HDB) and Singapore's rapid growth. It includes textual information, images, and a video link.

## Prediction Dashboard Section

Allows users to input details about a flat and predict its resale price. The user inputs include month, town, flat type, flat model, floor area, price per sqm, year, block, lease commence date, remaining lease, years holding, storey start, and storey end. The model predicts the resale price based on these inputs.

# Conclusion

This project demonstrates an effective approach to predicting resale prices of flats in Singapore using machine learning techniques and creating an interactive web application with Streamlit. By leveraging a dataset on Singapore flat resale prices, the project performs essential steps such as data loading, exploratory data analysis (EDA), data preprocessing, model training, evaluation, and deployment.

### Key highlights of the project include:

### Data Exploration and Preprocessing: 

Through EDA, we gained insights into the dataset's structure, identified correlations, and handled missing values. Preprocessing steps involved feature engineering and normalization to prepare the data for modeling.

### Model Selection and Training: 

Multiple regression models including Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Extra Trees Regressor were evaluated. The models were trained and their performances compared using metrics like R2 score, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

### Streamlit Web Application: 

The interactive Streamlit web application allows users to explore the dataset, visualize data distributions, train models, evaluate model performance, and predict resale prices based on user inputs. It enhances user experience through intuitive navigation and real-time predictions.
 
 ### Predictive Accuracy: 
 
 The best-performing model, determined through rigorous evaluation, was saved using pickle. This ensures that the model can be easily loaded and used for future predictions with minimal computational overhead.

In conclusion, this project successfully combines data science techniques with web development to create a practical tool for predicting Singapore flat resale prices. It highlights the importance of data preprocessing, model selection, and interactive visualization in solving real-world problems. Future enhancements could focus on incorporating additional features, improving model performance further, and expanding the application's functionality to cater to broader user needs. Overall, this project serves as a valuable resource for stakeholders interested in understanding and predicting Singapore's real estate market dynamics.








