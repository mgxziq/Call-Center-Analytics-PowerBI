# 📊 Call Center Performance Analysis — Power BI

## 📌 Overview

This project is an interactive **Call Center Performance Analysis Dashboard** built using **Microsoft Power BI**.

The dashboard analyzes call center operations and provides insights into call volume, handled calls, abandoned calls, service performance, response time, and agent performance.

The dataset covers **February, March, and April 2022** and was combined and transformed to create a unified analytical dataset.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze the overall call center performance.
* Compare forecasted calls with actual calls offered.
* Measure handled and abandoned calls.
* Analyze service performance using **ASA (Average Speed of Answer)**.
* Evaluate calls handled within the defined threshold.
* Analyze agent performance.
* Identify trends in call volume and service quality.
* Build an interactive dashboard for business decision-making.

---

## 📂 Dataset

The project uses three CSV datasets:

* `Sallah Call Center Data Base - Feb(2).csv`
* `Sallah Call Center Data Base - Mar(1).csv`
* `Sallah Call Center Data Base -Apr(1).csv`

The datasets contain information about:

| Column                           | Description                                |
| -------------------------------- | ------------------------------------------ |
| `Project`                        | Project identifier                         |
| `Date`                           | Call date                                  |
| `Month`                          | Month of the record                        |
| `Forecasted Calls`               | Expected number of calls                   |
| `Calls Offered`                  | Total calls offered to the call center     |
| `Calls Handled`                  | Calls successfully handled                 |
| `Calls Handled With in Thrshold` | Calls handled within the defined threshold |
| `Calls Abandon`                  | Calls abandoned before being handled       |
| `ASA`                            | Average Speed of Answer                    |
| `Answer Time`                    | Answer time measurement                    |
| `Agent Name`                     | Agent responsible for handling the calls   |

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **CSV**
* **Data Modeling**
* **Data Visualization**

---

## 🔄 Data Preparation

The project includes a data preparation workflow in Power Query.

The main steps include:

1. Importing the monthly CSV files.
2. Combining the datasets using **Append Queries**.
3. Cleaning and transforming the data.
4. Checking and correcting data types.
5. Preparing the dataset for analysis.
6. Creating the data model.
7. Creating DAX measures.
8. Building interactive Power BI visualizations.

---

## 📊 Key Performance Indicators

The dashboard focuses on important Call Center KPIs such as:

* **Total Forecasted Calls**
* **Total Calls Offered**
* **Total Calls Handled**
* **Total Abandoned Calls**
* **Service Level / Threshold Performance**
* **ASA — Average Speed of Answer**
* **Answer Time**
* **Agent Performance**
* **Call Volume Trends**

---

## 📈 Dashboard Analysis

The dashboard allows users to analyze:

### Call Volume

Compare the number of forecasted calls against actual calls offered to identify differences between expected and actual demand.

### Call Handling

Analyze how many calls were successfully handled compared with the total calls offered.

### Abandoned Calls

Monitor abandoned calls and identify periods where abandonment increased.

### Service Performance

Analyze calls handled within the required threshold and evaluate the quality of the call center service.

### ASA

**ASA (Average Speed of Answer)** measures how quickly calls are answered by the call center.

Lower ASA generally indicates that customers are being connected to agents faster.

### Agent Performance

Compare performance between agents using call handling and service-related KPIs.

---

## 📅 Analysis Period

The project contains call center data for:

* **February 2022**
* **March 2022**
* **April 2022**

This makes it possible to analyze changes in call center performance over time.

---

## 🖥️ Power BI Dashboard

The main dashboard was created using Microsoft Power BI and provides interactive filtering and visualization of the call center data.

**Power BI file:**

`Sallah Call Center .pbix`

> Open the `.pbix` file using Microsoft Power BI Desktop to interact with the dashboard.

---

## 💡 Business Insights

The analysis can help call center management:

* Identify periods with high call demand.
* Monitor abandoned calls.
* Evaluate service-level performance.
* Understand agent performance.
* Compare forecasted demand with actual call volume.
* Identify potential operational issues.
* Support data-driven workforce and resource planning.

---

## 📁 Project Structure

```text
Call-Center-Performance-Analysis-PowerBI/
│
├── Data/
│   ├── Sallah Call Center Data Base - Feb(2).csv
│   ├── Sallah Call Center Data Base - Mar(1).csv
│   └── Sallah Call Center Data Base -Apr(1).csv
│
├── Sallah Call Center .pbix
│
└── README.md
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Install **Microsoft Power BI Desktop**.
3. Open `Sallah Call Center .pbix`.
4. Explore the dashboard using the available filters and visualizations.

---

## 👨‍💻 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Data Transformation
* Power Query
* Data Modeling
* DAX
* KPI Development
* Business Intelligence
* Data Visualization
* Call Center Analytics
* Performance Analysis

---

## 📌 Project Purpose

This project was created as a **Data Analytics / Business Intelligence portfolio project** to demonstrate the ability to transform raw operational data into an interactive analytical dashboard using Power BI.

---

## ⭐ If you find this project useful

Feel free to explore the project, review the Power BI dashboard, and use it as a reference for learning Call Center Analytics and Power BI.
