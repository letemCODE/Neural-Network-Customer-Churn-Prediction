# Customer Churn Prediction Neural Network Model

## 1. Project Overview
This project aids in accurately predicting whether a customer stays or stops using an internet provider's services based on various aspects . This prediction is based on various features like gender, SeniorCitizen,	Partner,	Dependents,	tenure,	Phone Service,	Internet Service, Online Security and more.
This could help the company in several ways by enabling them to make data driven decisions to retain and keep their customers happy. The project involves data cleaning and preparation, build a neural network model for accurate prediction.

## 2. Features
- **Data Cleaning and Processing**  
  Apply data manipulation techniques to create derived features and create a pipline that Processes, Prepares and Cleans the data making it suitable for the predictive model.    

- **Predictive Model**  
  Uses Tensorflow, Keras to determine the classification model based on features and Earlystopping to obtain the best weights for it and prevent overfitting.

## 3. Installation

To run the project locally, follow these steps:

  1. Download the `Customer_Churn_Perdiction.ipynb` and `ChurnData.csv` files.
  2. Ensure you have Jupyter Notebook installed on your device.
  3. Install the required libraries:
     ```bash
     pip install pandas numpy plotly.express matplotlib.pyplot collections regex sklearn plotly.graph_objects pandas numpy seaborn tensorflow
  4. Open the notebook using Jypyter Notebook.

## 4. Files Included

### 1. `Customer_Churn_Perdiction.ipynb`
  - Performs initial Data Exploration, Analytics. Further grouping, aggregating, combining processing and preparing the data.
  - Performs Predection of customer churn using a neural network predective model with the best weights.
  - Libraries used in this notebook: pandas, numpy, plotly.express, matplotlib.pyplot, collections, regex, sklearn, seaborn, tensorflow, keras.

## 5. Data Sources

### Source 1: `ChurnData.csv`
A csv file containing the data on the Customer ID, gender, family details, Service details, PAymet details, Churn and more. 

1. **ChurnData.csv**  
   House information: customerID, gender, Senior Citizen, Partner, Dependents, tenure, Phone Service, Multiple Lines, Internet Service, Online Security, Online Backup, Device Protection, Tech Support, Streaming TV, Streaming Movies, Contract, Paperless Billing, Payment Method, Monthly Charges, Total Charges, Churn.

## 6. Libraries Used

This project uses the following Python libraries:

1. **pandas** – For data manipulation and cleaning.  
2. **numpy** – For numerical operations and transformations.  
3. **plotly.express** – For creating interactive visualizations with Plotly.
4. **matplotlib.pyplot** - For creating visualizations.
5. **seaborn** – Visualising the confusion matrix to aid in determining model performance.
6. **collections** – Grouping and Counting classes for each feature.
7. **regex** - Aids in feature cleaning and preparation
8. **sklearn** - For splitting the data appropriately for testing and training.
9. **tensorflow** - For building and compiling the Sequential Neural Network predective model, retaining the best weights and stopping training at the right time.

## 7. How to Use

### Running the Notebooks:

1. **Data Cleaning, Model Building and Prediction**:
   - Open `Customer_Churn_Perdiction.ipynb` in Jupyter Notebook.
   - Follow the steps to extract, clean, transform the data, build the model, evaluate the model and predict.
   - Evaluate the output.
