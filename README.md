# 📊 Power BI Interactive Dashboard: Customer Purchases & Sentiment Analysis

This project presents a comprehensive **interactive dashboard** in Power BI that provides insight into customer behavior, order value, product category sentiment, and customer demographics. It combines purchase data with sentiment ratings to enable data-driven decision-making for product optimization and customer experience enhancement.

---

## 📁 Dataset Overview

The dataset (`Sheet1`) contains the following columns:

| Column              | Description                               |
|---------------------|-------------------------------------------|
| Customer Name       | Name of the customer                      |
| Email               | Customer's email address                  |
| Gender              | Male or Female                            |
| Age                 | Customer age                              |
| Location            | Customer location                         |
| Category            | Product category (e.g., Sports, Books)    |
| Purchases Per Month | Number of monthly purchases               |
| Order Value ($)     | Value of orders in USD                    |
| Sentiment           | Feedback sentiment (Positive, Neutral, Negative) |
| Rating              | Numerical rating (e.g., 1 to 5)           |

---

## 📊 Dashboard Visuals

### 1. 💰 **Purchases & Order Value Summary**
- **Type:** Horizontal Bar Chart
- **Insight:** Visualizes total purchases and order value across the dataset.

### 2. 📦 **Category Sentiment Breakdown**
- **Type:** Clustered Column Chart
- **Insight:** Displays sentiment distribution (Positive, Neutral, Negative) across each product category.

### 3. 🧁 **Sentiment-wise Rating & Purchase Distribution**
- **Type:** Donut Chart
- **Insight:** Shows total rating and purchase count per sentiment class.

### 4. 🧓 **Age Distribution by Category**
- **Type:** Tree Map
- **Insight:** Shows the total age distribution of customers grouped by product category.

### 5. 📈 **Category-wise Contribution to Metrics**
- **Type:** Waterfall Chart
- **Insight:** Depicts how each category contributes to order value, ratings, and purchase volume.

---

## 🎯 Key Insights

- 📌 Categories like **Books** and **Home & Kitchen** show consistent ratings across all sentiment levels.
- 📌 **Clothing** has moderate ratings and neutral sentiment, indicating a need for product improvement.
- 📌 **Sports** category customers are generally younger and highly engaged.

---

## 💡 Technologies Used

- **Power BI Desktop**
- **Excel** (for preprocessing)
- **Data Modeling & DAX Measures**
- **Interactive Visual Slicers and Filters**

---

## 🛠 How to Use

1. Open `Power BI Desktop`.
2. Click **"Get Data" → Excel** and load the dataset.
3. Build visuals using the **Visualizations pane** and **Fields pane**.
4. Apply filters and slicers as needed.
5. Analyze and interact with the dashboard for insights.

---

## 📌 Recommendations

- Focus marketing efforts on age-targeted campaigns for Sports & Electronics.
- Investigate low-rated segments in **Clothing** for product improvement.
- Encourage positive feedback loops through follow-up emails for high spenders.

---

## 📷 Sample Visuals

Below are screenshots included in the repository:

- `CBC.png`: Category-Based Comparison Chart  
- `TM.png`: TreeMap (Sum of Age by Category)  
- `DC.png`: Donut Chart (Sentiment Breakdown)  
- `WC.png`: Waterfall Chart (Category Metrics)  
- `ECSP_Dataset.png`: Raw Dataset Preview  
- `CCC.png`: Clustered Column Chart (Rating vs. Sentiment)

---

## 👤 Author

**Aakash Selvaraj**  
📧 aakashselvaraj2005@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/aakash-selvaraj-8b91a027b/)

---

## 📜 License

This project is open for academic, personal, and educational purposes only. Please credit the author when using or presenting.
