# E-Commerce Data - Exploratory Data Analysis (EDA)
📄 Project Description
This project focuses on analyzing an e-commerce dataset to derive insights aimed at optimizing business processes. Using Exploratory Data Analysis (EDA) techniques, the dataset was cleaned, missing values were handled, outliers were corrected, and statistical analyses were performed.

🗂️ Dataset Features
The dataset contains sales records from an e-commerce business. The features are as follows:

InvoiceNo: Invoice number (a unique identifier for each transaction).
StockCode: Product code.
Description: Product description.
Quantity: Number of products sold.
InvoiceDate: Date and time of the invoice.
UnitPrice: Price per unit (£).
CustomerID: Customer ID (a unique identifier for each customer).
Country: Country where the customer resides.
Dataset link: E-Commerce Dataset
Kaggle notebook: E-Commerce Sales EDA

# 🛠️ Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For mathematical operations and type management.
Matplotlib: For creating visualizations.
Seaborn: For advanced visualization tools.
Scikit-learn: For preprocessing and modeling.

# 📝 Detailed Analysis Steps
1. Dataset Selection and Loading
The dataset was loaded using Pandas. The following steps were performed:

The first 10 rows of the dataset were reviewed.
The size of the dataset (number of rows and columns) was analyzed.
Data types and missing values were checked.
2. Exploratory Data Analysis (EDA)
2.1 Handling Missing Values
Missing values in columns like CustomerID were identified.
Missing values were filled using mean or mode or removed if necessary.
2.2 Data Type Conversion
The InvoiceDate column was converted to datetime format.
Columns such as Quantity and UnitPrice were checked for negative values and corrected.
2.3 Identifying and Handling Outliers
Outliers were detected using Z-score and IQR (Interquartile Range) methods.
Outliers were reviewed and addressed based on business rules.
2.4 Statistical Analysis
Summary statistics (mean, median, min, max) for each column were generated.
Total spending and purchase frequencies were calculated per customer.
2.5 Data Visualization
Matplotlib and Seaborn were used to create visualizations for sales trends and product performance:
Total sales by country.
Time-series analysis (daily/monthly sales).
Distribution of top-selling products.
3. Correlation Analysis
A Correlation Matrix was used to analyze relationships between variables.
A heatmap was created for visualization.
4. Feature Selection & Feature Engineering
Relevant features were selected to optimize the dataset for modeling.
New features were engineered:
TotalPrice: Total transaction amount (Quantity × UnitPrice).
PurchaseFrequency: Purchase frequency per customer.
Irrelevant columns were removed.

# 📂 File Structure
ecommerce-data/: Folder containing the dataset.
data.csv: E-commerce data.
e-commerce-sales-eda.ipynb: Notebook file for the analysis.
README.md: Project overview and instructions.

# 🚀 How to Run
Clone this repository:
bash
Kodu kopyala
git clone https://github.com/your-username/e-commerce-sales-eda.git
Install required libraries:
bash
Kodu kopyala
pip install -r requirements.txt
Open the notebook file:
bash
Kodu kopyala
jupyter notebook e-commerce-sales-eda.ipynb

# 🌟 Insights and Outcomes
Top Performing Countries: The UK contributes the majority of sales.
Sales Time Distribution: Most sales occur in the afternoon.
Top-Selling Products: Top 10 products were analyzed based on sales frequency.
