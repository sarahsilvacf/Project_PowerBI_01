🌱 Agricultural Production Analysis - Power BI Dashboard

  🌍 Overview

Interactive dashboard analyzing production volumes across Brazilian states (2019-2023), featuring:

📂 Annual quantity trends

📂 Regional performance benchmarking

📂 Key productivity insights

📊 Core Metrics

DAX
Total Production Region = 
SUM('Production-State'[Quantidade Produzida])

// YoY Growth Calculation
VAR CurrentProd = [Total Production]
VAR PriorProd = CALCULATE([Total Production], SAMEPERIODLASTYEAR('Date'[Date]))
RETURN DIVIDE(CurrentProd - PriorProd, PriorProd, 0)

🛠 Technical Stack

Component	Details
Data Model	Star schema (3M+ rows optimized)
DAX	50+ measures, time intelligence
Visuals	Custom tooltips, bookmarks

🖼️ Dashboard Highlights

🔍 📈 1. Production Timeline
Annual Trend
Identified 22% YoY growth in 2022 harvest season

🔍 🗺️ 2. Regional Heatmap
Regional View
Top 3 producing states: MT, PR, RS

🔍 🌽 3. Crop Performance
Top Crops
Corn accounted for 58% of total volume

📬 Connect: LinkedIn Profile https://www.linkedin.com/in/sarah-silva-0b9061142/

📌 Dataset Sources: IBGE SIDRA  https://sidra.ibge.gov.br/

  
![Visual_Production](https://github.com/user-attachments/assets/e004a582-4eb4-4b7c-8365-e74e115521e1)






