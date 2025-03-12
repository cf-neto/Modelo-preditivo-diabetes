<h1 align="center">Previsão de Diabetes com Regressão Logística</h1>
<p align="center"><i>Repositório dedicado à previsão de diabetes utilizando regressão logística, incluindo visualizações e análise de dados.</i></p>

<p align="center" display="inline-block">
  <img src="https://img.shields.io/badge/Status-Ativo-brightgreen" alt="Status"/>
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Seaborn-v0.11.2-yellowgreen?logo=seaborn&logoColor=white" alt="Seaborn"/>
  <img src="https://img.shields.io/badge/Pandas-v1.5.0-green?logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Scikit--learn-v0.24.2-blue?logo=scikit-learn&logoColor=white" alt="Scikit-learn"/>
  <img src="https://img.shields.io/badge/Matplotlib-v3.4.3-red?logo=matplotlib&logoColor=white" alt="Matplotlib"/>
</p>

## Sobre este projeto

Este repositório contém o código para prever a presença de diabetes em pacientes com base em um conjunto de dados clínicos. Utilizamos um modelo de regressão logística treinado e validado com o conjunto de dados **Pima Indians Diabetes**. O repositório também inclui visualizações interativas, análise de correlação entre as variáveis e a avaliação do modelo.

### Objetivo
O objetivo deste projeto é prever se um paciente tem ou não diabetes com base em variáveis clínicas. A regressão logística foi usada para modelar e fazer previsões, enquanto a análise de correlação entre as variáveis ajuda a entender melhor o comportamento dos dados.

---

## Visualizações

### 1. **Número de Pessoas com ou sem Diabetes**
Um gráfico de barras que mostra o número de pessoas diagnosticadas com diabetes e sem diabetes.

![a](https://github.com/user-attachments/assets/3ef0889c-c6fd-4da9-b1ef-a2c563941dba)


**Explicação**: Este gráfico ajuda a visualizar a distribuição do conjunto de dados quanto ao diagnóstico de diabetes, que é a variável alvo no nosso modelo.

### 2. **Matriz de Correlação**
A matriz de correlação é usada para entender como as variáveis estão correlacionadas entre si. A correlação entre a glicose e o diabetes, por exemplo, pode indicar uma forte relação.

![output](https://github.com/user-attachments/assets/6df65a31-8a1c-46b1-ac99-6421bb2680cc)


**Explicação**: A matriz de correlação mostra a relação entre as variáveis. O valor varia de -1 a 1, onde 1 indica correlação positiva, -1 indica correlação negativa e 0 indica nenhuma correlação.

### 3. **Acurácia do Modelo**
Após o treinamento do modelo, a acurácia de 80% foi alcançada. O modelo previu corretamente a presença ou ausência de diabetes na maioria dos casos.

---

## Como Rodar o Projeto

1. Clone o repositório:
```bash
  git clone https://github.com/CarlosFCode/previsao-diabetes-logistica.git
```
2. Instale as dependências listadas no **requirements.txt**:
```bash
  pip install -r requirements.txt
```

## Autor

- [@cf-neto](https://www.github.com/cf-neto)
