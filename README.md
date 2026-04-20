Customer Shopping Behavior Analysis
Overview
This project analyzes customer shopping behavior to uncover patterns in spending, product preferences, and customer segments. The goal is to turn raw transaction data into clear insights that can support better business decisions. The analysis is based on a dataset of around 3,900 transactions with 18 features .
Dataset
The dataset includes customer demographics, purchase details, shipping methods, discounts, ratings, and subscription status.
Key highlights:


~3,900 purchase records

18 total features

Average spend: ~$59.76

Average rating: ~3.75 




Tools & Technologies

Python (pandas, numpy, matplotlib, seaborn)

SQL (PostgreSQL, MySQL, SQL Server)

Power BI (dashboard and visualization)

Gamma (presentation slides)
Jupyter Notebook 


Project Steps
1. Data Loading & Exploration


Loaded dataset using pandas


Used df.info() and df.describe() to understand structure and summary stats



2. Data Cleaning & Feature Engineering


Handled missing values such as ratings


Created new features like age_group and purchase_frequency_days


Standardized column names using snake_case


Removed unnecessary columns



3. Database Integration


Loaded cleaned dataset into a SQL database


Connected Python to PostgreSQL/MySQL/SQL Server



4. SQL Analysis


Segmented customers into new, returning, and loyal


Analyzed revenue by gender, category, and shipping type


Evaluated product performance and discount usage


Ranked top products using window functions



5. Dashboard Development


Built an interactive Power BI dashboard


Added filters for gender, category, subscription, and shipping


Displayed key KPIs like revenue, average spend, and customer counts 



6. Reporting & Presentation


Created a written report summarizing insights


Built a presentation using Gamma to communicate results clearly


Dashboard
The Power BI dashboard provides a quick view of key metrics and trends. It allows users to filter data by different attributes, compare revenue across segments, and identify high-performing categories and customer groups.
Key Results


Male customers generated about 2× more revenue than female customers


Express shipping users spent slightly more on average


Some products rely heavily on discounts, which may impact profit margins


Most customers fall into the loyal segment, with fewer new customers


Younger age groups contributed the most revenue 


Business Recommendations


Improve subscription offerings to increase retention


Build stronger loyalty programs for repeat customers


Reevaluate discount strategies to protect margins


Focus marketing on high-value customer segments





How to Run the Project


Clone the repository and open the project folder


Install required Python libraries such as pandas, numpy, matplotlib, seaborn, sqlalchemy, and psycopg2


Run the Python notebook or script to load and clean the data


Set up a SQL database and update the connection settings


Load the dataset into the database and run SQL queries


Open the Power BI file to explore the dashboard


Final Note
This project shows a full data analytics workflow, starting from raw data and ending with business insights. It highlights skills in data cleaning, SQL, visualization, and storytelling, which are all important for data analyst roles.
