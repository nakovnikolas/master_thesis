# 🧠 Using Brain Signal Features to Predict Children’s Learning Performance During Second Language Learning

This repository contains the full codebase for my Master’s thesis, completed as part of the MSc Data Science and Society program at Tilburg University. The thesis explores how EEG-derived brain signal features can be used to predict children’s learning performance during second language acquisition using machine learning techniques.

📄 **Full Thesis (PDF)**: [Using Brain Signal Features to Predict Children’s Learning Performance – Tilburg University](https://arno.uvt.nl/show.cgi?fid=161326)  
📅 **Date of Submission**: 26 June 2022  
👨‍🎓 **Author**: Nikolas Nakov  
🎓 **Supervisor**: Dr. Maryam Alimardani, Tilburg University

---

## 🧠 Project Overview

The objective of this research was to explore whether children’s learning performance in a second language task could be predicted using features extracted from EEG recordings. The analysis focuses on hand-crafted EEG features designed for interpretability and linked to relevant cognitive processes.

No raw EEG signals are included in this repository—only the processed and anonymized features derived through well-established signal processing methods.

---

## 🧪 Methodology

- **Spectral Features**: Extracted using the Fast Fourier Transform (FFT) across standard EEG frequency bands (alpha, beta, theta).
- **Temporal Features**: Calculated using **Detrended Fluctuation Analysis (DFA)** to capture long-range temporal correlations in the EEG time series.
- **Feature Selection**: Applied **Minimum Redundancy Maximum Relevance (MRMR)** to select the most informative and least redundant features for classification.
- **Classification Models**: Implemented and compared:
  - **K-Nearest Neighbors (KNN)**
  - **Support Vector Machines (SVM)** with linear and RBF kernels

---

📊 Technologies Used
Language: Python

Libraries:
pandas, numpy, scikit-learn, matplotlib, seaborn, mne, scipy

Environment: Jupyter Notebook

🎓 Academic Context
This thesis was submitted in June 2022 as part of the Master of Science in Data Science and Society program at Tilburg University. It was conducted under the supervision of Dr. Maryam Alimardani, whose expertise in neurotechnology and affective computing provided critical academic guidance throughout the project.

The project complies with all ethical standards for data collection and anonymization. EEG data was collected in an academic research setting and transformed into derived features suitable for public sharing and analysis.

📬 Contact
If you're interested in neurotechnology, EEG-based ML, or educational applications of physiological data, feel free to get in touch:

Nikolas Nakov
📧 Email: nikolas.nakov@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/nikolas-nakov-60880515b/

This work is shared for academic and educational purposes. Please cite the original thesis if referencing this repository.