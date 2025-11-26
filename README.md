# 📊 BMW Sales Analysis (Excel Project)
This project presents a comprehensive analysis of BMW’s sales data using Excel, covering sales trends, customer preferences, revenue insights, and an interactive dashboard.
The dataset consists of 50,000 sales records with details on models, pricing, regions, engine types, fuel types, and more.
The final output includes cleaned data, exploratory analysis, KPIs, charts, pivot summaries, and a dynamic dashboard.

## 📝 Project Overview
BMW generates large volumes of sales data across regions, models, and customer preferences. Without proper analysis, identifying market trends and business opportunities is challenging.
This project aims to answer key business questions such as:
1. Which models and regions contribute the most to sales and revenue?
2. What fuel types, colours, and transmissions are preferred by customers?
3. How do price ranges and engine sizes impact sales?
4. How are sales trending year over year?

📂 Dataset Description
Source: Kaggle
Records: 50,000 rows
| Features include |
| ---------------- |
| Model |
| Year |
| Region |
| Colour |
| Fuel Type |
| Transmission |
| Engine Size |
| Mileage |
| Price (per unit) |
| Sales Volume |


## 🔧 Data Preparation
Performed using Power Query:
1. Null value treatment
2. Column type correction
3. Additional calculated fields

🆕 New Columns Created
1. Revenue = Price × Sales Volume
2. Engine Size Classification:
<2 L, 2–4 L, >4 L


## 🔍 Exploratory Data Analysis (EDA)
1. Highest Selling Model BMW 7 Series

  	* Sales Volume: 23,786,466
  	* Revenue: 1,790,070,249,282 

2. Sales Trend Over the Years
	* Sales remained stable with minor fluctuations between 2010–2024.

3. Regional Performance
	* Asia leads with 16.96% of total sales & 17.10% of total revenue.
	* Europe and North America follow.

4. Most Popular Car Colours
	* Red and Silver are highest in demand.

5. Fuel Type Preference
	* Customer prefer Hybrid fuel type most. Followed by Petrol, Electric, Diesel.

6. Transmission Preference
	* Manual transmission is preferred over automatic.

7. Engine Size Popularity
	* 2–4 litre engines dominate sales.

8. Influence of Price & Engine Size
	* Price range $50,000–$100,000 contributes to 55% of total sales.
	* Mid-sized engines show highest performance.

9. YOY Sales & Revenue Trends
   * Graphs on page 3 display fluctuations across years.

Regional Averages

| Region        | Sales Volume | Avg Price (USD) |
| ------------- | ------------ | --------------- |
| Africa        | 41,565,252   | 74,885.77       |
| Asia          | 42,974,277   | 75,554.93       |
| Europe        | 42,555,138   | 74,988.36       |
| Middle East   | 42,326,620   | 74,726.78       |
| North America | 42,402,629   | 75,070.05       |
| South America | 41,551,818   | 74,973.60       |
|               |              |                 |

		
## 📊 Dashboard Preview

![dashboard](https://github.com/Debdatta7/BMW-Sales/blob/main/dashboar.JPG)

## 💡 Key Insights

* BMW 7 Series is the highest-performing model in both sales and revenue.

* Asia is the strongest market with the largest contribution.

* Diesel and Petrol vehicles dominate, though Electric & Hybrid are growing.

* Sales trends remain mostly stable across the years.


## 📘 Conclusion

BMW’s growth is driven by: 
* Premium luxury segment (7 Series)
* Mid-priced vehicles ($50k–$100k)
* Customer preference for manual transmission, bold colours, and 2–4 litre engines
* There is significant opportunity for expanding electric and hybrid models, especially in fast-growing Asian markets.
