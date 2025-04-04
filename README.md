# 🚀 SPACE DEBRIS PREDICTION

This project uses a machine learning approach to predict potential risk from space debris. It utilizes a Random Forest classifier trained on a binary risk dataset, aiming to assist in proactive debris mitigation.

## 📁 Project Structure

- `main.py` - Runs predictions using the trained model.
- `train_model.py` - Trains a Random Forest classifier on the dataset.
- `rf_model.pkl` - Serialized trained model file.
- `space_debris_binary_risk.csv` - CSV dataset containing features and risk labels.

## 🛠 Installation

```bash
git clone https://github.com/def-hrithik/SPACE_DEBRIS_PREDICTION.git
cd SPACE_DEBRIS_PREDICTION
pip install -r requirements.txt  # if available

#🚀 Usage
To Run Predictions
python train_model.py


