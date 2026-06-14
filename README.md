# financial-sentiment-bilstm-bert
Financial news sentiment analysis using Bi-LSTM and               DistilBERT on Financial PhraseBank dataset
# Financial News Sentiment Analysis
## Bi-LSTM vs DistilBERT on Financial PhraseBank

## Overview
3-class sentiment classification (Positive/Negative/Neutral) 
on Financial PhraseBank dataset.
Compares classical deep learning (Bi-LSTM) against transformer 
fine-tuning (DistilBERT) on financial text.

## Live App
[Click here](your-flask-link-here)

## Dataset
Financial PhraseBank — Malo et al. 2014
sentences_allagree: 2,264 sentences, 3 classes

## Model Results
(fill after building)

## Key Findings
(fill after EDA)

## Tech Stack
Python · TensorFlow · Keras · HuggingFace Transformers · 
WandB · Flask · Pandas · NLTK · Scikit-learn

## Project Structure
notebooks/
├── 01_eda.ipynb
├── 02_preprocessing.ipynb  
├── 03_bilstm.ipynb
└── 04_distilbert.ipynb
app/
└── app.py
models/
└── (saved after training)

## References
- Malo et al. 2014 — Good Debt or Bad Debt: Detecting Semantic 
  Orientations in Economic Texts
- DistilBERT: Sanh et al. 2019
