🚢 Titanic Exploratory Data Analysis (EDA)

Uncovering the social and structural factors that determined survival aboard the RMS Titanic through data cleaning, feature engineering, statistical analysis, and visualization.

📌 Project Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) on the Titanic passenger dataset. The objective is to identify the key factors that influenced survival during the Titanic disaster using data preprocessing, feature engineering, descriptive statistics, and visual analytics.

🎯 Project Goal

Analyze passenger data to understand how variables such as gender, passenger class, age, fare, and family size affected survival outcomes.

❓ Central Question

Was survival a matter of luck, or was it influenced by social and economic factors?

The analysis shows that survival was strongly influenced by gender, passenger class, and wealth rather than random chance.

✅ Skills Demonstrated
Data Cleaning and Preprocessing
Missing Value Treatment
Feature Engineering
Exploratory Data Analysis (EDA)
Statistical Analysis
Data Visualization
Correlation Analysis
Insight Generation
Professional Project Documentation
📂 Repository Structure
Titanic_EDA_project/
│
├── data/
│   └── titanic.csv
│
├── images/
│   ├── missing_value_analysis.png
│   ├── plot1_survival_count.png
│   ├── plot2_survival_by_gender.png
│   ├── plot3_survival_by_class.png
│   ├── plot4_age_distribution.png
│   ├── plot5_fare_distribution.png
│   ├── plot6_correlation_heatmap.png
│   ├── plot7_boxplots_outliers.png
│   └── plot8_multivariable_analysis.png
│
├── Titanic_EDA.ipynb
├── titanic_eda.py
├── titanic_cleaned.csv
├── requirements.txt
└── README.md
📊 Dataset

Source: Kaggle Titanic: Machine Learning from Disaster

Dataset Size: 891 Rows × 12 Columns

Key features include:

PassengerId
Survived
Pclass
Name
Sex
Age
SibSp
Parch
Ticket
Fare
Cabin
Embarked
🔧 Data Cleaning & Feature Engineering
Data Cleaning
Dropped Cabin column (77.1% missing values)
Removed Name and Ticket columns
Filled missing Age values using median
Filled missing Embarked values using mode
Encoded categorical variables
Engineered Features
FamilySize
IsAlone
AgeGroup
FareBand

Final dataset:

891 rows
16 columns
0 missing values
📈 Analysis Pipeline
Environment Setup
Data Loading
Dataset Inspection
Missing Value Analysis
Duplicate Detection
Data Cleaning
Feature Engineering
Descriptive Statistics
Data Visualization
Insight Extraction
Clean Dataset Export
🖼️ Visualizations

Generated visualizations include:

Missing Value Analysis
Survival Count
Survival by Gender
Survival by Passenger Class
Age Distribution
Fare Distribution
Correlation Heatmap
Outlier Detection Boxplots
Multi-variable Relationship Analysis

All generated plots are saved in the images/ folder.

🔍 Key Findings
Overall Survival
Total Passengers: 891
Survivors: 342
Survival Rate: 38.4%
Gender Impact
Female Survival Rate: 74.2%
Male Survival Rate: 18.9%
Passenger Class Impact
1st Class: 63.0%
2nd Class: 47.3%
3rd Class: 24.2%
Fare Impact

Passengers who paid higher fares generally had higher survival rates.

Age Impact

Children had better survival rates than adults.

Family Size Impact

Passengers traveling in small family groups had better survival outcomes than solo travelers or very large families.

📉 Correlation Summary

Strongest relationships with survival:

Feature	Relationship
Sex_Encoded	Strong Positive
Pclass	Strong Negative
Fare	Moderate Positive
IsAlone	Weak Negative
Age	Weak Negative
🚀 Installation
Clone Repository
git clone https://github.com/YOUR_USERNAME/Titanic-EDA.git
cd Titanic-EDA
Install Dependencies
pip install -r requirements.txt
▶️ Usage
Run Jupyter Notebook
jupyter notebook Titanic_EDA.ipynb
Run Python Script
python titanic_eda.py

Outputs:

Cleaned dataset (titanic_cleaned.csv)
Visualizations (images/)
Analysis summary
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
🔮 Future Improvements
Logistic Regression Model
Random Forest Classifier
Feature Importance Analysis
Hyperparameter Tuning
ROC-AUC Evaluation
Interactive Dashboard using Streamlit
📝 Conclusion

The analysis demonstrates that survival on the Titanic was heavily influenced by:

Gender
Passenger Class
Economic Status

Female passengers and first-class travelers had significantly better survival rates, while third-class male passengers faced the lowest survival probabilities.

This project demonstrates a complete EDA workflow, from raw data exploration to actionable insights and machine learning readiness.

🙋 Author

Sriya Patil

GitHub: https://github.com/SriyaPatil

