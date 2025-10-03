# 🧠 AI Prediction Project: Airbnb & Insect Classification

This project uses **Orange** to build two machine learning workflows:

1. 🐜 **Insect Image Classifier** – Classifies images of ants and bees using neural networks.
2. 🏠 **Airbnb Cancellation Predictor** – Predicts cancellation policy (flexible, moderate, strict) based on listing features.

---

## 📁 Project Structure

- `CSV_Files/` – Contains Airbnb dataset and prediction data
- `image_dataset/` – Training and testing images for insect classification
- `orange_files/` – Orange workflows for data analysis, modeling, prediction, and image processing
- `saved_models/` – Pre-trained models saved from Orange
- `final_report.docx` – Full documentation of the project
- `Presentation.pptx` – Visual summary for presentation

---

## 🔍 Workflow Summary

### 🐜 Insect Classification
- **Training**: Images of ants and bees
- **Model**: Neural Network via Orange
- **Testing**: Unlabeled images in `/test` folder
- **Output**: Predicted insect type shown using Image Grid widget

### 🏠 Airbnb Prediction
- **Dataset**: 1999 instances, 24 features (room type, price, service fee, etc.)
- **Target**: Cancellation policy (flexible, moderate, strict)
- **Steps**:
  - Data analysis (distribution, correlation, ranking)
  - Modeling (imputation, preprocessing, outlier removal)
  - Evaluation (confusion matrix, test & score)
  - Prediction on new data

---

## 🚀 How to Run

1. Open Orange
2. Load `.ows` files from `orange_files/`
3. Follow the workflow steps:
   - For Airbnb: use `data_analysis`, `data_modeling`, and `data_prediction`
   - For insects: use `image_processing` and `image_prediction`
4. Use saved models from `saved_models/` if needed

---

## 👨‍💻 Authors

- Mostafa Ayman  
- Seif Ahmed  
- Abdullah Hossam

---

## 📚 References

- [Airbnb Dataset – Kaggle](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)
- [Simplilearn AI Tutorial](https://www.simplilearn.com/tutorials/artificial-intelligence-tutorial/what-is-artificial-intelligence)
