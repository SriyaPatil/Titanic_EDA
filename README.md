# 🚢 Titanic Exploratory Data Analysis (EDA)

Uncovering the social and structural factors that influenced survival aboard the RMS Titanic through data cleaning, feature engineering, statistical analysis, and visualization.

---

## 📌 Project Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the Titanic passenger dataset to identify the key factors that influenced survival during the Titanic disaster. The analysis incorporates data preprocessing, feature engineering, statistical exploration, and visual analytics to derive meaningful insights.

---

## 🎯 Project Goal

To analyze passenger data and understand how factors such as **gender, passenger class, age, fare, and family size** affected survival outcomes.

### ❓ Central Question

**Was survival a matter of luck, or was it influenced by social and economic factors?**

The analysis reveals that survival was strongly associated with **gender, passenger class, and socioeconomic status**, rather than random chance.

---

## 🛠️ Skills Demonstrated

* 🧹 Data Cleaning and Preprocessing
* 🔍 Missing Value Treatment
* ⚙️ Feature Engineering
* 📊 Exploratory Data Analysis (EDA)
* 📈 Statistical Analysis
* 📉 Data Visualization
* 🔗 Correlation Analysis
* 💡 Insight Generation
* 📝 Professional Project Documentation

---

## 📂 Repository Structure

```text
Titanic_EDA/
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
```

---

## 📊 Dataset Information

* **Source:** Kaggle - Titanic: Machine Learning from Disaster
* **Dataset Size:** 891 Rows × 12 Columns

### Features Included

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked

---

## 🔧 Data Cleaning & Feature Engineering

### 🧹 Data Cleaning

* Removed `Cabin` column due to high missing values (77.1%)
* Dropped `Name` and `Ticket` columns
* Filled missing `Age` values using the median
* Filled missing `Embarked` values using the mode
* Encoded categorical variables for analysis

### ⚙️ Engineered Features

* `FamilySize`
* `IsAlone`
* `AgeGroup`
* `FareBand`

### ✅ Final Dataset

* **Rows:** 891
* **Columns:** 16
* **Missing Values:** 0

---

## 📈 Analysis Pipeline

* 📥 Environment Setup
* 📂 Data Loading
* 🔍 Dataset Inspection
* 🧹 Missing Value Analysis
* 🔎 Duplicate Detection
* ⚙️ Data Cleaning
* 🛠️ Feature Engineering
* 📊 Descriptive Statistics
* 📉 Data Visualization
* 💡 Insight Extraction
* 💾 Clean Dataset Export

---

## 🖼️ Visualizations

The following visualizations were generated during the analysis:

*  Missing Value Analysis
*  Survival Count Distribution
*  Survival by Gender
*  Survival by Passenger Class
*  Age Distribution
*  Fare Distribution
*  Correlation Heatmap
*  Outlier Detection Boxplots
*  Multi-variable Relationship Analysis

> All generated plots are available in the `images/` directory.

---

## 🔍 Key Findings

### 🚢 Overall Survival

* Total Passengers: **891**
* Survivors: **342**
* Survival Rate: **38.4%**

### 🚺 Gender Impact

* Female Survival Rate: **74.2%**
* Male Survival Rate: **18.9%**

### 🎟️ Passenger Class Impact

| Passenger Class | Survival Rate |
| --------------- | ------------- |
| 1st Class       | 63.0%         |
| 2nd Class       | 47.3%         |
| 3rd Class       | 24.2%         |

### 💰 Fare Impact

Passengers who paid higher fares generally had higher survival probabilities.

### 🎂 Age Impact

Children exhibited better survival rates compared to adults.

### 👨‍👩‍👧 Family Size Impact

Passengers traveling in smaller family groups had better survival outcomes than solo travelers or those in very large families.

---

## 📉 Correlation Summary

| Feature     | Relationship with Survival |
| ----------- | -------------------------- |
| Sex_Encoded | Strong Positive            |
| Pclass      | Strong Negative            |
| Fare        | Moderate Positive          |
| IsAlone     | Weak Negative              |
| Age         | Weak Negative              |

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/SriyaPatil/Titanic_EDA.git
```

Navigate to the project directory:

```bash
cd Titanic_EDA
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Run the Jupyter Notebook

```bash
jupyter notebook Titanic_EDA.ipynb
```

### Run the Python Script

```bash
python titanic_eda.py
```

### Outputs Generated

* 📄 Cleaned Dataset (`titanic_cleaned.csv`)
* 📊 Visualizations (`images/`)
* 📝 Analysis Summary

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔮 Future Improvements

* 🤖 Logistic Regression Model
* 🌲 Random Forest Classifier
* 📌 Feature Importance Analysis
* ⚙️ Hyperparameter Tuning
* 📈 ROC-AUC Evaluation
* 🌐 Interactive Dashboard using Streamlit

---

## 📝 Conclusion

The analysis demonstrates that survival aboard the Titanic was heavily influenced by:

* 🚺 Gender
* 🎟️ Passenger Class
* 💰 Economic Status

Female passengers and first-class travelers had significantly higher survival rates, while third-class male passengers faced the lowest survival probabilities.

This project showcases a complete **Exploratory Data Analysis workflow**, transforming raw data into meaningful insights and preparing the dataset for future predictive modeling tasks.

---

## 👨‍💻 Author

Sriya Patil

### 🔗 Connect with Me


Linkedin: https://linkedin.com/in/sriya-patil-63240332a

---
