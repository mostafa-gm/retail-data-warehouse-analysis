# 📊 Retail Data Analytics 

## 🎯 Project Overview
A comprehensive SQL-based business intelligence analysis of a retail data warehouse, demonstrating end-to-end analytical capabilities from data exploration to executive reporting. This project simulates real-world BI tasks using a **star schema** design with 14 distinct analytical techniques.

## 📈 Business Context
Analyzes customer purchasing behavior, product performance, and sales trends to derive actionable business insights for a retail organization. The analysis answers critical business questions across multiple domains including customer segmentation, product optimization, and revenue forecasting.

## 🛠️ Technologies Used
- **SQL:** T-SQL (SQL Server)
- **Database Design:** Star Schema (Fact & Dimension Tables)
- **Analytical Techniques:** 14 different SQL analysis methods
- **Version Control:** Git & GitHub
- **Documentation:** Markdown

- ### Star Schema Design
-%3CmxGraphModel%3E%3Croot%3E%3CmxCell%20id%3D%220%22%2F%3E%3CmxCell%20id%3D%221%22%20parent%3D%220%22%2F%3E%3CmxCell%20id%3D%222%22%20edge%3D%221%22%20parent%3D%221%22%20source%3D%223%22%20style%3D%22edgeStyle%3DorthogonalEdgeStyle%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3B%22%20target%3D%224%22%20value%3D%22%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%223%22%20parent%3D%221%22%20style%3D%22text%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D14%3BspacingTop%3D5%3BspacingBottom%3D5%3B%22%20value%3D%22%26lt%3Bb%20style%3D%26quot%3Bfont-size%3A%2018px%3B%26quot%3B%26gt%3BRetail%20Data%20Warehouse%20-%20Star%20Schema%26lt%3B%2Fb%26gt%3B%26lt%3Bbr%26gt%3B%26lt%3Bspan%20style%3D%26quot%3Bfont-size%3A%2012px%3B%20color%3A%20%23666%3B%26quot%3B%26gt%3BGold%20Layer%20-%20Production%20Ready%26lt%3B%2Fspan%26gt%3B%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2240%22%20width%3D%22300%22%20x%3D%22300%22%20y%3D%2220%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%224%22%20parent%3D%221%22%20style%3D%22rounded%3D0%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3BstrokeColor%3D%23cccccc%3BfillColor%3D%23f5f5f5%3Bdashed%3D1%3BdashPattern%3D1%201%3BstrokeWidth%3D1%3B%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%22100%22%20width%3D%22220%22%20x%3D%2220%22%20y%3D%2220%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%225%22%20parent%3D%221%22%20style%3D%22text%3Bhtml%3D1%3Balign%3Dleft%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D12%3B%22%20value%3D%22%26lt%3Bb%26gt%3BLEGEND%26lt%3B%2Fb%26gt%3B%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2220%22%20width%3D%2260%22%20x%3D%2240%22%20y%3D%2230%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%226%22%20parent%3D%221%22%20style%3D%22rounded%3D0%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3BstrokeColor%3D%232E75B6%3BfillColor%3D%23DEEBF7%3BstrokeWidth%3D2%3B%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2215%22%20width%3D%2215%22%20x%3D%2240%22%20y%3D%2255%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%227%22%20parent%3D%221%22%20style%3D%22text%3Bhtml%3D1%3Balign%3Dleft%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D10%3B%22%20value%3D%22Primary%20Key%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2215%22%20width%3D%2260%22%20x%3D%2260%22%20y%3D%2255%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%228%22%20parent%3D%221%22%20style%3D%22rounded%3D0%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3BstrokeColor%3D%23C00000%3BfillColor%3D%23FCE4D6%3BstrokeWidth%3D2%3B%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2215%22%20width%3D%2215%22%20x%3D%2240%22%20y%3D%2275%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%229%22%20parent%3D%221%22%20style%3D%22text%3Bhtml%3D1%3Balign%3Dleft%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D10%3B%22%20value%3D%22Foreign%20Key%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2215%22%20width%3D%2260%22%20x%3D%2260%22%20y%3D%2275%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2210%22%20parent%3D%221%22%20style%3D%22rounded%3D0%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3BstrokeColor%3D%23548235%3BfillColor%3D%23E2F0D9%3BstrokeWidth%3D2%3B%22%20value%3D%22%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2215%22%20width%3D%2215%22%20x%3D%2240%22%20y%3D%2295%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2211%22%20parent%3D%221%22%20style%3D%22text%3Bhtml%3D1%3Balign%3Dleft%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D10%3B%22%20value%3D%22Fact%20Table%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2215%22%20width%3D%2260%22%20x%3D%2260%22%20y%3D%2295%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2212%22%20parent%3D%221%22%20style%3D%22rounded%3D1%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3BfontSize%3D12%3Balign%3Dleft%3BarcSize%3D0%3B%22%20value%3D%22%26lt%3Btable%20border%3D%26quot%3B0%26quot%3B%20cellpadding%3D%26quot%3B4%26quot%3B%20cellspacing%3D%26quot%3B0%26quot%3B%20style%3D%26quot%3Bborder-collapse%3A%20collapse%3B%20width%3A%20100%25%3B%26quot%3B%26gt%3B%26lt%3Btr%26gt%3B%26lt%3Btd%20colspan%3D%26quot%3B2%26quot%3B%20style%3D%26quot%3Bbackground-color%3A%20%232E75B6%3B%20color%3A%20white%3B%20text-align%3A%20center%3B%20font-weight%3A%20bold%3B%20padding%3A%208px%3B%20border-radius%3A%204px%204px%200%200%3B%26quot%3B%26gt%3Bgold.dim_customers%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%26gt%3B%26lt%3Btd%20colspan%3D%26quot%3B2%26quot%3B%20style%3D%26quot%3Bbackground-color%3A%20%23DEEBF7%3B%20text-align%3A%20center%3B%20font-style%3A%20italic%3B%20padding%3A%204px%3B%26quot%3B%26gt%3B(Dimension%20Table)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%20background-color%3A%20%23DEEBF7%3B%20border-right%3A%202px%20solid%20%232E75B6%3B%26quot%3B%26gt%3B%26lt%3Bb%26gt%3Bcustomer_key%26lt%3B%2Fb%26gt%3B%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BINT%26lt%3Bbr%26gt%3B%26lt%3Bspan%20style%3D%26quot%3Bcolor%3A%20%232E75B6%3B%20font-size%3A%209px%3B%26quot%3B%26gt%3BPRIMARY%20KEY%26lt%3B%2Fspan%26gt%3B%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bcustomer_id%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BINT%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bcustomer_number%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bfirst_name%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Blast_name%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bcountry%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bmarital_status%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bgender%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bbirthdate%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BDATETIME%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bcreate_date%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BDATE%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3B%2Ftable%26gt%3B%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%22310%22%20width%3D%22260%22%20x%3D%2230%22%20y%3D%22150%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2213%22%20edge%3D%221%22%20parent%3D%221%22%20source%3D%2214%22%20style%3D%22edgeStyle%3DorthogonalEdgeStyle%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3BentryX%3D0.996%3BentryY%3D0.347%3BentryDx%3D0%3BentryDy%3D0%3BentryPerimeter%3D0%3B%22%20target%3D%2215%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%3E%3CArray%20as%3D%22points%22%3E%3CmxPoint%20x%3D%22725%22%20y%3D%22598%22%2F%3E%3C%2FArray%3E%3CmxPoint%20x%3D%22620%22%20y%3D%22610%22%20as%3D%22targetPoint%22%2F%3E%3C%2FmxGeometry%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2214%22%20parent%3D%221%22%20style%3D%22rounded%3D1%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3BfontSize%3D12%3Balign%3Dleft%3BarcSize%3D0%3B%22%20value%3D%22%26lt%3Btable%20border%3D%26quot%3B0%26quot%3B%20cellpadding%3D%26quot%3B4%26quot%3B%20cellspacing%3D%26quot%3B0%26quot%3B%20style%3D%26quot%3Bborder-collapse%3A%20collapse%3B%20width%3A%20100%25%3B%26quot%3B%26gt%3B%26lt%3Btr%26gt%3B%26lt%3Btd%20colspan%3D%26quot%3B2%26quot%3B%20style%3D%26quot%3Bbackground-color%3A%20%232E75B6%3B%20color%3A%20white%3B%20text-align%3A%20center%3B%20font-weight%3A%20bold%3B%20padding%3A%208px%3B%20border-radius%3A%204px%204px%200%200%3B%26quot%3B%26gt%3Bgold.dim_products%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%26gt%3B%26lt%3Btd%20colspan%3D%26quot%3B2%26quot%3B%20style%3D%26quot%3Bbackground-color%3A%20%23DEEBF7%3B%20text-align%3A%20center%3B%20font-style%3A%20italic%3B%20padding%3A%204px%3B%26quot%3B%26gt%3B(Dimension%20Table)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%20background-color%3A%20%23DEEBF7%3B%20border-right%3A%202px%20solid%20%232E75B6%3B%26quot%3B%26gt%3B%26lt%3Bb%26gt%3Bproduct_key%26lt%3B%2Fb%26gt%3B%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BINT%26lt%3Bbr%26gt%3B%26lt%3Bspan%20style%3D%26quot%3Bcolor%3A%20%232E75B6%3B%20font-size%3A%209px%3B%26quot%3B%26gt%3BPRIMARY%20KEY%26lt%3B%2Fspan%26gt%3B%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bproduct_id%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BINT%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bproduct_number%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bproduct_name%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bcategory_id%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bcategory%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bsubcategory%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bmaintenance%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bcost%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BINT%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bproduct_line%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bstart_date%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BDATE%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3B%2Ftable%26gt%3B%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%22330%22%20width%3D%22220%22%20x%3D%22590%22%20y%3D%22150%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2215%22%20parent%3D%221%22%20style%3D%22rounded%3D1%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3BfontSize%3D12%3Balign%3Dleft%3BarcSize%3D0%3B%22%20value%3D%22%26lt%3Btable%20border%3D%26quot%3B0%26quot%3B%20cellpadding%3D%26quot%3B4%26quot%3B%20cellspacing%3D%26quot%3B0%26quot%3B%20style%3D%26quot%3Bborder-collapse%3A%20collapse%3B%20width%3A%20100%25%3B%26quot%3B%26gt%3B%26lt%3Btr%26gt%3B%26lt%3Btd%20colspan%3D%26quot%3B2%26quot%3B%20style%3D%26quot%3Bbackground-color%3A%20%23548235%3B%20color%3A%20white%3B%20text-align%3A%20center%3B%20font-weight%3A%20bold%3B%20padding%3A%208px%3B%20border-radius%3A%204px%204px%200%200%3B%26quot%3B%26gt%3Bgold.fact_sales%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%26gt%3B%26lt%3Btd%20colspan%3D%26quot%3B2%26quot%3B%20style%3D%26quot%3Bbackground-color%3A%20%23E2F0D9%3B%20text-align%3A%20center%3B%20font-style%3A%20italic%3B%20padding%3A%204px%3B%26quot%3B%26gt%3B(Fact%20Table%20-%20Transaction%20Data)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Border_number%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BNVARCHAR(50)%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%20background-color%3A%20%23FCE4D6%3B%20border-right%3A%202px%20solid%20%23C00000%3B%26quot%3B%26gt%3B%26lt%3Bb%26gt%3Bproduct_key%26lt%3B%2Fb%26gt%3B%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BINT%26lt%3Bbr%26gt%3B%26lt%3Bspan%20style%3D%26quot%3Bcolor%3A%20%23C00000%3B%20font-size%3A%209px%3B%26quot%3B%26gt%3BFOREIGN%20KEY%20%E2%86%92%20dim_products%26lt%3B%2Fspan%26gt%3B%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%20background-color%3A%20%23FCE4D6%3B%20border-right%3A%202px%20solid%20%23C00000%3B%26quot%3B%26gt%3B%26lt%3Bb%26gt%3Bcustomer_key%26lt%3B%2Fb%26gt%3B%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BINT%26lt%3Bbr%26gt%3B%26lt%3Bspan%20style%3D%26quot%3Bcolor%3A%20%23C00000%3B%20font-size%3A%209px%3B%26quot%3B%26gt%3BFOREIGN%20KEY%20%E2%86%92%20dim_customers%26lt%3B%2Fspan%26gt%3B%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Border_date%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BDATE%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bshipping_date%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BDATE%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bdue_date%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BDATE%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bsales_amount%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BINT%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%20style%3D%26quot%3Bborder-bottom%3A%201px%20solid%20%23ddd%3B%26quot%3B%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bquantity%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BTINYINT%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3Btr%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3Bprice%26lt%3B%2Ftd%26gt%3B%26lt%3Btd%20style%3D%26quot%3Bpadding%3A%204px%208px%3B%26quot%3B%26gt%3BINT%26lt%3B%2Ftd%26gt%3B%26lt%3B%2Ftr%26gt%3B%26lt%3B%2Ftable%26gt%3B%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%22340%22%20width%3D%22260%22%20x%3D%22310%22%20y%3D%22480%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2216%22%20parent%3D%221%22%20style%3D%22text%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D11%3BfillColor%3D%23ffffff%3BstrokeColor%3Dnone%3B%22%20value%3D%22%26lt%3Bb%26gt%3B1%20%3A%20N%26lt%3B%2Fb%26gt%3B%26lt%3Bbr%26gt%3B%26lt%3Bspan%20style%3D%26quot%3Bfont-size%3A%2010px%3B%26quot%3B%26gt%3B(One%20product%2C%20Many%20sales)%26lt%3B%2Fspan%26gt%3B%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2240%22%20width%3D%2260%22%20x%3D%22690%22%20y%3D%22530%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2217%22%20edge%3D%221%22%20parent%3D%221%22%20source%3D%2219%22%20style%3D%22edgeStyle%3DorthogonalEdgeStyle%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3BentryX%3D0%3BentryY%3D0.476%3BentryDx%3D0%3BentryDy%3D0%3BentryPerimeter%3D0%3B%22%20target%3D%2215%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2218%22%20edge%3D%221%22%20parent%3D%221%22%20source%3D%2212%22%20style%3D%22edgeStyle%3DorthogonalEdgeStyle%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3BentryX%3D0%3BentryY%3D0.476%3BentryDx%3D0%3BentryDy%3D0%3BentryPerimeter%3D0%3B%22%20target%3D%2219%22%20value%3D%22%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%3E%3CArray%20as%3D%22points%22%3E%3CmxPoint%20x%3D%22160%22%20y%3D%22640%22%2F%3E%3CmxPoint%20x%3D%22210%22%20y%3D%22640%22%2F%3E%3C%2FArray%3E%3CmxPoint%20x%3D%22290%22%20y%3D%22305%22%20as%3D%22sourcePoint%22%2F%3E%3CmxPoint%20x%3D%22355%22%20y%3D%22692%22%20as%3D%22targetPoint%22%2F%3E%3C%2FmxGeometry%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2219%22%20parent%3D%221%22%20style%3D%22text%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3BfontSize%3D11%3BfillColor%3D%23ffffff%3BstrokeColor%3Dnone%3B%22%20value%3D%22%26lt%3Bb%26gt%3B1%20%3A%20N%26lt%3B%2Fb%26gt%3B%26lt%3Bbr%26gt%3B%26lt%3Bspan%20style%3D%26quot%3Bfont-size%3A%2010px%3B%26quot%3B%26gt%3B(One%20customer%2C%20Many%20sales)%26lt%3B%2Fspan%26gt%3B%22%20vertex%3D%221%22%3E%3CmxGeometry%20height%3D%2240%22%20width%3D%2260%22%20x%3D%22220%22%20y%3D%22620%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3C%2Froot%3E%3C%2FmxGraphModel%3E

