🛡️ Network Intrusion Detection System (NIDS)

A machine learning–based Network Intrusion Detection System (NIDS) designed to classify normal and malicious traffic from benchmark datasets such as KDD Cup 1999 and NSL-KDD. This project demonstrates how supervised learning models can help detect cyber threats in real-time network environments.

🚀 Features

Preprocessing of raw network traffic datasets (KDD Cup / NSL-KDD).

Multiple ML algorithms tested: Decision Tree, Random Forest, Naïve Bayes, Logistic Regression, SVM, etc.

Performance evaluation with accuracy, precision, recall, F1-score, and confusion matrix.

Visualization of dataset distribution and results.

Modular structure — easy to extend with deep learning models.

📂 Project Structure
network-intrusion-detection-system/
│── data/                # Dataset files (KDD, NSL-KDD, etc.)
│── notebooks/           # Jupyter notebooks with experiments
│── src/                 # Core Python scripts
│   ├── preprocessing.py # Data cleaning and feature engineering
│   ├── train.py         # Model training
│   ├── evaluate.py      # Performance metrics & plots
│── requirements.txt     # Dependencies
│── README.md            # Project documentation

⚙️ Installation

Clone the repo:

git clone https://github.com/pragyabose1011/network-intrusion-detection-system.git
cd network-intrusion-detection-system


Create a virtual environment & install dependencies:

pip install -r requirements.txt

▶️ Usage
1. Preprocess Dataset
python src/preprocessing.py

2. Train Model
python src/train.py

3. Evaluate Performance
python src/evaluate.py

4. Run Jupyter Notebook (for exploration)
jupyter notebook notebooks/

📊 Results

Random Forest achieved ~99% accuracy on binary classification (Normal vs Attack).

Decision Tree and Logistic Regression provided faster training but slightly lower accuracy.

Confusion matrices show strong detection of DoS attacks, with some misclassifications in U2R/R2L categories (expected due to dataset imbalance).
