# Heart Disease Prediction using Neural Networks

Este projeto tem como objetivo desenvolver um modelo de **rede neural artificial** capaz de prever a presença de doenças cardíacas com base em atributos clínicos de pacientes. A análise foi realizada utilizando um conjunto de dados amplamente conhecido na área de Machine Learning: o **Cleveland Heart Disease Dataset**, disponibilizado pelo *UCI Machine Learning Repository*.

---

## 🩺 Problema

A doença cardíaca é uma das principais causas de mortalidade no mundo. Prever precocemente a probabilidade de um paciente apresentar algum grau de comprometimento cardíaco pode auxiliar médicos e instituições de saúde a tomarem decisões mais rápidas e precisas.

O problema consiste em **classificar pacientes** de acordo com indicadores clínicos, como:

- idade  
- sexo  
- pressão arterial  
- níveis de colesterol  
- frequência cardíaca máxima  
- resultados de exames específicos  

O objetivo é estimar se um paciente possui ou não doença cardíaca.

---

## 🧠 Metodologia

O notebook realiza o seguinte fluxo de trabalho:

1. **Carregamento e análise do conjunto de dados**
2. **Pré-processamento**, incluindo:
   - limpeza dos dados  
   - tratamento de valores ausentes  
   - codificação de variáveis categóricas  
   - normalização  
3. **Criação de conjuntos de treino e teste** com *stratified split*
4. **Construção e treinamento de uma rede neural** usando Keras/TensorFlow
5. Ajustes experimentais para:
   - evitar overfitting  
   - melhorar acurácia  
   - testar abordagem binária de classificação  
6. **Avaliação dos resultados** e comparação de desempenho entre diferentes modelos

---

## 📊 Resultados Obtidos

Os modelos treinados apresentaram **desempenho consistente na tarefa de classificação**, demonstrando:

- boa capacidade de generalização
- melhora significativa ao utilizar:
  - estratificação na divisão dos dados  
  - normalização adequada  
  - ajustes de arquitetura e hiperparâmetros  
- resultados ainda melhores ao reformular o problema como **classificação binária** (doença vs. ausência de doença)

Os experimentos mostraram que redes neurais podem ser uma ferramenta eficaz na previsão de doenças cardíacas, quando combinadas com limpeza de dados adequada e técnicas de otimização durante o treinamento.

