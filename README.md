
# Telco Customer Churn Analysis and Prediction

## Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses such as telecommunications companies. Losing customers directly affects revenue and growth, making it important to understand **why customers leave and how to predict churn before it happens**.

This project performs a complete **data analysis and machine learning workflow** to identify the key factors influencing customer churn and to build predictive models that can classify whether a customer is likely to leave the service.

The analysis includes **data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning modeling** to generate insights and predictive capability.

---

## Objectives

The main goals of this project are:

- Analyze customer data to understand churn patterns
- Identify factors that contribute to customer churn
- Prepare and clean data for machine learning models
- Build predictive models to classify churned customers
- Evaluate model performance and compare different algorithms

---

## Dataset

The dataset used in this project is the **Telco Customer Churn dataset**, which contains customer information such as:

- Customer tenure
- Monthly charges
- Total charges
- Contract type
- Payment method
- Internet services
- Customer churn status

Each record represents a customer and whether they have **churned (left the service) or remained active**.

---

## Tools and Technologies

The project was developed using the following tools and libraries:

- **Python**
- **Pandas** – data manipulation and cleaning
- **NumPy** – numerical computations
- **Matplotlib & Seaborn** – data visualization
- **Scikit-learn** – machine learning modeling
- **Jupyter Notebook** – interactive analysis environment

---

## Project Workflow

The project follows a structured data science workflow:

### 1. Data Loading
The dataset is imported into a Pandas DataFrame for analysis.

### 2. Data Cleaning
Data preprocessing includes:

- Handling missing values
- Correcting data types
- Removing unnecessary columns

### 3. Exploratory Data Analysis (EDA)
EDA is performed to understand customer behavior and identify relationships between variables and churn.

Visualizations include:

- Churn distribution
- Monthly charges vs churn
- Contract type analysis
- Customer tenure patterns

### 4. Feature Engineering
Categorical variables are encoded using **one-hot encoding** to prepare the data for machine learning models.

### 5. Model Building
Several machine learning algorithms are trained to predict customer churn, including:

- Logistic Regression
- Decision Tree
- Random Forest

### 6. Model Evaluation
Models are evaluated using:

- Accuracy score
- Confusion matrix
- Classification report

This allows comparison of model performance and identification of the best-performing model.

---

## Key Insights

The analysis reveals several important patterns:

- Customers with **month-to-month contracts** are more likely to churn.
- **Higher monthly charges** increase the probability of churn.
- Customers with **longer tenure** are less likely to leave the service.
- Contract type and billing methods significantly influence churn behavior.

These insights can help telecom companies **design retention strategies and reduce customer loss**.

---

## Project Structure
telco-customer-churn-analysis
│
├── data
│ └── Telco_customer_churn.xlsx
│
├── notebook
│ └── telco_customer_churn_analysis.ipynb
│
├── requirements.txt
│
└── README.md


---

## How to Run the Project

To run this project locally:

### 1. Clone the repository
git clone https://github.com/Abdihakim70/telco-customer-churn-analysis.git


### 2. Install dependencies
pip install -r requirements.txt

### 3. Open the notebook
jupyter notebook

Then open:
notebook/telco_customer_churn_analysis.ipynb

---

## Future Improvements

Possible future improvements for this project include:

- Hyperparameter tuning for machine learning models
- Feature importance analysis
- Implementing advanced algorithms such as **XGBoost or Gradient Boosting**
- Building an interactive **Power BI or Tableau dashboard**
- Deploying the model as a simple web application

---

## Author

**Abdihakim Ali Abdi**

Data Analyst with a background in Information Technology, focused on data analysis, data visualization, and machine learning projects.

---

## License

This project is for educational and portfolio purposes.




