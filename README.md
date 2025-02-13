# Peter J. Bentley Heartbeat Sound Challenge Dataset


## 📌 Overview
This dataset originates from the **Peter J. Bentley Heartbeat Sound Challenge**, which aims to classify normal and abnormal heart sounds. The dataset contains heart sound recordings collected from various sources, annotated with different cardiac conditions.

## 📂 Dataset Structure
```
/Heartbeat_Sound
├── normal/
├── murmur/
├── extrahls/
├── extrastole/
├── artifact/
```
- **Heartbeat_Sound/**: Contains labeled heart sound recordings for each classes.


## 🔍 Classes
The dataset is categorized into the following heart sound types:
- ✅ **Normal**: Healthy heart sounds.
- ⚠️ **Murmur**: Abnormal sounds indicating potential cardiac issues.
- 🔊 **Extrahls**: Extra heart sounds.
- 📣 **Extrastole**: Extra heartbeats before the normal beat.
- 🎵 **Artifact**: Noisy or corrupted recordings.

## 📄 File Format
The heart sound recordings are stored in **WAV format**, with metadata provided in CSV format.

## 🚀 Usage
This dataset can be used for training and evaluating machine learning models for **heart sound classification**. Some potential applications include:
- 🧠 Deep learning models (e.g., CNN, LSTM) for classification.
- 🎼 Feature extraction using **Short-Time Fourier Transform (STFT)** and **Mel-Frequency Cepstral Coefficients (MFCC)**.
- 🎛️ Augmentation techniques such as **time stretching, pitch shifting, and noise addition**.

## 🔧 Preprocessing
The dataset has been preprocessed as follows:
- 📏 **Resampled** to a uniform frequency.
- ✂️ **Trimmed** to remove silent parts.
- 🖼️ **Converted** into spectrograms for deep learning.

## 📜 Citation
If you use this dataset, please cite the original source:
> Bentley, P. J., et al. "The PASCAL Classifying Heart Sounds Challenge." (2011).

## 📜 License
This dataset is provided for research and educational purposes only. Ensure proper attribution when using it in your projects.

## 📞 Contact
For any issues or questions, feel free to create an issue on this repository or reach out to [Your Email or GitHub Profile].

---
⭐ **Star this repository** if you find it helpful!

