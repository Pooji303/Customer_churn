# *Customer Churn Prediction – PRCL-0017*

## *Project Overview*  
The *Customer Churn Prediction* project focuses on analyzing customer behavior and building predictive models to identify customers who are likely to churn. By understanding churn drivers, businesses can take proactive measures to retain customers and improve overall customer satisfaction. This project uses real-world customer data to deliver valuable business insights and a deployable machine learning solution.

---

## *Problem Statement*

### *Task 1: Data Analysis & Business Insights*
- Conduct an in-depth *Exploratory Data Analysis (EDA)* to understand customer behavior.
- Identify trends, patterns, and key factors contributing to customer churn.
- Apply *statistical analysis and data visualization* to derive actionable insights for business improvement.

### *Task 2: Churn Prediction Modeling*
- Develop a *supervised machine learning model* to classify churn-prone customers.
- Train and evaluate models including *Logistic Regression, Decision Tree, and Random Forest* classifiers.
- Improve performance using *feature selection, scaling, and cross-validation*.

### *Task 3: Model Performance & Comparison*
- Evaluate models using metrics like *Accuracy, Precision, Recall, F1-score, and ROC-AUC*.
- Analyze *feature importance* to understand what drives churn.
- Select the most robust model for deployment based on predictive power and interpretability.

### *Task 4: Business Recommendations*
- Use model insights to create targeted strategies for retention.
- Propose enhancements to *customer support*, *ticket prioritization*, and *touchpoint personalization* for high-risk customers.

---

## *Dataset Information*

The dataset includes customer interaction and demographic details. Key features include:

| *Feature Name*                | *Description*                          |
|------------------------------|----------------------------------------|
| *Customer_Age*               | Age of the customer                    |
| *Gender*                     | Gender identity                        |
| *Dependent_count*           | Number of dependents                   |
| *Education_Level*           | Customer's education level             |
| *Marital_Status*            | Marital status of the customer         |
| *Income_Category*           | Annual income range                    |
| *Card_Category*             | Type of credit card held               |
| *Months_on_book*            | Duration of relationship with the bank |
| *Total_Relationship_Count* | Number of products held                |
| *Contacts_Count_12_mon*    | Number of customer service calls       |
| *Churn_Flag*                | Target variable (1: Yes, 0: No)        |

*Note:* The dataset has been cleaned, encoded, and transformed for analysis and modeling.

---

## *Repository Structure*

├── data/ │ 
├── raw/ # Original customer data │
└── processed/ # Cleaned and prepared datasets │
├── notebooks/ │ 
├── PRCL-0017.ipynb # Full pipeline: EDA, Modeling, Insights │
├── src/ │
├── data_processing.py # Scripts for cleaning and transformation │
├── model_training.py # Scripts for training and evaluating models │
└── utils.py # Helper functions │
├── reports/ │
├── churn_analysis.pdf # Business analysis and key insights │
└── summary.md # Project findings and recommendation summary


---

## *Technologies Used*

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Models Used:** Logistic Regression, Decision Tree, Random Forest  
- **Analysis Focus:** Feature importance, business impact, and actionable insights

---

## *Results & Key Findings*

- The model helped identify **key customer behaviors that indicate potential churn**, enabling better targeting for retention strategies.
- Top churn indicators identified:
  - **Low number of product holdings** (*Total_Relationship_Count*)
  - **Frequent customer service calls** (*Contacts_Count_12_mon*)
  - **Short relationship duration with the company** (*Months_on_book*)
  - **Customers with lower income and education levels**
- These findings can help businesses:
  - Flag at-risk customers for priority outreach
  - Customize offers and touchpoints for customers showing early signs of churn
  - Improve service quality by reducing unnecessary customer contacts

---

## *Next Steps & Future Enhancements*

- Deploy the churn prediction model into a real-time environment for live monitoring.
- Integrate churn signals with CRM tools for proactive engagement strategies.
- Build a Power BI dashboard to visualize and monitor customer churn trends, segment performance, and intervention impact.
