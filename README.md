# 🎬 IMDb API Data Extraction using Python & Pandas

## 📌 Project Description
This project demonstrates how to **fetch movie data from the IMDb API**, convert the JSON response into a **Pandas DataFrame**, select only the **required columns**, and export the cleaned data into a **CSV file**.

It represents a practical **API-to-CSV data pipeline**, commonly used in **data analytics and data engineering workflows**.

---

## ⚙️ Technologies Used
- **Python**
- **Requests**
- **Pandas**
- **IMDb API (via RapidAPI)**

---

## 🔄 Data Workflow
1. Send a GET request to the IMDb API using `requests`
2. Receive data in JSON format
3. Convert JSON data into a Pandas DataFrame
4. Select only relevant columns
5. Save the processed data as a CSV file

---

## 📂 Project Structure
├── py.ipynb
├── imdb_titles.csv
└── README.md

---

## 📊 Output
- A structured CSV file containing selected IMDb movie details  
- Ready for **EDA**, visualization, or dashboard creation  

---

## 🎯 Use Cases
- Movie data analysis  
- API data extraction practice  
- Data analyst portfolio project  
- Learning JSON to DataFrame conversion  

---

## 🚀 Possible Enhancements
- Handle pagination for larger datasets  
- Add error handling for API failures  
- Automate data updates  
- Store data in a database instead of CSV  
