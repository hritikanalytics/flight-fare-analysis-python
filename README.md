# Flights Ticket Price Analysis Using Python

## 📌 Project Summary
This project presents a comprehensive exploratory data analysis (EDA) of airline flight ticket pricing using Python. The analysis aims to identify key factors influencing ticket prices, such as booking time, departure and arrival slots, and demand-driven pricing behavior.

The project is designed to demonstrate real-world data analysis skills, business interpretation, and visualization techniques commonly expected from a Data Analyst role.

---

## 🧠 Business Problem Statement
Airline ticket prices are highly dynamic and fluctuate based on multiple factors including demand, time to departure, and flight schedules.  

### Key Questions Addressed:
- When is the best time to book flights at the lowest price?
- How does ticket pricing change as the departure date approaches?
- Do departure and arrival time slots affect ticket prices?
- What pricing patterns can travelers and airlines leverage?

---

## 🎯 Project Objectives
- Perform structured data cleaning and validation
- Analyze price behavior across booking windows
- Identify peak vs off-peak pricing patterns
- Extract actionable insights from descriptive analytics
- Visualize trends for clear business interpretation

---

## 📊 Dataset Overview
The dataset consists of structured airline booking records with both categorical and numerical variables.

### Key Features:
- Airline
- Source City
- Destination City
- Departure Time (Morning, Afternoon, Evening, Night)
- Arrival Time
- Days Left Before Departure
- Ticket Price (INR)

### Target Variable:
- **Price** – Airline ticket fare in Indian Rupees

---

## 🧹 Data Preparation & Cleaning
Before analysis, the dataset was carefully prepared using the following steps:

- Checked for missing values and inconsistencies
- Standardized categorical labels
- Converted data types where required
- Verified logical ranges (e.g., days left, price values)
- Ensured dataset quality for accurate analysis

---

## 🔍 Exploratory Data Analysis (EDA)
The analysis follows an exploratory approach to uncover pricing trends and relationships.

### Techniques Used:
- Distribution analysis of ticket prices
- Group-by aggregations
- Trend analysis based on booking windows
- Comparative analysis of time slots
- Visualization using bar charts and distributions

---

## 📈 Key Findings & Insights

### ⏳ Booking Time vs Price
- Flights booked **60+ days before departure** have the lowest average prices
- Prices moderately increase between **30–60 days**
- Significant price escalation occurs within **30 days of departure**
- **Last-minute bookings** are the most expensive

### 🕒 Departure & Arrival Time Analysis
- Morning and evening flights tend to be more expensive
- Late-night and early-morning flights are generally cheaper
- Peak hours reflect higher demand, especially from business travelers

### 📌 Overall Insight
There is a **clear inverse relationship** between days left before departure and ticket prices — as departure approaches, prices rise.

---

## 🛠 Tools & Technologies
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **IDE:** Jupyter Notebook
- **Output Formats:** Notebook (.ipynb), HTML, PDF Report

---

## 📄 Project Deliverables
- **PDF Report:** Business-style analytical report with insights
- **Jupyter Notebook:** Complete Python analysis with code and plots
- **HTML File:** Rendered notebook for easy viewing on GitHub
- **Dataset:** Raw CSV used for analysis

---

## 🚀 Future Scope & Enhancements
- Build machine learning models for ticket price prediction
- Include flight duration and number of stops
- Airline-wise and route-wise comparative analysis
- Incorporate seasonality, holidays, and demand surges
- Deploy analysis as an interactive dashboard

---

## 👨‍💻 Author
**Hritik Mishra**  
Commerce Graduate | Aspiring Data Analyst  

### Skills Demonstrated:
- Python for Data Analysis
- Exploratory Data Analysis (EDA)
- Data Cleaning & Validation
- Business Insight Generation
- Data Visualization

---

## 📌 Disclaimer
This project is created for educational and portfolio purposes to demonstrate data analysis skills using real-world inspired datasets.
