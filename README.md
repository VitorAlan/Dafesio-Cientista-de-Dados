# Dafesio-Cientista-de-Dados


1. **Análise descritiva dos dados (EDA)**
  1. Construa uma análise descritiva extraindo conhecimento das variáveis e apresentando quais insights podem ser obtidos a partir delas;
  2. Mostre-nos um caminho para selecionar graficamente as variáveis mais ou menos importantes para cada problema, como elas se relacionam e porquê.
  3. Em cada problema descreva quais outras técnicas poderiam ser aplicadas e porquê você não as escolheu.
  4. Utilize os dados: eda_receitas_data.zip (receitas.json);

2. **Teste técnico de modelagem**
  Nessa parte, será necessário implementar um algoritmo de acordo com o paradigma do problema. Cada problema tem um conjunto de métricas que são requeridas. A variável alvo sempre será a coluna de nome “target”, exceto para os problemas não-supervisionados.
  1. Construa um classificador e identifique quais variáveis exercem maior impacto sobre o “target” e informe o porquê interpretando os resultados obtidos. 
    1. métricas: precision, recall e F1-score;
    2. dados: classification_data.zip;
  2. Selecione um sku (produto) e realize uma previsão da demanda do mesmo nos próximos 4 intervalos de tempo de sua escolha (dia, semana, mês, etc) 
    1. métricas: rmse, mape;
    2. dados: time_series_data.xlsx;
  3. Construa um regressor e identifique quais variáveis exercem maior impacto sobre o “target” e informe o porquê interpretando os resultados obtidos. 
    1. métricas: RMSE, R2 e cor(target_observado, target_predito);
    2. dados: regression_data.zip.
