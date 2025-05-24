# ✈️ Big Data Flight Performance Analysis

This project presents a comprehensive analysis of 22 years of U.S. flight performance data using a Hadoop-based data pipeline orchestrated with Apache Oozie. It focuses on extracting actionable insights on airline punctuality, taxi operations, and cancellation patterns across major airports and airlines.

---

## 📊 Features

- **On-Time Performance Analysis**
  - Identifies airlines with the highest and lowest punctuality rates.
  
- **Taxi Time Analysis**
  - Calculates average taxi-in and taxi-out times for major U.S. airports.
  
- **Flight Cancellation Analysis**
  - Evaluates cancellation rates and categorizes reasons (e.g., carrier issues, weather, NAS delays).

---

## 📌 Key Findings

- **Top Airlines for Punctuality**:  
  Southwest Airlines (WN), Eastern Air Lines (EA), Alaska Airlines (AS)

- **Airports with Longest Taxi-Out Times**:  
  Nantucket Memorial (ACK), Pinehurst–Southern Pines (SOP), Rafael Hernández (BQN)

- **Most Common Cancellation Reason**:  
  Carrier-related issues

---

## ⚙️ Technology Stack

- **Big Data Framework**: Apache Hadoop  
- **Workflow Orchestration**: Apache Oozie  
- **Programming Language**: Python (MapReduce jobs)  
- **Processing Techniques**: Distributed computing, ETL, aggregation pipelines

---

## 🚀 Getting Started

1. **Clone this repository**  
   ```bash
     git clone [https://github.com/jkumar1006/BigData_Flight_Analysis.git]
   cd BigData_Flight_Analysis
2. **Set up a Hadoop environment**
Ensure Hadoop and Oozie are properly installed and configured.

3. **Deploy and run Oozie workflows**
Use the included configuration files to schedule and execute the data workflows.

4. **Explore Results**
Analyze the generated output to discover insights using visualization or reporting tools.

