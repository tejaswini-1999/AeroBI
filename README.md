# ✈️ AeroBI
<br>

## 📌 Overview
The airline industry plays a crucial role in global transportation, but flight delays and cancellations remain persistent challenges, causing inconvenience for passengers and operational inefficiencies for airlines. This project aims to analyze historical flight data, identify patterns, and extract insights to improve operational efficiency and customer experience.
<br><br>


## 🎯 Objectives
- Analyze historical flight data to identify trends in delays and cancellations.
- Determine key factors influencing flight delays and cancellations.
- Perform sentiment analysis on customer reviews to understand passenger experiences.
- Design and implement a Data Warehouse (DW) with a Star Schema for efficient data analysis.
- Develop interactive visualizations and real-time dashboards to provide actionable insights.
<br><br>


## 📂 Project Components
<ol>
  <li>Data Warehouse Design & Implementation </li>
  <ul>
    <li>Star Schema: Designed a dimensional model with Airline, Airports, Date, Cancellation, and Reviews dimensions</li>
    <li>Fact Table: Stores flight details such as delays, cancellations, departure and arrival times</li>
    <li>ETL Pipeline: Built using SQL Server Integration Services (SSIS) to extract, transform, and load data efficiently</li>
    <li>Slowly Changing Dimensions (SCD Type 2) implemented for tracking changes in airport names</li></ul>

  <li>Datasets</li>
  <ul>
    <li>Flight Delay & Cancellation Data (3M+ records, 30+ attributes) – Sourced from Kaggle <a href="https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023?select=flights_sample_3m.csv" target="_blank">(Link)</a></li>
    <li>Airline Reviews (23K+ reviews) which captures passenger experiences - Sourced from Kaggle <a href="https://www.kaggle.com/datasets/juhibhojani/airline-reviews" target="_blank">(Link)</a></li>
    <li>Airport Information (380 records) – Scraped data on US airports</li></ul>

<li>Exploratory Data Analysis (EDA)</li>
  <ul>
    <li>Data Cleaning: Handled missing values, removed duplicates, and standardized data</li>
    <li>Sentiment Analysis: Used TextBlob and NLTK (VADER) to classify customer reviews into Positive, Neutral, or Negative</li>
    <li>Feature Engineering: Extracted important attributes for predictive analysis</li></ul>
    
<li>Data Visualization</li>
  <ul>
    <li>Power BI dashboards were created to present insights effectively:</li></ul></ol>
<br>


## 📊 Key Dashboards:
<ol>
<li>Net Promoter Score (NPS) Dashboard 📈</li>
<ul>
  <li>Measures customer satisfaction based on sentiment analysis</li>
  <li>Compares Promoters, Passives, and Detractors for different airlines.</li></ul>

<li>Airline Performance Dashboard ✈️</li>
<ul>
  <li>Analyzes cancellations and delays across different airlines</li>
  <li>Visualizes reasons for flight delays: Carrier, Weather, Security, NAS, and Late Aircraft delays</li></ul>

<li>Real-Time Flight Tracker Dashboard 🛰️</li>
<ul>
  <li>Displays live flight status, including departure delays and reasons</li>
  <li>Maps flight routes and updates in real-time</li></ul>
</ol>
<br>


## 🚀 Technologies Used
1. Python (Pandas, Numpy, Matplotlib, Seaborn, NLTK, TextBlob) <br>
2. SQL Server (ETL, Star Schema, SSIS)  <br>
3. Power BI (Data Visualization, Dashboarding) <br>
4. Jupyter Notebooks (EDA, Sentiment Analysis) <br>
5. Kaggle (Dataset Source) <br>
<br><br>


## 📜 Business Implications
The insights from this project can help airlines, passengers, and industry analysts in the following ways:
1. Airline Management: Identify and mitigate operational bottlenecks affecting delays and cancellations.
2. Customer Service Teams: Address key concerns from customer reviews to enhance satisfaction.
3. Investors & Analysts: Use NPS and performance metrics to assess airline reputation.
4. Passengers: Make informed decisions based on airline reviews and reliability scores.
<br><br>


## 📢 Contributors
Tejaswini Kshirsagar <br>
Minita Joshee <br>
Neha Bharambe <br>
<br><br>


## 🔗 References
Flight and review datasets sourced from Kaggle <br>
Sentiment analysis using TextBlob and NLTK (VADER) <br>
SQL Server for ETL and Data Warehouse Implementation <br>
Power BI for Dashboarding and Real-time Analytics <br>
