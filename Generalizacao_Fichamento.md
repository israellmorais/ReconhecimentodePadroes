# Fichamento - Artigo sobre Generalização - Reconhecimento de Padrões

## Aluno: Israel de Morais Madalena

## Professor: Francisco Boldt

## Artigo: An experimental methodology to evaluate machine learning methods for fault diagnosis based on vibration signals
## Autores: Rauber, Thomas Walter; Loca, Antonio Luiz da Silva; Boldt, Francisco de Assis; Rodrigues, Alexandre Loureiros; Varejão, Flávio Miguel

### O que o artigo propõe? Qual é a novidade que ele apresenta?

O artigo apresenta uma metodologia experimental para avaliar métodos de aprendizado de máquina para diagnóstico de falhas com base em sinais de vibração. 
Expõe um procedimento sistemático para comparar quatro classificadores distintos com base em tarefas de generalização como: K-Nearest-Neighbor, 
Support Vector Machine, Random Forest and One-Dimensional Convolutional Neural Network. O trabalho propõe uma metodologia experimental de avaliação do 
aprendizado de máquina para diagnóstico de falhas com base nos sinais de vibração, concentrando nas técnicas de aprendizado de máquina que usam os sinais 
para treinar e testar os classificadores para identificação de falhas, isolando o conjunto de teste, evitando a similaridade e verificando diferenças 
estatisticamente significativas e permitindo a reprodutibilidade. O artigo propõe também um estudo com um conjunto de dados sintéticos que sugerem uma 
abordagem diferente de validação cruzada. Além disso, a identificação de problemas comuns de trabalhos de investigação na área do diagnóstico de falhas.

### Como os experimentos do artigo são modelados para corroborar a hipótese proposta?

O artigo trata a reprodutibilidade para evitar o viés de similaridade e verifica a significância estatística da diferença nos resultados. Quanto a 
reprodutibilidade se baseia em uma boa documentação, inclusive na especificação dos parâmetros dos algoritmos utilizados para que haja a possibilidade 
de comparação dos resultados. Já para tratar o viés de similaridade, coloca que deve-se garantir que a divisão dos folds para treinamento e teste não 
permita que os padrões extraídos de um arquivo estejam presentes em mais de um fold e também através do ajuste dos hiper parâmetros, mantendo as folds 
estratificadas e com tamanho equivalente. Em termos estatísticos, os experimentos do artigo se baseiam na diferença dos resultados por meio de destes 
de hipóteses estatísticas. A proposta é utilizar a validação cruzada aninhada como método de avaliação. Salienta-se que o propósito do artigo não é 
criar algo novo, mas combinar os diferentes algoritmos e a validação cruzada para obter resultados não viciados.

### Quais os pontos fortes do artigo?

O artigo aborda sobre as vantagens da utilização das técnicas de avaliação de desempenho da aprendizagem supervisionada, mostrando como os hiper parâmetros 
devem ser definidos para que as soluções sejam diferentes um da outra, conseguindo assim bons resultados através da validação cruzada. Outro ponto a 
evidenciar é a divisão dos dados em treino e teste, de forma a não ter uma solução viciada. Considero que a automatização na validação cruzada k-fold 
aninhada com loops interno e externo seja uma das partes de destaque, visto que os hiper parâmetros são definidos de forma automática na execução do loop 
interno.

### Quais os pontos fracos dele?

Vejo que quando aborda sobre a questão de evitar a similaridade, acabou colocando quee em determinado modo de aquisição dos dados da máquina 
por uma única sessão de aquisição, não terá como separar os padrões de diferentes fontes de aquisição nos subconjuntos de treinamento e teste. Vejo que 
poderia ter colocado algumas opções a se fazer para tratar estes casos.

### O artigo está relacionado de alguma forma com o seu projeto de dissertação? Por quê?

O artigo se relaciona sim com o projeto de dissertação devido a metodologia abordada, os algoritmos de classificação utilizados para comparação e a validação
cruzada. Se assemelham também pela característica abordada. Enquanto o artigo trata de diagnóstico de falhas a partir de sinais de vibração, o meu projeto de 
dissertação aborda a estimação de fluxo dado valores característicos de corrente. Os algoritmos K-Nearest-Neighbor, Support Vector Machine, Random Forest and 
One-Dimensional Convolutional Neural Network podem também ser utilizados no projeto de dissertação a fim de determinar qual algoritmo obterá uma precisão maior.



