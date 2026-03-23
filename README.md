# Site-Dos-Cientistas-

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pioneiros da Computação</title>
    
    <style>
        /* --- Configurações Gerais --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box; /* Garante que padding não aumente o tamanho dos elementos */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6; /* Um cinza muito claro para o fundo */
            color: #333;
            line-height: 1.6;
            padding-bottom: 40px;
        }

        /* --- Cabeçalho (Header) --- */
        header {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            text-align: center;
            padding: 4rem 1rem;
            margin-bottom: 2rem;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        header h1 {
            font-size: 2.8rem;
            margin-bottom: 0.5rem;
            letter-spacing: 1px;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
            font-weight: 300;
        }

        /* --- Container Principal (Grid) --- */
        .container {
            display: flex;
            flex-wrap: wrap; /* Permite que os cards pulem de linha em telas menores */
            justify-content: center; /* Centraliza os cards */
            gap: 30px; /* Espaço entre os cards */
            max-width: 1200px;
            margin: 0 auto; /* Centraliza o container na tela */
            padding: 0 20px;
        }

        /* --- Estilização dos Cards --- */
        .card {
            background: white;
            border-radius: 12px;
            box-shadow: 0 6px 18px rgba(0,0,0,0.08);
            width: 320px; /* Largura fixa para desktop */
            padding: 30px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border-top: 6px solid #3498db; /* Barra de cor no topo */
            display: flex;
            flex-direction: column;
        }

        /* Efeito ao passar o mouse */
        .card:hover {
            transform: translateY(-10px); /* Move o card para cima */
            box-shadow: 0 12px 25px rgba(0,0,0,0.15);
        }

        .card h2 {
            color: #2c3e50;
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        /* Tag de título/especialidade */
        .tag {
            display: inline-block;
            background: #e1f0fa;
            color: #3498db;
            font-size: 0.85rem;
            font-weight: bold;
            padding: 6px 12px;
            border-radius: 20px;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .card p {
            font-size: 1rem;
            color: #555;
            flex-grow: 1; /* Faz o texto ocupar o espaço vertical restante */
        }

        /* Destaque para termos importantes */
        .card strong {
            color: #2c3e50;
        }

        /* --- Responsividade (Telas de Celular) --- */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            .container {
                gap: 20px;
            }

            .card {
                width: 100%; /* Card ocupa toda a largura disponível */
                max-width: 400px; /* Mas não fica gigante */
            }
        }
    </style>
    </head>
<body>

    <header>
        <h1>Pioneiros da Computação</h1>
        <p>As mentes que desenharam o futuro digital</p>
    </header>

    <main class="container">
        
        <section class="card">
            <div class="info">
                <h2>Charles Babbage</h2>
                <span class="tag">O Pai do Computador</span>
                <p>Polímata britânico que projetou a <strong>Máquina Analítica</strong>. Embora nunca finalizada em sua vida, seu design continha todos os elementos essenciais de um computador moderno, como memória e unidade de processamento.</p>
            </div>
        </section>

        <section class="card">
            <div class="info">
                <h2>Ada Lovelace</h2>
                <span class="tag">A Primeira Programadora</span>
                <p>Matemática e escritora, Lovelace colaborou com Babbage e escreveu o primeiro algoritmo destinado a ser processado pela Máquina Analítica. Ela foi a primeira a perceber que computadores poderiam processar mais do que apenas números, como música e arte.</p>
            </div>
        </section>

        <section class="card">
            <div class="info">
                <h2>Alan Turing</h2>
                <span class="tag">Pai da Computação Moderna</span>
                <p>Lógico e criptoanalista que formalizou os conceitos de algoritmo com a <strong>Máquina de Turing</strong>. Teve papel crucial na Segunda Guerra Mundial ao decifrar códigos nazistas e lançou as bases para a Inteligência Artificial com o Teste de Turing.</p>
            </div>
        </section>

    </main>

</body>
</html>
