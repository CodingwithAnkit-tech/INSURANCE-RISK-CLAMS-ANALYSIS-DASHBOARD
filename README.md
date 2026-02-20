# 📌 Project Overview

- This project focuses on analyzing insurance policyholders, vehicle details, and claim patterns to generate meaningful business insights using Power BI.
- The goal of this dashboard is to help insurance companies:
- Understand customer risk profiles
- Track claim trends and financial exposure
- Identify high-risk segments
- Optimize premium pricing strategies
- Support data-driven business decisions
- This interactive Power BI dashboard centralizes scattered insurance data into a single analytical view.

# 🎯 Business Requirement

- The insurance company wanted to:
- Track overall policy performance
- Monitor total claim exposure
- Analyze claim frequency and severity
- Understand demographic and vehicle-based risk factors
- Identify high-risk customer segments
- This dashboard solves those problems through KPI tracking and advanced visual analytics.

# 📊 Key Performance Indicators (KPIs)

- The dashboard includes the following core KPIs:

1️⃣ Total Policies

Measures total active policyholders.

2️⃣ Total Claim Amount

Tracks total financial loss due to claims.

3️⃣ Claim Frequency

Analyzes how often claims are filed.

4️⃣ Average Claim Amount

Helps measure claim severity.

5️⃣ Gender-wise Total Policies

Understands customer distribution across gender groups.

# 📈 Visualizations & Insights

- All visuals are designed around two dynamic measures:
- Total Policies
- Total Claim Amount

🚘 1. By Car Use (Donut Chart)

Compares Personal vs Commercial vs Commute usage

Identifies high-risk usage patterns

🚗 2. By Car Make (Bar Chart)

Analyzes claims by vehicle brand

Detects high-maintenance or high-risk brands

🌍 3. By Coverage Zone (Donut Chart)

Regional risk comparison

Urban vs Rural claim patterns

👥 4. By Age Group (Histogram)

Identifies age groups with higher claim frequency

Supports age-based premium pricing

📅 5. By Car Year (Area Chart)

Studies impact of vehicle age on claims

Older vs newer car risk exposure

👨‍👩‍👧 6. By Kids Driving (Ribbon Chart)

Analyzes impact of young drivers in household

Higher kids driving → higher accident probability

🎓 7. By Education (Pie Chart)

Studies correlation between education and claims

🔥 8. Education & Marital Status (Matrix Heat Grid)

Identifies high-risk customer profiles

Combines demographic risk factors

# 🗂 Dataset Description

The dataset includes:

 👤 Customer Demographics

- ID
- Birthdate (used to calculate Age)
- Gender
- Marital Status
- Education
- Parent
- Household Income
- Kids Driving

🚘 Vehicle Details

- Car Make
- Car Model
- Car Year
- Car Color
- Car Use
- Coverage Zone

💰 Claims & Financial Data

- Claim Amount
- Claim Frequency

🔎 Business Insights Generated

This dashboard helps identify:

✔ High-frequency claim segments
✔ High-severity claim customers
✔ Risk based on vehicle type
✔ Regional accident trends
✔ Household-based risk exposure
✔ Demographic-based pricing strategies

# 🛠 Tools & Technologies Used

- Power BI
- Data Modeling
- DAX Measures
- Data Cleaning & Transformation
- Interactive Dashboard Design

# 🧮 Important DAX Measures Used

- Total Policies = COUNT(ID)
- Total Claim Amount = SUM('Table'[Claim Amt])
- Claim Frequency = SUM('Table'[Claim Freq])
- Average Claim Amount = 
- DIVIDE([Total Claim Amount], [Claim Frequency])
  
# 📌 Business Value Delivered

- This solution enables:
- Risk profiling
- Premium optimization
- Fraud detection signals
- Customer segmentation
- Strategic underwriting decisions

# 📷 Dashboard Preview

<img width="1255" height="746" alt="dasboard image" src="https://github.com/user-attachments/assets/cefc39e7-a345-4133-b580-537496163a76" />


# 🚀 Future Improvements

- Predictive modeling using Machine Learning
- Loss ratio analysis
- Fraud detection modeling
- Customer churn prediction
- Integration with real-time insurance systems

# 👨‍💻 About Me

Ankit Verma
B.Tech CSE | Data Analytics Enthusiast
Power BI | Python | SQL | Machine Learning

⭐ If You Like This Project

Please consider giving it a ⭐ on GitHub!


