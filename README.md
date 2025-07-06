# 📊 Lending & Collections BI Dashboard

**Tools Used:** Power BI Service | SQL Server | DAX | Power Query

---

## 🔍 Overview

This case study showcases the development of a comprehensive BI solution for the lending and collections domain. The objective was to deliver an interactive and automated reporting system to track KPIs across loan disbursal, repayments, user engagement, and collection performance. The solution was implemented in a financial services environment using Power BI integrated with SQL Server.

---

## 🧩 Business Objective

To enable data-driven visibility into critical lending and recovery metrics by:

- Monitoring loan disbursement trends  
- Identifying delinquent accounts and tracking Non-Performing Assets (NPA)  
- Analyzing collection efficiency over time  
- Empowering internal teams with stakeholder-specific dashboards  

---

## 🏗️ Solution Architecture

### Data Sources

- SQL Server views and stored procedures were used to extract data from transactional loan management systems  
- Power Query was used for data cleaning and transformation  

### Data Modeling

- Implemented a star schema with:
  - Fact tables: loans, repayments, offers  
  - Dimension tables: users, dates, products  
- Relationships were optimized for performance and accuracy  

### KPIs Defined

- **NPA %**: Ratio of overdue loans to total disbursed loans  
- **Approval Rate**: Ratio of approved loans to total applications  
- **Collection Efficiency**: Recovered amount vs scheduled EMI  

### Dashboards & Reports

- Role-based access implemented via **Row-Level Security (RLS)**  
- Intuitive dashboards with:
  - Drill-through functionality for user/branch-level analysis  
  - Dynamic filters and slicers for flexible reporting  
  - Segmented views: Loan Lifecycle, Recovery Funnel, User Activity Tracking  

### Automation & Optimization

- Scheduled data refresh using **Power BI Gateway**  
- Performance-tuned DAX measures and Power Query transformations  
- Reduced load time and improved dashboard responsiveness  

---

## 📈 Impact & Results

- Enabled near real-time monitoring of critical financial KPIs  
- Reduced manual reporting time by **over 70%** through automation  
- Enhanced decision-making for operations and recovery teams via actionable insights and visual storytelling  

---

## 🔐 Note

This project is based on a professional implementation in the financial domain. To respect data privacy and confidentiality agreements, the case study focuses on technical execution, domain knowledge, and Power BI best practices.
