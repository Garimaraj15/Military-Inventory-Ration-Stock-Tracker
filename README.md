# Military Inventory & Ration Stock Tracker

An Excel VBA-powered military inventory management and analytics system designed to streamline stock tracking, expiry monitoring, reporting, and inventory risk analysis through an interactive dashboard.

---

## 📊 Dashboard

<img width="1535" height="441" alt="dashboard" src="https://github.com/user-attachments/assets/33e6c424-4d82-4371-9a1f-ff59729cb654" />

The interactive dashboard provides a centralized view of inventory status, stock levels, category distribution, and key operational metrics.

---

## 📈 Analytics & Visualizations

<img width="1059" height="630" alt="Charts" src="https://github.com/user-attachments/assets/55d9ed92-8a69-4034-8f34-13cba864527c" />

The dashboard includes dynamic charts for category-wise inventory analysis, inventory distribution, and top inventory items.

---

## 🤖 AI Inventory Advisor

The project includes an **AI-powered Inventory Advisor** integrated with the Gemini API.

The AI analyzes inventory data and generates a concise risk and replenishment summary covering:

- Critical low-stock items
- Expired inventory
- Items nearing expiry
- Replenishment priorities
- Overall inventory recommendations

The AI analyzes inventory fields such as:

- Item ID
- Item Name
- Category
- Quantity
- Expiry Date
- Stock Status

The generated analysis is displayed directly inside the Excel dashboard.

> **Note:** The public demo workbook does not contain an API key. Users must provide their own Gemini API key to enable the AI Inventory Advisor.

---

## ✨ Key Features

### Inventory Management
- Store and manage inventory records
- Track item quantities and units
- Record received dates and expiry dates
- Manage suppliers
- Track storage locations
- Categorize items into Ration, Ammunition, and Equipment

### Interactive Dashboard
- Total Items KPI
- Total Quantity KPI
- Low Stock monitoring
- Expiring Soon monitoring
- Expired Items tracking
- Category-wise inventory statistics
- Dynamic charts and visualizations

### Inventory Risk Monitoring
- Automatic low-stock identification
- Expiry monitoring
- Expired inventory identification
- Conditional formatting for critical stock levels
- Status-based inventory tracking

### AI-Powered Analysis
- Gemini API integration
- Automated inventory risk analysis
- Low-stock prioritization
- Expiry risk identification
- Replenishment recommendations
- Concise AI-generated management summary

### Reporting & Automation
- Automated inventory report generation
- PDF export
- Excel VBA automation
- Dashboard refresh functionality
- Automated data processing

---

## 🛠️ Technologies Used

- Microsoft Excel
- Excel VBA
- Google Gemini API
- Pivot Tables
- Excel Charts
- Conditional Formatting
- Data Validation
- Form Controls

---

## 📁 Workbook Structure

```text
Military Inventory & Ration Stock Tracker
│
├── Dashboard
│   ├── KPI Cards
│   ├── Inventory Charts
│   ├── AI Inventory Advisor
│   └── Dashboard Controls
│
├── Inventory
│   └── Main Inventory Dataset
│
├── Lookup
│   ├── Categories
│   ├── Units
│   ├── Suppliers
│   ├── Storage Locations
│   └── Status Values
│
└── Reports
    └── Automated Inventory Reports