### Table Details
- **`gold.dim_customers`**: 10+ customer attributes with `customer_key` as PRIMARY KEY
- **`gold.dim_products`**: 10+ product attributes with `product_key` as PRIMARY KEY  
- **`gold.fact_sales`**: Transactional data with FOREIGN KEY constraints to both dimensions


- ## 📁 Analysis Pipeline
| # | Analysis Type | Purpose | Key SQL Functions |
|---|--------------|---------|-------------------|
| 1 | **Database Exploration** | Understand structure & metadata | `INFORMATION_SCHEMA`, `DISTINCT` |
| 2 | **Dimensions Exploration** | Profile dimension tables | `DISTINCT`, `ORDER BY` |
| 3 | **Date Range Exploration** | Temporal boundaries analysis | `MIN()`, `MAX()`, `DATEDIFF()` |
| 4 | **Measures Exploration** | Aggregate key metrics | `SUM()`, `AVG()`, `COUNT()` |
| 5 | **Magnitude Analysis** | Data distribution across dimensions | `GROUP BY`, aggregate functions |
| 6 | **Ranking Analysis** | Identify top/bottom performers | `RANK()`, `DENSE_RANK()`, `ROW_NUMBER()` |
| 7 | **Change Over Time** | Trend & seasonality analysis | `DATEPART()`, window functions |
| 8 | **Cumulative Analysis** | Running totals & moving averages | `SUM() OVER()`, `AVG() OVER()` |
| 9 | **Performance Analysis** | YoY/MoM comparisons | `LAG()`, window functions |
| 10| **Data Segmentation** | Customer/product categorization | `CASE`, `GROUP BY` |
| 11| **Part-to-Whole Analysis** | Contribution analysis | Window aggregates |
| 12| **Customer Report** | Consolidated customer intelligence | Multiple joins, derived columns |
| 13| **Product Report** | Comprehensive product performance | Complex aggregations |

