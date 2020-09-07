# SVG_chart 
Esse projeto consiste em cria gráficos em ".svg" sem uso de bibliotecas com os dados coletados sobre Covid-19, anteriormente, no projeto coletor de dados.

O algoritimo consiste em cinco arquivos, um para cada país. Cada arquivo é composto por cinco funções. A primeira é responsável por receber os dados, criar 4 listas e distribuí-los dentre estas listas. Retorna os dados em forma de dicionário.

A segunda função, arredonda o número máximo possível nos eixos para o a dezena de milhar completa mais próxima.

A terceira função é usada para traçar o gráfico. A príncipio, variáveis que desenham o eixo x e y e demais detalhes do gráfico. Posteriormente, desenhamos as linhas do gráfico. Os dados anteriormente recebidos nas listas juntos a um indice são recebidos outra vez dentro da propriedade polyline para desenhar a linha representando dados.

As funções seguintes controlam os marcadores do gráfico.

# SVG_chart

This project is made to create charts in *.svg* with no libraries using data about Covid-19 colected previously in Covid-19 data collector project. This algorithm consists in five archives, one for each country. Each archieve is composed for five functions. The first function is responsable for receiving data, creating four lists and delivering the data between them., returning the data in a dictionary format.

The second function is made to round the maximum possible number in the axies to the nearest complete ten thousands.

The third function is used to plot the chart. At first, variables that draw the x and y axies and more deatails in the chart. Thereafter, it's drawn the lines. The data previously received in a list next to a index are received again inside the polyline property to draw a line represeting those data.

The following functions controll chart's marks.
