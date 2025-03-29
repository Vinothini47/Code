# Code
Code
# FRCNN-GJS: COVID-19 Severity Detection from CT Scans using MATLAB

This repository provides a modular MATLAB implementation of a novel framework for automatic COVID-19 severity detection from CT scan images. The model integrates preprocessing, segmentation using nnU-Net (conceptual), severity prediction using Faster R-CNN, and hyperparameter tuning using Golden Jackal Search (GJS) optimization.

---

## 🧠 Overview of the Methodology

The proposed pipeline consists of the following four major stages:

1. **Preprocessing**  
   - Grayscale Conversion  
   - Median Filter Denoising  
   - Gaussian Blurring  
   - Reverse Coloring  
   - Image Flipping  

2. **Segmentation** (Placeholder)  
   - Simple threshold-based segmentation (can be replaced by nnU-Net output)

3. **Severity Prediction**  
   - Bounding box estimation using infected regions  
   - Percentage of lung infected is calculated  
   - Severity classified as:  
     - Healthy (0%)  
     - Mild (1-25%)  
     - Moderate (26-50%)  
     - Severe (51-75%)  
     - Critical (76-100%)

4. **Golden Jackal Search Optimization**  
   - Dummy fitness function used for hyperparameter simulation  
   - Replace with actual Faster R-CNN training loop if desired

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `main.m` | Main file to run the complete workflow |
| `preprocessing.m` | Preprocessing steps on CT images |
| `segmentation.m` | Mock segmentation logic |
| `severity_prediction.m` | Severity classification based on infection area |
| `gjs_optimization.m` | Golden Jackal Search optimization (placeholder logic) |
| `sample_ct_scan.png` | Sample CT scan image (add your own dataset) |

---

## 🚀 How to Run

1. Clone the repository or download the files
2. Open MATLAB
3. Place all `.m` files in the same directory
4. Run the script:  
   ```matlab
   main
