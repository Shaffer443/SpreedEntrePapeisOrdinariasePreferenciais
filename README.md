# Spreed de ações entre papeis Ordinárias e Preferenciais

Utilizando o Python para obter o spreed entre ações ordinárias e preferenciais.

Importando algumas libs e capturar os dados dos pares PETR4/PETR3, depois BBDC4/BBDC3 e CMIG4/CMIG3 (01/2022 e 09/2022)

#Instalando e importando bibliotecas usadas

- !pip install investpy
- import investpy as inv
- import plotly.express as px

Calcular essa métrica é importante pois nos dá uma noção de como os papéis estão esticados com relação ao seu par.

Para o calculo de uma razão, simplesmente dividimos o preço de uma pela outra e alocamos o resultado numa nova coluna (imagem)

Quando a razão se estica muito (se distancia da média), maiores são as chances de voltar à média.

Vamos criar um plot utilizando a biblioteca Plotly para entender como essa razão se comportou ao longo do tempo

Utilizar estatistica, dados e programção para tomar decisões de investimento é uma desas tarefas do analista quantitativo.
