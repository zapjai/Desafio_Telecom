# Alura Data Science Challenge

Neste Repositório está o meu projeto desenvolvido durante a participação no Challenge de Data Scienda promovido pela Alura. A Alura é uma plataforma online brasileira de cursos de tecnologia.

O objetivo desse Challenge é aprofundar os conhecimentos dos alunos na área de Data Science, por meio de desafios práticos.

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Alura Data Science Challenge**
| :label: Tecnologias | Python
| :rocket: URL         | -
| :fire: Desafio     | [https://www.alura.com.br/challenges/data-science/](https://cursos.alura.com.br/course/challenge-telecom-x-analise-evasao-clientes/task/193249)

---

## Sobre o Challenge

**Empresa Solicitante:** Alura Voz, operadora de telecomunicações.

**Objetivo:** Reduzir o Churn Rate, isto é, a Taxa de Evasão de Clientes. 

**Dados disponibilizados:** Foi disponibilizado um conjuto de dados no formato json, junto com um arquivo contendo o dicionário desses dados

**Entrega:** Ao final de cada semana, será entregue um Notebook Python, desenvolvido no VSCODE, com  o código e análises efetuados para a resolução das atividades solicitadas pela empresa. Adicionalmente, poderão ser disponibilizados  arquivos CSV com resultados obtidos, bem como imagens de gráficos gerados. Tanto os Notebooks quanto os arquivos adicionais ficarão disponíveis no [Repositório criado para o projeto no GitHub](https://github.com/zapjai/Desafio_Telecom).

**Linguagem:** Python foi a linguagem utilizada no desenvolvimento, utilizando Jupyer Notebooks para apresentar os resultados. Os principais pacotes utilizados foram:

**Bibliotecas utilizadas:**
- pandas
- numpy
- plotly
- seaborn
- scikit-learn
- imbalanced-learn

---

## Semana 1

A primeira semana é dedicada a extração dos dados em formato json para o python, para posterior transformação/limpeza dos dados, seguido da carregamento dos dados para um arquivo no formato csv. Ou seja, o processo de ETL dos dados.

Nesta etapa também foi realizada a tradução dos dados para o Português.

O resultado final foi exportado para um [arquivo CSV](https://github.com/zapjai/Desafio_Telecom/blob/main/1%20-%20Limpeza%20de%20dados/DadosLimpos.csv).

Todas as atividades executadas estão documentadas neste [notebook](https://github.com/zapjai/Desafio_Telecom/blob/main/1%20-%20Limpeza%20de%20dados/Limpdf.ipynb).

---

## Semana 2

A segunda semana foi dedicado a exploração dos dados por meio de análises visuais e descrição das conclusões/hipóteses geradas pelos gráficos e outras análises. A variável target do projeto é o churn rate (taxa de evasão). 

Nessa semana também foi possível aprender na prática como utilizar a biblioteca Plotly para criar gráficos.

Todas as atividades executadas estão documentadas neste [notebook](https://github.com/zapjai/Desafio_Telecom/blob/main/2%20-%20An%C3%A1lise%20explorat%C3%B3ria%20e%20Visualiza%C3%A7%C3%A3o/ExplorandoDados.ipynb).

---

## Semana 3

Na terceira semana, entrei na área de Machine Learning, avaliando e aplicando o balanceamento na variável target, aplicando 4 modelos de Machine Learning, e 1 dummy classifier. Para depois escolher e otimizar o melhor modelo.

Essa foi a etapa de conclusão do projeto onde pude validar as hipóteses e sugerir ações para redução da taxa de evasão de clientes.

Todas as atividades executadas estão documentadas no [notebook](https://github.com/zapjai/Desafio_Telecom/blob/main/3%20-%20Criando%20Modelos%20de%20ML/MachineLearning.ipynb).

---
