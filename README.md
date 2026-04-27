# Classification ML Models to Predict Client Subscriptions

**Machine learning classification approaches** for predicting whether a client will **subscribe** to a product/campaign. The work is organized into notebooks covering **dataset preparation**, **Random Forest modeling (baseline + enhanced)**, and **Neural Network modeling (original + updated)**.

Repository: https://github.com/d-senyaka/Classification-ML-Models-to-Predict-Client-Subscriptions  
Default branch: `master`

---

## Contents

The repo currently includes the following notebooks:

- **`Dataset preparation.ipynb`** — data loading, cleaning, feature engineering, and preparation for modeling
- **`Random Forest.ipynb`** — Random Forest classification workflow (baseline)
- **`Random Forest Enhanced.ipynb`** — improved Random Forest workflow (tuning and/or enhanced preprocessing)
- **`Neural_Network.ipynb`** — initial neural network classifier experiment
- **`Neural_Network_updated.ipynb`** — refined/updated neural network implementation


---

## Project Goal

The main objective is to build classification models that can predict **client subscription outcomes** based on historical client/campaign features. This helps support:

- better targeting of clients likely to subscribe
- improved campaign efficiency
- model comparison across classic ML and neural network approaches

---

## Typical Workflow (as implemented across notebooks)

While each notebook focuses on a specific stage/model, the general pipeline is:

1. **Data Preparation**
   - Load the dataset
   - Clean and transform variables
   - Encode categorical variables
   - Scale/normalize numerical features (as needed)
   - Split into training/testing sets

2. **Model Training**
   - Train a **Random Forest** classifier
   - Train a **Neural Network** classifier
   - Experiment with improved versions (enhanced RF, updated NN)

3. **Evaluation**
   Common classification evaluation outputs usually include:
   - confusion matrix
   - accuracy and/or error rate
   - precision, recall, F1-score
   - ROC-AUC (if included)

---

## How to Run

### 1) Clone the repository
```bash
git clone https://github.com/d-senyaka/Classification-ML-Models-to-Predict-Client-Subscriptions.git
cd Classification-ML-Models-to-Predict-Client-Subscriptions
```

### 2) Create an environment (recommended)
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate
```

### 3) Install dependencies
If you don’t have a `requirements.txt` yet, install the core stack commonly used for these notebooks:
```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
```

If your neural network notebooks use TensorFlow/Keras or PyTorch, install the relevant framework as well:
```bash
# Example:
pip install tensorflow
```

### 4) Launch Jupyter Notebook
```bash
jupyter notebook
```

Open and run the notebooks in this recommended order:
1. `Dataset preparation.ipynb`
2. `Random Forest.ipynb` / `Random Forest Enhanced.ipynb`
3. `Neural_Network.ipynb` / `Neural_Network_updated.ipynb`

---

## Models Implemented

- **Random Forest Classifier**
  - Baseline implementation
  - Enhanced variant (e.g., tuning, improved preprocessing, feature selection, etc.)

- **Neural Network Classifier**
  - Initial neural network approach
  - Updated version with refinements (architecture/training changes)

---

## Author

GitHub: https://github.com/d-senyaka
