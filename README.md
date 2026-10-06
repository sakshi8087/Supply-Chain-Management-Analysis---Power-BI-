<div align="center">
📦 AtliQ Mart FMCG Supply Chain Dashboard
📊 Power BI | DAX | Supply Chain Analytics

Show Image Show Image Show Image

</div>

🎯 Power BI dashboard built for the Codebasics Resume Project Challenge. Instead of a mock-up, the challenge gave a conversation between company stakeholders and a data analyst. From that conversation, I identified the requirements and built a dashboard that gives stakeholders an overall view of supply chain performance and helps them find the causes of delivery problems.

#codebasicsresumeprojectchallenge

📑 Table of Contents
🔗 Quick Links
❓ Business Problem
🖥️ Dashboard Overview
📐 Key Metrics
💡 Key Insights
✅ Recommendations
🛠️ Tools and Skills
👩‍💻 Author
🔗 Quick Links
Resource	Link
🏆 Challenge	Codebasics Resume Project Challenge
🌐 Interactive Dashboard	[add your hosted link]
💼 LinkedIn Post	[add your post link]
📜 Certificate	[add your certificate link]
❓ Business Problem

AtliQ Mart is an FMCG company whose stakeholders were concerned about supply chain performance, especially orders that were late or not delivered in full. They needed a dashboard that:

📈 Shows overall delivery performance at a glance
🔍 Helps identify which cities, customers, and products are underperforming
🔮 Supports planning with a view of expected future demand
🖥️ Dashboard Overview

The report has three main dashboards plus a conclusion section.

1️⃣ Executive Summary
Section	Details
🎯 KPIs	On-Time Delivery %, On-Time In-Full (OTIF) %, In-Full (IF) %
🧮 Cards	Total Orders, Total Orders Shipped, Orders Not Shipped, Total Order Quantity

📊 Charts

🔄 Metric trend by month: A field parameter lets the user switch between VOFR %, LIFR %, On-Time %, and IF %, and the line chart shows the selected metric by month.
🏙️ Order count by month and city
📦 Total orders by category (line)
🌆 Total orders by city
2️⃣ Product Insights
Section	Details
🎛️ Filters	Slicers for product name and category name, with product name styled as tabs
🧮 Cards	Volume Fill Rate %, Line Fill Rate %, Best city by OTIF %, Worst city by OTIF %, Best product by OTIF %

📊 Visuals

🧾 Matrix table: city, product name, total order lines, LIFR %, VOFR %
⏰ Delay in delivery: stacked bar by product showing 1, 2, and 3 days late
🔮 Order quantity forecast: Actual order quantity for Mar-Aug, with Power BI's forecast projecting Sep-Nov (30-day seasonality, 95% confidence band)
3️⃣ Performance Analysis
🗂️ Split tables: performance split by customer and by city
📊 Chart: ordered quantity vs. undelivered quantity for each city, broken down by customer
🏙️ City slicer styled as tabs
🔎 Drill-through pages for customer and city
🎚️ Filters for date, week number, month, and customer name
🏁 Conclusion Pages
📝 Conclusion: summary of overall performance
💡 Insight 1: [add title and one-line finding]
💡 Insight 2: [add title and one-line finding]
🖼️ Screenshots

Executive Summary

<img width="683" height="359" alt="image" src="https://github.com/user-attachments/assets/52581647-bdc5-4dcd-8903-0ebfe16eb2d9" />

Product Insights

<img width="677" height="356" alt="image" src="https://github.com/user-attachments/assets/fbbe3cf5-0a0d-43ed-a03e-f330d50b63a8" />

Performance Analysis

<img width="694" height="365" alt="image" src="https://github.com/user-attachments/assets/be8c9aca-dba5-4783-8faa-c0f9b5516921" />

Conclusion

<img width="679" height="363" alt="image" src="https://github.com/user-attachments/assets/1c87aa2a-9810-4f28-9f7f-5e5f6d1073a1" />

📐 Key Metrics
Metric	Meaning
⏱️ On-Time %	Share of orders delivered on or before the agreed date
📦 In-Full % (IF)	Share of orders delivered with the full quantity
✅ OTIF %	Share of orders that were both on time and in full
🧾 LIFR % (Line Fill Rate)	Order lines delivered in full out of total order lines
📏 VOFR % (Volume Fill Rate)	Quantity delivered out of quantity ordered
💡 Key Insights
🔍 Product Insights Page
📉 Volume vs. line fill: Volume Fill Rate is 96.59%, but Line Fill Rate is only 65.96%. Most of the ordered quantity is delivered, but only about two-thirds of order lines are delivered in full.
🏙️ City performance: Surat is the best city by OTIF and Vadodara is the worst. Vadodara's LIFR (about 62-65% by product) is lower than Surat's and Ahmedabad's (about 65-68%).
🏆 Best product: Tea is the best product by OTIF.
⏰ Delay pattern: For every product, most late deliveries are 1 day late. Few are 3 days late, so delays are frequent but short.
🔮 Order Quantity Forecast (Sep-Nov)
📊 From Mar to Aug 2022, daily order quantity stayed fairly stable at about 65K-85K, with no strong upward or downward trend.
🔁 A forecast with 30-day (monthly) seasonality was applied to project Sep-Nov. For Sep 1, it predicts about [X]K orders, with a 95% confidence range of 47K to 70K.
⚠️ The forecast starts below the recent average, likely because of a sharp drop in the last days of August that looks like incomplete data and not a real fall in demand.
📐 The confidence band is wide, so the forecast is a directional estimate and not an exact prediction. With only six months of history, it can't capture yearly seasonality such as festival peaks.

<img width="675" height="353" alt="image" src="https://github.com/user-attachments/assets/172c89c5-2a46-4e2e-b165-2f8688b4c42f" />
<img width="676" height="355" alt="image" src="https://github.com/user-attachments/assets/b1de3aac-5c39-4e80-9e96-f9f0a8458487" />
<img width="680" height="350" alt="image" src="https://github.com/user-attachments/assets/cc70d762-3f6f-4650-b2f0-51a4770451f2" />



✅ Recommendations
🎯 Focus on improving in-full delivery at the order-line level, since the gap between LIFR and VOFR is large.
🔧 Investigate the causes of low OTIF in Vadodara and apply practices from Surat.
📦 Plan inventory and delivery capacity using the forecast range and not a single number, and re-run the forecast as more data arrives.
🛠️ Tools and Skills

Tools: Power BI DAX Power Query

Skills demonstrated:

🗣️ Requirement gathering from a stakeholder conversation
🧩 Data modeling and DAX measures
🎛️ Field parameters, forecasting, drill-through, and tab-style slicers
📊 Dashboard design and data storytelling

Dataset: Provided by Codebasics as part of the challenge.

🚀 How to Use This Repository
📥 Download the .pbix file from this repository.
💻 Open it in Power BI Desktop.
🔄 Refresh the data if prompted.
👩‍💻 Author

Sakshi Dhobale 📍 Mumbai, India 📧 dhobalesakshi5102@gmail.com 🔗 LinkedIn | GitHub

<div align="center">

⭐ If you found this project useful, consider giving it a star! ⭐

</div>
