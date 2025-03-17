# 📊 Takealot Product Analysis  

## 📝 Project Overview  
This project analyzes **Takealot** product data using **SQL Server**, **Python**, and **Power BI**. The goal is to extract insights on product performance, pricing trends, customer preferences, and availability.  

## 🛠 Tech Stack  
- **Python**: Data extraction, cleaning, and transformation (`pandas`, `sqlalchemy`, `pyodbc`)  
- **SQL Server**: Data storage and querying  
- **Power BI**: Data visualization and reporting  

## 📂 Dataset Overview  
The dataset includes:  
- **Product ID**: Unique identifier  
- **Title**: Product name  
- **Brand**: Manufacturer or seller  
- **Star Rating**: Average customer rating  
- **Reviews**: Number of customer reviews  
- **Price**: Product price in ZAR (Rands)  
- **Availability**: Stock status  
- **Image URL**: Product image link  

## 🔍 Key Analyses  
### ✅ SQL Queries  
- Most popular products by **ratings and reviews**  
- **Price distribution** by brand and category  
- **Stock availability trends**  
- **Average price of top-rated products**  

### 📊 Power BI Dashboards  
- **Sales and pricing trends**  
- **Customer ratings distribution**  
- **Brand performance comparison**  

## 🚀 How to Run the Project  
### 1️⃣ Set Up SQL Server  
- Create a database  
- Import the dataset into a table  

### 2️⃣ Install Dependencies  
```sh  
pip install pandas sqlalchemy pyodbc matplotlib seaborn  
```

### 3️⃣ Run Python Scripts  
- Load data into SQL Server:  
```sh  
python data_processing.py  
```
- Run SQL queries for insights:  
```sh  
python sql_queries.py  
```

### 4️⃣ Open Power BI Dashboard  
- Connect to SQL Server  
- Load the **Takealot Insights Dashboard**  

## 📊 Sample Power BI Dashboard  
![Dashboard Preview](dashboard_screenshot.png)  

## 🔄 Future Enhancements  
- **Sentiment analysis** on customer reviews  
- **Category-based price trend analysis**  
- **Time-series analysis** for price fluctuations  

## 🤝 Contributing  
Fork the repo and submit a pull request for improvements.  

## 📜 License  
This project is open-source under the **MIT License**.  

---
🚀 **Happy Analyzing!** 🚀  

