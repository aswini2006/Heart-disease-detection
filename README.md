# Heart Disease Detection 🫀

This project builds a machine learning model to predict the presence of heart disease using a publicly available dataset. The model is trained using the Random Forest algorithm and evaluated based on accuracy, confusion matrix, and classification report.

## 📁 Dataset

The dataset contains various medical attributes such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- ST Slope
- **Target** (0 = No Heart Disease, 1 = Heart Disease)

The dataset file used: `dataset.csv`

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/heart-disease-detection.git
cd heart-disease-detection

### 2. Install dependencies

```bash
pip install -r requirements.txt

### 3. Run the code

```bash
python heart_disease_detection.py


## 🧠 Model Used
Random Forest Classifier

Train-Test Split: 80% training, 20% testing

Features are scaled using StandardScaler

## 📊 Output
Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

## 📌 Requirements
See requirements.txt.

## 📜 License
This project is open-source and free to use under the MIT License.
