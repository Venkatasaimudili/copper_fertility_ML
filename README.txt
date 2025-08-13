
Geochemical Classification of Copper Fertility Using Ensemble Machine Learning

This repository contains the source code and workflow for the study titled:

"Geochemical classification of copper fertility using ensemble model: A framework for addressing class imbalance and enhancing geochemical interpretability"

Overview:

This study presents a machine learning framework for classifying copper mineralization from geochemical datasets. The framework addresses class imbalance using SMOTE, applies various supervised ML models, and interprets the results through feature importance analysis.

---

Methods Implemented:

- Data Preprocessing (Z-score normalization)
- Class Imbalance Handling (SMOTE)
- Supervised ML Models:
  - Logistic Regression (LR)
  - Support Vector Machine (SVM)
  - Multilayer Perceptron (MLP)
  - Random Forest (RF)
  - Ensemble Model (Voting Classifier)
- Evaluation Metrics:
  - Accuracy, Precision, Recall, F1-score, ROC-AUC
- Feature Importance:
  - Gini Importance
  - Permutation Importance
  - Normalized Feature Scores

---

File Structure:

- `copper_paper.ipynb` – Main Jupyter notebook containing full pipeline
- `data/` – Folder for uploading the geochemical dataset (not publicly available)
- `README.md` – Project overview and instructions (this file)

---

Requirements:

Install the following Python libraries before running the notebook:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn imbalanced-learn
```

---

Running the Code:

1. Clone the repository or download the notebook.
2. Place your geochemical CSV dataset in a `data/` folder.
3. Open the notebook:  
   ```bash
   jupyter notebook copper_paper.ipynb
   ```
4. Execute the notebook cells step-by-step.

---

Output Highlights:

- Ensemble model performance:  
  - Accuracy: `0.9735`
  - Recall: `0.9896`
  - F1-score: `0.9740`
- Important Pathfinder Elements:  
  - Fe, K, Mn, Sr, Tb — consistent with known hydrothermal processes

---

Data Availability:

Due to project-level restrictions, the full dataset cannot be shared. However, a sample dataset and preprocessing format are provided for demonstration.

---

Citation:

If you use this code, please cite the corresponding paper:

```
Avatharam Ganivada, P.V. Sunder Raju, Venkata Sai Mudili. 
"Geochemical Classification of Copper Fertility Using Ensemble Machine Learning: 
A Framework for Addressing Class Imbalance and Enhancing Geochemical Interpretability." 
Artificial Intelligence in Geosciences, 2025.
```

---

Authors:

- Avatharam Ganivada – [avatharg@uohyd.ac.in](mailto:avatharg@uohyd.ac.in)  
- P.V. Sunder Raju – CSIR-NGRI  
- Venkata Sai Mudili – University of Hyderabad

---

License:

This code is open for academic use. For commercial use or collaborations, contact the corresponding author.
