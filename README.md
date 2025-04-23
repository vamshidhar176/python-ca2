  📊 Serious Injury Outcome Indicators (2000–2023)
🔍 Overview
This project analyzes serious injury outcomes in New Zealand from 2000 to 2023. It covers key metrics such as injury rates, severity levels, affected population groups, and causes (like transport crashes, assaults, and falls). The goal is to extract insights using statistical methods, visualizations, and correlation analysis to support public health decision-making.
 
📁 Dataset
Source: Government public health records

Format: CSV (Comma-Separated Values)

Records: 3,094 rows  

Key Fields:
     
Period: Rolling time intervals (e.g., 2000–02) 

Data Value: Injury count or rate

Cause: Type of incident (e.g., Falls, Assault)

Population: Group affected (e.g., Whole pop, Māori, Children)

Severity: Injury level (e.g., Fatal, Serious)

✅ Project Objectives
Data Cleaning & Preprocessing

Statistical Analysis

Data Visualization

Correlation Analysis

Predictive Analysis

Understanding Variable Relationships

Outlier Detection

1️⃣ Data Cleaning & Preprocessing
Converted time periods into numerical mid-years (e.g., 2000–02 → 2001)

Verified data types and ensured consistency

Handled missing data (minimal in this dataset)

Added columns for time-based and grouped analysis

2️⃣ Statistical Analysis
Descriptive statistics revealed the average injury rates

Calculated measures like mean, median, and standard deviation

Found wide variance in certain years and severity levels

Severity categories showed distinctly different value ranges

3️⃣ Data Visualization
🔹 Top 10 Causes of Serious Injuries
A bar chart highlighted the most impactful causes such as:

Motor vehicle traffic crashes

Falls

Assault

Work-related injuries

🔹 Injury Rate Over Time
A line chart showed the trend of average injury rates across years, revealing:

Some fluctuations

A few spikes indicating specific years of high injury events

🔹 Injury Severity Distribution
A pie chart showed:

Majority of cases are Serious non-fatal

Smaller portions are Fatal

🔹 Age Group Analysis
A column graph showed which age groups experienced the highest injury rates — elderly and children stood out in different categories.

4️⃣ Correlation Analysis
A heatmap and pair plot were used to check:

High correlation between Data_value, Lower_CI, and Upper_CI

Mild correlation between Year and injury trends (useful for prediction)

Relationship insights between confidence intervals and actual values

5️⃣ Predictive Analysis
Injury rates plotted over time showed patterns that can guide forecasting

Predictive models (e.g., Linear Regression) can be added for future projections

Trend lines indicated gradual increase in some injury categories

6️⃣ Relationship Between Units and Causes
Causes with higher average values were plotted

Found strong positive correlation between certain causes and injury rates

Visualized with pair plots and heatmaps for deeper interpretation

7️⃣ Outlier Detection
Boxplots identified outliers, especially in Data_value

Z-score method showed few extreme values (possible recording errors or real anomalies)

Helps highlight years with unusually high injury counts

📌 Key Insights
Top Causes: Motor vehicle crashes, Falls, Assault

Most Affected Groups: Elderly (falls), Young adults (assault), Children (varied causes)

Severity Matters: Fatal cases have different distribution and impact

Trends: Some types of injuries show increase over time

Correlations: Confidence intervals closely align with actual data values

📈 Visual Gallery
Bar Chart: Top 10 Causes by Average Injury Rate

Line Chart: Trend Over Time (2000–2023)

Pie Chart: Severity Distribution

Column Chart: Average Data Value by Age Group

Heatmap: Correlation Matrix

Pair Plot: Variable Relationships

Boxplot: Outlier Detection

Scatter Plot: Injury Rate vs Confidence Intervals

🔮 Future Scope
Add location-based mapping (heatmaps of hotspots)

Integrate real-time injury reporting (live dashboards)

Use machine learning for risk prediction and classification

Extend demographic fields (income, occupation, etc.) for deeper insights

👨‍🎓 About the Project
Submitted by: M. Vamshidhar Reddy

Course: INT375 – Data Science Toolbox

Semester: January–April 2025

University: Lovely Professional University

Under the Guidance of: Mrs. Aashima

📚 References
Dataset: Serious Injury Indicators

Python Libraries: Pandas, NumPy, Seaborn, Matplotlib

Techniques: EDA, Correlation, Z-score, IQR, Visualization

