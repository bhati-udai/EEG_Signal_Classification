# EEG Signal Classification Using Machine Learning for Epileptic Seizure Detection  

## 📌 Project Overview  
This project focuses on **EEG signal classification** using **machine learning techniques** to detect epileptic seizures. The classification pipeline involves **feature extraction** using **Discrete Wavelet Transform (DWT)** and **dimensionality reduction** using **PCA, ICA, and LDA**. The extracted features are then fed into a **Support Vector Machine (SVM)** for classification, achieving an accuracy of over **98% using LDA**.  

## 🚀 Features  
- **EEG Signal Processing**: Decomposes EEG signals using **DWT** to extract time-frequency features.  
- **Feature Reduction**: Uses **PCA, ICA, and LDA** to improve classification efficiency.  
- **Machine Learning Classification**: Implements **SVM** for epileptic vs. non-epileptic classification.  
- **Performance Optimization**: Evaluates and compares classification performance across different feature extraction methods.  

## 📂 Dataset  
The project utilizes a **publicly available EEG dataset** (Andrzejak et al., 2001), consisting of EEG signals recorded from both **healthy individuals and epileptic patients**. The dataset contains:  
- **Set A & B**: Healthy individuals (eyes open/closed)  
- **Set C, D, & E**: Epileptic patients (recorded from different brain regions)  

## 🛠️ Tech Stack  
- **Programming Language**: Python  
- **Libraries Used**:  
  - `numpy`, `pandas` – Data handling  
  - `scipy`, `pywt` – Signal processing (DWT)  
  - `sklearn` – Machine learning (PCA, ICA, LDA, SVM)  
  - `matplotlib`, `seaborn` – Data visualization  

## 🔧 Installation & Usage  
### 1️⃣ Install Dependencies  
```bash
pip install numpy pandas scipy pywt scikit-learn matplotlib seaborn
