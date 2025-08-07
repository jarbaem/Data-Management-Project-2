# ✈️ Airline Performance 2007

This project explores the patterns behind these disruptions using the **Airline On-Time Performance** dataset from [Kaggle](https://www.kaggle.com/datasets/wenxingdi/data-expo-2009-airline-on-time-data/data?select=1993.csv) to uncover the *when*, *where*, and *why* of flight delays and cancellations.


## 🛠️ Tools & Environment Setup

The analysis was conducted in a virtual environment using **Oracle VirtualBox**. The workflow involves:

- 📂 **HDFS**: To upload and manage large datasets across the cluster  
- 🐍 **Jupyter Notebook**: Used as the main Python IDE for scripting, analysis, and visualization. The .ipynb file include on how to connect with Hive.  


## 🔍 Analysis Scope
The analysis was conducted to answer questions:

### 1. **Delay Patterns**
- What times of day (morning/afternoon/evening) have the lowest average delays?
- Which days of the week show better on-time performance?
- During which months or seasons are flights most likely to be on time?

### 2. **Delay Factors**
- Identify and rank the top 3–5 causes of flight delays based on dataset categories.
- Quantify the impact of each factor in minutes and as a percentage of total delays.

### 3. **Cancellation Analysis**
- Identify the main reasons for flight cancellations (Carrier, Weather, NAS, Security).
- Analyze whether cancellations correlate with specific airlines, airports, or time periods.

### 4. **Problematic Routes**
- Identify routes (origin-destination pairs), carriers, or flight numbers that consistently underperform.
- Analyze the reasons these flights are frequently delayed or cancelled.

## 🧠 Methodology

To efficiently handle and analyze this large dataset:
- Data was loaded into Hive tables via HDFS
- SQL queries were used to extract relevant subsets
- Python (via Jupyter Notebook) was used for deeper analysis, data wrangling, and visualizations

