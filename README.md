# SQuAD Chatbot with BERT

This project is a simple chatbot built using the Stanford Question Answering Dataset (SQuAD) and the BERT (Bidirectional Encoder Representations from Transformers) model. The approach involves fine-tuning the pre-trained BERT-base-uncased model on the SQuAD 2.0 dataset, which consists of context-passages paired with questions and answers.

## Approach

My approach begins with the selection of the pre-trained BERT-base-uncased model. I fine-tune this model on the SQuAD 2.0 dataset to train a Question Answering (QA) model. The dataset consists of context-passages paired with questions and answers. To facilitate the training process, I preprocess the data and create a custom dataset class, transforming the raw JSON format into a format suitable for training the BERT-based QA model. Additionally, I implement text normalization techniques to enhance the model's performance.

## Key Components

- BERT-base (bert-base-uncased) pre-trained model.
- PyTorch for model training and evaluation.
- Tokenization using BERT tokenizer.
- Monitoring training progress with tqdm.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/Melisaaydinci/Wiki-chatbot.git
