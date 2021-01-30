# santander-customer-satisfaction

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/feliperpv/santander-customer-satisfaction.svg">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/feliperpv/santander-customer-satisfaction.svg">

  <a href="https://www.codacy.com/app/feliperpv/santander-customer-satisfaction?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=feliperpv/santander-customer-satisfaction&amp;utm_campaign=Badge_Grade">
    <img alt="Codacy grade" src="https://img.shields.io/codacy/grade/04db4b43120b4d05b9b39c9d2da97300.svg">
  </a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/feliperpv/santander-customer-satisfaction.svg">
  <a href="https://github.com/feliperpv/santander-customer-satisfaction/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/feliperpv/santander-customer-satisfaction.svg">
  </a>

  <a href="https://github.com/feliperpv/santander-customer-satisfaction/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/feliperpv/santander-customer-satisfaction.svg">
  </a>

  <img alt="GitHub" src="https://img.shields.io/github/license/feliperpv/santander-customer-satisfaction.svg">
</p>

Este é um projeto desenvolvido na Formação Cientista de Dados na [Data Science Academy](https://www.datascienceacademy.com.br/), no curso Big Data Real-Time Analytics com Python e Spark.

## Descrição do Projeto

A satisfação do cliente é uma medida fundamental de sucesso. Clientes insatisfeitos cancelam seus serviços e raramente expressam sua insatisfação antes de sair. Clientes satisfeitos, por outro lado, se tornam defensores da marca!

O Banco Santander deseja identificar clientes insatisfeitos no início do relacionamento. Isso permitiria que o Santander adotasse medidas proativas para melhorar a felicidade de um cliente antes que seja tarde demais.

Neste projeto de aprendizado de máquina, você trabalhará com centenas de recursos anônimos para prever se um cliente está satisfeito ou insatisfeito com sua experiência bancária.

**PROBLEMA**: Prever a satisfação do cliente do banco santander em relação a sua experiência bancária

**META**: Acurácia igual ou supereior a 70%

**DATASET**: [https://www.kaggle.com/c/santander-customer-satisfaction/overview](https://www.kaggle.com/c/santander-customer-satisfaction/overview)

## Descrição da Resolução

- Utilizou-se **Python 3** com **Apache Spark 2.4.2**

- Arquivo [`balance-dataset.ipynb`](https://github.com/feliperpv/santander-customer-satisfaction/blob/master/balance-dataset.ipynb) é responsável por balancear as classes do arquivo `data/train.csv`, por meio do método SMOTE, gerando o arquivo `data/clientes_smote.csv`.

- Arquivo [`santander-customer-satisfaction.ipynb`](https://github.com/feliperpv/santander-customer-satisfaction/blob/master/santander-customer-satisfaction.ipynb) contém a resolução do problema, desde a limpeza dos dados até a avaliação do modelo de ML.

## Resultados Obtidos

- O modelo apresentou uma acurácia de 89,07%, sendo acima da métrica estabelecida inicialmente.

- O modelo previu com uma taxa de 88,25% de acerto os clientes insatisfeitos, sendo este o objetivo principal do projeto.

- O modelo previu com uma taxa de 89,89% os clientes satisfeitos.

### Sugestões de melhorias futuras
- Aprofundar a análise exploratória.
- Aprofundar a limpeza dos dados.
- Realizar tuning (otimização) dos hiperparâmetros do modelo
