# VidFlow

Projeto desenvolvido junto ao curso "JS: consumindo e tratando dados de uma API" da Alura.

VidFlow é um site com um compilado de videos dos mais variados temas da área de tecnologia, como programação, data science e etc..
O site além de aglomerar e exibir os videos também filtra por categorias ou pela barra de pesquisa do mesmo.

Esse site utiliza um arquivo json que contém as informações dos videos que são exibidos, utilizando esse json como uma API fake.

Para o site funcionar completamente será nescessário além de baixar o projeto aqui, instalar o json server. 

Instalação do Json server: para instalar você precisa apenas abrir o terminal ou prompt  de comando e colar o código abaixo:
"npm install -g json-server" (sem as aspas)

Após isso, para funcionar você precisa abrir mais um terminal, agora diretamente na pasta do projeto e escrever o código abiaxo:
"json-server --watch backend/videos.json" (sem as aspas)

Se o terminal exibir a porta http localhost no final, o código estará funcionando.

Aí basta abrir o arquivo html no navegador, sem fechar ou encerrar a janela do terminal ao qual está rodando o código escrito acima.
