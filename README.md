# Speech Emotion Recognition (SER) - TESS Audio EDA

Exploratory Data Analysis (EDA) and audio feature visualization for Speech Emotion Recognition using the **Toronto Emotional Speech Set (TESS)**.

---

## 📌 Overview

This project focuses on loading, preprocessing, and visualizing emotional speech audio signals. It analyzes acoustic properties across different human emotion classes using time-domain waveforms and Short-Time Fourier Transform (STFT) spectrograms.

---

## Dataset

The project utilizes the **Toronto Emotional Speech Set (TESS)** dataset from Kaggle.

* **Total Samples:** 2,800 audio files (`.wav` format)
* **Classes:** 7 balanced emotional categories (400 samples each)
  * `angry`
  * `disgust`
  * `fear`
  * `happy`
  * `neutral`
  * `ps` (pleasant surprise)
  * `sad`
* **Speakers:** Young Female (YAF) and Older Female (OAF) actors reciting set carrier phrases.

---

## 🛠️ Features & Pipeline

* **Dataset Retrieval:** Automated download using `kagglehub`.
* **Metadata Extraction:** Automated extraction of file paths and emotion labels into a structured pandas DataFrame.
* **Class Distribution Analysis:** Balanced class validation via Seaborn count plots.
* **Audio Visualizations:**
  * **Waveplots:** Amplitude variation over time using `librosa.display.waveshow`.
  * **Spectrograms:** Frequency and intensity analysis over time using STFT and amplitude-to-dB conversion (`librosa.display.specshow`).
* **Audio Playback:** Interactive audio preview using `IPython.display.Audio`.

---

## 💻 Tech Stack

* **Language:** Python 3
* **Audio Processing:** `librosa`
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Environment:** Google Colab / Jupyter Notebook

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name
