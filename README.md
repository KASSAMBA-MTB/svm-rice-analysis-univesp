# Classificação de Espécies de Arroz com SVM

Este projeto utiliza o algoritmo **Support Vector Machine (SVM)** para classificar dois tipos de arroz (Jasmine e Gonen) com base em suas características morfológicas.

## 📋 Objetivos do Exercício
1. **Classificação Multivariada**: Treinamento utilizando todos os atributos do dataset (exceto ID).
2. **Pré-processamento**: Divisão de treino/teste (90/10) e escalonamento de atributos (*StandardScaler*).
3. **Análise de Kernels**: Comparação entre os kernels:
   - Polinomial (com todos os atributos)
   - Linear, Polinomial e Sigmoidal (utilizando apenas 2 atributos para visualização).
4. **Visualização**: Plotagem das fronteiras de decisão em 2D.

## 📊 Atributos Analisados
- **Área, Perímetro, Redondeza, Eixos (Maior/Menor)**, entre outros.
- **Classe Alvo**: `1` (Jasmine) e `0` (Gonen).

## 🚀 Tecnologias Utilizadas
- Python
- Pandas & NumPy
- Scikit-learn (SVC, accuracy_score, StandardScaler)
- Matplotlib (Visualização de fronteiras)

## 📈 Resultados
O melhor desempenho observado foi obtido com o kernel **[INSIRA AQUI O KERNEL QUE DEU MAIOR ACURÁCIA, ex: Polinomial com todos os atributos]**, atingindo uma acurácia de **[X]%**.
