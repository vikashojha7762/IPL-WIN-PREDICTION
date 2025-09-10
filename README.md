# IPL-WIN-PREDICTION
# 🏏 IPL Win Predictor

This project predicts the winning probability of IPL matches using historical match data and machine learning.  
It provides an interactive Streamlit web app where users can select match conditions (teams, city, target, score, overs, wickets) and get real-time win probabilities.

---

## 📁 Project Structure
- Ipl win prediction.ipynb** → Jupyter Notebook for data cleaning, feature engineering, and model training.
- matches.csv → Dataset containing IPL match-level information.
- deliveries.csv → Dataset containing ball-by-ball details of IPL matches.
- app.py → Streamlit web application for win probability prediction.
- pipe.pkl → Trained machine learning model (loaded in `app.py`).

---

## 🚀 Features
- Cleaned and processed IPL historical data.
- Built predictive features such as:
  - Current Run Rate (CRR)
  - Required Run Rate (RRR)
  - Runs/Wickets left
- Trained a Machine Learning model to predict win probability.
- Developed an interactive Streamlit dashboard for end users.

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy (data processing)
- Scikit-learn (machine learning model)
- Matplotlib/Seaborn (data visualization)
- Streamlit (web application)

---

## ▶️ How to Run

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/ipl-win-predictor.git
cd ipl-win-predictor
