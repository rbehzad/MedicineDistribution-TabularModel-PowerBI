# 💊 Medicine Distribution Dashboard

This Power BI project demonstrates data modeling, data preparation, and interactive dashboard design using business data.

## 📌 Project Overview

- **Dataset**: Medicine Distribution
- **Goal**: Analyze distribution performance and visualize key metrics for decision-making
- **Tools**: SSMS, SSAS, Power BI

## 🔧 Features

- **Star Schema**: Built a tabular model with fact and dimension tables
- **Data Preparation**: Created SQL views to clean and structure the dataset
- **Interactive Dashboard**: Developed a two-page dashboard with the following features:
  - Filters by **distribution center**, **pharmaceutical company**, **month**, and **city**
  - Displays **distribution targets vs. actual fulfillment**

## 📊 Dashboard Pages

1. **Overview Page**: Distribution Center, target fulfillment
2. **Details Page**: A drill-through page from the overview, filtered by **Distribution Center Name**, showing detailed distribution breakdowns and performance metrics

## 🧱 Data Model

The model follows a **star schema** structure with:
- **Fact Table**: SQL View
- **Dimension Tables**: Company, Goods, Target, Distribution Center
## 📁 Files

- `.pbix`: Power BI project file
- `schema_diagram.png`: (Optional) Star schema diagram

## 🚀 Getting Started

1. Clone this repo
2. Open the SSAS tabular model file (`.smproj` or similar).
3. Deploy the tabular model to your Analysis Services server.
4. Open the Power BI Desktop file (`.pbix`).
5. Connect Power BI to the deployed tabular model as the data source.
6. Explore the interactive dashboard using filters and slicers.

## 📌 Screenshots
![Screenshot 2025-05-28 010343](https://github.com/user-attachments/assets/164b8a2c-f728-4868-a0af-78f5d694cf8a)
![Screenshot 2025-05-28 010350](https://github.com/user-attachments/assets/2afac267-d80c-4e56-8e42-9a72954f493d)





Feel free to ⭐ the repo if you find it useful!
