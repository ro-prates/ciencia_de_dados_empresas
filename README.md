# Classificador de sentimentos (relações públicas)

Entender o que as pessoas estão comentando sobre os produtos da Amazon.

É um modelo de aprendizagem supervisionada, será realizado a classificação dos comentários dos clientes, existe a coluna **feedback** que possui valores do tipo boleano, 1 para comentários positivos (nota >= 4) e 0 para comentários negativos (nota <= 3). Os valores dessa coluna foram definidos de acordo com a nota que os clientes deram para os produtos.

Uma boa ideia para fazer a classificação de comentários das redes sociais, é pegar bases de dados prontas que existem no kaggle.

**One-Hot-Encoding** serve para criar diversas colunas com todas categorias existentes e atribuir valores binários para as suas respectivas classificações. Por exemplo:

<p align="center">
  <img width="178" height="138" src="/relacoes_publicas/images/img1.png">
</p>

Ao invés de criar diversas classificações como fora feito a seguir:

<p align="center">
  <img width="179" height="141" src="/relacoes_publicas/images/img2.png">
</p>

É criado diversas colunas com valores binários:

<p align="center">
  <img width="600" height="144" src="/relacoes_publicas/images/img3.png">
</p>

#### Tokenização (Count vectorizer)

Transformar letras em números para depois prassar para o algoritmo realizar o treinamento.

O algoritmo Naive Bayes é um algoritmo de classificação baseado no teorema de Bayes.
