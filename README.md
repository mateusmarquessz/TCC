# Projeto de TCC: Classificação de Imagens Médicas com Deep Learning

Este repositório contém o código do meu Trabalho de Conclusão de Curso, que visa classificar imagens médicas, especialmente tomografias computadorizadas (TC), utilizando técnicas de Deep Learning. O modelo foi treinado usando as arquiteturas **DenseNet201**, **ResNet50V2**, e **EfficientNet** para identificar doenças renais.

## Descrição do Código

### 1. Importação de Bibliotecas
Importação de bibliotecas essenciais como `numpy`, `pandas`, `tensorflow`, `matplotlib`, entre outras.

### 2. Carregamento e Pré-processamento de Dados
As imagens são carregadas, redimensionadas, normalizadas e aumentadas para melhorar a performance do modelo.

### 3. Construção do Modelo
Definição das arquiteturas DenseNet201, ResNet50V2 e EfficientNet usando o Keras.

### 4. Treinamento
Utilização de `fit` para treinar o modelo com monitoramento de métricas de desempenho.

### 5. Avaliação
Avaliação do modelo usando o conjunto de dados de teste.

### 6. Visualização de Resultados
Resultados do treinamento são visualizados usando `matplotlib`.

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/mateusmarquessz/TCC.git
