# Projeto 1 de Aprendizagem Automatizada 1: Previsão de Sucesso de Anúncios no Airbnb

## Objetivo

Utilizando dados públicos da plataforma Airbnb, o objetivo deste projeto é construir e comparar diferentes modelos de
Machine Learning para prever o **sucesso de um anúncio** com base em suas características.

O "sucesso" será definido como:

> 🔶 **recomendado** (`target = 1`) se apresentar **boa avaliação média** (ex: `review_scores_rating` ≥ Quartile 3
(`review_scores_rating`)) **e** **um número significativo de reviews** (ex: `number_of_reviews` ≥ Quartile 2 (
`number_of_reviews`)). Caso contrário, será considerado **não recomendado** (`target = 0`).

---

## 📜 Tarefas

### 1. Obtenção dos Dados

- Usar um dos datasets públicos do Airbnb, disponíveis por cidade no repositório.
- Escolher uma cidade (Cada estudante deverá escolher uma cidade distinta).
- Fazer o download e leitura do dataset.

---

### 2. Preparação dos Dados

- Realizar uma análise exploratória inicial.
- Limpar e transformar os dados:
    - Tratar valores em falta.
    - Converter variáveis categóricas.
    - Normalizar ou padronizar variáveis numéricas.
    - Entro outros...
- Selecionar atributos relevantes para os modelos.
- Criar a variável alvo (`target`) com base na fórmula de recomendação mencionada acima.

---

### 3. Treino de Modelos

- Separar os dados em treino/teste (ou usar _cross validation_).
- Treinar **pelo menos três modelos** de ML, lecionados ao longo do semestre:
    - Regressão linear
    - Regressão Logística
    - K-Nearest Neighbors (KNN)
    - Nearest Centroid
    - Decision Tree

- Nota: Podem ser utilizados outros algoritmos que estejam previsto a ser lecionados ao longo da UC (ver aula 1 no
  Moodle), desde que devidamente justificados no relatório que acompanha este trabalho.

---

### 4. Avaliação e Comparação

- Utilizar métricas adequadas de classificação:
    - _Accuracy_
    - _Precision_ (opcional)
    - _Recall_ (opcional)
    - _F1-score_ (opcional)
- Comparar o desempenho dos modelos.
- Discutir qual modelo parece mais adequado, justificaando com base nos resultados e nos dados.

---

### 5. Relatório

Cada estudante deve entregar um pequeno relatório (2 a 4 páginas), incluindo:

- Descrição da escolha da cidade/dataset.
- Etapas de preparação dos dados.
- Justificação para escolha dos modelos selecionados.
- Apresentação das métricas e comparação dos resultados.
- Conclusão com reflexões e possíveis melhorias.

---

## Notas Finais

- Não é necessário utilizar **todos** os modelos estudados, devem ser utilizados pelo menos **três distintos**.
- O uso de visualizações no notebook (ex: gráficos de dispersão, histogramas, heatmaps) é altamente recomendado.
- Podem e devem utilizar bibliotecas para leitura, manipulação e criação de modelos de dados (
  Ex: [pandas](https://pandas.pydata.org/docs/index.html), [scikit-learn](https://scikit-learn.org/stable/), entre outras).

---

## Entrega
A entrega realizar-se-à via ficheiro `.zip` no Moodle da UC, no dia 02.05.2025, ás 23:59 (hora de Lisboa).

Os artefactos a entregar serão:
- Ficheiro python notebook (.ipynb)
- Relatório em formato PDF

<br>



Bom trabalho! 🚀
