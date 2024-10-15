# Portfolio-Projects
Aspiring Business Analyst, Seeking entry-level opportunities in Business Intelligence / Data Analysis. I'm eager to join an organisation that fosters skill development and offers a positive environment for applying these skills to improve business results.

In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

## 1. Market Trend Analysis
**Code:** [`Market Trend Analysis.ipynb`](https://github.com/VishakhaMann/Portfolio-Projects/blob/aa8cad9b322f06d418d4fad911e4b3722b158236/Market%20Trend%20Analysis.ipynb)

### Objective
The goal is to analyze the provided data set to identify the root causes of the issue regarding the inefficiency of recent marketing campaigns and recommend data-driven solutions.

**Description**: The project analyzed a dataset of marketing campaigns accepted by customers, which included features such as income, recency, complaints, response, marital status, amount spent on various products, campaigns accepted, and other family demographics.

**Skills**: data cleaning, data analysis, data visualization.

**Technology**: Python, Pandas, Numpy, Seaborn, Matplotlib.

**Results**: 
1. Advertising Campaign Acceptance:
Acceptance is positively correlated with income and negatively correlated with having kids/teens.
Suggested Action: Develop two targeted advertising campaign streams: one for high-income individuals without kids/teens, and another for lower-income individuals with kids/teens.

2. Product Success:
The most successful products are wines and meats, as these categories show the highest average customer spending.
Suggested Action: Enhance advertising efforts to promote less popular items, leveraging the success of wines and meats as benchmarks.

3. Channel Performance:
Underperforming channels include deals and catalog purchases, with the average customer making fewer purchases through these methods. Conversely, the best-performing channels are web and store purchases, where customers tend to make the most purchases.
Suggested Action: Concentrate advertising campaigns on the more successful channels (web and store) to maximize customer reach and engagement.

## 2. Customer-Churn-Banking
**Code:** [`Customer-Churn-Banking.ipynb`](https://github.com/VishakhaMann/Portfolio-Projects/blob/563c179ece36bb32a24990152016e33aac019bcd/Customer-Churn-Banking.ipynb)

### Objective
The objective of this analysis is to explore the "Bank Customer Churn" dataset to identify the factors contributing to customer attrition and provide actionable insights for improving customer retention strategies

**Description**: The dataset utilized in this analysis includes details about bank customers, such as demographic information, credit score, account balance, tenure, and other attributes. The target variable, "Exited," indicates whether a customer has churned (1) or remained (0).

**Skills**: data analysis, data visualization.

**Technology**: Python, Pandas, Numpy, Seaborn, Matplotlib.

**Results**: 
**A-> Gender and Churn:** Female customers have a higher churn rate (25.1%) than males (16.5%).

- **Recommendation:** Launch targeted marketing campaigns for women, such as beauty product vouchers for loyalty.

**B-> Geography and Churn:** Churn rates are highest in Germany (32.4%), followed by Spain (16.7%) and France (16.2%).

- **Recommendation:** Conduct localized surveys in Germany to identify pain points and offer tailored loyalty programs.

**C-> Age Group and Churn:** The 50-60 age group shows the highest churn (56.2%), while under-30s have the lowest (7.5%).

- **Recommendation:** Provide tailored support for older customers to assist with digital banking.

**D-> Number of Products and Churn:** The relationship between product count and churn needs further analysis.

- **Recommendation:** Improve the app/website dashboard to help customers easily view their products.

**E-> Credit Card and Balance:** Credit card ownership & Balance does not significantly impact churn rates.

**F-> Activity Status and Churn:** Active customers have lower churn rates.

- **Recommendation:** Increase engagement through personalized notifications and exclusive offers, especially for older customers and women.


## 3. Academic-Performance-of-Students
**Code:** [`Academic-Performance-of-Students.ipynb`](https://github.com/VishakhaMann/Portfolio-Projects/blob/a0479ca15cf0cc639861244dbc4c2c146ebec06e/Academic-Performance-of-Students.ipynb)

### Objective
The goal of this study is to gain a deeper understanding of how various contextual elements influence the educational outcomes and achievements of students.

**Description**: The project focused on analyzing a dataset of academic performance of students. The dataset included gender, race/ethnicity,	parental level of education,	lunch,	test preparation course,	math score,	reading score,	writing score .The project involved loading the data, cleaning and preprocessing it, performing exploratory data analysis (EDA).

**Skills**: data cleaning, data analysis, data visualization.

**Technology**: Python, Pandas, Numpy, Seaborn, Matplotlib.

**Results**: Using Python functions the analysis revealed that 
1. Economic disparities may influence student achievement, as data shows that students from households with higher incomes, who are more likely to select standard lunches, often demonstrate greater academic success. 
2. Race/ehnicity/Gender has no major influence on the academic performance of students.
3. Higher parental level of education has a positive impact on the academic performance of students.


## 4.  Travel Trip Data Analysis
**Code:** [`travel-trip-analysis.ipynb`](https://github.com/VishakhaMann/Portfolio-Projects/blob/7642a1a791e8dbbead66aa84c617ba22ee97a110/travel-trip-analysis.ipynb)

**Objective**:
To examine the effects of various characteristics on trip types and travel costs and create meaningful visualizations from the travel trip dataset.

**Description**:
The dataset utilized in this analysis includes details about travel trips, such as trip destination, start and end dates, traveler demographics (age, gender, nationality), accommodation types and costs, transportation types and costs, and trip duration.

**Skills**:
Data analysis, data visualization.

**Technology**:
Python, Pandas, Plotly, NumPy.

**Results**:
A -> Result - Average cost by accommodation type:
Hotels and Resorts rank as the most expensive accommodation types.

Recommendation of Result - A:
Travelers looking to reduce accommodation costs should consider Airbnb or villas over hotels and resorts.

B -> Result - Average cost by transportation type:
Flights are the most common mode of transport and tend to have the highest associated costs, followed by trains.

Recommendation of Result - B:
For budget-conscious travelers, using train or alternative transportation modes can help save on travel costs.

C -> Result - Number of travelers by gender:
The dataset shows that male and female travelers are nearly equally represented, with a slight lead in trips taken by female travelers.

Recommendation:
Travel agencies can design travel packages that equally appeal to both male and female travelers, taking into account the relatively balanced distribution of genders.
