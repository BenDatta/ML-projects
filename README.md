# 🧠 ML-practice

A curated collection of hands-on machine learning projects using Python, built to strengthen foundational ML skills and showcase applied data science techniques. This folder focuses on end-to-end implementation of supervised learning tasks such as classification and regression.

🔗 [Project Folder on GitHub](https://github.com/BenDatta/ML-projects/tree/main/Classification)

---

## 🛠️ Tech Stack

| Category          | Tools/Technologies                                        |
|-------------------|------------------------------------------------------------|
| **Language**       | Python                                                    |
| **Data Handling**  | `pandas`, `NumPy`                                         |
| **Preprocessing**  | `train_test_split`, `OneHotEncoder` (from `scikit-learn`) |
| **Modeling**       | `scikit-learn` (Linear Regression, Random Forest, etc.)   |
| **Visualization**  | `matplotlib`, `seaborn`                                   |
| **Serialization**  | `pickle`                                                  |
| **Notebook IDE**   | Jupyter Notebook                                          |
| **Model Tracking** | MLflow                                                    |

---

## 📁 Folder Structure


---

## 📊 Project Highlights

### ✅ Classification Projects
- Built classifiers using `RandomForestClassifier`, `LogisticRegression`, and others.
- Evaluated using accuracy, precision, recall, F1-score, and confusion matrix.
- Preprocessed data using encoding techniques and ensured clean train-test splits.

### 🔢 Regression Projects
- Applied linear and ensemble regressors on real-world datasets.
- Assessed with MAE, RMSE, and R² metrics.
- Visualized performance and residuals for interpretation.

---

## 🔄 ML Pipeline Management

Each project follows a consistent pipeline structure:
1. **Data Ingestion** – Load and explore the dataset.
2. **Preprocessing** – Clean, encode, and split data.
3. **Model Training** – Train and evaluate multiple models.
4. **Model Tracking** – Log parameters and metrics with **MLflow**.
5. **Serialization** – Save final models using `pickle`.

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/BenDatta/ML-projects.git
cd ML-projects/Classification

# 2. (Optional) Create virtual environment
python -m venv venv
source venv/bin/activate       # On Windows use: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Start Jupyter Notebook
jupyter notebook
