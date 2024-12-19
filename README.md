# Employee-Performence
# Employee Performance Analysis and Prediction

## Project Overview
This project involves analyzing employee performance data from the **INX Future Inc Employee Performance dataset**. The goal is to identify key factors influencing performance, predict performance ratings, and provide actionable recommendations to improve overall employee productivity.

## Features
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Visualizations (Histogram, Violin Plots, Correlation Heatmap, etc.)
- Outlier Detection and Removal
- Predictive Modeling using Machine Learning Algorithms
- Hyperparameter Tuning with GridSearchCV
- Feature Importance Analysis and Recommendations
- Custom Function for Predicting Performance of New Employees

## Technologies Used
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Visualization**: SweetViz, Violin Plots, Correlation Heatmaps
- **Machine Learning Models**:
  - Random Forest
  - Decision Tree
  - Support Vector Classifier
  - K-Nearest Neighbors
  - Naive Bayes
  - Bagging Classifier
- **Data Processing**: Label Encoding, StandardScaler
- **Evaluation Metrics**: Accuracy, Classification Report

## Dataset
The dataset includes employee details such as demographics, job roles, work environment satisfaction, and performance ratings. Data preprocessing includes handling null values, encoding categorical variables, and removing outliers.

## Key Steps
### 1. Data Preprocessing
- Removed missing values and handled categorical data using Label Encoding.
- Detected and removed outliers from key features such as:
  - `TotalWorkExperienceInYears`
  - `ExperienceYearsAtThisCompany`
  - `YearsSinceLastPromotion`

### 2. Exploratory Data Analysis (EDA)
- Analyzed data distribution using histograms and box plots.
- Created department-wise and job role-based performance visualizations.
- Explored correlations using a heatmap.
### Correlation Heatmap
![Correlation Heatmap](https://github.com/omkarnitturkar/Employee-Performence/blob/main/heatmap.png)
### 3. Model Training and Evaluation
- Trained multiple machine learning models and compared performance.
- Used GridSearchCV for hyperparameter optimization.
- Identified the top 3 most important features affecting performance.


### Department-wise Performance
![Department-wise Performance](https://github.com/omkarnitturkar/Employee-Performence/blob/main/Department_wise_performence.png)

### 4. Predictive Function
A custom function, `predict_employee_performance`, predicts the performance rating for new hires based on input features.

## Results
- Best-performing model: **Random Forest Classifier** with optimized hyperparameters.
- Accuracy: Over **85%**.
- Top 3 Important Factors:
  1. `YearsSinceLastPromotion`
  2. `EmpEnvironmentSatisfaction`
  3. `EmpLastSalaryHikePercent`

## Recommendations
- Improve work-life balance for employees to boost performance.
- Increase training opportunities for underperforming employees.
- Tailor performance incentives based on specific job roles.



### Violin Plot for OverTime
![Violin Plot for OverTime](https://github.com/omkarnitturkar/Employee-Performence/blob/main/Violin.png)

## How to Run the Project
1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn sweetviz
