# Epilepsy-seizer-classification-project
Epilepsy prediction using EEG: Loads and cleans data, visualizes signals, extracts DWT features, balances classes with SMOTE, and trains a CNN for classification. Evaluates with accuracy, confusion matrix, and ROC curve. Includes plots and performance metrics.

# Epilepsy-seizer-classification
# Overview
This project predicts epileptic seizures from EEG signals using deep learning. It preprocesses EEG data, extracts features with Discrete Wavelet Transform (DWT), balances classes with SMOTE, and trains a 1D CNN for classification. Performance is evaluated using accuracy, confusion matrix, and ROC curve.

# Features
* Loads and cleans EEG data
* Visualizes raw EEG signals and DWT decomposition
* Extracts DWT features for each signal
* Data balancing with SMOTE and augmentation
* 1D CNN model for classification
* Evaluation with accuracy, confusion matrix, ROC curve, and plots

# Usage
* Place your EEG data as CSB_MIT.csv in the project folder.
* Run the notebook Epilepsy seizer classification.ipynb in Jupyter or VS Code.
* View results and plots generated in the notebook.
* Requirements
* Python 3.x
* numpy, pandas, matplotlib, seaborn
* pywt
* scikit-learn
* imbalanced-learn
* tensorflow, keras
* Install dependencies with:

# Results
* Visualizations of EEG signals and DWT components
* Model accuracy and loss curves
* Confusion matrix and ROC curve

# License
* This project is for educational and research purposes.
