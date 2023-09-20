# Kaggle-Data-Sets

Practical exercises on data visualization using datasets from the website  https://www.kaggle.com/

# Projeto 1 -- Top 50 Bestselling Novels 2009-2021 of Amazon(Amazon top50_books.ipynb)

Link to the dataset: https://www.kaggle.com/datasets/zwl1234/top-50-bestselling-novels-20092021-of-amazon

Exploratory Data Analysis
This repository contains an exploratory data analysis of a dataset aimed at extracting relevant information to provide valuable insights for the company's decision-making.

Objective
The objective of this analysis is to explore the dataset and uncover meaningful insights that can contribute to the company's growth and success.

Key Findings
During the exploratory data analysis, several key findings were discovered:

1) Non-fiction books have a significant presence in total sales.
2) Non-fiction customers show a higher willingness to pay premium prices for books compared to fiction customers.
3) There has been a noticeable increase in the number of customer reviews, and the overall rating of these reviews has improved.
4) On average, customers are willing to spend $11 on books.
5) These findings provide valuable insights that can guide strategic decisions and help the company enhance its offerings and customer experience.

# Projeto 2 -- Housing Price Competition

Este exercício é baseado na competição "House Prices: Advanced Regression Techniques" do Kaggle, em que o objetivo é prever o preço final (target) de uma casa na cidade de Ames, Iowa, com base nas vendas ocorridas entre Janeiro de 2006 e Julho de 2010, a partir de 79 variáveis explanatórias (features), tanto categóricas quando numéricas. É um problema de aprendizagem supervisionada, em que desejamos, baseado em um conjunto de dados de treinamento, que determinado modelo possa aprender a relação entre as features e o target, e assim ser capaz de prever o preço de venda de casas nesta cidade para novos dados. E, como a variável a ser prevista é contínua, nos deparamos com um problema de regressão. Disponíveis em [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

Link para acesso: [Estatística Descritiva -- Housing Prices Competition for Kaggle Learn Users](https://github.com/valeriolonde/Kaggle-Data-Visualization/blob/main/Housing%20Price%20Competition/Estat%C3%ADstica%20Descritiva%20--%20Housing%20Prices%20Competition%20for%20Kaggle%20Learn%20Users.ipynb)

Nessa primeira parte da análise, exploramos as estatísticas descritivas dos dados disponíveis. Realizamos uma análise detalhada das variáveis numéricas e categóricas em relação aos preços de venda das casas. Para isso, criamos gráficos que nos forneceram insights valiosos que serão úteis na etapa de modelagem.

Ao examinar as variáveis numéricas, observamos sua distribuição e relação com os preços de venda. Isso nos permitiu identificar possíveis padrões e tendências que podem influenciar o valor final das casas. Também exploramos as variáveis categóricas e sua relação com os preços de venda, buscando entender se certas características específicas têm um impacto significativo nos preços.

Essa análise nos ajudará a ter uma compreensão mais completa dos dados e nos orientará na próxima etapa do processo, que é a modelagem dos preços de venda das casas.

Link para acesso: [Modelagem](https://github.com/valeriolonde/Data-science-Kaggle/blob/main/Housing%20Price%20Competition/Engenharia%20de%20Features%20e%20Modelagem%20--%20Housing%20Prices.ipynb)

Nessa segunda parte, exploramos os principais métodos básicos de machine learning, lasso, OLS, random forest e gradient boosting. Além disso, fizemos análises e tratamentos para variáveis ausentes e outras questões da base de dados. 

# Projeto 3 -- Restaurant Revenue Prediction

Este exercício é baseado na competição "Restaurant Revenue Prediction" do Kaggle, em que o objetivo é prever possíveis receitas de outros restaurantes com base em suas características e estimativas. A variável a ser prevista é contínua e a base de dados pode ser baixada em [Restaurant Revenue Prediction](https://www.kaggle.com/c/restaurant-revenue-prediction).

Na primeira parte, fizemos uma estatística descritiva para analisar as variáveis com relação ao feature. Na segunda parte fizemos engenharia de feature e modelagem. A análise também pode ser vista em [Restaurant Revenue Prediction](http://prorum.com/?qa=8116/exercicio-machine-learning-restaurant-revenue-prediction#a8227). Utilizamos vários métodos tais como random forest, linear regression, gradient boosting e decision tree. Depois escolhemos o modelo com menor erro quadrado médio.  

# Projeto 4 -- Automobile Data Sets

Este exercício é baseado na base de dados presente em [AUTO DATA SET](https://www.kaggle.com/datasets/toramky/automobile-dataset). No caderno [Estatísticas descritivas](https://github.com/valeriolonde/Kaggle-Data-Sets/blob/main/Automobile%20DataSet/Estat%C3%ADsticas%20descritivas%20--%20data.set.ipynb) fiz análises das relações entre a variável mpg -- que é a quantidade de milhas por galão, que é uma medida de eficiência de combustível em veículos automotores, especialmente carros --, com as outras variáveis quantitativas e qualitativas com o objetivo de buscar bons preditores dessa variável. 

Já o exercício desenvolvido em [OLS AUTO DATA SET](https://github.com/valeriolonde/Kaggle-Data-Sets/blob/main/Automobile%20DataSet/auto_OLS.ipynb) é uma aplicação de OLS no contexto dessa nova base de dados. Foi feita uma regressão para avaliar quais variáveis impactam milhas por galão de um carro e depois alguns testes de normalização dos resiúdos e homocedasticidade foram feitos. 