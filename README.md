# ExoHub Matrix  

ExoHub Matrix is a multidisciplinary astronomy and machine learning research project. The project combines **spectroscopy, exoplanet atmospheric analysis, machine learning, deep learning, and planetary habitability prediction** to explore real-world astronomical data and build intelligent predictive systems.

---

## 📌 Project Overview

This project focuses on multiple domains of astrophysics and artificial intelligence, including:

- Atmospheric Composition Spectroscopy
- Spectroscopy Analysis using Python
- Machine Learning Fundamentals
- Data Preprocessing and Augmentation
- CNN Architecture for Facial Expression Recognition
- Facial Emotion Recognition using CNN
- Exoplanet Ranking using Earth Similarity Index (ESI)

The objective is to apply computational techniques to solve astronomy-related problems and analyze exoplanet data for identifying Earth-like planets.

---

## 🛰️ Modules Included

### 1. Atmospheric Composition Spectroscopy

Study of atmospheric gases through electromagnetic spectrum analysis.

Topics Covered:
- Spectroscopic fingerprints
- Beer-Lambert Law
- Rydberg Equation
- FTIR Spectroscopy
- LIBS (Laser Induced Breakdown Spectroscopy)
- Atomic Absorption Spectroscopy

Applications:
- Atmospheric gas detection
- Remote sensing
- Planetary atmosphere analysis

---

### 2. Spectroscopy Analysis Using Python

Python-based spectral analysis pipeline for exoplanet atmospheric data.

Features:
- Spectrum stitching (Blue + Red spectrograph arms)
- Peak detection using `scipy.signal.find_peaks()`
- Element identification using NIST Atomic Spectra Database
- Absorption line analysis
- Element abundance estimation

Tools Used:
- NumPy
- SciPy
- Matplotlib
- Pandas

---

### 3. Machine Learning Fundamentals

Core ML concepts implemented for astronomical prediction tasks.

Covered Concepts:
- Data preprocessing
- Data augmentation
- Train-test splitting
- Hyperparameter tuning
- Model evaluation metrics

Algorithms:
- Random Forest Regression
- Support Vector Machines (SVM)

---

### 4. Data Preprocessing & Augmentation

Data preparation pipeline for deep learning models.

Techniques Used:
- Image resizing
- Random rotation
- Horizontal flipping
- Affine transformations
- Color jitter
- Data normalization

Libraries:
```python
torchvision.transforms
PyTorch DataLoader
```

---

### 5. CNN Architecture for Facial Expression Recognition

Deep learning architecture designed for image classification.

Architecture:

```text
Input (48x48 grayscale)

Conv2D (32 filters)
Conv2D (64 filters)
MaxPooling
Dropout

Conv2D (128 filters)
MaxPooling
Conv2D (128 filters)
MaxPooling
Dropout

Flatten
Dense (1024)
Dropout
Dense (7 classes)
Softmax
```

Framework:
- TensorFlow
- Keras

Total Parameters:

```text
2,345,607 trainable parameters
```

---

### 6. Facial Emotion Recognition Using CNN

Model built to classify human facial emotions.

Emotion Classes:
- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

Pipeline:
- Image preprocessing
- CNN training
- Model evaluation
- Custom image testing

Techniques:
- Batch Normalization
- Dropout Regularization
- Early Stopping
- Data Augmentation

---

### 7. Exoplanet Ranking using Earth Similarity Index (ESI)

Machine learning model developed to predict Earth Similarity Index (ESI) for exoplanets.

Objective:
Identify potentially habitable Earth-like planets.

Features Used:

```text
P_RADIUS
P_PERIOD
P_SEMI_MAJOR_AXIS
P_ECCENTRICITY
P_INCLINATION
P_TEMP_EQUIL
S_TEMPERATURE
S_RADIUS
S_MASS
```

Models Implemented:

### Random Forest Regressor

Results:

```text
R² Score = 0.995082
MSE = 8.483417
```

### Support Vector Regressor (SVR)

Results:

```text
R² Score = 0.89
MSE = 0.0039
```

Best Model:
✅ Random Forest Regressor

---

## 🌍 Top Earth-like Planets Predicted

### Kepler Dataset

| Rank | Planet | ESI |
|--------|--------|--------|
| 1 | Kepler-296 e | 0.922824 |
| 2 | Kepler-1512 b | 0.892083 |
| 3 | Kepler-442 b | 0.852161 |
| 4 | Kepler-1410 b | 0.846040 |
| 5 | Kepler-438 b | 0.845212 |

---

### TESS Dataset

| Rank | Planet | ESI |
|--------|--------|--------|
| 1 | TRAPPIST-1 e | 0.892674 |
| 2 | TRAPPIST-1 d | 0.857618 |
| 3 | LHS 1140 b | 0.850860 |
| 4 | TRAPPIST-1 f | 0.847545 |
| 5 | K2-18 b | 0.704132 |

---

## 🛠 Tech Stack

### Programming Languages

- Python

### Libraries & Frameworks

- NumPy
- Pandas
- Matplotlib
- SciPy
- Scikit-learn
- TensorFlow
- Keras
- PyTorch
- OpenCV

### Machine Learning

- Random Forest Regression
- Support Vector Regression
- CNN (Convolutional Neural Networks)

---

## Repository Structure

```text
ExoHub-Matrix/
│
├── spectroscopy/
│   ├── spectral_analysis.py
│   ├── peak_detection.py
│
├── machine_learning/
│   ├── random_forest.py
│   ├── svm_model.py
│
├── cnn_emotion_detection/
│   ├── model.py
│   ├── train.py
│   ├── predict.py
│
├── exoplanet_ranking/
│   ├── esi_prediction.py
│   ├── kepler_analysis.py
│   ├── tess_analysis.py
│
├── dataset/
│
├── notebooks/
│
└── README.md
```

---

## Team Members

### Mentors

- Rishabh Kumar  
- Rishabh Verma  
- Toshika Kamble  
- Mayank Pattnaik  

### Contributors

- Tanmay Shukla  
- Aman Pal  
- Astha Yadav  
- Abhinav Bhardwaj  
- Dalima  
- Harshit Pandey  
- Haryashva Gupta  
- Ishaan Dasgupta  
- Mahi Mittal  
- Lalit Meena  
- Mayank Agrawal  
- Mihir Tejaswi  
- Mishthi Sharma  
- Nikhil Patel  
- Saket Garg  
- Pranjali Deshpande  

---

## Future Improvements

- Better exoplanet habitability prediction models
- Deep learning for spectral classification
- Real-time astronomical data pipeline
- Planetary atmosphere simulation
- Improved CNN architectures

---

## Conclusion

ExoHub Matrix demonstrates the intersection of **Astronomy + Artificial Intelligence + Data Science**.

The project explores how machine learning and spectroscopy can be applied to:
- Understand planetary atmospheres
- Detect chemical signatures
- Predict Earth-like planets
- Analyze complex astronomical datasets

---

## License

This project is created for educational and research purposes under **Astronomy Club Summer Project 2025**.

---

## Acknowledgements

Special thanks to all mentors and contributors who worked on making this interdisciplinary astronomy project successful.

⭐ If you like this project, give the repository a star.
