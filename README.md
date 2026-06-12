# AI and Machine Learning Portfolio

Two end-to-end machine learning projects covering computer vision and natural language processing.

---

## Project 1 — Skin Cancer Classification

Multi-class skin cancer classification using CNN and transfer learning on the ISIC dataset.

**Dataset:** ISIC — 9 skin lesion classes  
**Model:** ResNet50 (transfer learning)  
**Accuracy:** ~66%  
**Tech:** Python · TensorFlow · Keras · NumPy · Matplotlib

**Approach:**
- Loaded and preprocessed ISIC dataset with augmentation
- Fine-tuned ResNet50 pretrained on ImageNet
- Evaluated using accuracy, confusion matrix, and classification report

---

## Project 2 — Sentiment Analysis (IMDb)

Binary sentiment classification on IMDb movie reviews using RNN and LSTM with GloVe embeddings.

**Dataset:** IMDb — 50,000 movie reviews (positive/negative)  
**Models:** RNN · LSTM · GloVe embeddings  
**Best Accuracy:** ~88% (LSTM)  
**Tech:** Python · TensorFlow · Keras · GloVe · Gradio

**Approach:**
- Preprocessed and tokenized review text
- Compared RNN vs LSTM performance
- Used pretrained GloVe word embeddings
- Built an interactive Gradio UI for real-time sentiment prediction

---

## Results Summary

| Project | Model | Dataset | Accuracy |
|---|---|---|---|
| Skin Cancer Classification | ResNet50 | ISIC (9 classes) | ~66% |
| Sentiment Analysis | LSTM + GloVe | IMDb (50k reviews) | ~88% |

---

## How to Run

```bash
git clone https://github.com/Lamsalyusu/6CS012-AI-and-Machine-Learning
cd 6CS012-AI-and-Machine-Learning
pip install -r requirements.txt
```

Open `sentiment_analysis.ipynb` in Jupyter or Google Colab and run all cells.  
The Gradio interface launches automatically in the final cell for real-time sentiment prediction.

## Module

6CS012 — AI and Machine Learning  
Herald College Kathmandu | University of Wolverhampton
