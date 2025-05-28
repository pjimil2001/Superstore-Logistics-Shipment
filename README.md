# 📦 Superstore Logistics Shipment Performance Dashboard

This repository presents an interactive logistics dashboard built using **Tableau** to analyze and monitor the shipment performance of a fictional Superstore company. The dashboard integrates various KPIs, visualizations, and filters to help stakeholders understand logistical efficiencies and areas of improvement.

---

## 📊 Dashboard Overview

### Key Metrics:
- **Total Shipments:** 51,290  
- **On-Time Shipments:** 34,760  
- **Delayed Shipments:** 16,530  
- **Average Shipping Days:** 3.97  

---

## 🔍 Dashboard Features

### 1. **Delivery Timeliness Trends**
A line graph tracks average shipping days over time for different shipment classes:
- Same Day
- 1st Class
- 2nd Class
- Standard

### 2. **Shipment Volume by Region**
A stacked horizontal bar chart visualizes shipment volumes across multiple regions by product categories:
- Technology
- Office Supplies
- Furniture

### 3. **Global Product Movement**
An interactive map highlights product flow between warehouse locations worldwide, enabling visual analysis of shipment density and region-based activity.

### 4. **Filters**
The dashboard supports filtering by:
- Year
- Region
- Product Category
- Delivery Status

---

## 🌍 Insights

- **Central and South regions** show the highest shipment volumes.
- **Office Supplies** dominate the shipment share across regions.
- **Standard delivery class** takes the longest average shipping time.
- Shipment delays are significant, with over 16K out of 51K shipments being delayed.

---

## 🛠️ Tools Used

- Tableau Desktop
- OpenStreetMap (Map integration)
- Superstore Dataset (Fictional, available in Tableau sample data)

---

## 📁 Repository Structure

```bash
.
├── Dashboard.twb         # Tableau workbook file
├── README.md             # Project documentation
└── /images
    └── dashboard.png     # Screenshot of the final dashboard
