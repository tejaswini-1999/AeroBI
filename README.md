# ✈️ AeroBI
<br>

## 📌 Overview
The airline industry faces persistent challenges with **flight delays and cancellations**, leading to **passenger dissatisfaction and operational inefficiencies**. This project leverages **data warehousing, ETL, machine learning, and visualization techniques** to analyze **historical flight data, identify patterns, and extract actionable insights** for improving **operational efficiency and customer experience**.  
<br><br>


## 🎯 Objectives
- Analyze historical flight data to identify trends in delays and cancellations.
- Determine key factors influencing flight delays and cancellations.
- Perform sentiment analysis on customer reviews to understand passenger experiences.
- Design and implement a Data Warehouse (DW) with a Star Schema for efficient data analysis.
- Develop interactive visualizations and real-time dashboards to provide actionable insights.
<br><br>


## 📂 Project Components  

### 1. Data Warehouse Design & Implementation
- Star Schema: Designed a dimensional model with Airline, Airports, Date, Cancellation, and Reviews dimensions.  
- Fact Table: Captures flight details such as delays, cancellations, departure and arrival times.  
- ETL Pipeline: Built using SQL Server Integration Services (SSIS) for data extraction, transformation, and loading.  
- Slowly Changing Dimensions (SCD Type 2): Implemented for tracking changes in airport names.  

### 2. Datasets  
- Flight Delay & Cancellation Data (3M+ records, 30+ attributes) – Sourced from Kaggle <a href="https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023?select=flights_sample_3m.csv" target="_blank">(Link)</a>  
- Airline Reviews (23K+ reviews) that captures passenger experiences - Sourced from Kaggle <a href="https://www.kaggle.com/datasets/juhibhojani/airline-reviews" target="_blank">(Link)</a> 
- Airport Information (380 records) – Scraped airport metadata.  

### 3. Exploratory Data Analysis (EDA)  
- Data Cleaning: Handled missing values, removed duplicates, and standardized attributes.  
- Sentiment Analysis: Used TextBlob and NLTK (VADER) to classify reviews into Positive, Neutral, or Negative.  
- Feature Engineering: Extracted meaningful attributes for predictive analysis.  

### 4. Data Visualization & Dashboards  

#### 📊 Key Dashboards:  
1. Net Promoter Score (NPS) Dashboard  
   - Evaluates airline reputation using Promoters, Passives, and Detractors.  
   - Identifies customer satisfaction trends for individual airlines.  

2. Airline Performance Dashboard  
   - Analyzes flight delays and cancellations across airlines.  
   - Examines causes of delays: Carrier, Weather, Security, NAS, Late Aircraft.  

3. Real-Time Flight Tracker Dashboard  
   - Displays live flight status updates.  
   - Tracks departure delays and reasons for disruptions.  
<br>

## 🚀 Technologies Used
- Python (Pandas, Numpy, Matplotlib, Seaborn, NLTK, TextBlob)
- SQL Server (ETL, Star Schema, SSIS)
- Power BI (Data Visualization, Dashboarding)
- Jupyter Notebooks (EDA, Sentiment Analysis)
- Kaggle (Dataset Source)
<br>


## 📜 Business Implications
The insights from this project can help airlines, passengers, and industry analysts in the following ways:
- Airline Management: Identify and mitigate operational bottlenecks affecting delays and cancellations.
- Customer Service Teams: Address key concerns from customer reviews to enhance satisfaction.
- Investors & Analysts: Use NPS and performance metrics to assess airline reputation.
- Passengers: Make informed decisions based on airline reviews and reliability scores.
<br><br>


## 📢 Contributors
- Tejaswini Kshirsagar
- Minita Joshee
- Neha Bharambe
<br><br>


## 🔗 References
- Flight and review datasets sourced from Kaggle 
- Sentiment analysis using TextBlob and NLTK (VADER)
- SQL Server for ETL and Data Warehouse Implementation
- Power BI for Dashboarding and Real-time Analytics 
