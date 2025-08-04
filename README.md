# Machine Learning-Project
# Classification and Forecasting of Water Stress in Plants using Bioristor Data
This project presents a machine learning and deep learning-based system to classify and forecast water stress conditions in tomato plants. Leveraging sensor data from **bioristors**, we trained and evaluated models for both classification (4-status) and binary drought prediction, aiming to support real-world smart irrigation and precision agriculture.

# Models Implemented
### 🔹 Classification Models
- **Decision Tree (Gini & Entropy)**
- **Random Forest (GridSearchCV for hyperparameter tuning)**

### 🔹 Forecasting Model
- **RNN LSTM**: For time-series based drought prediction
- **CNN**: Used to experiment with multivariate feature extraction.

# Performance Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Tech Stack
- **Language**: Python 3.x  
- **Libraries**:
  - `scikit-learn` (classification models)
  - `keras` and `tensorflow` (LSTM, CNN)
  - `matplotlib`, `seaborn` (visualization)
  - `pandas`, `numpy` (data preprocessing)

# Installation & Setup
## Clone the repository
git clone https://github.com/<your-username>/tomato-water-stress-classification.git
cd tomato-water-stress-classification

## Install dependencies
pip install -r requirements.txt

## Run the main script
python main.py
