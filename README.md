# 🖼️ Image Caption Generator using DenseNet201 + GRU

This repository contains an image captioning deep learning model that generates natural language descriptions for images. The model uses a **DenseNet201** as the image encoder and a **GRU-based RNN** as the decoder, trained on the **Flickr8k** dataset.

## 🚀 Project Overview

- **Encoder**: DenseNet201 (pre-trained on ImageNet, excluding the final classification layer)
- **Decoder**: GRU-based RNN that generates captions word-by-word
- **Embedding Layer**: Trained from scratch to learn word representations
- **Dataset**: Flickr8k (8,000 images + 5 captions per image)
- **Loss Function**: Sparse Categorical Crossentropy (with masking for padded tokens)
- **Optimizer**: Adam

---

## 🧠 Model Architecture

```text
Input Image → DenseNet201 (CNN) → Fully Connected Layer → 
→ Concatenate with Word Embedding → GRU → Dense Layer → Output Word Probabilities
