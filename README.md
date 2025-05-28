<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jogos para Computadores Fracos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        h1, h2 {
            font-size: 2rem;
        }

        .game-list, .bird-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .game-item, .bird-item {
            background-color: #fff;
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
        }

        .game-item img, .bird-item img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .game-item h3, .bird-item h3 {
            margin-top: 10px;
            font-size: 1.5rem;
        }

        .game-item p, .bird-item p {
            font-size: 1rem;
            color: #666;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }

        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <header>
        <h1>Jogos para Computadores Fracos</h1>
        <p>Encontre jogos incríveis que rodam em máquinas mais modestas!</p>
    </header>

    <div class="container">
        <h2>Top 5 Jogos para PC Fraco</h2>
        <div class="game-list">
            <div class="game-item">
                <img src="https://via.placeholder.com/250" alt="Stardew Valley">
                <h3>Stardew Valley</h3>
                <p>Um simulador de fazenda com gráficos simples e uma jogabilidade envolvente.</p>
                <button onclick="window.open('https://www.stardewvalley.net/')">Saiba Mais</button>
            </div>
            <div class="game-item">
                <img src="https://via.placeholder.com/250" alt="Hotline Miami">
                <h3>Hotline Miami</h3>
                <p>Um jogo de ação frenética com gráficos retrô e uma trilha sonora marcante.</p>
                <button onclick="window.open('https://www.devolverdigital.com/games/hotline-miami')">Saiba Mais</button>
            </div>
            <div class="game-item">
                <img src="https://via.placeholder.com/250" alt="Undertale">
                <h3>Undertale</h3>
                <p>Um jogo de RPG que se destaca pela narrativa única e opções de combate criativas.</p>
                <button onclick="window.open('https://undertale.com/')">Saiba Mais</button>
            </div>
            <div class="game-item">
                <img src="https://via.placeholder.com/250" alt="FTL">
                <h3>FTL: Faster Than Light</h3>
                <p>Um simulador de nave espacial com uma jogabilidade de estratégia e exploração.</p>
                <button onclick="window.open('https://subsetgames.com/ftl.html')">Saiba Mais</button>
            </div>
            <div class="game-item">
                <img src="https://via.placeholder.com/250" alt="Celeste">
                <h3>Celeste</h3>
                <p>Uma plataforma desafiadora com gráficos lindos e uma história emocionante.</p>
                <button onclick="window.open('https://maddynotch.itch.io/celeste')">Saiba Mais</button>
            </div>
        </div>

        <!-- Nova Seção: Pássaros Raros -->
        <h2 style="margin-top: 60px;">Pássaros Raros do Brasil</h2>
        <div class="bird-list">
            <div class="bird-item">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4b/Ararinha-azul.jpg/300px-Ararinha-azul.jpg" alt="Ararinha-azul">
                <h3>Ararinha-azul</h3>
                <p>Extremamente rara, originária da Caatinga. Símbolo de conservação no Brasil.</p>
            </div>
            <div class="bird-item">
                <img src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Coracina_caudata.jpg" alt="Cuitelão">
                <h3>Cuitelão</h3>
                <p>Espécie rara e pouco avistada, encontrada em florestas tropicais densas.</p>
            </div>
            <div class="bird-item">
                <img src="https://upload.wikimedia.org/wikipedia/commons/1/17/Cyanocorax_chrysops_-_Blue-naped_Jay.jpg" alt="Gralha-azul">
                <h3>Gralha-azul</h3>
                <p>Conhecida por seu papel na disseminação de araucárias no sul do Brasil.</p>
            </div>
            <div class="bird-item">
                <img src="https://upload.wikimedia.org/wikipedia/commons/d/df/Rhopornis_ardesiacus_-_Slender_antbird.jpg" alt="Formigueiro-do-litoral">
                <h3>Formigueiro-do-litoral</h3>
                <p>Espécie ameaçada encontrada em áreas restritas da Mata Atlântica.</p>
            </div>
            <div class="bird-item">
                <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/Anodorhynchus_leari_-Brazil-8.jpg" alt="Arara-azul-de-Lear">
                <h3>Arara-azul-de-Lear</h3>
                <p>Habita a região do sertão baiano e está ameaçada pela perda de habitat.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Jogos para Computadores Fracos. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
