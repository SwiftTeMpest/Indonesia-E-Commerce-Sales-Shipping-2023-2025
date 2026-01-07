# **Project Background**
RetailCo is a fictional mid-sized retail fashion company in Indonesia established in 2021. The company sells its product via retail, wholesale and through their stores that is located at Jakarta, Bandung, Surabaya, Medan, and Denpasar.

The company has significant amounts of data on its transactions including products, customers, and revenue for 2024. This project thoroughly analyzes and synthesizes this data in order to uncover critical insights that would improve RetailCo commercial success as if it was a real company.

Insights and recommendations are provided on the following key areas:

* Sales Trends Analysis: Evaluation of sales patterns for 2024 focusing on Revenue, Order Volume, and Average Order Value (AOV).
* Regional Comparison: An analysis of RetailCo various Stores by Region, understanding their performance on sales and orders.
* Customer Type Analysis: An assessment of customers method of purchase impact on sales and orders.
* Product Analysis: An evaluation of sales and orders by products.

An interactive Tableau dashboard can be downloaded [here](https://github.com/SwiftTeMpest/Indonesia-E-Commerce-Sales-Shipping-2023-2025/raw/refs/heads/main/RetailCO%20Analysis%20Project.twbx).


# **Data Structure and Intitial Checks**
RetailCo database structure as seen below consists of three tables: Transaction, Csutomer, and Store, with a total row count of 750 records.

<img width="1044" height="612" alt="Opera Snapshot_2025-12-29_122729_dbdiagram io" src="https://github.com/user-attachments/assets/ef37f6fb-bd72-4aee-b0f1-e59461b4a7d9" />


# **Executive Summary**

### **Overview of Findings**
The company sustained positive sales momentum into the most recent period, building on performance from 2023. All core performance indicators improved year over year, with order volume rising 22%, average order value increasing 10%, and revenue growing 1%. These results reflect a combination of operational and market-driven factors. The following sections provide an overview of the primary drivers of performance and outline key opportunities to further accelerate growth.

Below is the overview page from the tableau dashboard and more examples are included throughout the report. The entire interactive storyboard can be downloaded [here](https://github.com/SwiftTeMpest/Indonesia-E-Commerce-Sales-Shipping-2023-2025/raw/refs/heads/main/RetailCO%20Analysis%20Project.twbx).

<img width="1673" height="936" alt="Screenshot (2186)" src="https://github.com/user-attachments/assets/815f656e-aacc-44c4-84a1-3b10ece019e8" />


### **Sales Trends Analysis**:
* Sales performance showed significant month-over-month volatility, with order volume ranging from a low of 43 orders in August to a peak of 99 orders in December.

* Revenue fluctuations were primarily volume-driven, with major increases in May (+94% MoM) and December (+102% MoM), aligned with order growth of +41% and +80%, respectively.
  
* Average order value (AOV) remained relatively stable, averaging approximately Rp1.1M, with notable increases in May (+38% MoM) and September (+5% MoM).

* AOV compression in April (-23% MoM) and October–November (-9% to -12%) exacerbated revenue softness despite moderate order volumes.

<img width="1674" height="930" alt="Screenshot (2187)" src="https://github.com/user-attachments/assets/fa12275f-b283-41a0-a204-074e87d102d7" />

### **Regional Comparison**:
* Surabaya emerged as the top-performing region overall, generating the highest monthly revenue peaks, including a high of approximately Rp28M, and consistently ranking among the top two regions throughout the year.

* Medan demonstrated episodic spikes, reaching approximately Rp23M in mid-year, followed by sharp pullbacks, indicating event-driven or less consistent demand.

* Revenue concentration remains skewed toward Java, with Surabaya, Jakarta, and Bandung collectively accounting for the majority of sales, highlighting continued growth opportunities in underpenetrated regions outside Java.

<img width="1662" height="934" alt="Screenshot (2188)" src="https://github.com/user-attachments/assets/781b6bdd-41a8-4cff-be0e-84aad3f5e6c6" />


### **Customer Type Analysis**:
* Retail customers were the largest revenue contributors overall, with monthly revenue frequently ranging between Rp20M–Rp45M and delivering the single highest monthly peak at approximately Rp47M, indicating strong in-store or direct-to-consumer demand.

* Online sales showed higher volatility, fluctuating between Rp9M and Rp31M per month, suggesting sensitivity to campaigns, traffic, and conversion performance rather than steady baseline demand.

* Average order value (AOV) varied meaningfully by customer type, with Online delivering the highest AOV in Q1 and Q3 (~Rp1.2M+), while Wholesale peaked in Q4 (~Rp1.2M), indicating larger basket sizes during end-of-year bulk purchasing.

* Wholesale revenue was more episodic but capable of outsized impact, spiking to approximately Rp42M in peak months while dropping sharply in off-cycle periods, reflecting deal-based or contract-driven purchasing behavior.

<img width="1654" height="919" alt="Screenshot (2189)" src="https://github.com/user-attachments/assets/3943a477-9929-4e42-81e9-c2719335438d" />

### **Product Analysis**:
* The top performing products are P015, P018, and P012 with shares of 5.55%, 5.24%, and 5.17% respectively. These three products accounted for Rp131,234,700 in revenue in 2024.

* The lowest performing product is P010 with share of 2.38% of total revenue, bringin in RP19,570,500 in 2024. This is followoed by the equally underperforming P006 and P017.

* The popularity of P015 are sustained by Online customers alone with P015 being the top products in online category while not being top 5 product in either wholesale or retail category.

<img width="1656" height="926" alt="Screenshot (2190)" src="https://github.com/user-attachments/assets/b6c13eb4-a9db-45d7-9994-27719dd263e6" />


### **Recommendations**:
Based on the uncovered insights, the following recommendations have been provided:

* Strengthen volume-driven growth by stabilizing monthly order flow to reduce volatility, leveraging proven peak periods (May and December) where order growth (+41% to +80%) drove outsized revenue gains (+94% to +102% MoM).

* Double down on retail-led performance, as retail customers consistently contribute the largest and most stable revenue stream (Rp20M–Rp45M monthly, with peaks ~Rp47M), indicating strong direct and in-store demand.

* Use wholesale selectively for revenue uplift, activating deal-based or contract-driven campaigns during high-demand cycles to capture outsized revenue spikes (up to ~Rp42M) while avoiding over-reliance in off-cycle periods.

* Expand beyond Java to diversify revenue concentration, building presence in underpenetrated regions outside Surabaya, Jakarta, and Bandung to unlock incremental growth and increase overall product revenue share beyond the current 2.38%–5.55%.

* Optimize and scale high-performing products across the 25 product range, leveraging the increase in revenue contribution from Rp19.6M to Rp45.6M (2.38%–5.55% share) by prioritizing top Stock Keeping Units (SKU), rationalizing underperformers, and aligning product availability with peak demand periods to maximize revenue impact.

