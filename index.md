# Segmentação Semântica Utilizando K-means

## Introdução

A segmentação é um tipo de processamento de imagem e existem inúmeras aplicações de grande importância onde ela pode ser empregada. Por exemplo localização de objetos em imagens de satélite (estradas, florestas, etc.), sistemas de reconhecimento facial, sistemas de controle automático de trafego e várias outras aplicações. Essa segmentação pode ser realizada utilizando algoritmos de agrupamento.

Esses algoritmos buscam criar partições dentro de um conjunto de dados a partir de similaridades entre as amostras. Um dos algoritmos mais utilizados para essa aplicação é o algoritmo **K-means**. Esse algoritmo associa as amostras do conjunto de dados de entrada a um determinado grupo, onde o que determina a qual grupo essa amostra está associada, é a média da distância entre ela e esse grupo. Nesse algoritmo uma amostra pertence a somente um grupo.

Para o presente trabalho foi utilizado o algoritmo **K-means** para realizar a segmentação de um determinado connjunto de imagens.

As figuras  de 1 a 11 apresentam a comparação entre as fotografias de referência e as segmentadas. A segmentação semântica tenta particionar a imagem em partes semanticamente significativas, e classificar cada uma dessas partes em grupos predeterminados. Para o problema aqui tratado os grupos são os canais de cor RGB das imagens. O algoritmo determina quais "píxeis" da imagem tem maior grau de pertinência a uma determinado grupo, então o algoritmo atribui uma mesma cor a todos "píxeis" desse grupo.

 <img  src="https://github.com/mendesrafael2/SegmentacaoSemanticaKmeans/blob/main/imgs_in/photo001.jpg" alt="some text" width=300 height=200>



<p align="center">
 <img  src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_in/photo001.jpg" alt="some text" width=300 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_out/photo001out.jpg" alt="some text" width=300 height=200>
 <br> <b>Figura 1. Foto 1</b>
</p> 

<p align="center">
 <img  src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_in/photo002.jpg" alt="some text" width=300 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_out/photo002out.jpg" alt="some text" width=300 height=200>
 <br> <b>Figura2. Foto 2</b>
</p>
<p align="center">
 <img  src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_in/photo003.jpg" alt="some text" width=300 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_out/photo003out.jpg" alt="some text" width=300 height=200>
 <br> <b>Figura3. Foto 3</b>
</p>

<p align="center">
 <img  src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_in/photo004.jpg" alt="some text" width=300 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_out/photo004out.jpg" alt="some text" width=300 height=200>
 <br> <b>Figura4. Foto 4</b>
</p>

<p align="center">
 <img  src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_in/photo005.jpg" alt="some text" width=300 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_out/photo005out.jpg" alt="some text" width=300 height=200>
 <br> <b>Figura5. Foto 5</b>
</p>

<p align="center">
 <img  src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_in/photo006.jpg" alt="some text" width=300 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_out/photo006out.jpg" alt="some text" width=300 height=200>
 <br> <b>Figura6. Foto 6</b>
</p>

<p align="center">
 <img  src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_in/photo007.jpg" alt="some text" width=300 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_out/photo007out.jpg" alt="some text" width=300 height=200>
 <br> <b>Figura7. Foto 7</b>
</p>

<p align="center">
 <img  src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_in/photo008.jpg" alt="some text" width=300 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_out/photo008out.jpg" alt="some text" width=300 height=200>
 <br> <b>Figura8. Foto 8</b>
</p>

<p align="center">
 <img  src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_in/photo009.jpg" alt="some text" width=300 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_out/photo009out.jpg" alt="some text" width=300 height=200>
 <br> <b>Figura9. Foto 9</b>
</p>

<p align="center">
 <img  src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_in/photo010.jpg" alt="some text" width=300 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_out/photo010out.jpg" alt="some text" width=300 height=200>
 <br> <b>Figura10. Foto 10</b>
</p>

<p align="center">
 <img  src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_in/photo011.jpg" alt="some text" width=300 height=200>
 <img src="https://github.com/mendesrafael2/Segmentacao-Semantica-K-means/blob/main/imgs_out/photo011out.jpg" alt="some text" width=300 height=200>
 <br> <b>Figura11. Foto 11</b>
</p>





 


