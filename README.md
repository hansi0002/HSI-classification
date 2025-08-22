# HSI-classification
“Hyperspectral Image Classification using SwinSpectral Transformer”
# 🌈 Hyperspectral Image (HSI) Classification  

This project implements a custom **SwinSpectral Transformer** model for **Hyperspectral Image (HSI) Classification**.  
The architecture is designed specifically for hyperspectral data, combining **spectral embeddings, attention mechanisms, and Swin Transformers** for accurate classification.  

---

## 🔍 Overview  

Hyperspectral images capture hundreds of narrow spectral bands, providing rich information for land-cover classification.  
However, their **high dimensionality** makes modeling challenging.  

Our proposed model addresses this by combining:  

- 🌀 **Swin Transformer Blocks** – Extract spatial features effectively using shifted windows  
- 🔗 **Group-wise Spectral Embedding (GSE)** – Reduces dimensionality while preserving spectral information  
- 🎯 **Channel Attention Fusion (CAF)** – Learns to emphasize important spectral channels  

This hybrid approach achieves **state-of-the-art performance** on benchmark HSI datasets such as **Indian Pines, Pavia University, and Salinas**.  

---



