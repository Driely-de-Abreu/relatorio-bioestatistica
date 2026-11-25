# Análise Bioestatística — Kidney Disease Dataset

## Sobre o projeto

Este projeto foi desenvolvido como parte da disciplina de Introdução à Bioestatística e tem como objetivo aplicar conceitos e métodos estatísticos na análise de um conjunto de dados relacionado a doenças renais.

A partir do conjunto de dados disponibilizado no Kaggle, serão realizadas análises exploratórias e estatísticas, buscando investigar características da população estudada e possíveis relações entre variáveis clínicas.

O projeto também busca aplicar conceitos de estatística descritiva e inferencial, incluindo representação gráfica de dados, medidas de tendência central e dispersão, intervalos de confiança e testes de hipóteses. 

## Objetivos

### Objetivo geral

Investigar a associação entre sete parâmetros relacionados à análise de urina e a classificação de doença renal crônica, utilizando métodos estatísticos para comparar os resultados entre pacientes com e sem a doença.

### Objetivos específicos

- Identificar e classificar as variáveis presentes no conjunto de dados.
- Realizar uma análise exploratória e descritiva dos dados.
- Representar graficamente as variáveis selecionadas.
- Investigar a distribuição das variáveis quantitativas.
- Aplicar métodos de inferência estatística.
- Formular e testar hipóteses estatísticas.
- Interpretar os resultados obtidos à luz dos conceitos estudados na disciplina.
- Caracterizar os sete parâmetros selecionados;
- Comparar os resultados dos exames entre os dois grupos de pacientes;
- Formular hipóteses estatísticas para cada parâmetro;
- Selecionar e aplicar testes estatísticos adequados;
- Interpretar os resultados obtidos.


## Conjunto de dados

O conjunto de dados utilizado neste projeto é o [Kidney Disease Dataset](https://www.kaggle.com/datasets/akshayksingh/kidney-disease-dataset), disponibilizado na plataforma Kaggle.

Os dados serão explorados e tratados utilizando a linguagem Python e bibliotecas voltadas à análise estatística e manipulação de dados.

A descrição detalhada das variáveis, das observações e dos procedimentos de preparação será apresentada após a exploração inicial do conjunto de dados.

## Metodologia

O desenvolvimento do projeto foi dividido em etapas de análise exploratória e análise estatística inferencial.

Inicialmente, foi realizada a exploração do conjunto de dados, com identificação das variáveis, análise de seus tipos e verificação da quantidade de valores ausentes. Também foi realizado o tratamento da variável de classificação dos pacientes, padronizando os rótulos correspondentes à presença ou ausência de doença renal crônica.

Na etapa exploratória, foram utilizadas tabelas de frequência e tabelas de contingência para investigar a distribuição das variáveis selecionadas e sua relação com a classificação dos pacientes.

Na etapa inferencial, foi aplicado o teste qui-quadrado de independência para avaliar a existência de associação entre os parâmetros analisados e a classificação dos pacientes. Antes da aplicação dos testes, foram verificadas as frequências esperadas das tabelas de contingência. Quando necessário, categorias foram agrupadas para atender aos critérios de aplicação do teste.

Foi adotado nível de significância de 5% (α = 0,05). As análises consideraram as observações disponíveis para cada variável, desconsiderando os valores ausentes.

### Notebook de análise

O desenvolvimento das análises estatísticas foi realizado no Google Colab, utilizando Python. O notebook completo, contendo os procedimentos de exploração dos dados, análises estatísticas e resultados, pode ser acessado pelo link abaixo:

[ Acessar notebook no Google Colab ](https://colab.research.google.com/drive/1f12V1FXTJq3Z957jPyoF8mMkG6Hx1tiG#scrollTo=yYMHd2V78KUg)

## Organização do repositório

Atualmente, o repositório contém o arquivo `README.md`, responsável por apresentar o projeto, seus objetivos, o conjunto de dados utilizado e a metodologia adotada.

O notebook com o desenvolvimento das análises estatísticas está disponível no Google Colab, por meio do link disponibilizado na seção anterior.

```text
relatorio-bioestatistica/
└── README.md
```

## Tecnologias utilizadas

## Autores

Carolina Jacovete dos Santos Breda
Driely Fernanda Oliveira de Abreu
