
# AI Mental Wellness Companion (Audio Stress Analysis)

This project is a **prototype mental wellness system** that analyzes **speech audio** to detect emotional stress patterns. It uses the RAVDESS emotional speech dataset and audio feature extraction techniques to classify stressed versus non-stressed speech.

---

## Project Details

The notebook implements an end-to-end audio analysis pipeline:

* Uses the **RAVDESS Emotional Speech Audio Dataset**
* Extracts emotion labels directly from audio file metadata
* Groups emotions into **stressed** and **non-stressed** categories
* Loads and processes `.wav` audio files
* Extracts audio features such as **MFCCs**
* Prepares a structured dataset for machine learning modeling

The goal is to demonstrate how **speech signals can be used as indicators of mental stress**, forming the foundation of an AI-powered mental wellness companion.

---

## Dataset

* **RAVDESS Emotional Speech Audio**
* Emotions include calm, happy, sad, angry, fearful, disgust, and surprised
* Labels derived programmatically from filename structure

---

## Tech Stack

* Python
* Jupyter Notebook
* Pandas, NumPy
* Librosa
* Scikit-learn
* Kaggle API

---

## Files

```
depression_detector.ipynb
README.md
```

---

## How to Run

1. Set up Kaggle API credentials
2. Run the notebook to download and extract the dataset
3. Execute cells sequentially to preprocess audio and extract features

---

## Notes

This project is a **research and educational prototype** and is not intended for medical or clinical diagnosis.

---

## Author

Aditya Singh