### Customer Insights
- **Segmentation**: Identified VIP, Regular, and New customer segments based on spending behavior
- **Demographics**: Sales distribution across countries, gender, and age groups

### Product Insights  
- **Revenue Leaders**: products generating highest revenue identified
- **Category Performance**: Bikes contributes 96.46% to total sales
- **Cost Analysis**: Average cost per category with profitability metrics

### Sales Trends
- **Temporal Patterns**: Monthly sales trends with running totals
- **Growth Analysis**: Year-over-year performance comparison
- **Seasonality**: Identified peak sales periods

retail-data-analysis/
├── sql_scripts/
│   ├── 00_database_exploration.sql
│   ├── 01_dimensions_exploration.sql
│   ├── 02_date_range_exploration.sql
│   ├── 03_measures_exploration.sql
│   ├── 04_magnitude_analysis.sql
│   ├── 05_ranking_analysis.sql
│   ├── 06_change_over_time.sql
│   ├── 07_cumulative_analysis.sql
│   ├── 08_performance_analysis.sql
│   ├── 09_data_segmentation.sql
│   ├── 10_part_to_whole_analysis.sql
│   ├── 11_customer_report.sql
│   ├── 12_product_report.sql
├── README.md

### Customer Segmentation
```sql
-- VIP/Routine/New Customer Segmentation
WITH customer_spending AS (
    SELECT
        c.customer_key,
        SUM(f.sales_amount) AS total_spending,
        MIN(order_date) AS first_order,
        MAX(order_date) AS last_order,
        DATEDIFF(month, MIN(order_date), MAX(order_date)) AS lifespan
    FROM gold.fact_sales f
    LEFT JOIN gold.dim_customers c
        ON f.customer_key = c.customer_key
    GROUP BY c.customer_key
)
SELECT 
    customer_segment,
    COUNT(customer_key) AS total_customers
FROM (
    SELECT 
        customer_key,
        CASE 
            WHEN lifespan >= 12 AND total_spending > 5000 THEN 'VIP'
            WHEN lifespan >= 12 AND total_spending <= 5000 THEN 'Regular'
            ELSE 'New'
        END AS customer_segment
    FROM customer_spending
) AS segmented_customers
GROUP BY customer_segment
ORDER BY total_customers DESC;
```

