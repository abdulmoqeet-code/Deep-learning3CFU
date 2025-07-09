# 📊 Comparative Study of Text Classification:  
### Transformer-Based Transfer Learning vs. LSTM-Based Deep Learning from Scratch

---

## 📌 Project Overview

This project compares two deep learning approaches for classifying **IMDB movie reviews** as either positive or negative.

---

### 🔹 Transformer-Based Transfer Learning

- Utilizes a **pretrained DistilBERT** model (a lighter version of BERT) from the **Hugging Face Transformers** library.
- Leverages **transfer learning** by fine-tuning the model on the text classification dataset.

---

### 🔸 GRU-Based Model From Scratch

- Builds a **GRU (Gated Recurrent Unit)** model **without** using any pretrained embeddings.
- Trains **all layers**, including the embedding matrix, **from scratch**.

---

## 🎯 Objective

Evaluate and compare the performance of both methods in terms of:

- 📉 Training and validation loss  
- ✅ Accuracy  
- 🌐 Generalization ability  
- 🕒 Training time and resource usage  

---

## 💡 Motivation

- **GRU-based models** are classical deep learning approaches for sequence modeling and offer **simpler alternatives** when computational resources are limited.
- **Transformer-based models** (e.g., BERT, DistilBERT) have achieved **state-of-the-art performance** on many NLP tasks.

---

## 🔍 Conclusion

This project demonstrates the **strengths and trade-offs** of both methods in a practical text classification scenario.

---

