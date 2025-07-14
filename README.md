# 📞 Call Center Performance Dashboard

## 📊 About the Project
An interactive Power BI dashboard designed to analyze call center performance. It uses a star schema data model, advanced DAX, calculation groups, KPIs, and field parameters.

---

## 🧱 Data Model (Star Schema)
- Fact Table: `CallCenterLogs`
- Dimension Tables:
  - `DimAgent`
  - `DimComplaintType`
  - `DimClient`
  - `DimDate`

---

## 📈 Key Metrics (KPIs)
- Total Complaints
- Avg. Service Duration
- % Excellent (PerformanceLevel = "Fast")
- Peak Hour & Busiest Day
- Call End Category Distribution

---

## 🧠 Advanced Features
- Calculation Groups (Time Intelligence, Formatting)
- Field Parameters for dynamic visuals
- Heat Maps, Donut Charts, KPI Cards, and Slicers
- Dynamic Overview Page + Performance Page + Time Analysis Page

---

## 📷 Screenshots
### Executive Overview  
![overview](Dashboard_Screenshots/overview.png)

### Performance Analysis  
![performance](Dashboard_Screenshots/performance.png)

### Time Analysis  
![time](Dashboard_Screenshots/time.png)

---

## ✅ Recommendations
- Train agents with low satisfaction scores.
- Improve response in Financial Complaint Group.
- Monitor agents with high service duration regularly.

---

## 🛠️ Tools Used
- Power BI
- Power Query
- DAX / Tabular Editor 3
- GitHub
