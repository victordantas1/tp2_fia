# **Heart Disease Prediction Using Neural Networks**

Este projeto implementa um modelo de **rede neural artificial (RNA)** para prever a presença de doenças cardíacas com base em um conjunto de 13 atributos clínicos. O trabalho segue as etapas de carregamento, limpeza, normalização, treinamento, avaliação e conclusão sobre a importância dos métodos utilizados.

O repositório contém:

* `README.md` — descrição geral do projeto
* Jupyter Notebook `.ipynb` — código completo, explicações e visualizações
* Avaliação final incluindo matriz de confusão, acurácia, precisão e recall
* Conclusões sobre o desempenho do modelo e sobre a normalização dos dados

---

## **Problema**

O objetivo é classificar pacientes entre:

* **0 — ausência de doença cardíaca**
* **1 — presença de doença cardíaca**

Utilizando 13 atributos, como idade, colesterol, pressão arterial, tipo de dor no peito, taxa máxima de batimentos, entre outros.

As redes neurais são avaliadas antes e depois de ajustes, comparando modelos categóricos e binários.

---

## **Metodologia**

1. **Importação e limpeza do dataset**
2. **Normalização dos dados** para melhor desempenho do modelo
3. **Divisão em treino e teste**
4. **Treinamento de redes neurais**
5. **Avaliação usando:**

   * Matriz de confusão
   * Acurácia
   * Precisão
   * Recall

---

## **Resultados — Seção 6 (Tarefa Principal TP2)**

A seguir estão os principais resultados do notebook.

### **Modelo Binário com 2 camadas, e saida binária com ativação simoide**

* **Acurácia:** **≈ 0.951**
* **Precisão / Recall / F1 (weighted avg):**

  * Precisão: **0.95**
  * Recall: **0.95**
  * F1-score: **0.95**
* **Resumo:**
  Este foi o **melhor modelo do estudo**, superando todos os demais. A matriz de confusão indica uma divisão equilibrada de acertos entre as duas classes, com baixo número de falsos positivos e falsos negativos.

---

## **Conclusão**

O uso de redes neurais artificiais mostrou-se eficaz para a tarefa de predição de doenças cardíacas.
Entre todos os experimentos realizados:

* O **modelo binário otimizado** alcançou a melhor performance (**95% de acurácia**).
* A normalização dos dados foi **fundamental** para o aumento significativo no desempenho, reduzindo dispersão entre atributos e melhorando a estabilidade do treinamento.
* A análise das métricas demonstra que o modelo é confiável tanto em precisão quanto em recall, o que é essencial em aplicações médicas onde falsos negativos podem ser críticos.

Este projeto demonstra como técnicas simples de pré-processamento, aliadas a modelos bem ajustados, podem gerar resultados robustos mesmo em datasets tabulares e de pequeno porte.