### Product Yearly Performance 
```sql
WITH yearly_product_sales AS (
    SELECT
        YEAR(f.order_date) AS order_year,
        p.product_name,
        SUM(f.sales_amount) AS current_sales
    FROM gold.fact_sales f
    LEFT JOIN gold.dim_products p
        ON f.product_key = p.product_key
    WHERE f.order_date IS NOT NULL
    GROUP BY 
        YEAR(f.order_date),
        p.product_name
)
SELECT
    order_year,
    product_name,
    current_sales,
    AVG(current_sales) OVER (PARTITION BY product_name) AS avg_sales,
    current_sales - AVG(current_sales) OVER (PARTITION BY product_name) AS diff_avg,
    CASE 
        WHEN current_sales - AVG(current_sales) OVER (PARTITION BY product_name) > 0 THEN 'Above Avg'
        WHEN current_sales - AVG(current_sales) OVER (PARTITION BY product_name) < 0 THEN 'Below Avg'
        ELSE 'Avg'
    END AS avg_change,
    -- Year-over-Year Analysis
    LAG(current_sales) OVER (PARTITION BY product_name ORDER BY order_year) AS py_sales,
    current_sales - LAG(current_sales) OVER (PARTITION BY product_name ORDER BY order_year) AS diff_py,
    CASE 
        WHEN current_sales - LAG(current_sales) OVER (PARTITION BY product_name ORDER BY order_year) > 0 THEN 'Increase'
        WHEN current_sales - LAG(current_sales) OVER (PARTITION BY product_name ORDER BY order_year) < 0 THEN 'Decrease'
        ELSE 'No Change'
    END AS py_change
FROM yearly_product_sales
ORDER BY product_name, order_year;
```

