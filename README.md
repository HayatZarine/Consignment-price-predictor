# Predicting Consignment Pricing Using Machine Learning
This is created by google colab. 

# Overview
The logistics industry is rapidly adopting data-driven methods to optimize operations and improve decision-making. This project aims to develop a machine learning model to predict consignment pricing based on various features from historical consignment data. Accurate pricing predictions can help organizations optimize costs and address supply chain challenges effectively.
# Project Objectives
1.Understand and explore the dataset to gain insights into factors influencing consignment pricing.
2.Perform data cleaning and preprocessing, addressing missing values and outliers.
3.Engineer meaningful features to improve predictive performance.
4.Train and evaluate multiple machine learning models to determine the best-performing one.
5.Validate the models using standard regression metrics (e.g., R², MAE, RMSE).
6.Write modular, reusable, and maintainable code following PEP 8 standards.
# Dataset
Source: The dataset is included in the repository under data/Consignment_pricing_raw.csv.
Dataset used- https://raw.githubusercontent.com/praj2408/Consignment-Pricing-using-MLOps-DVC/refs/heads/main/consignment_data/Consignment_pricing_raw.csv  
Description: The dataset contains various features like weight, delivery distance, mode of transportation, and target pricing. These features will be used to train machine learning models.
# Project Workflow
1. Data Exploration
Analyzed dataset features, identified missing values, and outliers.
Visualized data distributions and relationships between features using plots (e.g., correlation heatmap, scatter plots).
2. Data Preprocessing
Handled missing values by replacing or imputing them.
Removed outliers using statistical methods.
Scaled numerical features and encoded categorical variables as needed.
3. Model Training
Models Trained:
Linear Regression (baseline model)
Random Forest Regressor
XGBoost Regressor
Used Train-Test Split for model validation.
4. Model Evaluation
Metrics used to evaluate models:
R² Score: Measures the proportion of variance explained by the model.
Mean Absolute Error (MAE): Measures the average absolute error.
Root Mean Squared Error (RMSE): Penalizes large errors more heavily.
Selected the best-performing model based on metrics comparison.
5. Feature Importance Analysis
Identified key features contributing to consignment pricing.
# Setup Instructions
Requirements
Python 3.8 or higher
Required libraries:
1.pandas
2.numpy
3.matplotlib
4.seaborn
5.scikit-learn
# Installation
1. Clone this repository:
   git clone https://github.com/hayatzarine/consignment-pricing-ml.git
cd consignment-pricing-ml
2. Install the required libraries:
   pip install -r requirements.txt
*Running the Code*
1.Open the Jupyter Notebook (consignment_pricing.ipynb) in your preferred environment.
2.Execute the cells step-by-step to preprocess the data, train models, and evaluate their performance.
# Feature Importance
Key factors influencing pricing:
1.Weight of the consignment
2.Distance of delivery
3.Mode of transportation
4.Urgency of the shipment
# Folder Structure
consignment-pricing-ml/
│
├── data/
│   └── Consignment_pricing_raw.csv    # Dataset
├── notebooks/
│   └── consignment_pricing.ipynb      # Jupyter Notebook
├── models/
│   └── random_forest.pkl              # Trained Random Forest model
│   └── xgboost.pkl                    # Trained XGBoost model
├── README.md                          # Project Documentation
├── requirements.txt                   # Required Python libraries
# Contact
For any inquiries or issues, feel free to contact:

Name: HayatZarine
Email: hayatzarine@gmail.com 
## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

