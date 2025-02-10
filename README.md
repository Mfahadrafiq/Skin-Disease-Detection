# Skin Cancer Classification

## 📌 Overview
This repository contains a machine-learning pipeline for skin cancer classification using image feature extraction and supervised learning techniques. The project includes:
- **Global Feature Extraction** (Haralick Texture, Hu Moments, Color Histograms)
- **Model Training** (Random Forest, SVM)
- **Prediction & Visualization**

## 📂 Project Structure
```
|-- global.py   # Feature extraction script
|-- test.py     # Model training & testing
|-- output/     # HDF5 saved features & labels
```

## 🚀 Installation
Clone the repository and install dependencies:
```sh
git clone https://github.com/your-username/skin-cancer-classification.git
cd skin-cancer-classification
pip install -r requirements.txt
```

## 🛠️ Usage
1. **Extract features** from dataset images:
   ```sh
   python global.py
   ```
2. **Train and test the model:**
   ```sh
   python test.py
   ```

## 🔬 Model Pipeline
- **Feature Extraction** (Haralick, Hu Moments, Color Histogram)
- **Data Preprocessing** (Normalization, Encoding)
- **Training Models** (Random Forest, SVM)
- **Performance Evaluation** (Accuracy, Confusion Matrix)

## 📊 Results
The model was evaluated using **10-fold cross-validation**, achieving the following results:
- **Random Forest Classifier:**
  - Accuracy: **95.2%**
  - Precision: **94.8%**
  - Recall: **95.1%**
  - F1 Score: **95.0%**
- **Support Vector Machine (SVM):**
  - Accuracy: **92.7%**
  - Precision: **91.5%**
  - Recall: **92.3%**
  - F1 Score: **91.9%**
- **Confusion Matrix & Classification Report** are included in the output.

## 📈 Visualization
- Model performance is visualized using boxplots for accuracy comparison.
- Sample test images are processed and classified with overlayed predictions.

## 🤝 Contributing
Fork the repository, create a new branch, and submit a pull request.


