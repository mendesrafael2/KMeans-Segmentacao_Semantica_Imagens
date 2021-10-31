##Introdução

A segmentação é um tipo de processamento de imagem e existem inúmeras aplicações de grande importância onde ela pode ser empregada. Por exemplo localização de objetos em imagens de satélite (estradas, florestas, etc.), sistemas de reconhecimento facial, sistemas de controle automático de trafego e várias outras aplicações. Essa segmentação pode ser realizada utilizando algoritmos de agrupamento.

Esses algoritmos buscam criar partições dentro de um conjunto de dados a partir de similaridades entre as amostras. Um dos algoritmos mais utilizados para essa aplicação é o algoritmo **K-MEANS**.

O algoritmo **K-MEANS** associa as amostras do conjunto de dados de entrada a um determinado grupo, onde o que determina a qual grupo essa amostra está associada, é a média da distância entre ela e esse grupo. Nesse algoritmo uma amostra pertence a somente um grupo.

Para o presente trabalho foi utilizado o algoritmo \textit{Fuzzy C-MEANS}. Esse algoritmo é muito similar ao algoritmo \textit{K-MEANS} a diferença está na forma como os dados são agrupados. Para algoritmo \textit{K-MEANS} existe uma matriz de partições onde cada amostra está associada a somente 1 grupo. Já para o algoritmo \textit{Fuzzy C-MEANS} existe uma matriz de similaridade onde as amostras estão associados aos grupos com um grau de pertinência. Uma mesma amostra pode está associado a vários grupos, com graus de pertinência diferentes.
