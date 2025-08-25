# Customer Segmentation - RFM Analysis

![Project Screenshot](https://github.com/snehez/RFM-Customer-Segmentation/blob/main/Screenshot1.png))


## 👩‍💻 Author
**Sneha Ghosh**  
Aspiring Business & Data Analyst | Power BI & SQL Enthusiast  
🔗 [LinkedIn](https://www.linkedin.com/in/sneha-ghosh-98aaa9337)


## 📂 Project Files
- `Customer_Segmentation_RFM_Analysis.ipynb` → Google Colab / Jupyter Notebook with full RFM analysis  
- `Customer_Segmentation_RFM_Analysis.pdf` → Canva presentation (visual project summary)  
- `OnlineRetail.xlsx` → Dataset used for analysis  


## 📊 Project Overview
This project performs **RFM (Recency, Frequency, Monetary) Analysis** on retail data to segment customers and suggest marketing strategies.  
Built with **Python, Pandas, Seaborn, Matplotlib**.


## 🔑 Dataset
- **File:** `OnlineRetail.xlsx`  
- Contains transaction details including:  
  - `InvoiceNo`, `StockCode`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`


## ⚙️ Steps in Analysis
1. **Data Cleaning** → Remove nulls, set `InvoiceDate` as datetime  
2. **Feature Engineering** →  
   - Recency = Days since last purchase  
   - Frequency = Number of purchases  
   - Monetary = Total spend  
3. **RFM Scoring** → 1–5 scale for each metric  
4. **Segmentation** → Loyal, Inactive, At Risk, Potential, Regular  
5. **Visualization** → Heatmaps, bar charts (blue & green theme 🎨)


## 🛒 Customer Segments & Marketing Ideas
| Segment   | Strategy |
|-----------|----------|
| **Loyal** | Offer loyalty discounts, VIP deals |
| **Inactive** | Re-engagement campaigns, limited-time offers |
| **At Risk** | Win-back discounts, reminders |
| **Potential** | Upsell products, nurture |
| **Regular** | Bundle offers, referral programs |


## 📈 Results
- Identified customer groups based on RFM scores  
- Suggested tailored marketing strategies  
- Visualized customer segments with bar charts and heatmaps  


## 🚀 How to Run
1. Clone this repo or download the notebook  
2. Open `Customer_Segmentation_RFM_Analysis.ipynb` in **Google Colab** or Jupyter  
3. Upload the dataset `OnlineRetail.xlsx`  
4. Run all cells to reproduce results  


⭐ Don’t forget to star this repo if you found it useful!
