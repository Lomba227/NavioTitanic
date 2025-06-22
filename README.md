# NavioTitanic
Repositório criado para a competição do Kaggle sobre a previsão de sobreviventes do navio do Titanic

Primeiro foi feito o tratamento dos dados, substituindo todos os valores nulos, transformando as colunas categóricas importantes para a previsaão em numéricas e descartando as colunas categóricas que não eram importantes

Após o tratamento, foi feita divisão entre os dados de treino e os dados de teste, e a aplicação de três modelos (Árvore de decisão, KNN e regressão logística).

Foi feita a comparação da acurácia (métrica pedida pelo desafio) e analisado que a regressão logística foi o modelo que conseguiu a melhor acurácia (81,3%)

Como última análise, foi feita uma normalização dos dados para ver se a acurácia melhorava, e o único caso em que isso aconteceu foi com o KNN, saindo de 71,5% de acurácia e indo para 78,3%. Contudo, a acurácia da regressão logística normalizada ainda era maior que do KNN, então optei por usar a regressão logística normalizada para os dados de teste

Por fim, o mesmo trabalho foi feito com a base de teste, e o resultado obtido foi de 76,8%
