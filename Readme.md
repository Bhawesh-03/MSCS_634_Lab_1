# MSCS_634_Lab_1: Data Visualization and Preprocessing

**Name:** Bhawesh Shrestha  
**Course:** MSCS 634 – Advanced Data Mining  
**Lab Title:** Data Visualization, Preprocessing, and Statistical Analysis  

---

## Overview
This lab focuses on applying **data visualization**, **data preprocessing**, and **statistical analysis** techniques using Jupyter Notebook.  
The main goal is to explore, clean, and prepare a dataset for deeper analysis while gaining insights from visual patterns and statistical relationships.

---

## Dataset Description
- **Source:** [UCI / Kaggle / Custom dataset – replace with your actual source]
- **Type:** [e.g., Online Retail Sales / Weather / Product Performance]
- **Size:** [Number of rows and columns]
- **Attributes:** Briefly describe 3–4 key columns (e.g., `InvoiceNo`, `Quantity`, `UnitPrice`, `Country`).

Example:  
This dataset contains transactional records for an online retail store, including invoice numbers, product details, unit prices, and customer country information.

---

## Steps and Methods

### **Step 1: Data Collection**
- Loaded dataset using `pandas.read_csv()`.
- Displayed first five rows using `.head()`.
- Verified data types and column consistency.

### **Step 2: Data Visualization**
Created multiple visualizations using **Matplotlib** and **Seaborn**:
- **Scatter Plot:** Explored relationships between sales quantity and unit price.  
- **Histogram:** Analyzed distribution of numerical values.  
- **Box Plot:** Detected outliers in price-related fields.  
- **Pie Chart:** Displayed categorical proportions by region.

**Key Insights:**
- Higher quantities often correlated with lower unit prices (bulk purchases).
- Some extreme values indicated outliers in pricing.

### **Step 3: Data Preprocessing**
Performed multiple data cleaning operations:
- **Handling Missing Values:** Applied mean/mode replacement and removed empty rows.
- **Outlier Detection:** Used IQR to identify and remove extreme price values.
- **Data Reduction:** Removed irrelevant columns and sampled data for faster computation.
- **Scaling and Discretization:** Applied Min-Max normalization for numerical attributes.

### **Step 4: Statistical Analysis**
Computed various statistical measures:
- **Central Tendency:** Mean, Median, Mode, Min, Max.  
- **Dispersion:** Range, Variance, Standard Deviation, and IQR.  
- **Correlation Matrix:** Identified positive correlation between `Quantity` and `Sales`.

---

## Key Insights
1. Data cleaning significantly improved dataset quality by removing missing and inconsistent entries.  
2. Visualization helped reveal sales patterns and seasonal trends.  
3. Correlation analysis identified key relationships useful for predictive modeling.  
4. Scaling normalized features for better model compatibility.

---

## Challenges Faced
- Managing inconsistent data types (string vs numeric).
- Handling extreme outliers that skewed distributions.
- Choosing appropriate scaling technique for mixed-value data.

---

## Repository Contents
| File | Description |
|------|--------------|
| `Lab1_DataVisualization.ipynb` | Jupyter Notebook containing all code and visualizations |
| `dataset.csv` | Dataset used for analysis |
| `/screenshots` | Contains required screenshots for submission |
| `Lab1_Report.docx` | Word report summarizing the lab work |
| `README.md` | Project documentation file |

---

## 🧷 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/MSCS_634_Lab_1.git
