# 👁️ IRIS – Eye Disease Detection Using Deep Learning

### 1. Project Title

👁️ **IRIS – Eye Disease Detection Using Deep Learning**

A deep learning project developed using Python to classify diabetic retinopathy severity from retinal fundus images, generate Grad-CAM visualizations, and perform lesion segmentation using EfficientNet-B0 and U-Net.

---

### 2. Short Description

IRIS is a deep learning-based retinal image analysis project designed to classify diabetic retinopathy severity and visualize potential retinal lesions.

The project involves dataset exploration, image preprocessing, deep learning model development, classification, segmentation, and visual interpretation. EfficientNet-B0 is used to classify retinal images into five diabetic retinopathy grades, while U-Net generates pixel-level segmentation masks. Grad-CAM is used to visualize image regions influencing classification predictions.

---

### 3. Tech Stack

- 🐍 **Python** – Used for data processing and model development.
- 🔢 **NumPy** – Used for numerical operations and image arrays.
- 🐼 **Pandas** – Used for dataset handling and label analysis.
- 🖼️ **OpenCV** – Used for image processing tasks, where applicable.
- 📊 **Matplotlib** – Used to visualize retinal images, predictions, and segmentation masks.
- 📈 **Seaborn** – Used for statistical visualization and exploratory data analysis, where applicable.
- 🤖 **Scikit-learn** – Used for data splitting and evaluation utilities, where applicable.
- 🧠 **TensorFlow/Keras** – Used to build and train the deep learning models.
- 🏥 **EfficientNet-B0** – Used for diabetic retinopathy severity classification.
- 🧩 **U-Net** – Used for retinal lesion segmentation.
- 🔍 **Grad-CAM** – Used to visualize regions influencing model predictions.
- ☁️ **Google Colab** – Used for development and model training.

---

### 4. Data Source

The project uses the **Indian Diabetic Retinopathy Image Dataset (IDRiD)**, available through Kaggle.

Dataset link: https://www.kaggle.com/datasets/aaryapatel98/indian-diabetic-retinopathy-image-dataset

The dataset includes retinal fundus images and associated annotations for disease grading, lesion segmentation, and lesion localization.

The disease-grading data contains five severity classes:

- Grade 0 – No Diabetic Retinopathy
- Grade 1 – Mild
- Grade 2 – Moderate
- Grade 3 – Severe
- Grade 4 – Proliferative Diabetic Retinopathy

The segmentation component uses retinal images and corresponding ground-truth masks for supported lesion categories.

---

### 5. Features

- 📂 Dataset Loading and Organization
- 🔍 Dataset Quality Checks
- 📊 Exploratory Data Analysis
- 🏷️ Diabetic Retinopathy Grade Distribution Analysis
- 🖼️ Retinal Image Visualization
- ⚙️ Image Preprocessing and Resizing
- 🧠 EfficientNet-B0 Classification
- 🎯 Five-Class Severity Prediction
- 📊 Class Probability Analysis
- 🧩 U-Net Segmentation Model
- 🔬 Retinal Lesion Mask Prediction
- 🎨 Segmentation Mask Visualization
- 🔍 Grad-CAM Explainability
- 🧪 Model Evaluation and Prediction Testing
- 📤 Retinal Image Upload and Prediction Workflow

---

### Business Problem

Diabetic retinopathy is an eye condition associated with diabetes that can lead to vision impairment. Examining retinal fundus images requires specialized expertise, and analyzing large numbers of images can be time-consuming.

This project explores how deep learning can support retinal image analysis by classifying disease severity and highlighting potential lesion regions.

### Goal of the Project

The goal is to develop an experimental deep learning workflow that classifies diabetic retinopathy severity from retinal fundus images, generates lesion segmentation masks, and provides visual explanations of classification predictions.

### Key Analysis Areas

- Disease-Grading Dataset Exploration
- Retinal Image Preprocessing
- Class Distribution Analysis
- EfficientNet-B0 Model Development
- Five-Class Classification
- Classification Probability Analysis
- U-Net Architecture Development
- Retinal Lesion Segmentation
- Ground-Truth Mask Analysis
- Grad-CAM Visualization
- Model Prediction Testing
- Experimental Image Upload Workflow

### Key Outcomes & Insights

The project demonstrates:

- Application of deep learning to retinal fundus image classification.
- Classification of images into five diabetic retinopathy severity grades.
- Use of U-Net for pixel-level segmentation of potential retinal lesions.
- Use of Grad-CAM to visualize regions influencing classification predictions.
- Integration of classification, segmentation, and explainability in one project.
- Development of a foundation for an image-upload-based retinal analysis application.
- The importance of evaluating model performance on independent data before real-world use.

---

## 📁 Project Files

- `IRIS_Eye_Disease_Detection.ipynb` – Notebook containing dataset exploration, preprocessing, model development, and prediction workflows.
- `README.md` – Project documentation.
- `iris_classifier.keras` – Saved EfficientNet-B0 classification model.
- `iris_unet.keras` – Saved U-Net segmentation model.
- `gradcam_visualizations/` – Grad-CAM output images, if saved.
- `segmentation_results/` – Predicted segmentation masks and visualization outputs, if saved.

*Include only the files and folders that are actually present in your repository. The model filenames above match the saved models used in the current workflow.*

---

## ▶️ How to Run

1. Clone or download this repository.
2. Open `IRIS_Eye_Disease_Detection.ipynb` in Google Colab.
3. Download the IDRiD dataset from the provided Kaggle link.
4. Upload the dataset or configure the appropriate dataset paths.
5. Run the notebook cells sequentially to reproduce the preprocessing and model workflow.
6. Load the saved classification and segmentation models when available.
7. Upload a retinal fundus image to test classification and segmentation predictions.

---

## 📷 Project Preview

The notebook includes retinal image visualizations, disease-grade predictions, class probabilities, Grad-CAM heatmaps, and U-Net segmentation outputs.

These visualizations demonstrate the experimental workflow for analyzing retinal images using deep learning.

---

## 🛠️ Tools Used

**Python | Pandas | NumPy | OpenCV | Matplotlib | Seaborn | Scikit-learn | TensorFlow | Keras | EfficientNet-B0 | U-Net | Grad-CAM | Image Classification | Image Segmentation | Google Colab**

---

## 👩‍💻 Author

**Hemavarshini Manoharan**

[GitHub](https://github.com/HemavarshiniManoharan) | [LinkedIn](https://www.linkedin.com/in/hemavarshini-m-1b95072b3/)

---

**Disclaimer:** This project is intended for educational and research purposes only. It is not a clinically validated diagnostic system and should not be used to make medical decisions.
