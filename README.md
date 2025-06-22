![RFM segment_page-0001](https://github.com/user-attachments/assets/05778c28-3c2c-4d5a-bd15-3f1689939a22)# Customer Segmentation using RFM Analysis & KMeans Clustering

This project focuses on segmenting customers based on their behavior using **RFM (Recency, Frequency, Monetary)** analysis, clustering them using **KMeans**, and visualizing insights through an interactive **Power BI dashboard**.

---

## 🚀 Tools & Technologies
- **Python**: pandas, numpy, seaborn, matplotlib, scikit-learn
- **Machine Learning**: KMeans Clustering
- **Business Intelligence**: Power BI
- **Data Processing**: RFM Analysis

---

## 📁 Project Workflow

### 1. Data Cleaning (Python)
- Removed nulls, duplicates, and canceled orders
- Filtered invalid price/quantity rows
- Added `TotalPrice` column

### 2. RFM Analysis
- Calculated Recency, Frequency, Monetary values
- Scored each using quantiles
- Combined into RFM_Score & RFM Segment

### 3. Clustering (KMeans)
- Used Elbow Method to determine optimal clusters
- Applied KMeans to segment customers into 4 clusters

### 4. Power BI Dashboard
- KPI cards (Revenue, Average Spend, Recency)
- Bar and Donut charts for segment distribution
- Cluster & Segment slicers
- Scatter plots to compare Frequency vs Monetary

---

## 📸 Dashboard Preview
[Dashboard Screenshot](RFM_segment_image.jpg)

---

## 🔗 Live Dashboard Link
[👉 View the Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMGY1YzEzZDEtYjg3YS00NjlhLTliY2MtYWRlYTAyYmYyMWEzIiwidCI6ImUxNGU3M2ViLTUyNTEtNDM4OC04ZDY3LThmOWYyZTJkNWE0NiIsImMiOjEwfQ%3D%3D&embedImagePlaceholder=true)

---

## 📂 Files
| File/Folder | Description |
|-------------|-------------|
| `Customer_Segmentation.ipynb` | Python code used for RFM scoring and clustering |
| `Online Retail.xlsx`     | Dataset used for python work |
| `rfm_customer_segments.csv`     | Cleaned dataset used in Power BI |
| `RFM_segment_image.jpg` | Power BI dashboard Image |
| `README.md` | This file |

---

## 🙋‍♂️ About Me
Hi, I’m Adarsh Raj, a Data Science enthusiast currently working on industry-level analytics projects. Always open to feedback and connections!

📧 [Email](mailto:adarshraj7750@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/adarsh-raj-810a5829a/)

---

#PowerBI #Python #CustomerSegmentation #RFM #KMeans #DataScience #PortfolioProject
