# Customer Purchase and Feedback Analysis

## Project Overview

This project focuses on analyzing customer purchase patterns, product performance, revenue trends, and customer satisfaction to help the business make data-driven decisions.Using real purchase and feedback data, the goal was to understand which products perform best, which customers groups contribute the most revenue, and what factors influence customer satisfaction.

## Datasets

Fields:
- Customer_ID
- Customer_Name
- Gender
- Age 
- Region
- Product_Category
- Product_Name
- Quantity
- Unit Price
- Purchase_Date
- Payment_Method
- Rating(1-5)
- Customer_Feedback

## Tools & Technologies Used
- **Python** - The main language used for analysis.
- **Pandas** - Used for data cleaning, transformation, and analysis.
- **Numpy** - Used jfor numerical calculations.
- **Matplotlib** - Used to create visual charts and graphs.
- **Visual Studio Code (VS Code)** - Primary environment used to write and run the analysis.
- **Jupyter Notebook (.ipynb)** - Used for step-by-step execution, visual output, and documentation.
- **Git & Github** - Used for version control and sharing the project.

## Data Preparation
To ensure the dataset was ready for analysis, several cleaning and processing steps were performed.The Process included:
- Checked and identified missing values in the dataset.
- Filled missing values in the rating column using the average rating.
- Converted the Purchase Date column into a proper datetime format.
- Created calculated fields including: **Purchase Amount = UnitPrice * Quantity**
- Cleaned and formatted the dataset to make it ready for analysis and visualization.
## Analysis & Visualizations

### Question 1 : Which products have the highest customer purchase frequency?

![Q1](/Images/Q1.png)
**Key Insights**
- **HP Keyboard** and **SanDisk 128GB Pendrive** are the top-selling products,each with the **highest purchase quantity**, indicating strong customer demand.

- Mid-range electronics like **Vivo V27** and **Dell Inspiron 15** also show high sales, suggesting consistent preference for tech-related items.

- Lower-ranked products such as **Apple Watch Series 8, ASUS ROG Strix, and Noise ColorFit Pro** still maintain steady sales but have noticeably lower quantity compared to the top products.

### Q2: What factors influence customer satisfaction ratings?

![Q2](/Images/Q2.png)

**Key Insights**
- Products like **Acer Aspire, Oppo Reno 10, MacBook Air M2, AND Lenovo ThinkPad** have the highest average ratings (close to 5), indicating very strong customer satisfaction.
- Mid-range products such as **Sony WH-1000XM4,Vivo V27,Boat Rockerz 550, and Amazfit GTS 4** show average ratings betwwen 4-4.5, reflecting consistently good performance.
- Lower-rated products like **Noise ColorFit Pro, HP Keyboard,JBL Tune 760NC , and Dell Monitor** have ratings around 3-3.5,suggesting potential customer dissatisfaction or areas where improvements may be needed.

### Q3: Is there a relationship between customer spending and feedback sentiment?

![Q3](/Images/Q3.png)

**Key Insights**

- **Higher purchase amount does not guarantee higher rating,** meaning satisfaction is not based on price.
- Ratings mostly remain between **4.0-5.0 range**, showing generally positive customer experience across products.
- Lower ratings (3.0-3.5) appear across both low and high purchase amounts,indicating some products underperform expectations regardless of price.

### Which customer segments contribute the most revenue?

![Q4](/Images/Q4.png)

**Key Insights**

- **Age group 30-35 contributes the highest revenue (28.7%)**, making them the most valuable customer segment.
- **Customers aged 25-30 and 35-40 also contribute significantly(22-25%)**, showing that 25-40 is the code revenue-driving range.
- **Young Adults (18-25) contribute less (13%),** indicating they buy less frequently or spend lower amounts.
- **Revenue from customers aged 40+ is very low (10%)**,suggesting the brand appeals more to younger working adults.

### How does company's revenue change over each day?

![Q5](/Images/Q5.png)

**Key Insights**

- Revenue fluctuates heavily day-to-day, showing both **high-spike days** and **very low-sale days.**
- A few specific days show **extremly high revenue**, indicating promotional offers,bulk purchases or seasonal demand.
- Mid-month and end-month both slow noticeable peaks, suggesting periodic buying patterns.

## Conclusion
The analysis shows that a few products generate most of the sales, and customers aged 30-35 are the most valuable segment. Overall customer satisfaction is high, but some products need improvement based on lower ratings. There is no clear link between higher spending and higher satisfaction. These insights can help the business focus on promoting best-selling products, improving low-rated items, and targeting the right customer segment.