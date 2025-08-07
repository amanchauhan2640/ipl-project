# 📊 IPL 2025 Data Engineering Analytics
Welcome to the **IPL 2025 Analytics** project! This is a complete **end-to-end data engineering and analytics pipeline**, powered by **Microsoft Fabric**, **BeautifulSoup**, and **Power BI**. The project fetches daily IPL 2025 match data from the web, processes and stores it in the Fabric Lakehouse, and presents it via insightful and interactive Power BI dashboards.
<br></br>
![Home Page](https://github.com/KirandeepMarala/IPL-Analytics/blob/main/Images/ipl_home_page.png)

---

## 🚀 Project Highlights

- ✅ End-to-End Data Engineering Workflow
- 🌐 Automated Web Scraping using Python + BeautifulSoup
- 🧠 Data Pipeline & Orchestration with Microsoft Fabric
- 🗃️ Data Storage in Fabric Lakehouse
- 📈 Dynamic Power BI Dashboard for Visual Analysis
- 🔁 Fully Automated Daily Data Refresh

---

## 🧱 Architecture Overview

![Pipeline Architecture](https://github.com/KirandeepMarala/IPL-Analytics/blob/main/Images/pipeline_architecture.jpg)

| Component              | Technology Used             |
|------------------------|-----------------------------|
| Data Source            | ESPN Cricinfo, IPL Website  |
| Data Extraction        | Python + BeautifulSoup (via Microsoft Fabric Notebook) |
| Data Pipeline          | Microsoft Fabric Pipeline (Scheduled @ 6:30 AM IST daily) |
| Storage                | Fabric Lakehouse            |
| Dashboard & Reports    | Power BI (Scheduled Refresh @ 7:00 AM IST) |

---

## ⚙️ Key Features in Power BI Report 📊

![Orange Cap](https://github.com/KirandeepMarala/IPL-Analytics/blob/main/Images/orange_cap.png) 
![Match Summary](https://github.com/KirandeepMarala/IPL-Analytics/blob/main/Images/match_summary.png)

  - Home screen features IPL branding and team logos to provide a clean, user-friendly start point.
  - Points table displays live standings, wins, losses, and net run rate.
  - Orange cap highlights the top run-scorers of the season along with key stats like strike rate and innings played.
  - Purple cap tracks leading wicket-takers with economy and bowling stats.
  - Match summary view complete scorecard summary for individual matches with player stats.

  🔗 **Live Interactive Report:** [Click Here to View Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiMGQwMDY2MjItNjI0NS00MWUzLTk3ZWQtNDc5Zjg0ZDZmNmYwIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)  

---

## 🔄 Automation Flow
![All Elements](https://github.com/KirandeepMarala/IPL-Analytics/blob/main/Images/all_elements.jpg)
- The pipeline is **automatically triggered daily at 6:30 AM IST** using Microsoft Fabric’s data pipeline.
- Python web scraping code fetches updated match data.
- Cleaned CSVs are stored in **Fabric Lakehouse**.
- Power BI dashboard is **auto-refreshed at 7:00 AM IST**, ensuring the latest insights are always visible.

---

## 🎯 Conclusion

This project showcases a **scalable and automated data engineering pipeline** for IPL 2025 analytics. By leveraging **Microsoft Fabric**, **Python (BeautifulSoup)**, and **Power BI**, we built a robust and efficient system to fetch, process, and visualize daily IPL data. The end-to-end workflow ensures real-time insights into match performances, player stats, and team standings.

Feel free to reach out for any questions, suggestions, or collaboration opportunities! 😊

---

## 📬 Contact

- **Author**: [kirandeep Marala](#)
- **Email**: [kirandeep.marala@gmail.com](mailto:kirandeep.marala@gmail.com)
- **LinkedIn**: [My LinkedIn Profile](https://www.linkedin.com/in/kirandeepmarala/)

---
