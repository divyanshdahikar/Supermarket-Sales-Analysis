This project performs Exploratory Data Analysis (EDA) on a real-world supermarket sales dataset to uncover trends and insights related to sales, product lines, days, and months.

---

## 📂 Dataset Information

- **Source**: [Kaggle - Supermarket Sales Dataset](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)
- **Size**: 1000 entries × 17 columns
- **Features**: Includes information like city, product line, price, payment method, gross income, date/time, and more.

---

## 🔧 Libraries Used

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `kagglehub`

---

## ✅ Data Preprocessing Steps

- Converted `Date` and `Time` columns to datetime formats.
- Created new columns:
  - `Datetime`: full timestamp
  - `Day_of_week`: name of the day
  - `Month`: name of the month
- Dropped unnecessary columns like `Invoice ID`.

---

## 📊 Exploratory Data Analysis (EDA)

### 1. 📈 Daily Sales Trend
Line plot showing how total sales varied across each date.

![Screenshot 2025-06-18 210654](https://github.com/user-attachments/assets/907fa12b-a299-44e4-8d90-f847c55d2b54)

---

### 2. 📅 Sales by Day of the Week
Bar chart showing which days had the highest total sales.

![Screenshot 2025-06-18 211518](https://github.com/user-attachments/assets/360aa3d8-971a-401e-94f2-8a8b298b636b)

---

### 3. 📦 Top Products on Tuesday
Identifies highest-selling product lines on Tuesdays by total revenue and quantity.

![Screenshot 2025-06-18 211619](https://github.com/user-attachments/assets/4a0f3a9b-990b-4d20-ac08-9fb8e5c58d16)

---

### 4. 🛍️ Saturday vs Sunday Product Sales
Compares top product lines on weekends — includes both total sales and quantity sold.

![Screenshot 2025-06-18 212023](https://github.com/user-attachments/assets/2dbf5158-9b05-408e-b64f-cadeac34da84)

![Screenshot 2025-06-18 212059](https://github.com/user-attachments/assets/a39cbc61-43ed-48b6-bebe-84a6a3787967)

---

### 5. 📅 Monthly Product Line Breakdown
Grouped bar chart comparing product sales across January, February, and March.

![Screenshot 2025-06-18 212355](https://github.com/user-attachments/assets/8cb9c631-37cd-40b2-888b-efb8ffa12a67)

---

### 6. 🔍 January Deep Dive
- Daily trend of sales in January across different product lines.
- Quantity of each product sold in January.

![Screenshot 2025-06-18 213357](https://github.com/user-attachments/assets/cb2a5470-a869-41fe-8644-8af30652d16c)

---

## 💡 Key Insights

- **Saturday** is the highest revenue day overall.
- **Food and beverages** and **Sports and travel** consistently generate top sales across multiple months.
- **E-wallet** is a popular mode of payment in Yangon.
- Monthly sales are fairly balanced, but **January** and **March** show high variation by product type.
- Product quantity and revenue don’t always correlate — higher quantity doesn’t mean higher revenue.

---

## 📎 Resources

- [Dataset Link](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)
