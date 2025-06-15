# 🌾 Crop Yield Predictor: Modeling Inputs & Rainfall for Indian Agriculture

This project analyzes agricultural trends across India to **predict crop yield**, **fertilizer usage**, **pesticide requirements**, and even **annual rainfall**, using real government datasets.

We use machine learning (XGBoost) to train on historical data (1997–2019) and test predictive accuracy by state, crop, and year.

---

## 📊 Project Goals

- ✅ Predict **crop yield** (tonnes/ha) using fertilizer, pesticide, and rainfall data
- ✅ Predict **fertilizer & pesticide use** based on environmental and yield trends
- ✅ Model **rainfall requirements** per state using past crop activity
- ✅ Evaluate model performance with MAE, RMSE, and visualizations
- ✅ Visualize predictions over time for top-performing states

---

## 🧪 Key Technologies

- Python, Pandas, NumPy
- XGBoost for regression modeling
- Scikit-learn metrics (MAE, RMSE, R²)
- Matplotlib & Seaborn for charts
- Google Colab + GitHub for deployment

---
## 🌍 Interactive Maps & Spatial Analysis

This project also includes an **interactive GIS-style notebook** that visualizes crop yields, soil zones, and rainfall trends using **Folium maps**.

🔗 [🌐 View the Full Interactive Notebook on Google Colab](https://colab.research.google.com/drive/1NgIWaODgIYsB3wkqdSYQR5TNUy6DaMbn)

> *Built with GeoPandas and Folium to simulate real-world agri-tech mapping tools, this notebook showcases how spatial datasets can be visualized and analyzed for actionable insights.*

---

## 📌 How to Use

1. Clone this repo or open the notebook directly in **[Google Colab](https://colab.research.google.com/github/CuHzQuixote/Crop-Yield-Predictor/blob/main/Updated_Crop_Yield_Predictor_With_Rainfall.ipynb)**.
2. Upload `Cleaned_Crop_Yield_For_Modeling.csv` to your Colab runtime.
3. Run through each section to:
   - Train yield prediction models
   - Forecast input usage (fertilizer/pesticide)
   - Analyze rainfall trends by state
4. Modify `target_crop`, `target_state`, and `target_year` to test different prediction scenarios.

---

## 📈 Sample Output

| Year | State   | Actual Yield | Predicted Yield | RMSE |
|------|---------|--------------|------------------|------|
| 2019 | Punjab  | 3.93         | 3.99             | 0.06 |
| 2018 | Punjab  | 4.12         | 4.08             | 0.04 |

> *(See full prediction charts in the notebook)*

---

## 🌿 Notes

- Raw data sourced from the Indian government's agriculture and rainfall databases.
- Rainfall was manually aligned using subdivision-to-state mapping for clean merging.
- Built as a final capstone project with a focus on **real-world agri-tech use cases**.

---

## 🙋‍♂️ Author

**jas chahal**  
Data science, agri-tech, and gym enjoyer 💪  
🔗 [GitHub.com/CuHzQuixote](https://github.com/CuHzQuixote)

