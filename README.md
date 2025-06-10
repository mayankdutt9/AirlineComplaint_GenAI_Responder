# ✈️ Airline Complaint Classification & GenAI-Based Response Generation

A real-world NLP + GenAI project focused on classifying airline complaints from Twitter and generating realistic, context-aware responses using a text-generation model.

## 📌 Project Overview

This project aims to simulate a smart customer support backend system by:

1. **Classifying complaint tweets** into categories like *Late Flight*, *Customer Service*, *Flight Booking Problems*, etc. using a fine-tuned BERT model.
2. **Generating realistic responses** to the classified complaints using a GenAI model pipeline.

Inspired by real airline customer support systems — built as part of my data science portfolio to explore NLP and transformers in action.

---

## Key Features

- Cleaned and preprocessed real-world tweet dataset  
- EDA to explore complaint categories, airline-wise tweet volume, and more  
- Used **BERT** (`bert-base-uncased`) model for multi-class classification  
- Custom **response generation pipeline** using Hugging Face GenAI tools  
- Evaluation with classification report and label-wise metrics

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming |
| Pandas, Seaborn, Matplotlib | Data cleaning & visualization |
| scikit-learn | Label encoding, train-test split, evaluation |
| Hugging Face Transformers | Tokenizer, BERT model, Trainer |
| Hugging Face Pipeline | Text generation |
| PyTorch | Model backend |

---

