# Data Driven Calssification of Hand Postures for Myoelectric Control

*Mtech Thesis Project – IIT Guwahati*  

## Project Overview
This project is my M.Tech thesis work, focused on developing a **data-driven framework** for classifying hand gestures using surface Electromyography (sEMG) signals.  
The long-term goal is to enable **intelligent and intuitive control of hand exoskeletons**, which can aid rehabilitation and assistive technologies.  

---

## Objectives
- Build a pipeline for **preprocessing raw EMG signals** (amplification, filtering, segmentation).  
- Extract **time, frequency, and statistical features** to create structured feature matrices.  
- Apply **machine learning algorithms (Random Forest, SVM, Extra Trees)** for gesture classification.  
- Implement **Non-Negative Matrix Factorization (NMF)** to uncover muscle synergies and reduce dimensionality.  
- Achieve high classification accuracy and provide insights into the data lifecycle.  

---

## Tools & Technologies
- **Languages:** Python (NumPy, Pandas, SciPy, scikit-learn, Matplotlib)  
- **Techniques:** Feature Engineering, Signal Processing, Dimensionality Reduction, Machine Learning  
- **Models:** Random Forest, Support Vector Machine, Extra Trees Classifier, Non-Negative Matrix Factorization (NMF)  

---

## Key Results
- Processed and analyzed multi-channel EMG data from **8 muscles, 15 gestures, 8 subjects**.  
- Achieved **98% classification accuracy** using Random Forest, SVM, and Extra Trees.  
- Extracted **2 dominant muscle synergies** using NMF with Variance Accounted For (VAF) > 95%.  
- Built a robust, reproducible pipeline from **raw EMG signals to final gesture classification**. 


