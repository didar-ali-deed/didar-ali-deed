<h1 align="center">Didar Ali</h1>

<p align="center">
  <strong>AI / ML Engineer</strong><br />
  Natural Language Processing · Speech · Computer Vision
</p>

<p align="center">
  <a href="https://didar-portfolio-web.vercel.app/">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/didar-ali-deed">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://doi.org/10.21015/vtse.v13i3.2174">Publication</a>
</p>

---

### From model experiments to usable applications

I build machine learning workflows from data preparation and model evaluation through API integration and application development. My projects span document verification, speech emotion recognition, and sentiment inference.

Based in **Islamabad, Pakistan**. Open to **full-time AI/ML engineering roles** and **freelance projects** involving NLP, computer vision, or model integration.

## Selected work

### 01 / Identity Verification System

**Document analysis and biometric matching in a single review workflow.**

Combines document uploads and selfie capture with a 10-stage verification pipeline. The application brings OCR, field consistency checks, liveness checks, and face similarity into an interface where administrators can inspect results and review flagged applications.

- **Pipeline:** Document acceptance, extraction, cross-validation, scoring, and decision rules.
- **Application:** Background processing with Celery, PostgreSQL persistence, and an admin review dashboard.
- **Delivery:** FastAPI backend, React and TypeScript frontend, and Docker Compose setup.

[Repository & architecture →](https://github.com/didar-ali-deed/Identity-Verification-System)

### 02 / Speech Emotion Recognition

**A research workflow with an interactive audio inference application.**

Uses Wav2Vec2 representations and a Transformer classifier to recognize emotions in speech from the RAVDESS and TESS datasets. Includes the steps needed to prepare data, train the model, and inspect its predictions.

- **Modeling:** Audio preprocessing, feature extraction, and classifier training with PyTorch.
- **Evaluation:** Accuracy, precision, recall, F1 score, and confusion matrix outputs.
- **Interface:** A Flask app for audio uploads, waveform visualization, and emotion probabilities.

[Repository →](https://github.com/didar-ali-deed/Vocal-Sentiment-Transformer-Based-Speech-Emotion-Recognition) · [Publication →](https://doi.org/10.21015/vtse.v13i3.2174)

### 03 / ONNX Sentiment Analysis

**Transformer inference through a web interface and JSON API.**

Serves a pretrained DistilBERT sentiment model with ONNX Runtime. Users can analyze text in the browser or integrate positive/negative predictions and confidence scores through the API.

- **Inference:** ONNX Runtime execution without a PyTorch runtime dependency.
- **Integration:** Flask application with a documented `/api/predict` endpoint.
- **Deployment:** Gunicorn configuration and setup instructions for Render.

[Repository & API example →](https://github.com/didar-ali-deed/sentiment-analysis-app)

[Browse all repositories →](https://github.com/didar-ali-deed?tab=repositories)

## Research

**[Vocal Sentiments: Transformer Based Speech Emotion Recognition](https://doi.org/10.21015/vtse.v13i3.2174)**

**Didar Ali**, Muhammad Shahab, Yasir Saleem Afridi, and Rehmat Ullah  
*VFAST Transactions on Software Engineering* · Vol. 13, No. 3 · pp. 187–197 · 2025  
DOI: [10.21015/vtse.v13i3.2174](https://doi.org/10.21015/vtse.v13i3.2174)

## Technical toolkit

| Area | Technologies |
| :--- | :--- |
| Modeling & inference | Python, PyTorch, TensorFlow, Hugging Face Transformers, ONNX Runtime |
| Computer vision | OpenCV, EasyOCR, DeepFace |
| APIs & background processing | FastAPI, Flask, Celery, Redis |
| Data & deployment | PostgreSQL, Docker, Docker Compose, Gunicorn |
| Frontend | React, TypeScript |

## Background

**BS in Computer Systems Engineering** · UET Peshawar  
**Certifications** · Google Data Analytics · Google Cybersecurity  
**Currently exploring** · Retrieval-augmented generation (RAG) and vector databases

---

### Work with me

For engineering opportunities or freelance projects, [connect with me on LinkedIn](https://www.linkedin.com/in/didar-ali-deed). Include a brief description of the role or project so we can discuss the fit.

[Explore my portfolio →](https://didar-portfolio-web.vercel.app/)
