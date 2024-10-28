# Projeto: Classificação de Concessão de Empréstimo usando Árvore de Decisão

## Descrição do Projeto

Este projeto utiliza um algoritmo de **Árvore de Decisão** para prever se um indivíduo será aprovado ou não para um empréstimo, com base em um conjunto de características fornecidas. A abordagem utiliza técnicas de aprendizado supervisionado para construir um modelo de classificação que pode ser treinado com dados históricos e gerar previsões para novos clientes.

## Funcionalidades

- **Treinamento do Modelo**: Treinamento de um modelo de árvore de decisão com um conjunto de dados de concessão de empréstimos.
- **Previsão**: O modelo é capaz de prever a concessão ou não de empréstimos com base nas características dos candidatos.
- **Avaliação de Desempenho**: Cálculo de métricas como acurácia, precisão, recall e F1 para avaliar o desempenho do modelo.
- **Visualização da Árvore de Decisão**: Geração e visualização gráfica da árvore de decisão treinada, ajudando a interpretar o processo de decisão.

## Requisitos

Para executar este projeto, você precisará das seguintes bibliotecas Python:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `graphviz` (opcional, para visualização da árvore de decisão)

## Descrição da Base de Dados

O conjunto de dados utilizado contém informações sobre indivíduos que solicitaram empréstimos. As variáveis incluem:

- **Empregado**: Indica se a pessoa está empregada ou não.
- **Devedor**: Se a pessoa já possui dívidas existentes.
- **Salário acima de 5SM**: Se o salário da pessoa está acima de cinco salários mínimos.
- **Empréstimo**: O alvo da classificação, indicando se o empréstimo foi aprovado ou não.

Essas variáveis são usadas como entrada para o modelo de árvore de decisão, que tenta prever o status do empréstimo com base nesses fatores.

## Resultados

Os resultados do modelo de árvore de decisão incluem:

- **Acurácia**: Avalia a porcentagem de previsões corretas do modelo.
- **Precisão e Recall**: Métricas de avaliação que analisam o equilíbrio entre falsos positivos e falsos negativos.
- **Matriz de Confusão**: Visualiza o desempenho do modelo ao classificar corretamente e incorretamente as amostras.
- **Visualização da Árvore de Decisão**: Gráfico ilustrando a árvore de decisão gerada após o treinamento, mostrando como as variáveis influenciam nas decisões.

Esses resultados ajudam a entender os fatores que influenciam a concessão de empréstimos e a avaliar o desempenho do modelo para aplicações futuras.

## Contato

Se você tiver dúvidas ou sugestões, entre em contato por [vitor13muniz09@gmail.com](mailto:vitor13muniz09@gmail.com).
