# MRI_EDA

This project provides **detailed cleaning, exploratory data analysis (EDA), and visualization** for the [Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection) dataset.  
The goal is to extract meaningful insights from MRI scans **without deep learning**, focusing on pixel-level statistics and image preprocessing techniques.

## 📂 Dataset

The Kaggle dataset contains two main folders:
* BrainMRI/yes/ -------> (MRI scans with brain tumor)
* BrainMRI/no/  --------> (MRI scans without brain tumor)

- **Format:** JPEG/PNG grayscale images  
- **Classes:** `yes` (tumor present) and `no` (no tumor)  
- **Resolution:** Varies (most around 240x240 pixels)  
- **Total Images:** ~250

## 🔎 Exploratory Analysis Highlights
* Tumor images show higher variance in pixel intensity due to irregular regions.
* Histogram equalization improves contrast, making tumor boundaries more visible.
* Clear class imbalance: ~150 tumor images vs. ~98 normal images.
