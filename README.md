# Reconhecimento de Dígitos Manuscritos usando Redes Neurais MLP

## Visão Geral

Este notebook apresenta uma implementação prática de Redes Neurais Perceptron Multicamadas (MLP) para o reconhecimento de dígitos manuscritos. O projeto explora a otimização da arquitetura MLP, focando no impacto de variações no tamanho da camada oculta, algoritmos de descida de gradiente e taxas de aprendizado.

## Estrutura do Projeto

- `data_tp1`: O conjunto de dados MNIST contendo 5000 entradas de dígitos manuscritos.
- `notebook.ipynb`: O notebook Jupyter implementando a rede neural MLP e analisando os resultados.
- `README.md`: Este documento fornecendo uma visão geral do projeto.

## Requisitos

- Python 3.x
- Jupyter Notebook
- Bibliotecas Python necessárias (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)

## Detalhes da Implementação

A implementação envolve:

1. **Exploração dos Dados:**
   - Importação e exploração do conjunto de dados MNIST.
   - Pré-processamento e visualização dos dados.

2. **Construção da Rede Neural:**
   - Implementação de uma rede neural MLP com três camadas (entrada, oculta, saída).
   - Utilização da função de ativação sigmoidal para não linearidade.
   - Definição da função de perda para treinamento.

3. **Ajuste de Hiperparâmetros:**
   - Variação do número de unidades na camada oculta (25, 50, 100).
   - Comparação de algoritmos de descida de gradiente (Batch, Stochastic, Mini-Batch).
   - Exploração de diferentes taxas de aprendizado (0.5, 1, 10).

4. **Treinamento e Avaliação do Modelo:**
   - Treinamento de vários modelos com diferentes configurações.
   - Avaliação de modelos nos conjuntos de treino e teste.
   - Análise de matrizes de confusão e curvas de aprendizado.

5. **Resultados e Conclusão:**
   - Discussão do impacto do tamanho da camada oculta, algoritmos de descida de gradiente e taxas de aprendizado.
   - Conclusões com base no desempenho do modelo e experimentação.

## Uso

1. Instale as bibliotecas necessárias:

   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```
