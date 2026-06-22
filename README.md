# Employee Attrition Prediction Using Machine Learning

## CodTech Data Analysis Internship - Task 2

### Project Overview
This project focuses on predicting employee attrition using Machine Learning techniques. Employee attrition refers to employees leaving an organization. The goal is to analyze employee-related factors and build predictive models that can identify employees who are likely to leave the company.

### Objective
To develop a machine learning model that predicts employee attrition using the IBM HR Analytics dataset. The project includes data exploration, preprocessing, feature selection, model training, evaluation, and business insights generation.

### Dataset
- Dataset: IBM HR Analytics Employee Attrition Dataset
- Total Records: 1470
- Total Features: 35
- Target Variable: Attrition

### Tools and Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Project Workflow

#### 1. Data Collection
The IBM HR Analytics dataset was imported and examined.

#### 2. Data Exploration
- Checked dataset shape
- Analyzed column information
- Verified missing values
- Explored employee demographics and attrition trends

#### 3. Data Preprocessing
- Removed unnecessary columns
- Converted categorical variables into numerical values
- Prepared features and target variable
- Split data into training and testing sets

#### 4. Exploratory Data Analysis (EDA)
Visualizations created:
- Employee Attrition Distribution
- Gender Distribution
- Department Distribution
- Attrition by Gender
- Monthly Income Distribution

#### 5. Machine Learning Models
The following models were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

### Model Performance

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 87.76% |
| Decision Tree | 79.93% |
| Random Forest | 88.10% |

### Best Model
Random Forest Classifier achieved the highest accuracy of **88.10%** and was selected as the best-performing model.

### Key Insights
- Research & Development department had the highest number of employees.
- Employee retention was significantly higher than attrition.
- Several employee-related factors influence attrition.
- Random Forest provided the most accurate predictions.
- Feature importance analysis helped identify the factors contributing most to employee attrition.

### Conclusion
This project successfully developed a machine learning model to predict employee attrition using the IBM HR Analytics dataset. After preprocessing, feature selection, and model training, the Random Forest model achieved the highest accuracy of 88.10%.

The analysis demonstrates how machine learning can assist organizations in identifying employees at risk of leaving and support proactive workforce retention strategies.

### Author
CodTech Data Analysis Internship - Task 2
Employee Attrition Prediction Using Machine Learning