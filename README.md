# Employee Attrition Analysis and Prediction

## Overview
This project implements machine learning models to predict and analyze employee attrition using workforce data. The study compares eight different machine learning techniques and introduces a custom ensemble model combining XGBoost and Random Forest, which achieved the highest prediction accuracy.

## 🎯 Key Features
- Comprehensive analysis of employee attrition factors
- Comparison of 8 different machine learning models
- Custom ensemble model (XGBRF) with superior performance
- Data preprocessing and feature engineering pipeline
- Model evaluation using multiple metrics (ROC-AUC, F1 Score, Cross-validation)

## 📊 Models Implemented
1. XGBoost
2. Random Forest
3. Decision Tree
4. Logistic Regression
5. Support Vector Machine
6. Perceptron
7. Naïve Bayes
8. KNN
9. Custom Ensemble Models:
   - AdaBoost with Grid Search CV
   - XGBoost + Random Forest (XGBRF Classifier)

## 📋 Dataset
- Combined dataset from IBM HR Analytics and Kaggle
- 4,400 records with 29 features
- Includes both categorical and numerical data

## 🔧 Technical Implementation
### Data Preprocessing
- Data cleansing and handling missing values
- Data imputation using mean values
- Feature binning for 'Age' and 'Income'
- Label encoding for categorical features
- Dataset split: 80% training, 20% testing

### Model Evaluation Metrics
- Cross-validation
- F1 Score
- ROC-AUC curve
- Precision and Recall

## 📈 Results
- The XGBRF ensemble model achieved the best performance
- ROC-AUC score of 0.85
- Superior prediction accuracy compared to individual models

## 🚀 Getting Started
```bash
# Clone the repository
git clone [repository-url]

# Install required packages
pip install -r requirements.txt

# Run the main script
python main.py
```

## 📦 Dependencies
- Python 3.x
- scikit-learn
- XGBoost
- pandas
- numpy
- matplotlib
- seaborn

## 👥 Contributors
- Pooja Alumalla (apooja@umich.edu) - Data gathering, analysis, cleansing, and structuring
- Sathya Narayanan Thothathri (sathyasn@umich.edu) - Data modeling, evaluation, ML algorithms, and visualization
- Harsha Vardhan Sai Machineni (hvm@umich.edu) - UI building, Deployment

## 📚 References
1. Springer Switzerland study on employee attrition prediction
2. MDPI research on machine learning for attrition prediction
3. International Journal of Advanced Computer Science and Applications study
4. Various academic papers on employee turnover and HR analytics

## 📄 License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

---
*This project was developed as part of ECE-579 Intelligent Systems course at the University of Michigan under the guidance of Professor Yi Lu Murphey.*
