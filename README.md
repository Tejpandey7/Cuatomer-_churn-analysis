1. __Concept of Customer Churn:__
The customer churn is when a customer stops using a company's products or services and ending their relationship with business.Today’s competitive conditions have led to numerous companies selling the same product at quite similar service and product quality. The Churn Analysis aims to predict customers who are going to stop using a product or service among the customers. The customer churn analysis is a data mining-based work that will extract these possibilities. Customer churn, defined as the frequency at which customers cease utilizing a company’s services, poses a notable challenge within the  industry. It not only results in revenue loss but also affects customer satisfaction and loyalty. Since the cost of retaining existing customers is usually lower than acquiring new ones, firms must predict customers canceling their services before it happens, also known as churn analysis and prediction.


 2. __Goal of the project:__
 The main goal of the project is to analyze customer behavior and identify the main factor why and which type of customer are leaving the business or service. By deeply studying the data, my aim to discover patterns asnd trends that help us to understand which type of customer are more likely to churn and what kind of factors influence them to leave the service. This project is focused on data analysis using charts and basic stastistics to find meaningful insights which help the business to create better strategies to improve customer retention.

 3. Data Dictionary:\
-customerID: Unique identifier for each customer.\
-gender: Gender of the customer (Male, Female).\
-SeniorCitizen: Whether the customer is a senior citizen or not (1: Yes, 0: No).\
-Partner: Whether the customer has a partner or not (Yes, No).\
-Dependents: Whether the customer has dependents or not (Yes, No).\
-tenure: Number of months the customer has stayed with the company.\
-PhoneService: Whether the customer has a phone service or not (Yes, No).\
-MultipleLines: Whether the customer has multiple lines or not (Yes, No, No phone service).\
-InternetService: Type of internet service the customer has (DSL, Fiber optic, No).\
-OnlineSecurity: Whether the customer has online security or not (Yes, No, No internet service).\
-OnlineBackup: Whether the customer has online backup or not (Yes, No, No internet service).\
-DeviceProtection: Whether the customer has device protection or not (Yes, No, No internet service).\
-TechSupport: Whether the customer has tech support or not (Yes, No, No internet service).\
-StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service).\
-StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No internet service).\
-Contract: The contract term of the customer (Month-to-month, One year, Two year).\
-PaperlessBilling: Whether the customer has paperless billing or not (Yes, No).\
-PaymentMethod: The payment method of the customer (Electronic check, Mailed check, Bank transfer, Credit card).\
-MonthlyCharges: The amount charged to the customer monthly.\
-TotalCharges: The total amount charged to the customer.\
-Churn: Whether the customer churned or not (Yes, No).

4. __Data Sources:__
Customer Churn Dataset from  Kaggle\
sources : https://www.kaggle.com/datasets/blastchar/telco-customer-churn\
https://www.kaggle.com/datasets/rashadrmammadov/customer-churn-dataset\

5.__Data Summary:__ There are two datasets\
First data records: rows = 7043 and column = 21\
Second data records: rows = 5880 and column = 21



 6.__Project Setup:__ 
 Data Analysis with VS Code & Jupyter Notebook\
  a.Prerequisites\
 b. Python 3\
 c. Visual Studio Code\
 d. Git \
 e. Internet connection to install dependencies\
3. Clone or download the project

git clone https://github.com/Tejpandey7/Cuatomer-_churn-analysis\
cd your-repo-name\
5. Create a virtual environment\
 Open PowerShell, git bash VS or  Code terminal and run:\
  __For windows__\
 python -m venv venv\
6. Activate the virtual environment\
 .\venv\Scripts\activate\
 __For macOS/Linux__\
 python3 -m venv venv\
source venv/bin/activate\
You’ll see (venv) in your terminal.\
7. Install required packages\
pip install -r requirements.txt\
8. If requirements.txt is missing or empty, you can install basic packages manually\
pip install pandas matplotlib seaborn jupyter\
9.  Launch Jupyter Notebook in VS Code\
 Open the project folder in VS Code\
 Make sure the Python extension is installed\
 Open churn_analysis.ipynb\
 In the top-right corner, select the kernel as Python (venv)\
Run the notebook cells to explore the data\
Open the project in VScode  or Jupyter Notebook.\
10.  Load and Explore the Data


__Load the dataset from the  folder using pandas.__

Conduct  EDA to visualize data  distributions, check for missing values, and understand correlations.\
Use visualizations such as histograms, bar charts, and piechart etc.


11. Data Cleaning and Preprocessing

Handle missing oandr inconsistent data.\
Convert categorical variables to numerical if needed


12.  Feature Engineering:\
Create a features if helpful (e.g., tenure groups, etc)

 14. __Key Findings__\
Overall churn rate is approximately 36.9%, indicating a significant customer loss.\
Customers with shorter tenure are more likely to churn.\
Month-to-month contracts have the highest churn rate.\
Users with electronic check payment method are more likely to churn.\
Senior citizens and customers with tech support unavailable are at higher risk of churning.


13.  Insights and Recommendations:\
Identify the top factors contributing to customer churn.\
Offer incentives  to new customers in their early tenure.\
Promote long-term contracts by offering discounts or added benefits.\
Improve customer support and reduce service issues.\
Investigate ways to transition customers away from electronic check payments.



15.  References:\
Pandas documentation\
Python documentation\
Matplotlib documentaton\
Seaborn Documentation\
Google\
Chatgpt\
git\
Kaggle