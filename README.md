📊 E‑Commerce Sales Analysis (Target – Brazil) using Python & SQL
📌 Project Overview
This project is an end‑to‑end data analysis case study built using MySQL and Python, based on a large real‑world e‑commerce sales dataset representing Target’s Brazilian operations.
The dataset contains ~100,000 orders (2016–2018) and mirrors a production‑grade retail database. The objective of this project is to answer practical business questions by combining SQL querying, data transformation in Python, and clear visual storytelling.
This project is designed to demonstrate core Data Analyst skills rather than just code syntax.
________________________________________
🗂️ Dataset Overview
The dataset represents Target’s e‑commerce operations in Brazil and includes detailed information on: - Customer demographics and locations - Orders and order lifecycle timestamps - Order items and product attributes - Payments and transaction behavior - Sellers and logistics information
The data is provided across multiple CSV files and loaded into MySQL for relational analysis.
📁 Tables Used
•	customers
•	orders
•	order_items
•	products
•	payments
•	sellers
•	geolocation
Each table is connected using realistic primary and foreign key relationships, enabling multi‑table joins and aggregations.
________________________________________
🛠️ Tech Stack
•	Database: MySQL 8.0
•	Programming Language: Python 3
•	Libraries:
o	pandas (data manipulation)
o	mysql‑connector‑python (database connection)
o	matplotlib (base visualizations)
o	seaborn (statistical plots)
•	Tools:
o	MySQL Workbench
o	Jupyter Notebook
________________________________________
🔍 Key Business Questions Answered
1️⃣ Customer & Geography Analysis
•	Identified unique customer cities
•	Analyzed customer geographic distribution using SQL and Pandas
2️⃣ Order Trend Analysis
•	Calculated monthly order counts for 2018
•	Identified seasonal and volume trends in customer purchases
3️⃣ Order Composition Analysis
•	Calculated number of items per order
•	Joined orders and order_items tables to understand order size patterns
4️⃣ Product‑Level Exploration
•	Explored product categories and attributes
•	Analyzed how products contribute to overall order volume
________________________________________
📈 Data Visualizations
The project includes visualizations such as: - Monthly order volume (2018) - Order item count distribution - Category‑level summaries
All charts are created using Seaborn and Matplotlib, with careful attention to: - Correct categorical ordering (e.g., months) - Readability and labeling - Business‑friendly interpretation
________________________________________
🧠 Key Skills Demonstrated
•	Writing optimized SQL queries using:
o	JOINs
o	GROUP BY
o	Aggregate functions
o	Date functions
•	Connecting MySQL with Python
•	Transforming SQL outputs into Pandas DataFrames
•	Debugging common SQL and database issues
•	Translating raw data into business insights
________________________________________
🚀 How to Run the Project
1.	Clone this repository
2.	Import the CSV files into MySQL
3.	Create the ecommerce database schema
4.	Update database credentials in the Jupyter Notebook
5.	Run the notebook cells step by step
git clone <repository‑url>
________________________________________
📌 Future Enhancements
•	Revenue and payment method analysis
•	Customer lifetime value (CLV)
•	Delivery time and logistics performance
•	Advanced SQL (CTEs, window functions)
•	Interactive dashboards
________________________________________
👤 Author
Salman Naeem
Data Analyst | SQL | Python | Data Visualization
________________________________________
⭐ Acknowledgement
This project is part of my hands‑on learning journey to build strong foundations in SQL‑driven analytics and Python‑based data analysis using realistic, production‑style datasets.
If you find this project useful, feel free to ⭐ star the repository.
