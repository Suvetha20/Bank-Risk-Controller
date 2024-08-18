# Bank-Risk-Controller

## Overview
The Bank Risk Controller System is a robust predictive model designed to identify customers who are likely to default on their loans. The goal is to enable financial institutions to proactively manage their credit portfolio, implement targeted interventions, and reduce the risk of loan defaults. This system leverages various data processing, machine learning techniques, and a user-friendly Streamlit application for visualization and prediction.

## Project Structure

* Main Libraries Used:

  * pandas: Data manipulation and analysis.
  * numpy: Numerical operations.
  * streamlit: Web application framework.
  * streamlit_option_menu: Custom sidebar menu for navigation.
  * plotly.express: Interactive data visualizations.
  * matplotlib & seaborn: Data visualization.
  * scikit-learn: Machine learning algorithms.
  * nltk: Natural Language Processing for sentiment analysis.
    
* File Structure:

  * main.py: The primary Python file containing the Streamlit app code.
  * df_final.csv: The dataset used for model training and analysis.
  * xgbmodel_1.pkl: The pre-trained XGBoost model for loan default prediction.

    
## Installation

  1.Clone the repository:
               
        git clone <repository-url>
        cd <repository-folder>
          
  2.Install the required Python packages:

      pip install -r requirements.txt
      
  3.Run the Streamlit application:
  
      streamlit run main.py
      
## Features

1. Home
   
* Overview of the Bank Risk Controller System.
* Displays information about the domain, technologies used, and project objectives.
  
3. Matrix Insights
   
* Showcases the model performance metrics for different machine learning algorithms.
* Highlights the selected algorithm (XGradient Boosting) with a 98% accuracy.
  
5. EDA Visualization
   
* Provides exploratory data analysis (EDA) insights.
* Includes skewness detection, log transformation, and outlier handling.
  
7. Model Prediction
   
* A form-based interface to input customer data for predicting loan default status.
* Uses the pre-trained model to predict whether a customer will default.
  
9. ML Sentiment Analysis
    
* Sentiment analysis using the VADER model from NLTK.
* Analyzes and visualizes the sentiment of user-provided text.

11. About
* Detailed description of the project, dataset, and expected outcomes.

## Dataset

The dataset used in this project contains various features such as personal information, credit history, financial status, and employment details. The target variable (TARGET) indicates whether a customer defaulted on their loan.

## How to Use

1.Navigate through different sections of the app using the sidebar menu.
2.Use the Model Prediction section to predict the default status of a customer by filling out the form.
3.Explore the EDA Visualization section to understand the data characteristics.
4.Analyze text sentiment in the ML Sentiment Analysis section.

## Conclusion
The Bank Risk Controller System is an effective tool for predicting customer loan defaults, enabling financial institutions to manage their credit risk proactively. The Streamlit application provides an intuitive interface for model interaction and data analysis.
