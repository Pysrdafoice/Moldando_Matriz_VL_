# Moldando_Matriz_VL_
Introdução
para entender o código vamos entender o que é modelo de classificação

  Um modelo de classificação de dados visa realizar uma previsão com base
em ocorrências passadas. Para isso, o modelo utiliza um conjunto de dados
com entradas (indivíduos) e atributos (propriedades). Além disso, é
necessário conhecer o resultado esperado para esse conjunto de dados
(rótulos). Todas essas informações serão usadas para treinar um modelo que
será utilizado para predizer resultados esperados para novos dados que
surgirem no futuro. Ao treinar esse modelo deve-se utilizar um conjunto de
dados (não usados no treinamento) para testar o quanto o modelo acerta.
Entretanto, não basta apenas contar a quantidade de acertos que seu
modelo teve para dizer se ele é bom ou não. Dependendo do problema
estudado, métricas diferentes devem ser utilizadas para essa avaliação.
Entretanto, antes de apresentarmos essas métricas, precisamos entender
alguns conceitos para classificação binárias: as classes que os dados
preditos poderão receber.

Classes de dados preditos: VP, VN, FP e FN

Em um problema de classificação, há duas soluções possíveis: acerto ou erro.
Entretanto, para um problema de classificação binária temos ainda duas
outras classes possíveis, vamos chamá-las de classes positiva e negativa
(elas podem receber quaisquer nomes). Por exemplo, digamos que
desejamos construir um programa para predizer se irá chover. Os dias de
chuva serão nossa classe positiva. Os dias sem chuva serão nossa classe
negativa. Após construir nosso modelo, vamos usá-lo para predizer se
amanhã poderemos ir à praia. Nosso modelo poderá dizer se irá chover ou
não. No outro dia vamos a praia e observamos se choveu ou não, assim
vemos se o programa acertou ou errou. Logo, há quatro resultados possíveis

1. O programa disse que vai chover (positivo) e realmente choveu (predição
verdadeira);
2. O programa disse que vai chover (positivo), mas não choveu (predição
falsa);
3. O programa disse que não vai chover (negativo) e realmente não choveu
(predição verdadeira);
4. O programa disse que não vai chover (negativo), mas choveu (predição
falsa).
