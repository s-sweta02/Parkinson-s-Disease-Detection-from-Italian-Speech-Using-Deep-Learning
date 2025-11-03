# Parkinson-s-Disease-Detection-from-Italian-Speech-Using-Deep-Learning
Overview:
This project focuses on early and non-invasive detection of Parkinson’s Disease (PD) by analyzing Italian speech signals using Machine Learning and Deep Learning approaches.
The study introduces a Hybrid Feature Set — a fusion of 6,373 Linear and 9 Non-Linear acoustic features — to capture both spectral and chaotic properties of speech for robust PD classification.

 Key Highlights:

i) Dataset: Italian Parkinson’s Voice and Speech Dataset (IEEE DataPort).
21 Healthy Speakers
24 PD Speakers
ii) Preprocessing Steps:
Mono conversion
16 kHz resampling
Amplitude normalization
Silence trimming

 Methodology:

i) Feature Engineering:
Linear Features (6,373) — Extracted using openSMILE (ComParE 2016) capturing:
MFCCs, Pitch, Jitter, Shimmer, Spectral, Prosodic, and Phonatory properties.
Non-Linear Features (9) — Capturing chaotic speech system characteristics:
Shannon & Spectral Entropy
Hjorth Mobility & Complexity
Fractal Dimension
Higher-Order Statistics
Hybrid Feature Set (6,382 Total): Combination of all above.

 ii) Model Training:
Traditional Models: Random Forest, SVM, KNN, Naive Bayes
Deep Learning: CNN + BiLSTM for temporal–spectral modeling
Imbalance Handling: SMOTE applied to training data
