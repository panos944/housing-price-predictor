# 🏠 Real Estate Predictor

A Python-based machine learning portfolio project with regression, classification, and deep learning tasks. Built using real-world datasets to demonstrate core ML workflows, data preprocessing, model evaluation, and visualization.

---

## 📊 Project Features

### Regression
- Predicting housing prices using:
  - Simple Linear Regression
  - Multiple Linear Regression
- Visualizations: heatmaps, pairplots, prediction error plots

### Classification
- K-Nearest Neighbors (KNN) on secret customer data
- Feature scaling, model tuning (optimal k), performance evaluation

### Deep Learning
- MNIST digit classification using a simple CNN
- Includes plots and training insights

---

## 📁 Project Structure

```text
real-estate-predictor/
├── 01. Simple Linear Regression/
│   ├── housing.py
│   ├── correlation_heatmap.png
│   ├── linear_model_avg_area.png
│   └── predictions_vs_actuals.png
│
├── 02. Multi Linear Regression/
│   ├── housing2.py
│   ├── correlation_heatmap.png
│   ├── linear_model_joblib.pkl
│   ├── pairplot.png
│   └── predictions_vs_actuals.png
│
├── 03. Multi Linear Regression 2/ (optional section)
│   └── housing3.py
│
├── 04. Classification ClassifiedData/
│   ├── knn_classification.py
│   └── plots/
│       └── (KNN error rate, accuracy visuals, etc.)
│
├── 05. MNIST Dataset/
│   ├── mnist_cnn.py
│   └── mnist_plots/
│       └── (training loss/accuracy plots)
│
├── data/
│   ├── USA_Housing.csv
│   └── secret_data.csv
│
├── venv/
│   └── (virtual environment — excluded via .gitignore)
│
├── requirements.txt
└── README.md
```

# Getting Started

- Clone the repo
git clone https://github.com/panos944/real-estate-predictor.git
cd real-estate-predictor

- Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate

- Install required packages
pip install -r requirements.txt


# 📦 Requirements
See requirements.txt for full list. Includes:

	•	pandas
	•	numpy
	•	scikit-learn
	•	matplotlib
	•	seaborn
	•	tensorflow
	•	joblib
