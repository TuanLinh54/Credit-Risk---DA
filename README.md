
# Credit Risk Modeling in Python 🏦

## Overview 🔥

This project focuses on analyzing data to assess **credit risk** of customers for financial institutions or banks. Through exploratory data analysis (EDA), data preprocessing, and modeling, the goal is to build a system that predicts the likelihood of a customer becoming a credit risk.

## Dataset [https://drive.google.com/drive/folders/1JyzAj-llRy60zJQT41-6h1MozSutb14H?usp=sharing] 📊

The dataset consists of **3006 customers** with the following characteristics:

- **Độ tuổi**: Age of the borrower (in years).  
- **Giới tính**: Gender of the borrower (e.g., Male, Female).  
- **Tình trạng hôn nhân**: Indicates whether the borrower is single, married, divorced, etc.  
- **Trình độ học vấn**: Highest education level attained by the borrower.  
- **Tình trạng công việc hiện tại (số năm kinh nghiệm)**: Number of years the borrower has been employed.  
- **Số thành viên phụ thuộc trong gia đình**: Total number of people financially dependent on borrower.  
- **Tình trạng sở hữu nhà ở**: Indicates if the borrower owns, rents, or lives with family.
- **Thu nhập**: Monthly income of the borrower.  
- **Số tiền dự kiến vay**: The amount of money the borrower wants to borrow.  
- **Chứng minh thu nhập**: Whether the borrower can provide income documentation.  
- **Thời hạn khoản vay**: Duration of the loan in months.  
- **Tài sản thế chấp**: Indicates whether the borrower offers any assets as collateral.  
- **Chi tiêu (trung bình một tháng)**: Average monthly spending of the borrower.  
- **Mục đích vay**: Reason for applying for the loan (e.g., Education, Business, etc). 
- **Hóa đơn tiền điện**: Average monthly electricity bill of the borrower's household.
===============================================================================================
- **15 explanatory variables** (excluding customer ID)
- **7 integer variables (int64)**
- **2 float variables (float64)**
- **8 categorical variables (object)**
- Some columns contain missing values, including:
  - *Marital status*
  - *Years of work experience*
  - *Electric bill*
  - *Education level*

## Objectives 🎯

1. **Exploratory Data Analysis (EDA)**:
   - Understand distribution of numerical features such as age, income, expenses, electric bill, loan amount, loan term, number of dependents.
   - Analyze categorical features like gender, loan purpose, marital status, education, occupation, etc.
   - Visualize insights using `seaborn`, `matplotlib`.

2. **Data Preprocessing**:
   - Handle missing values using interpolation, imputation, or removal where necessary.
   - Encode categorical features using One-Hot Encoding or Label Encoding.
   - Normalize numerical features if required for modeling.

3. **Outlier Detection**:
   - Use techniques like IQR, Z-score, or models like Isolation Forest to detect and handle outliers.

4. **Model Building for Risk Prediction**:
   - Use machine learning algorithms:
     - **Logistic Regression**
     - **Random Forest**
     - **XGBoost / LightGBM**
   - Evaluate models using:
     - Confusion Matrix
     - Accuracy, Precision, Recall, F1-score
     - ROC-AUC

5. **Real-world Application**:
   - Integrate model into credit scoring systems.
   - Support lending decisions by credit departments.

## Current Progress ⚙️

✅ Completed:

- Descriptive analysis of the dataset
- Visualization of categorical and numerical data
- Initial handling of missing values

🔜 In Progress:

- Advanced outlier processing
- Machine learning model training
- Model evaluation and selection

## Tools & Libraries 🧰

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`, `xgboost`, `lightgbm`
  - `warnings`, `plotly`, `joblib`

## Next Steps 🚀

- Complete data preprocessing and model training
- Fine-tune and evaluate model performance
- (Optional) Deploy model using API or Streamlit app for demonstration
