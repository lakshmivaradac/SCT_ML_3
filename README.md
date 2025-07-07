# 🐱🐶 SVM Cat vs Dog Classifier

This is a simple machine learning project using **Support Vector Machine (SVM)** to classify images of **cats** and **dogs**.

## 📂 Dataset
- [Cats and Dogs Filtered Dataset (Google-hosted)](https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip)
- 1000 total images used (500 cats + 500 dogs)
- Images resized to 64x64 and converted to grayscale

## 🧠 Model
- Model: `SVC(kernel='linear')` from scikit-learn
- Features: Flattened grayscale images
- Split: 80% train / 20% test

## 🔍 Accuracy
Achieved high accuracy on test set using SVM

## 📁 Files in this Repo
- `svm_cat_dog_classifier.ipynb` – Full Google Colab notebook
- `svm_cat_dog_model.pkl` *(optional)* – Saved trained model (if added)

## 🚀 How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run each cell step by step
3. Try uploading your own image for prediction!

#

> ⭐ Star this repo if you liked it!
