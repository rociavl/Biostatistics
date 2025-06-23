# Kidney Disease Prediction & Biomarker Discovery

Machine learning pipeline for chronic kidney disease (CKD) prediction using clinical biomarkers and patient stratification analysis.

## 🎯 Project Overview

This project develops predictive models to identify patients at risk of chronic kidney disease using easily accessible clinical parameters. The goal is to enable early detection and intervention through computational biomarker analysis and patient stratification strategies.

## 🔬 Key Features

- **Biomarker Identification**: Statistical analysis to identify key predictive clinical features
- **Machine Learning Classification**: Multiple ML algorithms for CKD prediction
- **Feature Selection**: Advanced techniques to optimize biomarker panels
- **Patient Stratification**: Risk assessment and patient categorization
- **Clinical Validation**: Performance evaluation using clinically relevant metrics

## 📊 Dataset

The analysis uses clinical data including:
- Laboratory biomarkers (creatinine, blood urea nitrogen, hemoglobin, etc.)
- Patient demographics (age, gender, hypertension, diabetes history)
- Clinical measurements (blood pressure, specific gravity, albumin levels)
- Target variable: CKD diagnosis (binary classification)

## 🛠️ Methodology

### Data Preprocessing
- Missing value imputation
- Feature scaling and normalization
- Categorical encoding
- Outlier detection and handling

### Machine Learning Models
- **Classification Algorithms**: Logistic Regression, Random Forest, SVM, XGBoost
- **Feature Selection**: Recursive Feature Elimination, Statistical Testing
- **Model Evaluation**: Cross-validation, ROC-AUC, Precision-Recall curves
- **Clinical Metrics**: Sensitivity, specificity, positive/negative predictive values

### Biomarker Analysis
- Statistical significance testing
- Feature importance ranking
- Correlation analysis
- Clinical interpretation of key biomarkers

## 📈 Results

The analysis identifies key biomarkers for CKD prediction and evaluates their clinical utility:
- **Top Predictive Features**: Creatinine levels, blood urea nitrogen, hemoglobin
- **Model Performance**: Achieved high accuracy with clinically acceptable sensitivity/specificity
- **Risk Stratification**: Developed patient risk categories for targeted interventions

## 🔧 Technologies Used

- **Python**: Primary programming language
- **Pandas & NumPy**: Data manipulation and numerical analysis
- **Scikit-learn**: Machine learning algorithms and evaluation
- **Matplotlib & Seaborn**: Data visualization
- **Scipy**: Statistical analysis
- **Jupyter Notebook**: Interactive development environment

## 📁 Repository Structure

```
Biostatistics/
├── Primer proyecto: Predicción de Enfermedad Renal/
│   └── Proyecto1_Rocio_Ainhoa_final.ipynb    # Main analysis notebook
└── README.md                                  # This file
```

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy scikit-learn matplotlib seaborn scipy jupyter
```

### Running the Analysis
1. Clone the repository
2. Open `Proyecto1_Rocio_Ainhoa_final.ipynb` in Jupyter Notebook
3. Run all cells to reproduce the analysis

## 📋 Key Findings

- **Early Detection**: Machine learning models can effectively predict CKD using routine clinical tests
- **Biomarker Panel**: Identified minimal set of biomarkers for cost-effective screening
- **Clinical Impact**: Results support development of automated screening tools for healthcare settings
- **Patient Stratification**: Risk-based categorization enables personalized treatment approaches

## 🎯 Clinical Applications

- **Screening Programs**: Early identification of at-risk patients
- **Resource Allocation**: Prioritize high-risk patients for specialist referral
- **Treatment Planning**: Inform clinical decision-making with risk scores
- **Public Health**: Population-level CKD surveillance and prevention strategies

## 👥 Authors

**Rocío Ávalos Morillas**
- Biomedical Engineering Student, UPC
- Email: rocio.avalos029@gmail.com
- LinkedIn: [Rocío Ávalos Morillas](https://www.linkedin.com/in/roc%C3%ADo-%C3%A1valos-morillas-04a5372b1/)
- GitHub: [@rociavl](https://github.com/rociavl)

**Ainhoa Fraile Pulido**
- Biomedical Engineering Student, UPC

## 📄 License

This project is part of academic coursework in Biostatistics and is intended for educational and research purposes.

## 🤝 Contributing

This repository represents academic work. For questions or collaboration opportunities, please reach out via email or LinkedIn.

---

*This project demonstrates the application of machine learning techniques to biomedical data for improving chronic kidney disease detection and patient care.*
