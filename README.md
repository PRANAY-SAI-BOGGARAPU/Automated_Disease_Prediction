# Automated_Disease_Prediction
# 🩺 Automated Disease Prediction using Machine Learning

1. Data Loading & Preprocessing
Load CSV data, clean entries (e.g., missing values), encode categorical variables, and scale numeric features.

2. Model Training (train_model.py)
Train and compare multiple models: Logistic Regression, Random Forest, SVM. Save best-performing models.

3. Streamlit App UI (app.py)
Inputs via sliders, dropdowns, text fields

On "Predict", selected model loads via pickle

Show output probability/risk with visual explanation graphs

4. Model Performance & Explainability
Show ROC curves, confusion matrices, and feature importances for transparency and validation.
---

## 🧩 Installation

1. :contentReference[oaicite:7]{index=7}

    ```bash
    git clone https://github.com/yourusername/disease-predictor.git
    cd disease-predictor
    ```

2. :contentReference[oaicite:8]{index=8}

    ```bash
    pip install -r requirements.txt
    ```

3. :contentReference[oaicite:9]{index=9}

    - :contentReference[oaicite:10]{index=10}  
    - :contentReference[oaicite:11]{index=11}

---

## 🧪 Quick Start

:contentReference[oaicite:12]{index=12}

```bash
streamlit run app.py

