# 🐾 Animal Vocalization Recognition using Deep Learning

This project classifies animal sounds using a 1D Convolutional Neural Network (CNN) implemented with Keras. It processes audio clips, extracts features like MFCCs, and predicts the animal species based on vocal patterns. The goal is to support ecological monitoring and species identification through sound analysis.

---

## 📁 Project Structure

- `Sample_Audio/` – Test audio clips
- `Inference_Images/` – Output visualizations (waveforms, spectrograms, etc.)
- `Bird_Sound_Classification.ipynb` – End-to-end notebook for training & testing
- `model.h5` – Trained deep learning model
- `app.py` – Inference script for using the model
- `prediction.json` – Output predictions
- `requirements.txt` – List of dependencies
- `.gitignore` – Git ignored files and folders

---

## 🚀 How to Run the Project

1. **Install required packages**

   ```bash
   pip install -r requirements.txt
   ```

2. **Run inference using script**

   ```bash
   python app.py
   ```

3. **Or use the Jupyter Notebook**

   Open `Bird_Sound_Classification.ipynb` in Jupyter or VS Code

---

## 🧠 Model Info

- Architecture: 1D Convolutional Neural Network (Conv1D)
- Framework: Keras (TensorFlow backend)
- Features used: MFCCs (Mel-frequency cepstral coefficients)
- Purpose: Animal species classification based on sound

---

## 📦 Trained Model

The trained model file `model.h5` is included in this repository and ready for use.

---
