# Loan Approval Prediction System 🏦💡

This project implements a **machine learning pipeline** for predicting loan approval status based on user-specific data. The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, model building, and a **Graphical User Interface (GUI)** to provide real-time predictions.

## Features 🚀

1. **Data Preprocessing** 🛠️  
   - Handles missing values, outliers, and data normalization.  
   - Encodes categorical variables for compatibility with machine learning algorithms.  

2. **Exploratory Data Analysis** 🔍  
   - Visualizes data distributions and relationships through interactive plots.  
   - Highlights trends and potential correlations between variables.  

3. **Feature Engineering** ⚙️  
   - Optimizes the dataset with derived features like `loan_to_income_ratio`.  
   - Groups numerical values into meaningful categories for better predictions.  

4. **Model Building & Evaluation** 🤖  
   - Implements supervised learning algorithms for classification.  
   - Evaluates model performance using metrics like accuracy, precision, recall, and F1-score.  

5. **User-Friendly Predictions** 🎯  
   - Supports a GUI for users to input their details and receive predictions.  
   - Provides loan approval status and approval probability based on input features.

## GUI Implementation 💻

The **Loan Approval Prediction GUI** is built using **Tkinter**, a Python library for creating graphical user interfaces. Users can input their age, income, home ownership status, and car ownership status to receive a loan approval prediction. 

- **Inputs**: Age, Income, Home Ownership, and Car Ownership.  
- **Outputs**: Loan Approval Status (Approved/Denied) along with the probability of approval.
<p align="center">
  <img width="550" alt="Screenshot 2024-12-16 at 11 30 52" src="https://github.com/user-attachments/assets/98ace0a5-f548-4476-b239-1087b4d95148" />
</p>

### GUI Workflow:
1. **Input Fields**:  
   Users enter their **age**, **income**, **home ownership** status (Rent, Own, Mortgage), and **car ownership** (Yes/No).
2. **Prediction Button**:  
   After entering their information, users click the **Predict** button to get the result.
3. **Result Display**:  
   The application will show a message with the loan approval status and the predicted probability of approval.


## How It Works ⚡

### Dataset:
The dataset includes information such as age, income, employment history, and credit details. These features are used to predict the binary outcome of loan approval (approved or not approved).

### Steps:
1. Preprocess the data for cleaning and normalization.
2. Visualize insights from the data.
3. Train multiple machine learning models (e.g., Logistic Regression, Decision Trees) and select the best-performing one.
4. Provide a user interface for predictions.

