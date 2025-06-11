## 📊 Retail Sales Analysis and Prediction

This project performs **exploratory data analysis**, **feature engineering**, and **sales revenue prediction** using **Linear Regression** and **Random Forest** models. It provides insights into key sales drivers like product category, store location, discounts, and marketing spend.

---

### 🗂️ Project Files

* `Retail_Sales_Analysis_and_Prediction.ipynb` – Main notebook containing data processing, EDA, and model evaluation.
* `Retail_sales.csv` – Raw dataset (optional, assumed to be uploaded).
* `Retail_sales_cleaned.csv` – Cleaned and feature-engineered dataset.
  
### ✅ Features

* 🧹 Data Cleaning & Duplicate Removal
* 📅 Date Feature Extraction (`Year`, `Month`, `Day`)
* 📦 Categorical Encoding & Feature Scaling
* 📊 EDA with Histograms, Pairplots, Boxplots
* 🔍 Outlier Detection
* 🤖 ML Models: Linear Regression & Random Forest
* 📈 Performance Metrics: R² and RMSE

---

### 🔧 Tech Stack

* Python
* Jupyter Notebook
* **Pandas**, **NumPy**
* **Matplotlib**, **Seaborn**
* **Scikit-learn** – Preprocessing, Pipelines, Models

---

### 🚀 How to Run the Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/retail-sales-analysis.git
   cd retail-sales-analysis
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook Retail_Sales_Analysis_and_Prediction.ipynb
   ```

---

### 📊 Model Evaluation Results

| Model             | R² Score | RMSE   |
| ----------------- | -------- | ------ |
| Linear Regression | 0.8629   | 959.33 |
| Random Forest     | 0.9962   | 159.17 |

*Exact values will depend on your dataset split and randomness.*

---

### 📈 Insights Extracted

* Marketing spend has a strong correlation with units sold.
* Some product categories show consistently higher revenue.
* Sales peak on certain days of the week.

---

### 🔮 Future Enhancements

* Add time series forecasting (e.g., ARIMA, Prophet)
* Deploy as a web dashboard (e.g., Streamlit or Flask)
* Include real-time predictions from new inputs

---

### 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

### 🙌 Acknowledgments

* [Scikit-learn](https://scikit-learn.org/)
* [Pandas Documentation](https://pandas.pydata.org/)
* [Seaborn](https://seaborn.pydata.org/)

---
