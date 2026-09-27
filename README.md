Week 2 Task 1  : India Job Market 2024–2026 – Data Cleaning Project 
1. Project Title 
India Job Market 2024–2026 – Data Cleaning and Preprocessing 
 
2. Project Objective 
The objective of this project is to clean, preprocess, and transform the India Job Market 2024–2026 
dataset into a consistent and analysis-ready format. 
The project focuses on identifying and handling common data-quality problems such as: 
• Missing values 
• Duplicate records 
• Incorrect data types 
• Inconsistent text formatting 
• Potential outliers 
• Categorical variables0zation, Business Intelligence, and Machine Learning projects. 
 
3. Dataset Description 
The dataset contains information about job opportunities in India during the period 2024–2026. 
Dataset Size 
Description Value 
Total Records 5,000 
Original Columns 17 
Cleaned Records 5,000 
Missing Values 0 
Duplicate Records 0 
Main Dataset Columns 
Column Description Data Type 
Job_ID Unique job identifier Identifier 
Job_Title Job position/title Categorical 
Company Hiring company Categorical 
Company_Type Type of company Categorical 
Industry Industry sector Categorical 
City Job location/city Categorical 
Location_Tier Classification of city/location Categorical 
Experience_Level Required experience level Categorical 
Job_Type Type of employment Categorical 
Work_Mode Remote, hybrid, or on-site Categorical 
Salary_LPA Salary offered in Lakhs Per Annum Numeric 
Skills_Required Skills required for the job Categorical/Text 
Education_Required Required educational qualification Categorical 
Openings Number of available positions Numeric 
Applicants Number of applicants Numeric 
Company_Rating Company rating Numeric 
Date_Posted Date when job was posted Date 
 
4. Technologies Used 
Programming Language 
• Python 3.x 
Libraries 
• Pandas 
• NumPy 
• Matplotlib 
• Seaborn 
Development Environment 
• Jupyter Notebook 
• Google Colab 
• Visual Studio Code (optional) 
File Formats 
• CSV 
• Excel 
• Jupyter Notebook 
 
5. Dataset - Raw file: `india_job_market_2024_2026.csv` - Raw rows: 5000 - Raw columns: 17 - Cleaned rows: 5000 - Cleaned columns: 21 
 
6. Tools 
Python 3.x, Pandas, NumPy, Seaborn, Matplotlib, Jupyter Notebook/Google Colab. 
 
7.  Cleaning Performed 
1. Loaded and explored the CSV using `head()`, `info()`, `describe()`, shape and data-type checks. 
2. Checked missing values and generated a heatmap. 
3. Applied column-appropriate missing-value handling. 
4. Detected and removed exact duplicate rows. 
5. Standardized column names to snake_case. 
6. Corrected numeric and date data types. 
7. Standardized whitespace in text/categorical fields. 
8. Detected potential outliers with the IQR method. 
9. Flagged potential outliers instead of automatically deleting potentially valid job-market records. 
10. Created a separate one-hot encoded dataset for selected categorical columns. 
11. Validated missing values, duplicates, types and summary statistics. 
12. Exported cleaned and encoded CSV files. 
 
8. Missing-Value Strategy 
Numeric fields use the median when missing. Categorical fields use the mode. Date fields use a 
median date when required. 
 
9. Outlier Strategy 
IQR was applied to Salary LPA, Openings, Applicants and Company Rating. Outliers are retained 
and flagged because extreme values may represent legitimate observations. 
 
10. Project Deliverables 
The project contains the following deliverables: 
Task_1_India_Job_Market_Deliverables/ 
│ 
├── data/ 
│   ├── raw/ 
│   │   └── india_job_market_2024_2026.csv 
│   │ 
│   └── cleaned/ 
│       ├── india_job_market_2024_2026_cleaned.csv 
│       └── india_job_market_2024_2026_encoded.csv 
│ 
├── notebooks/ 
│   └── Task_1_India_Job_Market_Data_Cleaning.ipynb 
│ 
├── reports/ 
│   ├── Data_Cleaning_Report.md 
│   ├── before_after_comparison.csv 
│   ├── missing_value_report.csv 
│   └── outlier_iqr_report.csv 
│ 
├── visualizations/ 
│   ├── missing_values_heatmap.png 
│   ├── duplicates_before_after.png 
│   ├── boxplot_salary_lpa.png 
│   ├── boxplot_openings.png 
│   ├── boxplot_applicants.png 
│   ├── boxplot_company_rating.png 
│   └── iqr_outlier_counts.png 
│ 
└── README.md 
11. How to Run the Project 
Step 1 
Install Python 3.x. 
Step 2 
Install the required libraries: 
pip install pandas numpy matplotlib seaborn openpyxl 
Step 3 
Open the Jupyter Notebook: 
jupyter notebook 
Step 4 
Open: 
Task_1_India_Job_Market_Data_Cleaning.ipynb 
Step 5 
Run all cells from top to bottom. 
Step 6 
Review the generated: 
• Cleaned dataset 
• Encoded dataset 
• Reports 
• Visualizations 
• Data-quality results 
12. Major Findings 
The raw dataset contains 5,000 job records across 17 original fields. 
The dataset had: 
• No missing values 
• No duplicate records 
• Appropriate information for numerical and categorical analysis 
• Potential outliers in salary, openings, and applicant counts 
The IQR method identified potential extreme observations, but these were retained and flagged 
because they may represent genuine job-market conditions. 
The dataset was standardized and converted into an analysis-ready format. 
 
13. Business Use Cases 
The cleaned dataset can be used for further analysis such as: 
• Most in-demand job roles 
• Salary comparison by industry 
• Salary comparison by city 
• Remote vs on-site job analysis 
• Experience level analysis 
• Most requested technical skills 
• Company rating analysis 
• Applicant-to-opening ratio 
• Job posting trends over time 
• Industry-wise hiring analysis 
• Location-wise job opportunities 
 
14 . Future Improvements 
Future versions of the project can include: 
• Exploratory Data Analysis (EDA) 
• Interactive dashboards 
• Salary distribution analysis 
• Job demand forecasting 
• Skill-demand analysis 
• Machine-learning models 
• Job recommendation systems 
• City-wise employment analysis 
• Industry-wise salary prediction 
 
15. Conclusion 
The India Job Market 2024–2026 dataset was successfully cleaned and prepared for further data 
analysis. 
The project addressed the major data-quality requirements including: 
• Dataset exploration 
• Missing-value validation 
• Duplicate validation 
• Column standardization 
• Data-type correction 
• Text cleaning 
• IQR-based outlier detection 
• Categorical encoding 
• Final validation 
• Cleaned dataset export 
The resulting dataset is suitable for Data Analysis, Data Visualization, Business Intelligence, and 
Machine Learning applications. 
16 . Author 
Name: Megha Bidwe 
Project: Data Cleaning Project – Task 1 
Dataset: India Job Market 2024–2026 
Tools: Python, Pandas, NumPy, Matplotlib, Seaborn 
Environment: Jupyter Notebook / Google Colab 
