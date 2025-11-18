
# **Track AI & Data Science Competition**

## **Case Study: SkilioMall**

### **Project Setup & Execution Guide**



##  **1. Clone the Repository**

```bash
git clone https://github.com/RemMyDream/Churn-Rate-Prediction.git
cd Churn-Rate-Prediction
```

---

##  **2. Create Python Environment (Python 3.10)**

```bash
python3.10 -m venv skiliomall
source skiliomall/bin/activate   # On Windows: skiliomall\Scripts\activate
```
---

## **3. Install Dependencies**

Install all required packages using `requirements.txt`:

```bash
pip install -r requirements.txt
```

If you encounter any build issues, update pip first:

```bash
pip install --upgrade pip
```

---

##  **4. Project Structure**

```
Churn-Rate-Prediction/
│
├── dataset.csv          # Raw dataset
├── notebook.ipynb       # Jupyter notebooks for EDA, modeling, evaluation
├── requirements.txt     # Python dependencies
└── README.md            # This file
```

---

## **5. Running the Jupyter Notebook**

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open the notebook:

* `notebook.ipynb`

This notebook contains:

1. **Exploratory Data Analysis (EDA)**
2. **Modeling**
3. **Evaluation** (XGBoost / LightGBM / Stacking)
4. **Model Explanation** (Optuna)

Run all cells sequentially to reproduce the full workflow.

---