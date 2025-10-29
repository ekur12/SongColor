# SongColor

## Inferring Emotional Tone in Music and Visualizing it Through Color

This project builds an **end-to-end machine learning pipeline** that analyzes songs and translates their emotional tone into **color outputs** — syncing with **smart home devices** for immersive, mood-based lighting experiences.

---

## Overview

The goal of this project is to bridge **audio emotion recognition** and **visual expression**.  
The model has the following components:

1. **Extract 30-second audio preview files** through **Apple Music API** and compute **Mel Spectrogram** using **Librosa**.  
2. **Learn dense audio embeddings** by training **autoencoder** on Mel Spectrograms.  
3. **Compares Vanilla RNN and LSTM models** in inferring continuous **arousal** and **valence** values.  
   - Trains on human annotated datasets (ex: **DEAM**)  
   - Modeling emotion through **Russell's Circumplex Model of Emotion**  
4. **Maps the predicted (arousal, valence)** pair to a color on a **2D emotion-color space**.  
5. **Syncs lighting color changes** via the **Google Home API** for a real-time visual experience.

---

## Tech Stack

| Category | Tools |
|-----------|--------|
| **Languages** | Python |
| **Libraries** | TensorFlow / PyTorch, Librosa, NumPy, Matplotlib
| **APIs** | Google Home API, Apple Music API |
| **Containerization** | Docker |

---

## Inspiration
This project was inspired by the intersection of **music, emotion, and color perception**, exploring how we can translate emotional energy in sound into visual experiences.
Has implications in mood lighting and/or multimodal music therapy.

---

## Author

**Eesha Kurella**  
*Computer Science, University of Maryland*  
Focus: Machine Learning • Emotion AI • Multimodal Systems 
