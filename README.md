📌 **Project Overview** :

This project focuses on analyzing digital payment performance in India by comparing UPI and IMPS transaction datasets using Python-based data analytics techniques.

The main objective was to collect, clean, analyze, and visualize transaction data to understand growth trends, seasonal patterns, transaction behavior, and bank participation.

The analysis was performed using Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Plotly.

The project evaluates important digital payment metrics including:

📊 Transaction Volume (Mn.)

💰 Transaction Value (₹ Cr.)

🔎 Average Transaction Value

🏦 Bank Participation

The dataset contains monthly transaction information from April 2016 to March 2026, sourced from NPCI official statistics.

**🚀 Tech Stack** :

1.Python

2.Pandas

3.NumPy

4.Matplotlib

5.Seaborn

6.Plotly

7.Google Colab

**⚡ Python Concepts Used: **

1.Data Cleaning & Preprocessing.

2.Feature Engineering (Growth %, Financial Year Mapping, Quarter Extraction).

3.Exploratory Data Analysis (EDA).

4.Statistical Analysis (Mean, Variance, Skewness, Kurtosis).

5.Data Visualization (Bar Charts, Line Graphs, Heatmaps).

6.Business Insight Generation.

**📥 Dataset Information**:

Data Source: NPCI Official Product Statistics https://www.npci.org.in/product/upi/product-statistics and https://www.npci.org.in/product/imps/product-statistics

Domain: Digital Payments / Financial Analytics.

Timeline: April 2016 – March 2026.

Attributes: Transaction Volume, Transaction Value, Average Transaction Value, Bank Participation.

**🧹 Data Cleaning & Feature Engineering**:

✅ Checked dataset structure and data types.

✅ Removed duplicates and handled missing values.

✅ Converted month column into datetime format.

✅ Standardized transaction values to numeric.

✅ Derived features: Financial Year, Growth %, Quarter, Average Transaction Value,etc

**🎯 Project Objectives**:

1.Compare UPI vs IMPS transaction performance (2016–2026).

2.Analyze growth trends and seasonal variations.

3.Study transaction behavior (volume, value, average value).

4.Evaluate bank participation and adoption patterns.

5.Evaluate transaction efficiency across UPI and IMPS.

6.Evaluate bank utilization and participation patterns.

7.Compare value efficiency per million transactions.

8.Generate business insights for policymakers and banks.

**
📊 Exploratory Data Analysis**:

🔹 Transaction Volume Analysis
UPI mean volume = 6,079.21 Mn.

IMPS mean volume = 300.10 Mn.  

👉 UPI dominates in transaction count.

🔹 Transaction Value Analysis
UPI mean value = ₹8,92,022 Cr.

IMPS mean value = ₹3,26,927 Cr.  
👉 UPI handles larger overall value, but IMPS is strong in high-value transfers.

🔹 Average Transaction Value
UPI = ₹175.74

IMPS = ₹1,025.64  
👉 IMPS dominates in per-transaction value.

🔹 Bank Participation
UPI: 21 → 705 banks

IMPS: 143 → 971 banks
👉 Both platforms show strong institutional adoption.

**📈 Statistical Analysis**:

1.UPI shows higher variance & volatility in growth.

2.IMPS shows stable distribution with higher average transaction value.

3.Skewness: UPI positive (0.95), IMPS slightly negative (-0.21).

4.Kurtosis: Both flatter than normal distribution.



# Financial Year vs Transaction Growth %

<img width="851" height="533" alt="image" src="https://github.com/user-attachments/assets/fc010fa2-15f9-4bd8-881d-17c9c439e100" />


Interpretation:
UPI experienced rapid initial growth, peaking at around 37% in 2017–2018, before gradually stabilizing as the platform matured, while IMPS showed steady but slower growth throughout the study period.

Overall, the analysis indicates that UPI drove faster digital payment adoption, whereas IMPS maintained consistent and stable transaction growth, with both significantly contributing to India's digital payment ecosystem.

# Financial Year vs Number of Banks

<img width="870" height="533" alt="image" src="https://github.com/user-attachments/assets/9a1c1f17-f866-4ce2-b6fb-df2fe9509387" />

Interpretation:
UPI expanded rapidly from around 30 banks in 2016–17 to nearly 700 banks by 2025–26, while IMPS maintained broader participation, increasing from approximately 180 to 950 banks over the same period.