### Technical SQL Skills
- **Advanced Queries**: Complex joins, subqueries, CTEs, window functions
- **Data Modeling**: Star schema design with PK/FK relationships
- **Analytical Functions**: RANK(), LAG(), SUM() OVER(), CASE statements
- **Performance Optimization**: Efficient aggregation and filtering

### Business Intelligence
- **KPI Development**: Customer Lifetime Value, AOV, Recency
- **Segmentation Analysis**: demographic, behavioral segmentation
- **Trend Analysis**: Time series, YoY growth, moving averages
- **Reporting**: Executive-level summary reports

### Data Analysis Methodology
- **Exploratory Data Analysis (EDA)**: Comprehensive data profiling
- **Comparative Analysis**: Part-to-whole, benchmarking
### Setup Instructions
1. Clone the repository
2. Execute the SQL scripts in numerical order
3. Review the analytical outputs

### For Recruiters & Hiring Managers
- **Review files 04-10** for core analytical capabilities
- **Review files 11-12** for business reporting skills
- **Check the README** for methodology documentation

### Learning Objectives
This project demonstrates:
- Real-world business problem solving with SQL
- Progressive complexity in analytical techniques
- Professional documentation and code organization

- 1. **Mastered 14 analytical techniques** used in production BI environments
2. **Developed ability to translate** business questions into SQL queries
3. **Gained experience with** complete analytics pipeline from raw data to reports
4. **Learned to document** technical work for professional audiences
5. **Built a portfolio piece** demonstrating job-ready SQL skills

-Contact
-Name: Mostafa Galal
-LinkedIn: [linkedin.com/in/mostafa-galal-2a10123a1]
-Email: mostafagalal.mansour@gmail.com
