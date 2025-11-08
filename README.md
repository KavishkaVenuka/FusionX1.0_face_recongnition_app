# Face Recognition System using Support Vector Machine (SVM)

An educational project demonstrating face recognition using Support Vector Machine (SVM) algorithm with facial feature extraction.

## 🎯 Project Overview

This repository contains:
- **Educational Jupyter Notebook**: Step-by-step tutorial on SVM-based face recognition
- **Interactive Demo**: Streamlit web application for real-time face recognition
- **Training Scripts**: Code to train and save SVM models
- **Feature Extraction**: Using facial landmarks and HOG features

## 📚 What You'll Learn

- Understanding Support Vector Machines (SVM)
- Facial feature extraction techniques
- Working with face detection and recognition
- Model training and evaluation
- Deploying ML models as web applications
- Real-time face recognition using webcam

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- pip package manager
- Webcam (for demo application)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/thathsarabandara/FusionX1.0_face_recongnition_app.git
cd FusionX1.0_face_recongnition_app
```

2. Install dependencies:
```bash
chmod +x quick_start.sh
./quick_start.sh
```

## 📁 Project Structure

```
face_recognition_system/
├── app.py                              # Streamlit demo application
├── notebooks/
│   └── svm_face_recognition.ipynb      # Educational notebook
├── src/
│   ├── train_model.py                  # Model training script
│   ├── face_detector.py                # Face detection utilities
│   ├── feature_extractor.py            # Feature extraction
│   └── utils.py                        # Helper functions
├── models/                             # Saved trained models
├── data/
│   ├── raw/                            # Raw face images
│   └── processed/                      # Processed features
├── requirements.txt                    # Python dependencies
└── README.md                           # This file
```

## 🎓 Educational Content

### SVM Algorithm Basics

Support Vector Machine is a powerful algorithm that:
1. Finds the optimal hyperplane to separate different classes
2. Maximizes the margin between classes
3. Handles non-linear data using kernel tricks
4. Works well with high-dimensional feature spaces

### Face Recognition Pipeline

1. **Face Detection**: Detect faces in images using Haar Cascade or dlib
2. **Face Alignment**: Align detected faces to a standard orientation
3. **Feature Extraction**: Extract facial features (HOG, facial landmarks)
4. **Classification**: Use SVM to classify faces

### Why SVM for Face Recognition?

- **Effective**: Excellent performance on high-dimensional data
- **Interpretable**: Clear decision boundaries
- **Flexible**: Works with various feature representations
- **Scalable**: Efficient for moderate-sized datasets
- **Educational**: Great for learning ML concepts

## 📊 Expected Performance

- **Accuracy**: ~90-95% on test set (depends on dataset quality)
- **Inference Time**: ~0.2-0.5 seconds per face
- **Model Size**: ~10-50MB (depending on training data)

## 🛠️ Technologies Used

- **scikit-learn**: SVM implementation
- **OpenCV**: Face detection and image processing
- **dlib**: Advanced face detection and landmarks
- **NumPy**: Numerical computations
- **Matplotlib**: Visualizations
- **Streamlit**: Web application framework
- **Pillow**: Image processing
- **scikit-image**: Image feature extraction (HOG)

## 📝 License

MIT License - Feel free to use this for educational purposes!

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest improvements
- Add new features
- Improve documentation

## 📧 Contact

For questions or feedback, please open an issue on GitHub.

---

**Happy Learning! 🎉**
