# 🍫 Data Meets Chocolate | Power BI Dashboard

Welcome to my **Chocolate Sales Dashboard**, where rich data meets rich flavor!  
This Power BI project transforms raw chocolate sales data into an interactive and insightful analytics experience that helps understand performance trends, profit behavior, and shipment efficiency across multiple time periods.

---

## 📖 Project Overview

The dashboard was designed to provide a **360° view of chocolate sales performance**, focusing on sales volume, profit margins, and shipment details.  
It highlights how operational efficiency, box sizes, and profit percentages influence total sales and business growth over time.

The main goal is to help stakeholders make **data-driven decisions** by visualizing key metrics and identifying trends through **time-intelligence measures**.

---

## 📊 Key Performance Indicators (KPIs)

The dashboard includes the following key metrics:

- **Total Sales:** Overall revenue generated from chocolate sales  
- **Total Boxes:** Total number of boxes sold  
- **Total Shipments:** Total completed deliveries  
- **Total Cost:** Overall expenditure incurred during production and shipment  
- **Total Profit:** Difference between revenue and cost  
- **Profit %:** Percentage of profit compared to sales  
- **Low Box Shipments (LBS):** Count of shipments with low box quantities  
- **Low Box Percentage (LBS%)**: Ratio of low box shipments to total shipments  
- **Month-on-Month (MoM) Changes:** Growth or decline in metrics compared to the previous month  
- **Year-on-Year (YoY) Changes:** Annual performance comparison for long-term trends  

---

## 🧩 Data Modeling & DAX Development

The data model follows a **Star Schema**, ensuring efficient relationships between fact and dimension tables for faster report performance and simplified DAX calculations.

### Data Modeling Highlights:
- Designed **Fact and Dimension tables** (Sales, Shipments, Product, Date, Region)
- Established **relationships** for clean, logical data connections
- Created a **Dedicated Measure Table** for organized and scalable DAX measures

### DAX Measures Developed:
- Profit Calculation (`Total Profit = [Total Sales] - [Total Cost]`)
- Profit Margin Percentage  
- MoM & YoY Change Calculations using **Time Intelligence Functions**  
- Dynamic KPIs linked to slicers and date filters  

---

## 🎨 Power BI Visualizations & Features

### Visualization Techniques:
- **New Card Visuals:** Display KPIs with reference labels for intuitive insights  
- **Dynamic Trend Chart:** Created using Field Parameters for flexible metric comparison  
- **Gauge Chart:** Highlights Profit % and LBS % at a glance  
- **Histogram (Group Feature):** Shows distribution of box sizes and shipment volumes  
- **Conditional Formatting:** Emphasizes key trends in profit and sales tables  
- **Bookmarks:** Designed multiple dashboard views for detailed analysis and storytelling  
- **Zoom Slider:** Allows users to interactively analyze trends across custom time ranges  

### Design Principles:
- Clean, minimalist design using brand-inspired colors  
- Intuitive layout for quick insights  
- Emphasis on storytelling — each chart narrates part of the data journey  

---

## 🧠 Challenges Solved

- Fixed **DAX calculation conflicts** between different date hierarchies  
- Resolved **bookmark filter issues** to preserve selected states  
- Optimized **refresh time and performance** with efficient data relationships  
- Created **dynamic visuals** without overwhelming the viewer  

---

## 💡 Insights & Outcomes

This dashboard revealed several interesting insights:
- Certain months show consistent growth in profit despite fewer shipments — indicating **higher efficiency**.
- The LBS% metric helped identify inefficiencies in shipping patterns.
- Seasonal variations significantly impacted both total sales and box volumes, showing strong potential for **seasonal marketing strategies**.

---

## 🛠 Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| BI Tool | Power BI |
| Language | DAX (Data Analysis Expressions) |
| Data Modeling | Star Schema |
| Visualization | Power BI Dashboard |
| Analytics | MoM & YoY Calculations, KPI Analysis |

---

## 🖼 Dashboard Preview
*(You can upload your screenshot and rename it as `dashboard-preview.png`)*  
```markdown
![Chocolate Sales Dashboard Preview](dashboard-preview.png)

<img width="1920" height="1200" alt="Screenshot 2025-10-28 140750" src="https://github.com/user-attachments/assets/5481cf97-b2e9-403c-a94e-24197dd61223" />
