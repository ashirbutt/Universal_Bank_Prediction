# **Universal Bank Prediction**
This project focuses on predicting whether a customer will take a personal loan based on their financial and demographic data. By building machine learning models, the aim is to help the bank improve its decision-making and marketing strategies for personal loans. The dataset includes key information such as customer age, income, family size, average credit card spending, and education level. The process involves thorough data preprocessing, model training, and evaluation, with hyperparameter tuning to achieve optimal results.

## Dataset Overview
The dataset contains customer information such as:

- **Age**, **Experience**, I**Income**, **Family Size**, **Credit Card Average Spending (CCAvg)**, **Education**, **Mortgage**, and others.
- Target variable: **Personal Loan** (whether the customer has taken a personal loan).

## 1. Project Workflow
The dataset was initially explored to understand its structure and key features. Basic statistical analysis was performed to review distributions and identify important patterns.

### 2. Data Preprocessing
Key steps in cleaning and preparing the data:

- **Missing Values**: Handled missing values.
- **Duplicate Remova**l: Removed duplicate records.
- **Outlier Detection**: Detected and removed outliers using the IQR method.
### 3. Data Analysis
Performed distribution and correlation analysis:

- **Distribution Plots**: Visualized key features such as income, family size, and credit card spending.
- **Correlation Matrix**: Identified relationships between features to detect multicollinearity.
### 4. Train-Test Split & Feature Scaling
- **Train-Test Split**: The dataset was split into training and testing sets.
- **Feature Scaling**: Applied scaling to numerical variables for consistent model performance.
### 5. Model Training and Evaluation
**Support Vector Classifier (SVC)**
- **Model Training**: Trained an SVC model on the preprocessed data.
- **Evaluation**: The SVC model achieved an accuracy score of 97%.
 - **Classification Report**: Precision, recall, and F1-score were assessed.
 - **Confusion Matrix**: A confusion matrix was used to visualize model performance.

**DecisionTreeClassifier**
- **Hyperparameter Tuning**: Used GridSearchCV to optimize the DecisionTreeClassifier.
- **Best Parameters**: After tuning, the model achieved an improved accuracy score of 98%.
 - **Evaluation**: Precision, recall, and F1-scores were further evaluated.
 - **Confusion Matrix**: The confusion matrix was plotted to assess performance.
### 6. Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computing.
- **Matplotlib** & **Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning model building and evaluation.
- **Jupyter Notebook**: As the development environment.

### 7. Visualizations
- **Confusion Matrix**: Displayed for both the SVC and DecisionTreeClassifier models.
- **Correlation Heatmap**: Showed relationships between numerical features.
  
## Results
- **DecisionTreeClassifier Model Accuracy**: 98%

## How to Run the Project
Clone the repository: <br>
git clone https://github.com/Waseem2212/Universal-Bank-Prediction

## Conclusion
The **DecisionTreeClassifier** model, optimized through hyperparameter tuning, achieved the best result with an accuracy of **98%**. This demonstrates that decision trees are an effective tool for predicting customer behavior, especially after parameter optimization. These insights can be used by the bank for better-targeted marketing and customer service strategies.





