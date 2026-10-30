# Supply Chain Analytics & Late Delivery Prediction

## Project Overview
An end-to-end Supply Chain Analytics project focused on analyzing e-commerce delivery performance, identifying operational bottlenecks, measuring profitability, and predicting late-delivery risk using Machine Learning.

The project uses historical supply chain data to understand delivery patterns and generate actionable business insights.

## Business Objectives
- Analyze overall delivery performance and late-delivery rates.
- Identify operational bottlenecks across regions, shipping modes, customer segments, and departments.
- Evaluate order profitability and financial performance.
- Analyze delivery trends by month, weekday, and hour.
- Build a Machine Learning model to classify late-delivery risk.

## Tech Stack
- **Programming:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, Random Forest
- **Data Balancing:** SMOTE
- **Environment:** Jupyter Notebook

## Project Workflow
1. Data loading and initial exploration
2. Data cleaning and preprocessing
3. Feature engineering and delivery-delay calculation
4. Profitability and business KPI analysis
5. Exploratory Data Analysis (EDA)
6. Regional bottleneck and operational driver analysis
7. Time-based delivery trend analysis
8. Late-delivery risk classification using Random Forest
9. Model evaluation and business recommendations

## Key Findings
- Analyzed 172,765 records after data cleaning.
- Identified a 54.71% calculated delivery-delay rate.
- Analyzed profitability across delayed and non-delayed orders.
- Identified variations in delivery performance across customer segments and time periods.
- Evaluated a Random Forest model with 74% accuracy, 79% precision, and 75% recall.

## Machine Learning
A Random Forest Classifier was trained to predict the existing `Late_delivery_risk` target.

Key techniques:
- Frequency encoding for categorical variables
- 80:20 train-test split
- SMOTE for training-data class balancing
- Accuracy, precision, recall, and F1-score evaluation

## Repository Structure
```text
Supply-Chain-Analytics-and-Delivery-Prediction/
│
├── data/
│   └── README.md
│
├── Supply_Chain_Analytics.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run
1. Clone this repository.
2. Install the required Python libraries.
3. Download and place the dataset in the appropriate data folder.
4. Open the Jupyter Notebook.
5. Run the notebook cells sequentially.

## Note
The model predicts the dataset's existing late-delivery-risk label. The calculated delay metric and the original risk label are separate variables. Further validation is required before using the model for real-world pre-shipment predictions.

The original dataset is not included in this repository. Users should obtain the dataset from its original source and follow its applicable usage terms.