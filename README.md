# **Disease Classification Project**

## **Course: NLP (Semester 6) - Pillai College of Engineering**

### **Project Overview:**

This project is part of the **Natural Language Processing (NLP)** course for **Semester 6** students at **Pillai College of Engineering**. The project focuses on **Disease Classification**, where we apply various **Machine Learning (ML)**, **Deep Learning (DL)**, and **Language Models** to categorize patient-reported symptoms into predefined diseases or medical conditions. This project involves exploring techniques like text preprocessing, feature extraction, model training, and evaluating the models for their effectiveness in classifying symptoms accurately.

You can learn more about the college by visiting the official website of [Pillai College of Engineering](https://www.pce.ac.in/).

### **Acknowledgements:**

We would like to express our sincere gratitude to the following individuals:

- **Theory Faculty**:
  - **Dhiraj Amin**
  - **Sharvari Govilkar**

- **Lab Faculty**:
  - **Dhiraj Amin**
  - **Neha Ashok**
  - **Shubhangi Chavan**

Their guidance and support have been invaluable throughout this project.

### **Project Title:**

**Classifying Patient-Reported Symptoms into Possible Diseases or Conditions using Natural Language Processing**

### **Project Abstract:**

In contemporary healthcare, precise and timely diagnosis is essential for successful treatment and patient care. This project aims to create a system that categorizes patient-reported symptoms into potential diseases or medical conditions using **Machine Learning**, **Deep Learning**, and **Language Models**. The system leverages **Natural Language Processing (NLP)** techniques to process symptom descriptions and improve diagnostic accuracy. The dataset used in this research includes **30 unique diseases** providing diverse input for model training. 
Key preprocessing techniques such as **lowercasing**, **tokenization**, **stemming**, **stopword removal**, **punctuation removal**, and **whitespace normalization** were applied to prepare the symptom data for classification. The results demonstrate that the system accurately identifies potential diagnoses, reducing misdiagnosis risks and enhancing patient care. By automating preliminary symptom analysis, the model aids healthcare professionals in prioritizing complex cases, optimizing resource allocation, and improving clinical decision-making. This approach has the potential to streamline diagnostic workflows, leading to a more efficient and accurate healthcare system.

### **Algorithms Used:**

- **Machine Learning Algorithms**:
  - **Logistic Regression**
  - **Support Vector Machine (SVM)**
  - **Random Forest Classifier**
  - **K-Nearest Neighbors (KNN)**

- **Deep Learning Algorithms**:
  - **Convolutional Neural Networks (CNN)**
  - **Long Short-Term Memory (LSTM)**
  - **CNN-Bidirectional LSTM (CNN-BiLSTM)**
  - **Gated Recurrent Unit (GRU)**
  - **CNN-Gated Recurrent Unit (CNN-GRU)**
  - **Bidirectional LSTM-GRU (BiLSTM-GRU)**

- **Language Models**:
  - **BERT (Bidirectional Encoder Representations from Transformers)**
  - **RoBERTa (Robustly Optimized BERT Approach)**

### **Comparative Analysis:**

The comparative analysis of different models highlights their effectiveness in classifying symptoms into the correct disease. The following table summarizes the **accuracy**, **precision**, **recall**, and **F1-score** of the models tested:

| **Model Type**                                   | **Accuracy (%)** | **Precision (%)** | **Recall (%)** | **F1-Score (%)** |
|--------------------------------------------------|------------------|-------------------|----------------|------------------|
| Logistic Regression                              | 97               | 94                | 95             | 91               |
| SVM (Support Vector Machine)                     | 10               | 11                | 25             | 15               |
| Random Forest                                    | 93.75            | 97                | 98             | 96               |
| K-Nearest Neighbors                              | 89.5             | 91                | 99             | 98               |
| CNN (Convolutional Neural Networks)              | 4                | 0                 | 0              | 0                |
| CNN-Bidirectional LSTM                           | 2.9              | 3                 | 1              | 6                |
| Gated Recurrent Unit (GUR)                       | 2.9              | 3                 | 1              | 6                |
| LSTM (Long Short-Term Memory)                    | 4                | 0                 | 0              | 0                |
|Bidirectional LSTM-GRU                            | 33.3             | 0                 | 0              | 0                |
| BERT                                             | 72               | 60                | 38             | 46               |
|RoBERTa                                           |98                | 100               | 100            |100               |

### **Conclusion:**

This **Disease Classification** project demonstrates the potential of **Machine Learning**, **Deep Learning**, and **Language Models** for symptom-based diagnosis. The comparative analysis reveals that **BERT**, a transformer-based model, outperforms traditional methods and deep learning models in terms of **accuracy**, **precision**, and **recall**. By employing various algorithms, we gain insights into the strengths and weaknesses of each model, enabling the selection of the most suitable approach for symptom classification. The findings contribute to developing more accurate diagnostic tools, ultimately enhancing healthcare efficiency and patient outcomes.
