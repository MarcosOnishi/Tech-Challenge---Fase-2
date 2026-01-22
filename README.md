📌 Visão Geral

Este projeto tem como objetivo desenvolver um modelo preditivo capaz de identificar se o índice IBOVESPA irá fechar em Alta ou Baixa no dia seguinte, utilizando dados históricos do próprio índice.

Foram implementados e avaliados diferentes modelos de Machine Learning, com foco em classificação binária, sendo o Random Forest o modelo que apresentou melhor desempenho e maior acurácia no conjunto de testes.

🎯 Objetivo

Prever a direção do fechamento do IBOVESPA (Alta = 1, Baixa = 0) com base em informações históricas, atendendo a uma acurácia mínima de 75%, conforme especificado no desafio técnico.

📊 Modelos Utilizados

Os seguintes modelos foram treinados e comparados:

- K-Nearest Neighbors (KNN)

- Regressão Logística

- Árvore de Decisão

- Random Forest ✅


🔹 Resultado:
O modelo Random Forest apresentou a maior acurácia, destacando-se por sua capacidade de capturar relações não lineares, reduzir overfitting via ensemble e lidar melhor com variáveis financeiras.


## 🗂️ Estrutura do Repositório
```
├── Codigos/ notebooks (.ipynb) com:
│   ├── Tech_Challenger2_KNN.ipynb                               #(KNN)
│   ├── Arvore_decisao.ipynb                                     #(Arvore de Decisao)
│   ├── Exploração_e_Analise_de_dados_Regressão_Logistica.ipynb  #(Analise Exploratoria, Regressão Logistica e teste ADF)
│   └── Projeto_Fase_2_v2.ipynb                                  #(Random Forest) 
│
├── Base/
│   ├── Dados Históricos - Ibovespa 17.12.2015_17.12.2025.csv                # Dados brutos obtidos da fonte
│   └── Dados Históricos - Ibovespa 17.12.2015_17.12.2025 (Volume ADD).csv   # Base formatada e pronta para modelagem
│
├── README.md
```
