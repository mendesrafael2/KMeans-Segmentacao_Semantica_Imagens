## Introdução

A segmentação é um tipo de processamento de imagem e existem inúmeras aplicações de grande importância onde ela pode ser empregada. Por exemplo localização de objetos em imagens de satélite (estradas, florestas, etc.), sistemas de reconhecimento facial, sistemas de controle automático de trafego e várias outras aplicações. Essa segmentação pode ser realizada utilizando algoritmos de agrupamento.

Esses algoritmos buscam criar partições dentro de um conjunto de dados a partir de similaridades entre as amostras. Um dos algoritmos mais utilizados para essa aplicação é o algoritmo **K-means**. Esse algoritmo associa as amostras do conjunto de dados de entrada a um determinado grupo, onde o que determina a qual grupo essa amostra está associada, é a média da distância entre ela e esse grupo. Nesse algoritmo uma amostra pertence a somente um grupo.

Para o presente trabalho foi utilizado o algoritmo **K-means** para realizar a segmentação de um determinado connjunto de imagens.

As figuras  de \ref{foto001} a \ref{foto011} apresentam a comparação entre as fotografias de referência e as segmentadas. A segmentação semântica tenta particionar a imagem em partes semanticamente significativas, e classificar cada uma dessas partes em grupos predeterminados. Para o problema aqui tratado os grupos são os canais de cor RGB das imagens. O algoritmo determina quais "píxeis" da imagem tem maior grau de pertinência a uma determinado grupo, então o algoritmo atribui uma mesma cor a todos "píxeis" desse grupo.

<p float="left">
 <img src="https://github.com/mendesrafael2/Segmentacao_Semantica_K-means/blob/main/Imagens%20de%20Entrada/photo001.jpg" alt="some text" width=200 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao_Semantica_K-means/blob/main/Imagens%20de%20Entrada/photo001.jpg" alt="some text" width=200 height=200>
</p>

