# Question Answering System using PyTorch

This repository contains a custom Question Answering (QA) model using PyTorch and the Hugging Face Transformers library.

## 📌 Features
- Uses `DistilBERT` for Question Answering.
- Fine-tunes on the **SQuAD** dataset.
- Supports training on **Google Colab**.
- Can predict answers from any context.

## 📌 Training Details
- Model Used: DistilBERT (distilbert-base-uncased)
- Dataset: SQuAD (Stanford Question Answering Dataset)
- Max Sequence Length: 512
- Batch Size: 16
- Optimizer: AdamW (learning rate = 5e-5)
- Loss Function: Cross Entropy Loss

## Example Usage
`Context`
"The Great Pyramid of Giza, built around 2560 BCE, is the oldest of the Seven Wonders of the Ancient World and the only one still in existence. It was constructed as a tomb for the Pharaoh Khufu and originally stood at 146.6 meters tall. Over time, it has lost some of its height due to erosion and the removal of its outer casing stones."

`Question`
"How tall was the Great Pyramid of Giza originally?"

`Expected Answer`
"146.6 meters."

## 🚀 Setup
### 1️⃣ Clone Repository
```bash
git clone https://github.com/wajee-ul-hassan/QA-System-PyTorch.git
cd QA-System-PyTorch
