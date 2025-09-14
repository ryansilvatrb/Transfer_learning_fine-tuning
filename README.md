# Transfer Learning - Cats vs Dogs 🐱🐶

## 📌 Descrição
Este projeto foi desenvolvido como parte do desafio da **Digital Innovation One (DIO)**.  
O objetivo foi aplicar **Transfer Learning** em um problema de classificação binária utilizando o dataset **Cats vs Dogs**.

## 🚀 Tecnologias utilizadas
- Python 3.10+
- TensorFlow / Keras
- Google Colab
- Matplotlib

## 🧠 Estrutura do projeto
1. Pré-processamento com `ImageDataGenerator` (data augmentation).
2. Modelo pré-treinado **MobileNetV2** (ImageNet).
3. Camadas adicionais para classificação binária.
4. Treinamento inicial com modelo congelado.
5. **Fine-tuning**: ajuste das últimas camadas do modelo base.
6. Avaliação do modelo (acurácia e gráficos de treino).

## 📊 Resultados
- Acurácia média de validação: **~90%** (pode variar dependendo dos hiperparâmetros).
- Gráficos de acurácia/erro mostram aprendizado consistente sem overfitting excessivo.

## ▶️ Como executar
1. Abra o notebook no [Google Colab](https://colab.research.google.com/).
2. Instale as dependências (`tensorflow`, `matplotlib`).
3. Execute célula por célula.
4. O modelo final será salvo como `cats_vs_dogs_transfer_learning.h5`.

## 📷 Exemplos
Inclua aqui prints dos gráficos de acurácia/validação.

---
