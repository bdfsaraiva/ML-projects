# Projeto 2 de Aprendizagem Automatizada 1: Segmentação de Anúncios no Airbnb

## Objetivo

Neste projeto, o objetivo é aplicar técnicas de **clustering** e **redução de dimensionalidade** para segmentar os anúncios do Airbnb com base nas suas características. Pretende-se descobrir **grupos de anúncios semelhantes** e analisar os perfis identificados.

---

## 📄 Tarefas

### 1. Obtenção e Preparação dos Dados

* Utilizar um dataset do Airbnb (por cidade) disponível no moodle
* Sugere-se a mesma cidade do Projeto 1.

### 2. Redução de Dimensionalidade (PCA)

* Aplicar **PCA** aos dados:

  * Avaliar a variância explicada por cada componente.
  * Visualizar os dados em 2D ou 3D com os primeiros componentes principais.

### 3. Clusterização com K-Means

* Aplicar o algoritmo **K-Means** para agrupamento de anúncios.
* Determinar o número de clusters ideal:

  * Avaliar com a métrica de **silhueta**.
  * (Opcional) Usar o método **elbow**.

### 4. Análise dos Clusters

* Descrever os clusters encontrados:

  * Quais são as características médias de cada grupo?
  * Como variam atributos como `price`, `availability`, `room_type` entre os grupos?
* Tentar nomear ou caracterizar perfis típicos dos clusters (ex: "anúncios premium", "anúncios económicos")

### 5. Visualização

* Criar visualizações ilustrativas:

  * Gráficos 2D ou 3D com PCA + clusters.
  * Boxplots comparando distribuições dentro dos clusters.
  * Heatmaps de correlação, histogramas, etc.

---

## 📅 Entrega

* A entrega será feita através do Moodle da UC, até o dia **15.06.2025**, às **23:59 (hora de Lisboa)**.

**Artefactos a entregar:**

* Ficheiro notebook Python (`.ipynb`).
* Relatório em formato PDF.

---

## 📃 Conteúdo do Relatório
O Relatório deve ser uma extensão do entregue anteriormente, com as seguintes secções adicionais:

* PCA -> número de componentes, variância explicada, interpretação, entre outros
* Clusterização -> escolha de *k*, interpretação dos grupos entre outros
* Visualizações.
* Conclusões e sugestões futuras

---

## 🔹 Sugestões Opcionais (para nota extra ou exploração)

* Comparar K-Means com outro algoritmo de clustering (ex: DBSCAN, Agglomerative).
* Utilizar os clusters como feature para um modelo supervisionado.
* Aplicar PCA apenas para visualização e fazer clustering nos dados completos.

---

## Boa sorte!

Explorem, visualizem e tirem conclusões criativas! O projeto valoriza interpretação crítica e capacidade analítica.
