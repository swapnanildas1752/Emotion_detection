# 🎭 Emotion Detection from Speech

A compact and insightful project exploring **emotion classification** using **audio feature extraction**, **signal processing**, and **machine learning models**. The goal is to identify human emotions (like happy, sad, angry, neutral) from raw speech signals by transforming audio into meaningful vector representations.

---

## 📌 Features
- Extraction of **MFCC**, **chroma**, **mel spectrogram**, and other audio descriptors  
- Preprocessing pipeline for trimming, normalizing, and cleaning audio  
- Machine learning model training (SVM / Random Forest / MLP)  
- Evaluation using accuracy, confusion matrix, and performance metrics  
- Modular Python structure for easy extension  
- Supports custom datasets

---

## 🚀 How It Works
1. Load audio files  
2. Extract handcrafted features  
3. Feed features to ML model  
4. Predict emotion  
5. Evaluate results

The project follows a clean, stepwise pipeline so you can plug in new emotions or switch models effortlessly.

---

## 📁 Project Structure

```
Emotion-Detection/
│── data/                  # audio files (not included in repo)
│── features/              # extracted feature numpy files
│── models/                # saved ML models
│── src/
│   ├── extract_features.py
│   ├── train_model.py
│   ├── predict.py
│   └── utils.py
│── requirements.txt
│── README.md
```

---

## 🧪 Tech Stack
- Python  
- Librosa  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## 🖼️ Output Screenshots
(Add your output images here once you upload them)

```
![Feature Visualization](outputs/feature_plot.png)
![Confusion Matrix](outputs/cm.png)
```

---

## ▶️ Running the Project

### Install dependencies
```bash
pip install -r requirements.txt
```

### Extract features
```bash
python src/extract_features.py
```

### Train model
```bash
python src/train_model.py
```

### Predict emotion
```bash
python src/predict.py --file sample.wav
```

---

## 📈 Results
- Achieved strong accuracy on multi-class emotion dataset  
- Robust for real-world speech variations  
- Model generalizes well to unseen voices  

---

## 🙌 Contributions
Feel free to fork the repo, open issues, or submit PRs.

---

## 📜 License
MIT License

