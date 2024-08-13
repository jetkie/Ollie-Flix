<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
    <title>OliverFlix</title>
    <style>
        body {
            color: #fff; /* Texto branco */
            background: #000; /* Fundo preto */
            margin: 0;
            font-family: "Chakra Petch", sans-serif;
            margin-bottom: 100px;
        }

        header {
            border-bottom: solid 2px #2a7ae4; /* Linha inferior azul */
            padding: 20px;
            font-size: 32px;
            color: #2a7ae4; /* Texto azul */
        }

        .chamada {
            background: #b89cdd; /* Roxo claro */
            padding: 80px 0;
            display: flex;
            justify-content: center;
        }

        h1 {
            font-size: 40px;
            color: #ff66b2; /* Rosa */
        }

        p {
            font-size: 20px;
        }

        .categoria-videos {
            display: flex;
            overflow-x: auto;
            gap: 10px;
        }

        .categoria {
            padding-left: 20px;
            padding-right: 20px;
            margin-top: 50px;
        }

        .categoria-videos img {
            opacity: 0.7;
            height: 200px;
            border: 2px solid #ff4d4d; /* Vermelho */
            border-radius: 10px;
        }

        .categoria-videos img:hover {
            opacity: 1.0;
            border: 3px solid #00cc66; /* Verde */
        }

        .categoria h2 {
            color: #2a7ae4; /* Azul */
        }
    </style>
</head>
<body>
    <header>OllieFlix</header>

    <section class="chamada">
        <div class="chamada-texto">
            <h1>PADRINHOS MÁGICOS, UM NOVO DESEJO!</h1>
            <p>#oddparentsanewwish</p>
        </div>

        <div>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/EAaaVH_thwU?si=-PnsipKU95FdM2TC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </section>

    <section class="categoria">
        <h2>Mais de Padrinhos Mágicos:</h2>
        <div class="categoria-videos">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/-XNjBy0U-lo?si=T6GqqrYhMXO2MF5S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            <!-- Adicione outras imagens relacionadas aos filmes e séries -->
            <!-- Exemplo: <a href="seu-link-aqui"><img src="sua-imagem-aqui.jpg" alt="Descrição da imagem"></a> -->
        </div>
    </section>
</body>
</html>
