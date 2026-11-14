# 🏦 Loan Approval Prediction — Machine Learning Classification Pipeline

An end-to-end data analysis and Machine Learning project built to predict loan approval eligibility based on applicant demographics, income metrics, and credit history.

---

## 📊 Project Workflow & Key Features

* **🧹 Data Cleaning & Preprocessing:**
  * Inspected dataset dimensions and missing values across applicant features.
  * Handled missing records and duplicate entries to ensure high data integrity.
  * Applied One-Hot Encoding (`pd.get_dummies`) to transform categorical variables into model-ready numerical features.
* **📈 Exploratory Data Analysis (EDA):**
  * Built a multi-panel visualization dashboard using **Matplotlib** and **Seaborn** analyzing `Loan_Status` distribution, `Credit_History` impact, `Education` levels, `ApplicantIncome` distribution, and the relationship between income and `LoanAmount`.
* **🔢 Statistical Analysis (NumPy):**
  * Computed core descriptive statistics (Mean, Median, and Standard Deviation) for applicant income distributions.
* **🤖 Predictive Modeling & Evaluation (Scikit-Learn):**
  * Split the dataset into **80% Training** and **20% Testing** subsets (`random_state=42`).
  * Trained a **Logistic Regression** classifier (`max_iter=2000`) to predict loan approval outcomes.
  * Evaluated model performance using **Accuracy Score**, **Confusion Matrix**, and a full **Classification Report** (Precision, Recall, F1-Score).

---

## 🛠️ Tech Stack

* **Language:** Python 3
* **Data Manipulation & Math:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (`LogisticRegression`, `train_test_split`, `classification_report`)

---

## ⚙️ How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/abdulrahmanfawezi29-cmd/Loan-Approval-Prediction.git](https://github.com/abdulrahmanfawezi29-cmd/Loan-Approval-Prediction.git)
   cd Loan-Approval-Prediction
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the script:**
   Ensure the dataset file (`train_u6lujuX_CVtuZ9i.csv`) is in the same directory, then execute:
   ```bash
   python loan_approval_prediction_ml_ipynb.py
   ```

---

## 👨‍💻 Author

**Abdulrahman Fawezi** — Business Information Systems (BIS) | Data Analysis & AI
* **GitHub:** [@abdulrahmanfawezi29-cmd](https://github.com/abdulrahmanfawezi29-cmd)
* **LinkedIn:** [Abdulrahman Fawezi](https://www.linkedin.com/in/abdulrahman-fawezi)
