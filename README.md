
# 🧬 Blood Cell Classifier: Deep Learning for Microscopic Image Recognition

## 📌 Project Overview
This project focuses on building an image classification model using **Convolutional Neural Networks (CNNs)** to identify different types of blood cells from microscopic images. The goal is to create a robust classifier that can assist in automating blood cell categorization — a task traditionally performed manually by medical professionals.

## 📁 Dataset
The dataset used in this project is publicly available on Kaggle:

🔗 [Blood Cells Image Dataset](https://www.kaggle.com/datasets/unclesamulus/blood-cells-image-dataset)

It contains thousands of labeled images of blood cells, organized into various classes representing types such as:
- Neutrophils
- Eosinophils
- Basophils
- Lymphocytes
- Monocytes
- Platelets
- Immature Granulocytes (IG)
- Erythroblasts

## 🛠 Workflow Summary
This project consists of several key steps:
- **Data Exploration & Preprocessing**: Image resizing, normalization, augmentation.
- **Model Development**: Building and training CNN architectures using TensorFlow/Keras.
- **Model Evaluation**: Using metrics like accuracy, precision, recall, and confusion matrix.
- **Model Deployment**: Exporting trained models to multiple formats:
  - **TensorFlow SavedModel** (for server-based deployment)
  - **TensorFlow.js** (for web deployment)
  - **TensorFlow Lite** (for mobile & edge devices)

## 📂 Directory Structure
```

submission/
├───tfjs\_model
│   ├───group1-shard1of4.bin
│   └───model.json
├───tflite
│   ├───model.tflite
│   └───labels.txt
├───saved\_model
│   ├───assets/
│   ├───variables/
│   ├───fingerprint.pb
│   └───saved\_model.pb
├───notebook.ipynb
├───README.md
└───requirements.txt

````

## ⚙️ Environment Setup
### 1. Create and activate a virtual environment
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```
