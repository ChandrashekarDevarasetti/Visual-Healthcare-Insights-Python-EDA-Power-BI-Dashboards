<p align="center">
  <img src="Images/Healthcare Project Guide Illustration.png" alt="Healthcare Data Insights Banner" width="700" height = "400">
</p>

# Visual-Healthcare-Insights-Python-EDA-Power-BI-Dashboards

## 📑 Table of Contents

1. [Project Overview](#1-project-overview)
2. [Project Description](#2-project-description)
3. [Key Features](#3-key-features)
4. [Tools & Technologies](#4-tools--technologies)
5. [Project Folder Structure](#5-project-folder-structure)
6. [Installation & Setup](#6-installation--setup)
7. [How to Run](#7-how-to-run)
8. [Detailed Overview of Health_Care_EDA in Python](#8-detailed-overview-of-health_care_eda-in-python)
    - [8.1 Description of the Dataset](#81-description-of-the-dataset)
    - [8.2 Data Cleaning & Preparation](#82-data-cleaning--preparation)
        - [a. Merging All Datasets](#a-merging-all-datasets)
        - [b. Standardizing Data](#b-standardizing-data)
        - [c. Data Integrity Validation](#c-data-integrity-validation)
        - [d. Handling Missing Values](#d-handling-missing-values)
        - [e. Handling Duplicates](#e-handling-duplicates)
        - [f. Converting Datatypes](#f-converting-datatypes)
        - [g. Creating Derived Columns](#g-creating-derived-columns)
        - [h. Mapping Categorical Values](#h-mapping-categorical-values)
9. [Exploratory Data Analysis (EDA)](#9-exploratory-data-analysis-eda)
    - [a. Univariate Analysis](#a-univariate-analysis)
    - [b. Bivariate Analysis](#b-bivariate-analysis)
    - [c. Multivariate Analysis](#c-multivariate-analysis)
    - [d. Distribution Analysis](#d-distribution-analysis)
    - [e. Correlation Analysis](#e-correlation-analysis)
10. [Detailed Overview of Power BI Dashboard](#10-detailed-overview-of-power-bi-dashboard)


## 📌 Project Overview <a name="1-project-overview"></a>
&nbsp;&nbsp;&nbsp;&nbsp;This project focuses on analyzing healthcare data to uncover key insights into patient admissions, medical conditions, treatment outcomes, and hospital performance. By combining Python for data preparation and cleaning with Power BI for interactive dashboards, the project aims to support healthcare administrators in making data-driven operational and clinical decisions.

## 📌 Project Description
&nbsp;&nbsp;&nbsp;&nbsp;🩺 The Healthcare Data Analysis and Visualization Project involves working with a multi-sheet Excel dataset containing patient details, hospital information, doctor records, and patient visit data. The project workflow starts with merging and cleaning the data using Python libraries such as Pandas and NumPy in a Jupyter Notebook environment. Key data cleaning steps included handling missing values, standardizing text data, mapping admission type codes, calculating patient length of stay, and identifying high billing cases.

After preparing a clean and integrated dataset, exploratory data analysis (EDA) was performed in Python to validate data distributions and detect anomalies. The prepared dataset was then visualized in Power BI, where a series of interactive dashboards were built to deliver actionable insights.

The dashboards created include:

🔍 **Overview Dashboard** : Patient Admissions Summary: Visualizing patient admission counts, age distribution, gender splits, and admission trends.

🏥 **Medical Condition & Outcome Analysis** : Analyzing the frequency of medical conditions, treatment outcomes, and recovery rates.

💵 **Billing & Insurance Analysis** : Tracking billing amounts, insurance coverage patterns, and flagging high-cost cases.

🧑‍⚕️ **Doctor & Hospital Performance** : Evaluating doctor-wise and hospital-wise patient outcomes, admissions, and billing performance.

📅 **Time-Based Analysis** : Examining trends over time including admissions, discharges, and length of stay patterns.

This project demonstrates how Python-based data engineering can seamlessly integrate with BI tools like Power BI to deliver healthcare insights that improve operational efficiency and patient care decisions.

## 📌 Key Features
- 📑 Merges multiple Excel sheets into a single clean dataset.

- 🧹 Cleans and standardizes patient, doctor, and hospital details.

- ⚙️ Handles missing values (numeric → median, categorical → mode).

- 📏 Calculates Length of Stay for each patient.

- 💸 Flags patients with High Billing Amounts.

- 🔢 Maps Admission Types to numeric codes for analysis.

- 📊 Performs EDA using Python (Pandas, Matplotlib, Seaborn).

- 📈 Builds Power BI dashboards for dynamic visual insights.

## 📌 Tools & Technologies

- Python
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- 📊 Power BI
- 📑 Microsoft Excel
- 📓 Jupyter Notebook
- 📂 CSV & Excel Files (for data storage)

## 📌 Project Folder Structure

├── 📁 Data/ # Healthcare Excel dataset files

│ └── healthcare_dataset.xlsx

│

├── 📁 Images/ # Project images for README or dashboards

│

├── 📁 Python/ # Python notebook, requirements, and scripts

│ ├── HealthCare_EDA.ipynb

│ └── requirements.txt

│

├── 📁 PowerBI/ # Power BI dashboard files

│ └── HealthCare_Dashboard.pbix

│

├── 📄 .gitignore # Git ignore rules

├── 📄 LICENSE # Project open source license

├── 📄 README.md # Project overview and documentation

## 📌 Installation & Setup (One Block for Python + Power BI)

#### 1️⃣ Clone the repository
git clone [https://github.com/ChandrashekarDevarasetti/Visual-Healthcare-Insights-Python-EDA-Power-BI-Dashboards.git](https://github.com/ChandrashekarDevarasetti/Visual-Healthcare-Insights-Python-EDA-Power-BI-Dashboards)

cd Visual-Healthcare-Insights-Python-EDA-Power-BI-Dashboards

#### 2️⃣ Install required Python packages
pip install -r Python/requirements.txt

#### 3️⃣ Launch the Jupyter Notebook
jupyter notebook Python/HealthCare_EDA.ipynb

#### 4️⃣ Open the Power BI Dashboard manually:
#### Navigate to the 'PowerBI' folder and open 'HealthCare_Dashboard.pbix' in Power BI Desktop


## 📌  How to Run (For both Python EDA + Power BI)

### Run Python EDA Notebook

 #### 1️⃣ Install dependencies  
 &nbsp;&nbsp;&nbsp;&nbsp; Make sure you have all the necessary dependencies by running the following command:

 &nbsp;&nbsp;&nbsp;&nbsp; pip install -r Python/requirements.txt

 #### 2️⃣ Launch the Jupyter Notebook
 &nbsp;&nbsp;&nbsp;&nbsp; After installing the dependencies, open the Jupyter notebook with the following command:
 
 &nbsp;&nbsp;&nbsp;&nbsp; jupyter notebook Python/HEALTHCARE_EDA.ipynb

 #### 3️⃣ In your browser, open the notebook and run all cells sequentially
 &nbsp;&nbsp;&nbsp;&nbsp; Once the notebook is open in your browser, execute all the cells to run the EDA analysis.


### 📊 Open Power BI Dashboard
 #### 1️⃣ Install Power BI Desktop
 &nbsp;&nbsp;&nbsp;&nbsp; If you haven't already, install Power BI Desktop. You can download it from here.

 #### 2️⃣ Open the Power BI file
 &nbsp;&nbsp;&nbsp;&nbsp; To view the dashboards, open the Power BI file located in the PowerBI directory:

 &nbsp;&nbsp;&nbsp;&nbsp; PowerBI/HealthCare_Dashboard.pbix

 #### 3️⃣ Explore all the interactive dashboards
 &nbsp;&nbsp;&nbsp;&nbsp; Once the Power BI file is open, you can explore the following interactive dashboards:

  - 📊 Overview Dashboard

  - 🩺 Medical Condition & Outcome Analysis
 
  - 💸 Billing & Insurance Analysis

  - 🧑‍⚕️ Doctor & Hospital Performance

 #### 4️⃣ Refresh the dataset if needed

 &nbsp;&nbsp;&nbsp;&nbsp; If you need to refresh the data, connect to the Excel file located under the /data/ directory.

## 📌 Detailed Overview of Healthcare_EDA in Python
> Description of the Dataset
