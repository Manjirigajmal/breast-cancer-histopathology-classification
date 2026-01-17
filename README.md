🧠 Breast Cancer Histopathology Classification with Explainable AI
This project presents an end-to-end deep learning pipeline for classifying breast cancer histopathology images as Benign or Malignant using EfficientNetB0 and Grad-CAM explainability.

📌 Problem Statement
Accurate detection of malignant breast tissue is critical in clinical diagnostics. The goal of this project is to build a high-recall, explainable AI model that assists pathologists by identifying cancerous regions in histopathology slides.

📂 Dataset
- BreakHis Dataset
- 7,909 histopathology images
- Binary classification: Benign vs Malignant
- Multiple magnification levels

⚠️ Dataset not included due to licensing.
📎 Available on Kaggle.

🧠 Methodology
1. Exploratory Data Analysis (EDA)
2. Train / Validation / Test stratification
3. Data augmentation
4. Transfer Learning using EfficientNetB0
5. Model optimization with EarlyStopping & Checkpointing
6. Evaluation using Recall, Precision, ROC-AUC
7. Explainability using Grad-CAM

📊 Results
Metric	Score
Test Accuracy	~87.5%
Recall (Malignant)	~92%
Precision	~89%
ROC-AUC	~0.94


🔍 Explainability (Grad-CAM)
Grad-CAM heatmaps highlight clinically relevant tissue regions, improving trust and interpretability in medical AI systems.

🛠 Tech Stack
- Python
- TensorFlow / Keras
- EfficientNet
- NumPy, Matplotlib
- Scikit-learn


⚠️ Disclaimer
This project is for research and educational purposes only and is not intended for clinical deployment.
