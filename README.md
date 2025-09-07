# Customer service Analysis 📞


## 📊 Project Overview
This project analyzes **call center customer service performance** using **Power BI**.  
It provides insights into **agents’ efficiency, effectiveness, and the impact of dropped calls on sales**.  

The dashboards allow managers to track performance, identify top/low performers, and detect where coaching or process improvements are needed.





https://github.com/user-attachments/assets/487ceb37-0712-4258-a128-1b8ceb94a363





---

## 🛠 Steps Performed
- 📥 Imported data from **database (2024)** and **Excel sheet (2025)**.  
- 🔍 Checked column data types and performed **data cleaning**.  
- 🔗 Appended the two tables into one unified table called **`Datasets`**.  
- 📅 Created a **Date Table** with DAX and built relationships in the data model.  
- 📐 Created a **Measures Table** for important KPIs.  
- 📊 Calculated KPIs including:
  - Total Calls (with comparisons to LM, LQ, LY).  
  - Reached Calls.  
  - Closed Deals.  
  - Deal Values.  
- 📞 Added calculated columns/measures:
  - **Dropped Calls**.  
  - **Answer Rate** = Reached Calls / Total Calls.  
  - **Average Call Duration (minutes)**.  
  - **Conversion Rate**.  
- 🖼 Built two dashboards:
  - **Overview Dashboard** → High-level business summary.  
  - **Track Agents Performance Dashboard** → Agent-level KPIs, efficiency, and training needs.  

---

## 🎯 Key Business Questions
- How many calls were received, answered, and dropped?  
- Which agents are the **top performers** and which need **coaching**?  
- What is the **conversion rate per agent**?  
- How do **dropped calls** impact sales?  
- Are KPIs improving compared to **last month/quarter/year**?  

---

## 📌 KPIs Tracked
- Total Calls  
- Total Calls Reached  
- Answer Rate %  
- Dropped Calls %  
- Average Call Duration (minutes)  
- Conversion Rate %  
- Closed Deals & Sales Value  

---

## 📷 Dashboards
### Overview Dashboard
![customer services_page-0002](https://github.com/user-attachments/assets/71c68f39-4bee-4fcc-861c-d74760f17294)


### Track Agents Performance
![customer services_page-0003](https://github.com/user-attachments/assets/ce490b93-9141-4864-a15a-f77d37ebd91f)





## 📈 Insights
- **Top performers** close more deals with fewer calls → showing strong sales efficiency.  
- **High Dropped Calls %** during peak hours caused ~15% loss in potential deals.  
- **Pareto effect (80/20 rule):** 20% of agents generated ~75% of the total sales value.  
- **Agent X** handles the most calls but has one of the lowest conversion rates → needs coaching in sales closing techniques.  
- **Agent Y** makes fewer calls but achieves the highest conversion rate → can be used as a benchmark for best practices.  
- Agents with **long call duration + low conversion** → need training in improving efficiency and focusing conversations.  
- Agents with **short calls + high drop rate** → need training in customer engagement and call handling.  
- Monthly trend shows **Conversion Rate improved in Q2 vs Q1**, likely due to training or process changes.  
- **Dropped Calls spike** at the end of each month → suggests a system/process bottleneck during reporting/target-closing days.  


## ⚙️ Tech Stack
- **Power BI** (Data Modeling + Visualization)  
- **Excel & Database** (Data Sources)  
- **DAX** (Calculated Columns & Measures)  
