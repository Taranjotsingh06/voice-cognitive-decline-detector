# 🧠 Report: Voice-Based Cognitive Decline Pattern Detection

## 🔍 Objective
To build a proof-of-concept pipeline that analyzes short audio samples and extracts indicators of potential cognitive stress or early cognitive decline using NLP and audio signal features.

---

## 📊 Features Extracted
From each audio sample and its transcription, the following features were extracted:
- **Speech Rate** (words per minute)
- **Pitch Variability**
- **Pauses** (., !, ?)
- **Hesitation Markers** (`uh`, `um`)
- **Vague Word Usage** (e.g., “thing”, “stuff”)
- **Average Sentence Length**

These were chosen based on known markers of cognitive decline in speech patterns.

---

## 🧠 ML Techniques Used
- **KMeans Clustering**: To group speech samples into distinct speaking patterns.
- **Isolation Forest**: For anomaly detection to flag speech samples that deviate significantly from typical patterns.

---

## 💡 Insights
- **Pitch variability** and **hesitation markers** showed strong divergence in anomalous samples.
- Anomalous clusters often showed slower speech rate, more pauses, or vague word usage.

---

## 🚀 Next Steps
- Integrate automatic speech recognition (ASR) using Whisper to automate transcription.
- Expand dataset with labeled clinical samples.
- Incorporate syntactic/semantic analysis for word substitutions or memory recall patterns.
- Collaborate with cognitive science experts for medical validation.

---

