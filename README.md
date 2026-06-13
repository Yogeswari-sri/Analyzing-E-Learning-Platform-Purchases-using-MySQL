
#🧠 Analyzing-E-Learning-Platform-Purchases-using-MySQL
🏷️ Tagline
“Transforming raw purchase data into actionable insights for smarter e‑learning decisions.”
📋Project Overview
This project demonstrates how Data Analytics concepts can be applied using MySQL to analyze purchase behavior on an e‑learning platform. It covers database design, data exploration, analytical queries, and insight generation — all structured around real‑world learning and business scenarios.

🎯Objectives
Build a relational database with learners, courses, and purchase records.

Perform JOIN operations to explore relationships between tables.

Execute analytical queries (Q1–Q12) to uncover spending patterns, top courses, and category performance.

Apply CTE, CASE, Views, and NULL handling for advanced SQL analysis.

Derive actionable insights and recommendations for marketing and course optimization.

🧩 Analytical Dimensions

| Type | Purpose | Example Insights |
| --- | --- | --- |
| **Descriptive** | Summarize what happened | Identify top‑performing courses and total revenue trends |
| **Diagnostic** | Explain why it happened | Promotions and repeat buyers drive spikes in purchases |
| **Predictive** | Forecast future outcomes | High‑value learners will continue to dominate spending |
| **Prescriptive** | Recommend actions | Focus marketing on Technology & Business categories |

🧮Key SQL Concepts Used
Database Design: Primary & Foreign Keys, Data Types

Joins: INNER, LEFT, RIGHT for multi‑table exploration

Aggregations: SUM(), COUNT(), AVG(), GROUP BY

Subqueries & Correlated Subqueries: Comparative spending analysis

CTE & CASE: Learner segmentation and classification

Views: Category performance summary

NULL Handling: IFNULL(), COALESCE() for clean reporting

📊Key Insights
Revenue concentrated around high‑demand courses.

Technology and Business categories lead in both revenue and learner reach.

Beginner courses drive volume; advanced courses yield higher per‑purchase revenue.

A small group of learners contributes most of the spending.

Seasonal spikes occur during promotions and exam periods.

💡Recommendations
Focus marketing on top‑performing categories.

Target cross‑category learners with bundled offers.

Improve visibility of under‑purchased courses via discounts and trials.

Retain high‑value learners through loyalty programs.

Encourage exploration with curated learning paths.

🛠️ Tools & Technologies
MySQL for database creation and analytics

SQL Workbench / VS Code for query execution

Excel / Power BI (optional) for visualization

GitHub for documentation and version control

📁 Repository Structure

📂 Data_Analytics/
 ├── SQL_Scripts/
 │   ├── database_setup.sql

 <img width="1600" height="850" alt="s1" src="https://github.com/user-attachments/assets/cdea52ad-6d1f-426e-ba3f-3be71144d701" />

 <img width="1600" height="829" alt="s2" src="https://github.com/user-attachments/assets/5fa8e325-693a-433c-9ff8-393cda3bc0f3" />

 <img width="1583" height="821" alt="s3" src="https://github.com/user-attachments/assets/50ffc6ed-9d04-43af-8e8d-0d9bdeb57298" />

 │   ├── data_exploration.sql


 <img width="1596" height="814" alt="s4" src="https://github.com/user-attachments/assets/bac3f948-22eb-4e5c-9825-61f030749efb" />

<img width="1600" height="822" alt="s5" src="https://github.com/user-attachments/assets/ce100257-b1fb-4f53-8f16-da1aceb1165f" />

<img width="1600" height="799" alt="s6" src="https://github.com/user-attachments/assets/8deaf518-df7d-4cd7-9ab0-f5811dbb95cd" />

<img width="1600" height="811" alt="s7" src="https://github.com/user-attachments/assets/e6676ac7-69f5-45a2-8403-f6772745a62b" />

<img width="1600" height="819" alt="s8" src="https://github.com/user-attachments/assets/ef381f69-edea-40b6-9041-af86d9648e9e" />

 │   ├── analytical_queries.sql

 <img width="1590" height="795" alt="s10" src="https://github.com/user-attachments/assets/386eaf2c-62ef-416f-8b65-8cb8827ec297" />

<img width="1598" height="831" alt="s12" src="https://github.com/user-attachments/assets/98d98043-3281-40ed-80ff-89ef06c9e936" />


 │   └── views_and_cte.sql
 

<img width="1600" height="818" alt="s14" src="https://github.com/user-attachments/assets/df373549-8149-4932-88ca-6d2bce366a27" />

<img width="1600" height="822" alt="s15" src="https://github.com/user-attachments/assets/4d01ec98-bd93-4acf-8c68-4710c1a52c24" />

 <img width="1600" height="849" alt="View1" src="https://github.com/user-attachments/assets/a5d8fc25-7ecd-4f4e-bb2a-cf6e6fe10fc0" />

 ├── Report/
 │   └── One_Page_Summary_Report
 Key Insights
Revenue is concentrated around a few high‑demand courses.

Technology and Business categories generate the highest revenue and attract the most unique learners.

Beginner‑level courses drive purchase volume, while advanced courses yield higher per‑purchase revenue.

A small group of learners contributes disproportionately to overall spending.

Seasonal spikes occur during promotions and exam preparation periods.

Some courses remain unpurchased, indicating low visibility or relevance.

Brief Recommendations
Focus marketing on top‑performing categories (Technology, Business).

Target cross‑category learners with bundled offers or personalized recommendations.

Improve visibility of under‑purchased courses through discounts, free trials, or better placement.

Retain high‑value learners with loyalty rewards or subscription models.

Encourage diversification with curated learning paths combining beginner and advanced courses.

Analytics Perspectives
1️⃣ Descriptive Analysis
Summarizes what happened:

Identified top‑performing categories and high‑demand courses.

Quantified total revenue, purchase volume, and learner spending patterns.

Highlighted seasonal spikes and unpurchased courses.

2️⃣ Diagnostic Analysis
Explains why it happened:

Promotional and exam periods drive purchase peaks.

Repeat buyers inflate revenue in certain categories.

Low visibility and limited relevance cause some courses to remain unpurchased.

3️⃣ Predictive Analysis
Forecasts what may happen next:

High‑value learners will continue to dominate spending.

Promotional campaigns will trigger future purchase surges.

4️⃣ Prescriptive Analysis
Recommends what actions to take:

Strengthen marketing for Technology and Business courses.

Use personalized bundles to increase cross‑category purchases.

Offer discounts and trials to boost under‑purchased course visibility.

Implement loyalty programs to retain high‑value learners.

Design learning paths combining beginner and advanced levels to expand engagement.
 ├── README.md




