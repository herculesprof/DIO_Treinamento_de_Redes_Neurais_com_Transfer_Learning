# Desafio DIO - Transfer Learning com Dataset Integrado

Este projeto demonstra a aplicação de **Transfer Learning** em Deep Learning utilizando Python e TensorFlow no Google Colab.

## 📋 Sobre o Projeto
Para tornar a execução mais fluida, utilizei o dataset **tf_flowers**, disponível diretamente nas bibliotecas do TensorFlow. O objetivo é classificar imagens de flores em 5 categorias diferentes usando uma base de conhecimento pré-treinada.

## 🛠️ Tecnologias e Métodos
- **Ambiente:** Google Colab.
- **Dataset:** `tf_flowers` (TensorFlow Datasets).
- **Modelo Base:** MobileNetV2 (pré-treinado com ImageNet).
- **Técnica:** Congelamento de camadas (*Freezing*) e substituição do cabeçalho de classificação (*Top Layer*).

## 🚀 Como Executar
1. Abra o arquivo `.ipynb` no Google Colab.
2. Execute as células em sequência.
3. O dataset será carregado automaticamente pela biblioteca `tfds`, sem necessidade de uploads manuais ou links externos de download.

## 📈 Resultados
O modelo utiliza as características extraídas da ImageNet para aprender rapidamente a distinguir entre margaridas, dentes-de-leão, rosas, girassóis e tulipas, atingindo alta acurácia em poucas épocas de processamento.
