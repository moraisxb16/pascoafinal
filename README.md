<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cópia da Chave PIX</title>
    <style>
        body {
            background-color: #EDD9C5; /* Cor de fundo */
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: black; /* Alterado para preto para melhor contraste */
            font-family: Arial, sans-serif;
        }
        img {
            max-width: 300px; /* Tamanho máximo da imagem */
            margin-bottom: 20px;
        }
        button {
            padding: 15px 30px;
            font-size: 20px;
            background-color: #6A5137; /* Cor do botão */
            border: none;
            border-radius: 5px;
            cursor: pointer;
            color: white; /* Cor do texto do botão */
        }
        button:hover {
            background-color: #5F4831; /* Cor do botão ao passar o mouse */
        }
        #message {
            display: none; /* Inicialmente escondido */
            margin-top: 20px;
        }
        h1 {
            text-align: center; /* Centraliza o texto */
            word-wrap: break-word; /* Quebra a linha se necessário */
            margin: 0 10px; /* Margem para evitar que o texto encoste nas bordas */
        }
    </style>
</head>
<body>

    <h1>TERREIRO SOLDADOS DE ARUANDA</h1>
    <a href="https://im.ge/i/8629fdcb-acd1-4960-bf5b-e8207abc758c.pLgU0C"><img src="https://i.im.ge/2025/03/21/pLgU0C.8629fdcb-acd1-4960-bf5b-e8207abc758c.th.png" alt="8629fdcb acd1 4960 bf5b e8207abc758c" border="0"></a>
    <button id="copyButton">CLIQUE AQUI PARA COPIAR CHAVE PIX</button>
    <p id="message">Chave PIX copiada: <span id="pixKey">pascoatusa@gmail.com</span></p>

    <script>
        document.getElementById('copyButton').addEventListener('click', function() {
            const pixKey = "pascoatusa@gmail.com";
            navigator.clipboard.writeText(pixKey).then(() => {
                const message = document.getElementById('message');
                message.style.display = 'block'; // Mostra a mensagem
            }).catch(err => {
                console.error('Erro ao copiar a chave PIX: ', err);
            });
        });
    </script>

</body>
</html>
