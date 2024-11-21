# E-Commerce Data - Exploratory Data Analysis (EDA)

## 📄 Project Overview  
- **Objective**: Analyze e-commerce sales data to gain insights and improve business strategies.  
- **Techniques**: Data cleaning, outlier handling, correlation analysis, and feature engineering.  
- **Tools**: Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.  

---

## 🗂️ Dataset Information  
- Contains sales data from an e-commerce platform.  
- **Features**:  
  - `InvoiceNo`: Unique transaction number.  
  - `StockCode`: Product code.  
  - `Description`: Product description.  
  - `Quantity`: Quantity sold.  
  - `InvoiceDate`: Date and time of purchase.  
  - `UnitPrice`: Price per unit (£).  
  - `CustomerID`: Unique customer identifier.  
  - `Country`: Customer's country of residence.  

> Dataset link: [E-Commerce Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  
> Kaggle notebook: [E-Commerce Sales EDA](https://www.kaggle.com/code/zeynepkuri/e-commerce-sales-eda)  

---

## 🛠️ Libraries Used  
- **Pandas**: Data manipulation and analysis.  
- **NumPy**: Mathematical operations.  
- **Matplotlib**: Basic visualizations.  
- **Seaborn**: Advanced visualizations.  
- **Scikit-learn**: Preprocessing and modeling.  

---

## 📝 Analysis Workflow  

### 1. Dataset Loading  
- Loaded the dataset using **Pandas**.  
- Checked the first few rows, dataset shape, data types, and missing values.  

### 2. Data Cleaning  
- **Missing values**: Identified and filled or removed missing values.  
- **Data types**: Converted `InvoiceDate` to `datetime` and checked for logical inconsistencies.  
- **Negative values**: Corrected invalid entries in `Quantity` and `UnitPrice`.  

### 3. Handling Outliers  
- Detected outliers using **Z-score** and **IQR** methods.  
- Addressed outliers based on business logic.  

### 4. Statistical Analysis  
- Computed descriptive statistics (e.g., mean, median, min, max).  
- Analyzed customer spending patterns and sales frequency.  

### 5. Data Visualization  
- Used **Matplotlib** and **Seaborn** to visualize key insights:  
  - Sales trends by country.  
  - Time-series analysis of daily/monthly sales.  
  - Distribution of top-selling products.  

### 6. Correlation Analysis  
- Generated a **correlation matrix** to study variable relationships.  
- Visualized correlations using a heatmap.  

### 7. Feature Engineering  
- Created new features like:  
  - `TotalPrice`: `Quantity × UnitPrice`.  
  - `PurchaseFrequency`: Customer purchase count.  
- Removed irrelevant columns for a cleaner dataset.  

---

## 📂 File Structure  
- **ecommerce-data/**: Folder containing the dataset.  
  - `data.csv`: E-commerce data.  
- `e-commerce-sales-eda.ipynb`: Jupyter Notebook for the analysis.  
- `README.md`: Project documentation.  

---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/e-commerce-sales-eda.git

2. install the required libraries, and open the Jupyter Notebook with the following commands:
```bash
pip install -r requirements.txt  
jupyter notebook e-commerce-sales-eda.ipynb




  

