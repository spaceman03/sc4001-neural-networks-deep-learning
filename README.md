# Neural Networks & Deep Learning
This repository contains the project completed for the **SC4001 Neural Networks and Deep Learning** module. It includes implementations of state-of-the-art deep learning techniques applied to real-world tasks in **sentiment analysis** and **protein secondary structure prediction**.

## Introduction
This project explores advanced deep learning methodologies applied to two key domains: **sentiment analysis** and **protein secondary structure prediction**.
- In the first part, a compact Transformer model, DistilGPT-2, was fine-tuned on movie review data to perform sentiment classification, achieving an accuracy of 88.4%. The model was then adapted to predict star ratings, reaching 75.5% accuracy after consolidating rating classes. Comparative experiments with DistilBERT and TinyBERT demonstrated that DistilBERT outperformed other models in this task, particularly under limited data conditions.
- In the second part, we tackled protein secondary structure prediction from amino acid sequences. Baseline models using CNN, LSTM, and Seq2Seq architectures achieved moderate results in Q3 classification but underperformed in the more complex Q8 classification due to limitations in capturing long-range dependencies. To overcome this, we developed a Transformer-based model leveraging self-attention, which significantly improved performance by modeling both local and global interactions in the sequence data.

This repository provides a comparative analysis of deep learning architectures and highlights the robustness and versatility of Transformer models in handling complex sequence-based tasks across different domains.
## :busts_in_silhouette: Our Team
| Name | Parts Done | Github ID |
|---|:---:|---|
| Brandon Jang Jin Tian | Protein Structure Prediction | @BrandonJang |
| Chung Zhi Xuan | Protein Structure Prediction | @spaceman03 |
| Yau Jun Hao | Sentiment Analysis |  |

## Results
| Task | Model | Test Accuracy |
|---|:---:|:---:|
Sentiment Classification | DistilGPT-2 | 88.40%
Protein Structure Prediction (Q3) | Seq2Seq | 69.36%
Protein Structure Prediction (Q8) | Seq2Seq | 56.90%
