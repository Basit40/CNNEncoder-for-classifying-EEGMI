# EEG Motor Imagery Data Preparation  
_Preparing BCI Competition IV Data (2a & 2b) for Machine Learning and Deep Learning Classification_

## 📖 Overview
This repository provides scripts and guidelines for preprocessing EEG motor imagery (MI) data from **BCI Competition IV datasets 2a and 2b**. The prepared data is structured into **trials** suitable for training and evaluating machine learning and deep learning encoders for motor imagery classification tasks.

Datasets:
- **Dataset 2a**: 9 subjects, 22 EEG channels + 3 EOG channels, 4 MI classes (left hand, right hand, both feet, tongue).
- **Dataset 2b**: 9 subjects, 3 EEG channels, 2 MI classes (left hand, right hand).

---

## 📂 Repository Structure



## ☁️ Development Environment
All scripts for extracting and preprocessing the EEG motor imagery datasets were written and tested in **Google Colab**.  
This setup provides:
- Easy access to GPU acceleration for deep learning experiments.
- A reproducible environment with pre-installed scientific Python libraries.
- Seamless integration with Google Drive for storing raw data and processed trials.

To run the notebooks:
1. Open the `.ipynb` files in the `notebooks/` directory using Google Colab.
2. Mount your Google Drive to access the `data/` folder:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')