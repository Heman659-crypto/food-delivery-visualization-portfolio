🍔 Food Delivery Business Performance – Visualization Portfolio

📊 Project Overview

This project explores the performance of a food delivery business using Python data visualization techniques. The analysis examines customer behavior, revenue performance, delivery efficiency, marketing impact, weather conditions, cuisines, cities, and order channels.

The portfolio uses a dataset containing 360 daily order batches across 8 cities, 6 cuisines, 3 order channels, and 4 weather conditions throughout 2025.

The main objective is to transform raw business data into meaningful visual insights that can support better operational and business decisions.

---

🎯 Objectives

The project aims to:

- Analyze orders and revenue trends over time.
- Compare business performance across cities.
- Explore cuisine-wise order volume.
- Understand the relationship between marketing spend and revenue.
- Analyze the impact of delivery time on customer ratings.
- Study order and revenue distributions.
- Compare customer ratings across weather conditions.
- Evaluate delivery performance across order channels.
- Analyze revenue distribution by cuisine.
- Explore order channel and weather frequency.
- Measure the effect of weather and order channels on revenue.
- Identify important relationships using a correlation heatmap.

---

📂 Dataset Information

The dataset contains 360 records and 16 columns.

Features

Column| Description
"Order_Batch_ID"| Unique identifier for each order batch
"Date"| Date of the order batch
"Month"| Month of the order
"Day"| Day of the week
"City"| City where orders were placed
"Cuisine"| Type of cuisine
"Order_Channel"| Platform used to place the order
"Weather"| Weather condition
"Orders"| Number of orders
"Average_Order_Value"| Average value per order
"Revenue"| Total revenue generated
"Marketing_Spend"| Marketing expenditure
"Discounts"| Discounts provided
"Avg_Delivery_Minutes"| Average delivery time
"Customer_Rating"| Average customer rating
"Repeat_Customer_Percent"| Percentage of repeat customers

---

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

📈 Visualizations Included

1. Orders and Revenue Over Time

Line plots were used to analyze how orders and revenue changed throughout the year.

Insight: Orders and revenue fluctuate over time and generally move together, showing that order volume is a major driver of revenue.

---

2. City-wise Revenue Performance

A bar chart compares average revenue across different cities.

Insight: Bengaluru and Delhi show stronger revenue performance, while Kochi and Jaipur are among the lower-performing cities.

---

3. Cuisine-wise Order Volume

Average order volume was compared across different cuisine categories.

Insight: Order volume is relatively balanced across cuisines, with only small differences between the highest and lowest-performing categories.

---

4. Marketing Spend vs Revenue

A scatter plot was used to examine the relationship between marketing investment and revenue.

Insight: The relationship is weak, with a correlation of approximately 0.20, suggesting that higher marketing spend alone does not guarantee higher revenue.

---

5. Delivery Time vs Customer Rating

A scatter plot examines the impact of delivery speed on customer satisfaction.

Insight: This is the strongest relationship in the dataset, with a correlation of approximately -0.88. Longer delivery times are strongly associated with lower customer ratings.

---

6. Distribution of Orders and Revenue

Histograms were used to understand the distribution of business performance metrics.

Insight: Both orders and revenue are approximately bell-shaped with slight right skewness.

---

7. Customer Rating by Weather

A box plot compares customer ratings across weather conditions.

Insight: Customer ratings are highest during clear weather and noticeably lower during rainy conditions.

---

8. Delivery Time by Order Channel

Delivery performance was compared across different ordering channels.

Insight: App orders have the fastest median delivery time, while Partner Platform orders are slower.

---

9. Revenue Distribution by Cuisine

A violin plot was used to examine the distribution and variation of revenue across cuisines.

Insight: Revenue varies widely within every cuisine, and no single cuisine consistently dominates revenue generation.

---

10. Order Channel and Weather Frequency

Count plots show the frequency of order channels and weather conditions.

Insight: The App is the dominant order channel in the dataset.

---

11. Effect of Weather and Order Channel on Revenue

Bar charts compare average revenue across weather conditions and order channels.

Insight: Weather has limited impact on revenue, while the order channel shows more noticeable differences.

---

12. Correlation Heatmap

A correlation heatmap was used to identify relationships between numerical variables.

Key Correlations

Variables| Correlation
Avg Delivery Minutes vs Customer Rating| -0.88
Orders vs Revenue| 0.76
Average Order Value vs Revenue| 0.58
Marketing Spend vs Revenue| 0.20
Discounts vs Repeat Customer Percentage| 0.09

---

🔑 Key Business Insights

🚚 Delivery Speed Is Critical

Delivery time has the strongest relationship with customer satisfaction. Improving delivery speed could significantly improve customer ratings.

🌧️ Rainy Weather Affects Customer Experience

Customer ratings tend to decline during rainy weather, potentially because weather conditions increase delivery times.

📱 App Orders Perform Better

The App is the most frequently used order channel and also demonstrates stronger revenue performance compared with some other channels.

💰 Order Volume Drives Revenue

Orders have a strong positive relationship with revenue, making order growth an important business lever.

📢 Marketing Alone Is Not Enough

Marketing spend shows only a weak relationship with revenue. Campaign quality, targeting, and other business factors may be more important than spending alone.

🍽️ Cuisine Has Limited Impact on Order Volume

Order volume remains relatively consistent across cuisines, suggesting that demand is diversified rather than concentrated in a single food category.

---

🚀 Getting Started

1. Clone the Repository

git clone https://github.com/your-username/food-delivery-visualization-portfolio.git
cd food-delivery-visualization-portfolio

2. Install Dependencies

pip install -r requirements.txt

3. Run the Notebook

jupyter notebook

Open:

Food_Delivery_Visualization_Portfolio.ipynb

---

📦 Requirements

pandas
numpy
matplotlib
seaborn
jupyter

---

📸 Sample Visualizations

Add your exported chart screenshots inside the "images/" folder and display them here.

Example:

![Correlation Heatmap](images/correlation_heatmap.png)

---

📌 Future Improvements

- Build an interactive dashboard using Power BI or Tableau.
- Create a Streamlit web application.
- Add predictive models for revenue forecasting.
- Analyze customer retention in greater detail.
- Measure marketing campaign ROI.
- Add geographical visualizations for city-wise performance.

---

👤 Author

Heman 

BTech CSE 

Data Analytics Enthusiast | Python | SQL | Power BI | Data Visualization

---

⭐ Support

If you found this project useful, please consider giving the repository a star ⭐.

---

📜 License

This project is available for educational and portfolio purposes.