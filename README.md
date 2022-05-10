p align = "justify">1. Conversão RGB-YIQ-RGB (cuidado com os limites de R, G e B na volta!).</p>
<p align = "justify">2. Negativo. Duas formas de aplicação devem ser testadas: em RGB (banda a banda) e 
na banda Y, com posterior conversão para RGB.</p>
<p align = "justify">3. Correlação m x n sobre R, G e B, com offset, e filtro e pivô definidos em um arquivo
(txt) a parte. Testar com filtros Média e Sobel horizontal e vertical, e explicar os
resultados. Para visualização do resultado do Sobel, utilize valor absoluto seguido por
expansão de histograma para [0, 255].</p>
<p align = "justify">4. Filtro mediana m x n, com m e n ímpares, sobre a banda Y do YIQ.</p>
<p align = "justify">5. Reproduza o exemplo em <br>
<a href="https://la.mathworks.com/help/images/ref/normxcorr2.html?lang=en">
https://la.mathworks.com/help/images/ref/normxcorr2.html?lang=en</a>, com as 
imagens woman.png e woman_eye.png. Após localizar a região de correlação
máxima, repita a busca excluindo essa região, de modo a localizar a segunda região
mais correlacionada com a máscara. Você pode utilizar toda a funcionalidade da
linguagem de programação de sua escolha, incluindo bibliotecas avançadas. Para
visualização, utilize valor absoluto seguido por expansão de histograma para [0, 255]</p><br>
