
# 🫀 Predicting 10-Year Risk of Coronary Heart Disease

This project develops a **logistic regression model** to predict an individual’s 10-year risk of Coronary Heart Disease (CHD) using clinical and lifestyle features. It combines thorough data exploration, model development and interpretability using SHAP to support early detection and preventive care.

---

## 📁 Folder Structure

```
your-project/
├── dataset/
│   ├── cleaned_train_data.csv          # Cleaned dataset used in analysis
│   └── train.csv                       # Original dataset
├── notebooks/
│   ├── analysis.ipynb                  # Full analysis: EDA, modeling, SHAP
│   └── report.ipynb                    # Summary report of problem & findings
├── slides/
│   └── CHD_Risk_Prediction_Summary.pptx  # Presentation
├── requirements.txt				               
├── README.md                           
```

---

## 🧠 Project Summary

> A logistic regression model that predicts 10-year coronary heart disease risk using key health and lifestyle factors, empowering early intervention through data-driven insights. It was built with clean medical data, refined features and interpreted using SHAP for transparency. 

---

## 🔍 Features

- **Data Exploration & Profiling**
  - Quick overview using `ydata-profiling`
  - Missing value analysis and outlier detection

- **Preprocessing**
  - Imputation, feature selection, scaling
  - Label encoding where necessary

- **Modeling**
  - Logistic Regression for binary classification
  - Evaluated using Accuracy, Precision, Recall, AUC

- **Interpretability**
  - SHAP used for feature importance analysis
  - Global and local explanations for predictions

---

## 📊 Files Description

| Path | Description |
|------|-------------|
| `dataset/cleaned_train_data.csv` | Cleaned version of the dataset used in training |
| `dataset/train.csv` | Original dataset |
| `notebooks/analysis.ipynb` | Main notebook with full pipeline |
| `notebooks/report.ipynb` | Summary and documentation of findings |
| `slides/CHD_Risk_Prediction_Summary.pptx` | Presentation for stakeholders or portfolio |
| `README.md` | Project overview and setup instructions |

---

## 🚀 How to Run

1. Clone this repository
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch and explore the notebook:
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```

---

## 📦 Requirements

Key Python libraries used:
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `shap`
- `ydata-profiling`

> See `requirements.txt` for exact versions.

---

## 📝 License

This project is open for academic, research and portfolio use. Attribution is appreciated.

📬 Contact If you have any questions or suggestions, feel free to reach out:

Name: Ibukunoluwa Johnson

Email: ibukunjohnson02@gmail.com

LinkedIn: www.linkedin.com/in/ibukunoluwa-johnson-09a340353

GitHub: https://github.com/thatgirltomiie
