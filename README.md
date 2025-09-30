# UrbanNest — Next-Gen Short-Stay Listing Intelligence

UrbanNest is a data-driven project designed to extract insights from short-stay rental datasets 
(such as Airbnb’s open data). It predicts fair prices, classifies listing popularity, 
and flags risky hosts — with explainable AI and interactive dashboards.

## ✨ Features
- Price Prediction using Gradient Boosting (LightGBM).
- Popularity Classification (High/Medium/Low).
- Risk Scoring for host reliability.
- Explainable insights with SHAP.
- Interactive Streamlit dashboard.

## 📂 Project Structure
- `data/` → placeholder for datasets.
- `notebooks/` → Jupyter notebooks for exploration.
- `src/` → Python modules for preprocessing, modeling, scoring.
- `app/` → Streamlit dashboard.
- `outputs/` → Generated reports and plots.

## 🚀 Getting Started
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/UrbanNest-ShortStay-Intelligence.git
   cd UrbanNest-ShortStay-Intelligence
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run analysis (example):
   ```bash
   python src/price_model.py
   ```

4. Launch dashboard:
   ```bash
   streamlit run app/streamlit_app.py
   ```

## 📊 Dataset
We use the **Inside Airbnb open dataset** (New York City).  
Download here: http://insideairbnb.com/get-the-data.html

## 📜 License
MIT License.
