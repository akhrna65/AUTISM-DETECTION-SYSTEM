# 🧠 ASD Detection System Using CNN Feature Extractors and SVM Classifier
This project is a web-based system that classifies children’s visual tasks (coloring, drawing, and handwriting) to detect potential signs of Autism Spectrum Disorder (ASD). It uses deep learning models (VGG16, ResNet50, EfficientNetB0) for feature extraction, followed by an SVM classifier for final classification. The interface is built with Streamlit and includes a simple dashboard for visualization.

# 🚀 Features
- Classifies uploaded images into 4 ASD categories: Non-ASD, Mild, Moderate, Severe.
- Uses task-specific trained models:
  - Coloring → ResNet50 + SVM
  - Drawing → VGG16 + SVM
  - Handwriting → EfficientNetB0 + SVM
- Dashboard view with prediction result and analysis
- Simple web interface with no installation required when deployed via Streamlit Cloud.

# 🧪 Model Training
- Feature extractors: Pre-trained CNNs (include_top=False)
- Classifier: Support Vector Machine (Linear Kernel)
- Dataset: Labeled ASD visual tasks (handwriting, drawing, coloring)

# 🙏 Acknowledgments
- Project developed for Master in Technology (Data Science and Analytics), Universiti Teknikal Malaysia Melaka (UTeM)
- Data inspired by publicly available ASD handwriting/drawing datasets
