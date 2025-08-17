# Classificação de Imagens no CIFAR-10 com PyTorch

Este projeto implementa um pipeline completo de **treinamento e avaliação de modelos de Deep Learning** (ResNet-18 e VGG-19) para classificação de imagens no dataset **CIFAR-10**.  
O código foi desenvolvido em **Google Colab** com a biblioteca **PyTorch**.

---

## 📂 Estrutura do Projeto

- **Pré-processamento & Transformações**
  - Aumento de dados (flip horizontal, jitter de cor, rotação aleatória).
  - Normalização com estatísticas do ImageNet.
  - Conjunto de treino, validação e teste devidamente separados.

- **Modelos Implementados**
  - `ResNet18` com pesos do ImageNet.
  - `VGG19` adaptado para CIFAR-10.

- **Treinamento**
  - Otimizador: **Adam**
  - Agendador de taxa de aprendizado: **CosineAnnealingLR**
  - Critério: **CrossEntropyLoss**
  - Estratégias: **early stopping** e **grad clipping**.

- **Avaliação**
  - Métricas: Acurácia, Balanced Accuracy, Precisão, Recall, F1-score.
  - Visualizações: Curvas de loss/accuracy, predições de amostra e matriz de confusão.

---
