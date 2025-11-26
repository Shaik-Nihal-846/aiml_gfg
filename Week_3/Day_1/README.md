# Day 15 
## 🖼️ Image Caption Generator with Deep Learning

This project generates **natural-language captions for images** using a deep learning architecture combining CNNs and sequence models.

### 🎯 Objective
Automatically describe the content of an image in meaningful sentences.

### 📌 Workflow
1. Extract visual features using pretrained CNN (VGG/ResNet/Inception)
2. Preprocess caption text and tokenize
3. Train an Encoder-Decoder model using LSTM / GRU
4. Validate using BLEU score
5. Evaluate captions qualitatively on unseen images

### 🔍 Key Insights
- CNN captures spatial structure while LSTM learns language patterns
- Beam search improves caption fluency compared to greedy decoding
