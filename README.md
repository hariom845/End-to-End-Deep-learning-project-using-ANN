# End-to-End Deep Learning Project using ANN for prediction of Estimated Salary

---

## 📌 Project Overview

This project is about building and using an Artificial Neural Network (ANN) model for prediction tasks. It includes:

- Data preprocessing (encoding, scaling, etc.)  
- Model building, training, and hyperparameter tuning with ANN  
- Saving the trained model and required encoders / scalers  
- Notebooks for experimentation & prediction  

---

## 📂 Project Structure

├── .gitignore

├── Churn_Modelling.csv # Dataset used for training / evaluation

├── app.py # Script for building / running model

├── experiment.ipynb # Notebook for experiments

├── hyperparametertuningann.ipynb# Notebook for hyperparameter tuning

├── label_encoder_gender.pkl # Saved encoder for gender label

├── model.h5 # Trained ANN model for churn prediction

├── onehot_encoder_geo.pkl # Encoder for geographic one-hot features

├── prediction.ipynb # Notebook for making predictions

├── regression_model.h5 # Another model (regression task)

├── requirement.txt # Python dependencies

├── salaryregression.ipynb # Notebook for regression task

└── scaler.pkl # Saved scaler for feature scaling


---

## ⚙️ Getting Started

### 1️⃣ Prerequisites

- Python 3.7+  
- Packages listed in `requirement.txt` (e.g. TensorFlow / Keras, sklearn, pandas, etc.)  

### 2️⃣ Installation

# Clone the repository
git clone https://github.com/hariom845/End-to-End-Deep-learning-project-using-ANN.git
cd End-to-End-Deep-learning-project-using-ANN

# (Optional) Create virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirement.txt

# 🔧 Usage
Training / Hyperparameter Tuning
You can run:
- Use the notebook for hyperparameter tuning
- Or execute relevant cells in `hyperparametertuningann.ipynb`

# 🧪 Experiments / Notebooks
- experiment.ipynb → Basic experiments for ANN architecture and performance
- hyperparametertuningann.ipynb → Experimenting with different ANN parameters
- salaryregression.ipynb → Regression model tasks

# 🔮 Future Improvements

Try different architectures (more layers, dropout, etc.)
- Use cross-validation for robust evaluation
- Add metrics logging & visualization (e.g. loss/accuracy plots)
- Deploy as an API / web app
- Use larger / more varied datasets




