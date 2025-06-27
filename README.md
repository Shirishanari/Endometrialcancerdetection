# Endometrialcancerdetection
# AI-Powered Endometrial Cancer Detection System

**Keywords:** Endometrial Carcinoma, Generative AI, Machine Learning, Large Vision-Language Models (LVLMs), Medical Imaging Analysis

---

##  Introduction

Endometrial cancer is one of the most common gynecological cancers, primarily affecting women after menarche, especially during the postmenopausal stage. According to the **World Health Organization**, over **382,000 new cases** are diagnosed every year, with approximately **90,000 deaths** attributed to the disease. It is currently ranked **sixth** among all cancers globally.

Despite significant progress in cancer research, many cases are still diagnosed at **advanced stages**, reducing treatment efficacy. Early and accurate diagnosis is crucial—**the 5-year survival rate exceeds 95%** for localized cancer, but drops dramatically in later stages.

This project proposes an **AI-enabled diagnostic framework** that integrates cutting-edge **Machine Learning (ML)** and **Large Vision-Language Models (LVLMs)** for improved detection and classification of endometrial cancer.

---

##  System Overview

Our intelligent diagnostic pipeline brings together powerful deep learning and vision-language models for superior medical image analysis.

### Core Components

- **CLIP (Contrastive Language-Image Pretraining):** Extracts high-dimensional feature embeddings from endometrial images.
- **SVM (Support Vector Machine):** Performs robust classification based on CLIP-extracted features.
- **CNN (Convolutional Neural Network):** Analyzes spatial patterns and texture directly from the raw image.
- **Ensemble Approach:** Combines predictions from CNN and SVM to increase diagnostic accuracy and minimize false positives/negatives.
- **Streamlit Interface:** A user-friendly platform enabling clinicians and researchers to upload images and receive real-time diagnosis and reports.

---

##  Workflow

1. **Image Upload**  
   The user uploads an endometrial ultrasound or histopathological image via the Streamlit UI.

2. **Feature Extraction**  
   - CLIP generates image embeddings.
   - CNN analyzes raw image features.

3. **Classification**  
   - SVM processes CLIP embeddings.
   - Ensemble combines CNN and SVM predictions.

4. **Report Generation** 
   The system generates a diagnostic report including:
   - Predicted condition (e.g., adenocarcinoma, hyperplasia, polyps)
   - Severity level
   - Clinical description and recommended medical actions

5. **Interpretability **
   LVLMs enhance the explanation of results by aligning textual and visual data, providing trustworthy and understandable insights for clinicians.

---

##  Features

-  Simple drag-and-drop image upload
-  Advanced feature extraction using CLIP
-  Dual-model diagnosis (CNN + SVM ensemble)
-  Detailed diagnostic report with severity and medical guidance
-  Interpretable results powered by Vision-Language AI
-  Web-based app built using Streamlit

---

##  Tech Stack

- Python ≥ 3.6.5  
- TensorFlow ≥ 1.2.0  
- Keras ≥ 2.1.3  
- OpenAI CLIP  
- Scikit-learn (SVM)  
- Streamlit  

---

##  Motivation

While symptoms like abnormal uterine bleeding provide early clues, traditional clinical evaluations and imaging techniques often fail to detect subtle patterns. This system addresses such limitations by using **AI to identify hidden insights**, aiding **earlier, faster, and more accurate diagnoses**, and ultimately improving patient outcomes.

---

##  Future Enhancements

-  Integration with hospital EMR systems  
-  Privacy-preserving diagnosis using federated learning  
-  Expansion to classify more gynecological cancer types  
-  Mobile deployment for rural diagnostics  

---

##  Citation

If you use this system, dataset, or methodology in your work, please cite:

> Hao Sun, Xianxu Zeng, Tao Xu, Gang Peng, and Yutao Ma,  
"Computer-Aided Diagnosis in Histopathological Images of the Endometrium Using a Convolutional Neural Network and Attention Mechanisms,"  
_IEEE Journal of Biomedical and Health Informatics_, 2020, 24(6): 1664–1676.  
[IEEE Paper](https://ieeexplore.ieee.org/document/8854180)

---

##  Contact

For feedback, questions, or collaboration opportunities, please open an issue or reach out via email.

---

