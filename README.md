🛒 Supermarket Sales – Exploratory Data Analysis (EDA)

     This project dives into real supermarket transaction data to get a grip on product demand, revenue trends, and how discounts influence what customers buy. I'm analyzing a sample of 50,000 records to ensure  get the best performance.

🔧 Feature Engineering

     I created the following new attributes from the raw data:

New Feature Description

     Revenue	Calculated as Quantity Sold multiplied by Unit Selling Price
     Datetime	A combined Date & Time column
     Year, Month, Weekday, Hour	Extracted from the Datetime
     Sale or Return	Identified the type of transaction

📊 Visualizations Performed

Visualization Purpose

     Distribution of Quantity Sold to grasp demand levels
     Distribution of Revenue	to see typical transaction values
     Avg Revenue by Weekday	to find the best days for revenue
     Avg Revenue by Hour	to identify peak revenue times
     Sale vs Return Count to analyze the ratio of purchases to returns
     Revenue vs Discount	to determine if discounts boost spending

🧠 Key Insights

📌 1) Quantity Sold Distribution

     Most customers tend to buy small to medium quantities, reflecting typical household shopping habits.

     Very large purchases are uncommon and happen only occasionally.

📌 2) Revenue Distribution

     The majority of transactions yield moderate revenue figures.

     Only a few transactions bring in very high revenue, suggesting that bulk buyers are few and far between.

📌 3) Revenue by Weekday

     We see a slight uptick in revenue on weekends (Saturday & Sunday).

     Weekdays, on the other hand, maintain consistent transaction values.

📌 4) Revenue by Hour of the Day

     Evening hours (around 18:00–22:00) are when revenue peaks.

     Afternoon hours also show higher transaction values compared to the early morning.

📌 5) Sale vs Return

     The dataset is primarily made up of regular sale transactions.

     Returns are minimal, indicating customer satisfaction and product acceptance.

📌 6) Discount vs Revenue

     Transactions with discounts generally have higher average revenue, suggesting that customers tend to spend more when there are offers available.

     Discounts seem to encourage larger purchases.

🛠 Tech Stack

Tool/Library Usage

Python Analysis & Computation
Pandas Data Cleaning & Feature Extraction
Matplotlib Visualizations
Jupyter Notebook Development Environment

🚀 How to Run This Project

pip install pandas matplotlib
jupyter notebook

Open the notebook and run each cell step-by-step.

👩‍💻 Internship Details

Organization: CodeAlpha
Domain: Data Analytics
Task: Exploratory Data Analysis
Intern: Kavya Dharshini S
