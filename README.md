
# Inspiring Avaliações Front End

Bem vindo ao repo de avaliações Front End da Stefanini Inspiring. Agradecemos o seu interesse em se juntar a nós, agora leia as instruções com calma e happy coding.


## Pré Requisitos:
O conhecimento no sistema de versionamento git é um pré requisito para responder as seguintes questões, porém, não deve ser um impeditivo para os que não estão familiarizados com a ferramenta, pois a capacidade de pesquisar e aprender novos conceitos também será avaliada e é um requisito de trabalho em nosso dia a dia.

Ter uma versão do node.js instalada, utilizamos a v10.9.0 para estes projetos.

## Regras:
Esta avliação é composta por pequenas aplicações já criadas nas quais você deverá adicionar algumas funcionalidades conforme informado.
Também serão feitas algumas questões sobre as aplicações, que deverão ser respondidas.

O formato de entrega da avaliação será feito no github ou bitbucket, caso prefira, em uma conta de seu nome.

As questões de funcionalidades, serão avaliadas analisando os commits que você fizer.
As perguntas, deverão ser respondidas no arquivo respostas_README.md.

Antes de commitar o arquivo com as respostas, o arquivo respostas_README.md deverá ser renomeado para README.md.


Serão avaliados:
Qualidade do código (lógica, limpeza, identação, dentre outros)
A aplicação está funcional? (É possível rodar a aplicação depois das alterações?)
Resultado das alterações (As alterações feitas levam ao resultado esperado?)
Coerência das respostas (As respostas das perguntas são claras e demonstram entendimento do assunto?)

Observações:
Utilize a frequência de commits que julgar necessária para organizar bem o seu trabalho.


### Questão 1 - Javascript
Acesse a pasta `avaliacoes-frontend/javascript`

Neste diretório, temos um mapa com alguns pontos de interesse já mapeados no objecto criado com nome placesOfInterest dentro de index.js.
O projeto poderá ser acessado utilizando o servidor http-server do node.js, para executá-lo, você deverá rodar os seguintes comandos em um terminal dentro da pasta do projeto:

`npm install` <--- para instalar as dependências, como o http-server por exemplo

`./node_modules/http-server/bin/http-server .`   <--- para subir o servidor e servir a aplicação 

O site deverá estar acessível em http://localhost:8080

a) A aplicação exibe um marcador de 1 dos pontos de interesse, localizado na Avenida Paulista ao lado do Parque Trianon em frente ao MASP.
Modificque o código da aplicação para que ela passe a exibir todos os pontos de interesse listados no Array 'placesOfInterest'.

b) Modifique a aplicação para alterar a cor do marcador de um ponto de interesse quando este for clicado, conforme exemplo:
![Exemplo](resources/examples/exemplo01.gif)

c) Modifique a aplicação para abrir uma janela com com o nome do ponto de interesse quando clicado, conforme exemplo:
![Exemplo](resources/examples/exemplo02.gif)

d) Modifique a aplicação para voltar a cor original do marcador ao fechar a janela, conforme exemplo: 
![Exemplo](resources/examples/exemplo03.gif)

e) Modifique a aplicação para fechar uma janela de um marcador previamente aberta, quando outra janela for clicada. Também deverá restaurar a cor original do marcador peviamente selecionado, cofnrome exemplo:
![Exemplo](resources/examples/exemplo04.gif)


### Questão 2
Responda as perguntas sobre o projeto da questão 1:

a) No import da api do google maps no index.html, para que servem as tags async e defer?

b) Para que serve o parâmetro &callback=initMap na url da api do google maps?

c) O que acontece quando removemos o parâmetro &callback=initMap da url da api do google maps? Explique o porque.

d) Descreva pelo menos uma forma de como podemos fazer com que a aplicação funcione corretamente mesmo sem este parâmetro.

e) Explique para que servem as seguintes tags do index.html: 
  `<link rel="manifest" href="manifest.json">
  <meta name="theme-color" content="">
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="black">`
  
f) Está aplicação pode ser considerada um PWA? Em caso negativo, explique o que falta para que seja.

