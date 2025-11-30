# Self-Induced Laughter Emotion Recognition  
Official Code for IEEE ICRITO 2025 Study

This repository provides the official implementation for the paper:

**“Human Emotion Classification of Self-Induced Laughter Using Acoustic Features and Deep Learning Models”**  
IEEE ICRITO 2025.

---

## Description
The notebook includes the full experimental pipeline used in the study:

- MFCC-based global and segmented acoustic feature extraction  
- Delta and delta-delta temporal derivatives  
- Statistical filtering and Random Forest feature selection  
- SMOTETomek resampling  
- Machine learning baselines (SVM, RF, LR, GB)  
- **BiLSTM** model for temporal emotion classification  

The BiLSTM achieved the highest performance and forms the core deep learning component of this work.

---

## Contents
- `Emotion_Laughter_BiLSTM.ipynb` — complete end-to-end implementation  
- *(Dataset excluded due to participant privacy)*

---

## Citation
Please cite the following if you use this code:

Kashfi, Garg, Hewage.  
**“Human Emotion Classification of Self-Induced Laughter Using Acoustic Features and Deep Learning Models.”**  
IEEE ICRITO 2025.

---

## License
Released under the **MIT License**.

