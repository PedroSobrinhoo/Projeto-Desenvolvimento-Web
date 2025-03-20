<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil Pessoal</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Times New Roman', Times, serif, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f4f4f4;
        }

        .container {
            display: flex;
            max-width: 1000px;
            width: 100%;
            margin: 20px;
            background: white;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        header {
            width: 100%;
            background: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .content {
            display: flex;
            width: 100%;
        }

        aside {
            width: 25%;
            padding: 20px;
            background: #ddd;
        }

        main {
            width: 50%;
            padding: 20px;
        }

        .sidebar {
            width: 25%;
            padding: 20px;
            background: #ddd;
        }

        footer {
            width: 100%;
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }

        section {
            margin-bottom: 20px;
        }

    </style>
</head>
<body>

    <header>
        <h1>Pedro Sobrinho</h1>
        <p> Moro em Guarulhos, sou fatecano, empregado, corinthiano e viciado em café. Gosto muito de ler, jogar xadrez, e ir em shows de rock.</p>
    </header>

    <div class="container">
        <aside>
            <h2> </h2>
            <ul>
                <li>Guarulhos, São Paulo</li>
                <li>Faculdade de Tecnologia do Estado São Paulo</li>
                <li> sobrinhop605@gmail.com</li>
            </ul>
        </aside>

        <main>
            <section>
                <h2>Biografia</h2>
                <p>Estudei em escola pública ao longo da minha vida, venci dois campeonatos de xadrez: Olimpíada Colegial Guarulhos 
                e Jogos Escolares do Estado de São Paulo, passei pela Fatec pelo Provão Paulista e gosto muito de música, toco violão e estou aprendendo teclado</p>
            </section>
            <section>
                <h2>Experiências Profissional</h2>
                <p>Auxiliar de Escritório da empresa LOGUM logística S/A
                    2024 - 2025 </p>
            
        </main>

        <aside class="sidebar">
            <h2>Habilidades e Interesses</h2>
            <ul>
                <li>pensamento analítico</li>
                <li>resiliência, sou corinthiano né pae</li>
                <li>Português, Inglês, Espanhol </li>
                <li>Leitura, Xadrez, Música</li>
                <li>Rock, MPB, Blues</li>
                
            </ul>
        </aside>
    </div>

    <footer>
        <p>Redes Sociais: <a href="#">https://www.linkedin.com/in/pedro-sobrinho-feitosa-1729922b9?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app</a> | <a href="#"></a></p>
    </footer>

</body>
</html>
