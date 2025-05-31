
# 🚫🔗 Malicious URL Detection using Machine Learning (99.7% Accuracy)

Protect users from phishing and harmful websites using smart machine learning models! This project leverages advanced supervised learning algorithms to detect malicious URLs with up to **99.7% accuracy**, using features extracted from the URL structure.

---

## 🔍 Project Overview

Phishing and malicious links pose a significant threat to internet users. This project aims to **automatically detect such URLs** using machine learning. Instead of relying on blacklists or keyword matching, we extract structural features from URLs and train ML models to classify them as **malicious or benign**.

---

## ✅ Features

- 📊 Extracted 16+ handcrafted URL features (e.g., length, special character counts, IP usage)
- 🧠 Applied multiple ML algorithms: 
  - Decision Tree
  - Random Forest
  - Logistic Regression
- 🔁 Performed hyperparameter tuning using `GridSearchCV` and `StratifiedKFold`
- 📈 Achieved **99.72% accuracy** using Random Forest
- 🛠️ Modular and scalable code structure
- 📉 Visualizations for model comparison and accuracy

---

## 🗂️ Dataset

The dataset contains labeled URLs with the following structure-based features:
- Length of hostname and path
- Count of special characters like `@`, `-`, `%`, etc.
- Count of digits, letters, and directories
- Whether the URL contains an IP address
- Target label: `1` (malicious) or `0` (benign)

> *Note: The dataset is included within the notebook or should be uploaded by the user.*

---

## 🚀 Getting Started

### 🔧 Requirements

- Python 3.7+
- Jupyter Notebook / Colab
- Required libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

### 📥 Installation

```bash
pip install -r requirements.txt
```

Or manually install:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Malicious-URL-Detection.git
   cd Malicious-URL-Detection
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open `malicious_url_detection.ipynb` and run each cell step-by-step.

---

## 📊 Results

- **Best Model**: Random Forest Classifier
- **Accuracy**: 99.72%
- **Evaluation**:
  - Cross-validation with 5 folds
  - Grid search for optimal hyperparameters
  - Feature scaling using `StandardScaler`

---

## 📌 Key Takeaways

- Structural properties of URLs can reveal strong signals for phishing detection.
- Machine learning offers robust alternatives to traditional rule-based methods.
- High-performance models can be trained on relatively simple feature sets.

---

## 📚 Future Work

- Include deep learning models (e.g., LSTM on raw URLs)
- Real-time malicious URL detection web app
- Integration with browser extension for on-the-fly detection

---

## 🤝 Contributing

Feel free to fork this repo, improve the model, or adapt it for real-world applications! Contributions are welcome via pull requests or issues.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**[Your Name]**  
📧 [your.email@example.com]  
🌐 [LinkedIn/GitHub/Twitter Handle]

---

> ⭐ If you find this project helpful, please consider starring the repository!
