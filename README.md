<!DOCTYPE html> <!-- identifica um documento html 5 --> 
<html lang="pt-br"> <!-- elemento raiz -->
    <head> <!-- cabeça da página -->
        <style> body {
            font-family: Arial, sans-serif; /* Define a fonte do texto */
            display: flex; /* Usa flexbox para alinhar elementos */
            justify-content: center; /* Centraliza o conteúdo horizontalmente */
            align-items: center; /* Centraliza o conteúdo verticalmente */
            height: 100vh; /* Define a altura da página para ocupar toda a tela */
            background-color: #191b19; /* Define a cor de fundo */
        }
        .container {
            background: rgb(8, 8, 8); /* Define a cor de fundo do cartão */
            padding: 30px; /* Adiciona espaçamento interno */
            border-radius: 50px; /* Arredonda as bordas */
            box-shadow: 4px 8px black;/* Adiciona uma sombra suave */
            text-align: center; /* Centraliza o texto dentro do cartão */
            border: solid 3px black;
            color: white;
        }
        
        button {
            background: #007bff; /* Define a cor de fundo do botão */
            color: white; /* Define a cor do texto do botão */
            border: solid blue 1px ; /* Remove a borda do botão */
            padding: 10px 15px; /* Adiciona espaçamento interno */
            border-radius: 30px; /* Arredonda as bordas do botão */
            cursor: pointer; /* Muda o cursor para indicar clicabilidade */
        }
        button:hover {
            background: #f10000 ; /* Altera a cor de fundo ao passar o mouse */
            border: solid #b30000 1px;
        }
        
        .imagem{
            border-radius: 50%; /* Transforma a imagem em um círculo */
            width: 150px; /* Define a largura da imagem */
            height: 150px; /* Define a altura da imagem */
            margin-bottom: 5px; /* Adiciona espaço abaixo da imagem */
        }
        </style>
        <meta charset="UTF-8"> <!-- sistema de codificação português-->
        <!-- página terá a largura do dispositivo -->
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <!-- título da página -->
        <title>Profile Card </title>
        <!-- fazendo o html ler o css-->
        <!-- rel informa tipo da relação, folha de estilo -->
        <!-- href informa o local do CSS -->
        <link rel="stylesheet" href="progcomp.css">
    </head>
    <body> <!-- corpo da página -->
        <div class="container"> <!-- divisão lógica de conteúdo -->
            <img class="imagem" src="WhatsApp Image 2025-02-22 at 13.59.02.jpeg"/>     
            <h2> Eric Meleti </h2>
            <p> Engenharia de Software </p>
            <a href="https://www.instagram.com/eric_dsm016/">
                <button> Seguir perfil </button>
            </a>
        </div>
    </body>
</html>
