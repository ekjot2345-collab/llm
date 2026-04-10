# 🚀 LLM Fine-Tuning using LoRA (PEFT)

This project demonstrates fine-tuning a Large Language Model using efficient techniques on a custom dataset.

## 🔧 Overview
- Fine-tuned a LLaMA-based model
- Used PEFT (LoRA) for efficient training
- Trained on ~6000 samples
- Built full pipeline: tokenization → dataset → training

## 🧠 Key Learnings
- Data quality plays a crucial role in model performance
- Prompt format consistency is important
- PEFT enables training large models on limited hardware

## ⚡ Challenges
- Handling noisy dataset and low accuracy
- Managing GPU memory constraints
- Debugging training and preprocessing errors

## 📊 Results
Model generates structured Q&A responses from custom dataset.

## 🚀 How to Run

### 1. Install Dependencies
```bash
pip install -r requirements.txt
