# 🧠 Machine Learning: Projeto de Credit Score com Naive Bayes

Este projeto faz parte do Módulo Aprendizagem Baysiana do curso de Cientista de Dados da EBAC e tem como objetivo aplicar técnicas de *Machine Learning* para previsão de score de crédito (baixo, médio e alto), utilizando o algoritmo Naive Bayes.

O modelo foi desenvolvido a partir de uma base contendo variáveis socioeconômicas e demográficas, com foco em apoiar a tomada de decisão em contextos financeiros por meio da identificação de padrões nos dados.

## 🧩 Etapas Desenvolvidas

**1. Validação das bases de dados:** Conferência das bases de treino e teste, garantindo ausência de vazamento de dados (*data leakage*).

**2. Preparação final dos dados:** Utilização das bases previamente tratadas e estruturadas para modelagem.

**3. Treinamento do modelo:** Aplicação do algoritmo Naive Bayes.

**4. Avaliação do modelo:** Análise de desempenho nas bases de treino e teste, utilizando métricas como acurácia, recall e matriz de confusão.

## 📊 Resultados e Insights

- Acurácia de 98,4% na base de treino e 97,5% na base de teste.

- Recall elevado (98,4% treino / 94,4% teste), indicando boa capacidade de identificação das classes.

- Pequena queda de desempenho no teste, sem evidência de *overfitting* significativo.

- Matrizes de confusão indicam poucos erros, concentrados entre classes próximas.

- O modelo demonstrou boa capacidade de distinção entre os níveis de score de crédito.

## ✅ Conclusão

O modelo apresentou desempenho consistente e boa capacidade de generalização, sendo eficaz na classificação do score de crédito. O projeto demonstra como o uso de *Machine Learning*, por meio do algoritmo Naive Bayes, pode ser aplicado para prever o perfil de risco de clientes e apoiar decisões estratégicas no setor financeiro.
