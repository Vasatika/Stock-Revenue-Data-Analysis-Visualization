# 📊 Extracting and Visualizing Stock Data – IBM Python Project  

## 📌 Project Overview  
This project is part of the **IBM Python for Data Science Certification** and focuses on extracting, analyzing, and visualizing **stock market data** for **Tesla and GameStop**. Using **Python, yFinance, and Web Scraping (BeautifulSoup and read_html)**, I retrieved **historical stock prices & revenue data** and created an **interactive dashboard with Plotly** to uncover trends and insights.  

---

## 📈 Key Objectives  
1. Define a function to generate stock price & revenue graphs 📊  
2. Extract **Tesla & GameStop stock data** using **yFinance API**  
3. Web scrape **Tesla & GameStop revenue data** using **BeautifulSoup**  
4. Clean and preprocess the extracted data  
5. Visualize stock performance & revenue trends using **Plotly**  

---

## 🛠️ Technologies Used  
- **Python** – Data Extraction & Analysis  
- **yFinance** – Stock Market Data Retrieval  
- **BeautifulSoup** – Web Scraping Revenue Data  
- **Pandas** – Data Cleaning & Manipulation  
- **Plotly** – Interactive Data Visualization  
- **Jupyter Notebook** – Code Execution & Documentation  

---

## 📊 Data Extraction & Processing  
### **1️⃣ Stock Price Data (yFinance API)**  
- Retrieved historical stock price data for **Tesla & GameStop**  
- Converted **Date** column to `datetime` format  
- Filtered stock price data **up to June 14, 2021**  

### **2️⃣ Revenue Data (Web Scraping)**  
- Scraped **Tesla & GameStop revenue data** from **Macrotrends**  
- Cleaned revenue values by removing **"$" and ","**  
- Converted **string revenue values to float** for analysis  
- Filtered revenue data **up to April 30, 2021**  

---

## 📊 Data Visualization  
### **3️⃣ Interactive Stock & Revenue Graphs (Plotly)**  
- Created an **interactive two-panel dashboard** to display:  
  - **Stock Price Over Time** (Line Graph)  
  - **Revenue Over Time** (Line Graph)  
- Added **range slider, axis labels, and formatting** for clarity  
