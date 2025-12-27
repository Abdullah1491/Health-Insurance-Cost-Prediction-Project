# Health-Insurance-Cost-Prediction-Project
Ecodation Project

# Insurance Charges Prediction Project

## 📌 Project Overview (EN)
This project analyzes the **Insurance dataset** from Kaggle to predict medical charges based on demographic and lifestyle factors.  
We perform data loading, inspection, exploratory data analysis (EDA), preprocessing, and modeling with Linear Regression, Ridge, Lasso, and Random Forest.

## 📌 Proje Özeti (TR)
Bu proje Kaggle’daki **Insurance veri setini** kullanarak demografik ve yaşam tarzı faktörlerine göre sağlık masraflarını tahmin etmeyi amaçlar.  
Veri yükleme, kontrol, keşifsel veri analizi (EDA), ön işleme ve Lineer Regresyon, Ridge, Lasso, Random Forest modelleriyle tahmin yapılmıştır.

---

## 📂 Steps / Adımlar
1. **Data Loading / Veri Yükleme**  
   - Dataset added via Kaggle’s *Add Data* option  
   - Loaded with `pandas.read_csv()`

2. **Data Inspection / Veri Kontrolü**  
   - Checked data types, missing values, summary statistics

3. **Exploratory Data Analysis (EDA) / Keşifsel Veri Analizi**  
   - Distribution plots (charges, BMI)  
   - Smoking impact on charges  
   - Correlation heatmap

4. **Preprocessing & Feature Engineering / Ön İşleme & Özellik Mühendisliği**  
   - One-hot encoding for categorical variables  
   - Scaling numerical variables  
   - Train-test split

5. **Modeling / Modelleme**  
   - Baseline: Linear Regression  
   - Advanced: Ridge, Lasso, Random Forest

6. **Results / Sonuçlar**  
   - Random Forest achieved the best performance (lowest RMSE, highest R²)

---

## 📊 Results Table / Sonuç Tablosu
| Model            | RMSE   | R²   |
|------------------|--------|------|
| Linear Regression| ...    | ...  |
| Ridge Regression | ...    | ...  |
| Lasso Regression | ...    | ...  |
| Random Forest    | ...    | ...  |

---

## 🚀 How to Run / Çalıştırma
```bash
# Clone repository
git clone https://github.com/<username>/<repo-name>.git

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook insurance_project.ipynb
