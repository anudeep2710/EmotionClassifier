# Emotion Classification through audio

## Overview
This project implements a **Speech Emotion Classification system** that predicts the emotional state of a speaker from audio signals. The system focuses on extracting meaningful acoustic features from speech and applying classical machine learning algorithms to classify emotions such as **happy, sad, angry, and neutral**.

The project is designed to explore **real-world speech emotion recognition challenges**, including speaker variation, dataset diversity, and feature robustness.

---

## Motivation
Emotion recognition from speech is a key component of:
- Conversational AI
- Voice assistants
- Customer support analytics
- Human–computer interaction systems

Unlike text-based sentiment analysis, speech emotion recognition relies on **prosodic and spectral features** such as pitch, energy, and timbre, making it a challenging and practical ML problem.

---

## Datasets Used
The model is evaluated on multiple well-known speech emotion datasets to improve generalization:

- **RAVDESS** – Emotional speech and song recordings by professional actors  
- **CREMA-D** – Crowd-sourced emotional speech dataset with diverse speakers  
- **SAVEE** – Surrey Audio-Visual Expressed Emotion dataset  
- **EMO-DB (Berlin Database)** – Classic emotional speech dataset used in research  

Each dataset is processed independently using a consistent pipeline for fair comparison.

---

## Feature Extraction
Raw audio signals are transformed into numerical representations using:

- **MFCC (Mel-Frequency Cepstral Coefficients)**  
- **Spectral features** (e.g., chroma, contrast where applicable)

These features capture emotional cues related to pitch, tone, and speech dynamics and serve as input to machine learning models.

---

## Machine Learning Models
The following classifiers are implemented and compared:

- Support Vector Machine (SVM)
- Random Forest
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree

The goal is to analyze trade-offs between accuracy, robustness, and generalization across datasets.

---

## Evaluation Metrics
Model performance is evaluated using:

- **Accuracy**
- **F1-Score**

These metrics help assess performance on potentially imbalanced emotional classes.

---

## Project Structure
