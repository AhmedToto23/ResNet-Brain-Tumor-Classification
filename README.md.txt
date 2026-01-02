# Brain Tumor Classification using ResNet50

This project classifies brain MRI images into:
- Glioma
- Meningioma

using **ResNet50 transfer learning**.

## 🧠 Model Details
- Architecture: ResNet50 (ImageNet pretrained)
- Framework: TensorFlow / Keras
- Input size: 224 × 224

## 📁 Dataset Structure

dataset/
├── train/
│ ├── glioma/
│ └── meningioma/
├── val/
└── test/


> Dataset is not included in this repository.

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebook/ResNet_meningioma_vs_glioma.ipynb


📊 Output

Training & validation accuracy

Loss curves

👤 Author

Ahmed Toto