Overall, both payment systems showed consistent growth in bank participation, with UPI demonstrating faster expansion and IMPS retaining wider banking coverage, strengthening India's digital payment infrastructure.

# UPI vs IMPS - Transaction Efficiency Index Trend Analysis

<img width="1584" height="492" alt="image" src="https://github.com/user-attachments/assets/8b582266-c7e4-4036-9339-3d56b1325c10" />

Interpretation:

UPI's Transaction Efficiency Index increased dramatically from 2016 to 2026, significantly outperforming IMPS, which experienced moderate growth before stabilizing after 2022.

Overall, the analysis indicates that UPI achieved higher operational efficiency and faster scalability, while IMPS maintained stable transaction handling performance throughout the study period.

# UPI vs IMPS - Bank Utilization Ratio Trend Analysis

<img width="1584" height="492" alt="image" src="https://github.com/user-attachments/assets/187a0eeb-4400-46b7-a98c-ea102b8aebc7" />

Interpretation:

UPI's Bank Utilization Ratio increased significantly from approximately 0 in 2016 to around 30 by 2026, whereas IMPS rose from about 0.2 to a peak of 0.7 in 2022 before declining to nearly 0.3 by 2026.

Overall, UPI demonstrated substantially higher bank utilization and stronger institutional expansion, while IMPS exhibited moderate growth followed by a gradual decline, reflecting the increasing preference for UPI-based digital payments.

# UPI vs IMPS - Value per Million Transaction Trend Analysis

<img width="1583" height="492" alt="image" src="https://github.com/user-attachments/assets/04fd7ba2-cd4b-4ba2-8248-fa310d6e884d" />

Interpretation:

UPI's Value per Million Transaction peaked at approximately 500 during 2016–2017 and later stabilized between 100 and 200 from 2018 to 2026, whereas IMPS fluctuated around 1,000–1,500 before rising sharply to nearly 2,000 by 2026.

Overall, UPI exhibited stable value efficiency following widespread adoption, while IMPS recorded a substantial increase of approximately 500 units between 2024 and 2026, indicating stronger growth in high-value transactions.

Summary of Findings

1. Financial Year vs Transaction Growth (%)

UPI recorded substantially higher transaction growth than IMPS during the study period, indicating faster adoption and stronger expansion of digital payments in India.

2. Financial Year vs Number of Banks

The number of participating banks increased consistently for both UPI and IMPS, with UPI exhibiting rapid institutional growth while IMPS maintained broader banking coverage.

3. UPI vs IMPS – Transaction Efficiency Index

UPI demonstrated significantly higher transaction efficiency than IMPS, reflecting its ability to process increasing transaction values with greater operational efficiency.

4. UPI vs IMPS – Bank Utilization Ratio

The Bank Utilization Ratio showed that UPI achieved more effective utilization of participating banks over time, whereas IMPS experienced comparatively slower utilization growth.

5. UPI vs IMPS – Value per Million Transaction

Value per Million Transaction analysis revealed that UPI maintained stable value efficiency after widespread adoption, while IMPS showed stronger growth in high-value transactions during the later years of the study.


**🧠 Key Business Insights**:

🏆 UPI dominates in volume & overall value, reflecting mass consumer adoption.

💰 IMPS dominates in average transaction value, highlighting corporate & interbank strength.

📈 UPI’s growth peaked at ~37% (2017–18) but stabilized later.

🏦 Bank participation expanded significantly for both platforms, confirming institutional support.

🔍 UPI powers everyday retail payments, while IMPS secures high-value transfers.

**💡 Business Recommendations**:

1.Expand UPI adoption in rural areas for financial inclusion.

2.Strengthen IMPS for corporate & interbank transfers.

3.Promote security & infrastructure upgrades for both systems.

4.Integrate UPI & IMPS for a complementary digital payment ecosystem.


conclusion:

The comparative analysis of UPI and IMPS from 2016 to 2026 demonstrates significant growth in India's digital payment ecosystem. UPI emerged as the leading payment system with superior transaction growth, operational efficiency, and bank utilization, while IMPS maintained stable performance and wider banking participation throughout the study period. Overall, the findings highlight the successful expansion of digital payment services and provide valuable insights for strengthening the future development of India's cashless economy.
