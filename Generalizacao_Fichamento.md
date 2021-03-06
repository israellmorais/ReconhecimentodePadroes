# Fichamento - Artigo sobre Generalização - Reconhecimento de Padrões

## Aluno: Israel de Morais Madalena

## Professor: Francisco Boldt

## Artigo: An experimental methodology to evaluate machine learning methods for fault diagnosis based on vibration signals
## Autores: Rauber, Thomas Walter; Loca, Antonio Luiz da Silva; Boldt, Francisco de Assis; Rodrigues, Alexandre Loureiros; Varejão, Flávio Miguel

### O que o artigo propõe? Qual é a novidade que ele apresenta?

O artigo propõe um procedimento para comparação do desempenho dos métodos de aprendizagem para diagnóstico de falhas com base em sinais de vibração. Apresenta uma metodologia de avaliação das abordagens de aprendizado de máquina, propondo isolar o conjunto de teste para evitar o viés de similaridade, verificar as diferenças estaticamente significativas e permitindo a reprodutibilidade.


### Como os experimentos do artigo são modelados para corroborar a hipótese proposta?

Utilização da validação cruzada aninhada, reprodutibilidade, análise estatística e evitar o vies de similaridade, segregando os dados de treinamento e teste. Desta forma, o modelamento se consiste em: divisão dos dados entre treino e teste, utilização dos dados divididos em k folds para o ajuste dos hiperparametros com a validação cruzada. A cada rodada você tem o treino, validação e teste para os ajustes dos hiperparametros. Ao final, utiliza-se uma parte separada para teste para mensuração dos resultados de todo o treinamento.

### Quais os pontos fortes do artigo?

A ideia do artigo para avaliação dos classificadores é muito importante e outro ponto forte é a ideia colocada de independente do treinamento e dos ajustes a serem feitos, deve-se manter os dados de teste separados e estes serem utilizados somente na fase de teste do classificador.

### Quais os pontos fracos dele?

Não identifiquei um ponto fraco no trabalho, porém seria legal a proposição de um algoritmo que já faz este tratamento todo proposto e gera uma tabela de classificação dos melhores resultados.


### O artigo está relacionado de alguma forma com o seu projeto de dissertação? Por quê?

O meu trabalho esta mais relacionado com problemas de regressão, o qual estamos estudando a relação entre as variáveis de corrente de motores e a vazão de uma balança integradora. Claro que, alguns pontos abordados no artigo quanto a divisão dos dados, ajuste dos parâmetros dos algoritmos, dentre outros, pode ser seguido em qualquer trabalho na área de regressão e classificação.





