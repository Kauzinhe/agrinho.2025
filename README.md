<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Festejando a Conexão entre a Cidade e o Campo</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Arial, sans-serif;
            background: linear-gradient(to bottom, #f7e8c3 0%, #d0f0c0 100%);
            color: #333;
        }
        header {
            background-color: #8dc63f;
            color: white;
            padding: 2rem 1rem;
            text-align: center;
        }
        nav {
            background: #f1c40f;
            padding: 1rem;
            text-align: center;
        }
        nav a {
            color: #333;
            margin: 0 1rem;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 900px;
            margin: 2rem auto;
            background: white;
            border-radius: 12px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.07);
            padding: 2rem;
        }
        .section {
            margin-bottom: 2rem;
        }
        .galeria {
            display: flex;
            gap: 1.5rem;
            flex-wrap: wrap;
            justify-content: center;
        }
        .galeria img {
            width: 220px;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
            box-shadow: 0 1px 5px rgba(0,0,0,0.08);
        }
        footer {
            background: #8dc63f;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
        @media (max-width: 600px) {
            .galeria {
                flex-direction: column;
                align-items: center;
            }
            .container {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Festejando a Conexão entre a Cidade e o Campo</h1>
        <p>Uma celebração que une tradições rurais e urbanas</p>
    </header>
    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#galeria">Galeria</a>
        <a href="#eventos">Eventos</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="container">
        <section id="sobre" class="section">
            <h2>Sobre a Festa</h2>
            <p>
                Nossa festa celebra a união entre o campo e a cidade, promovendo cultura, música, gastronomia e integração de comunidades.
                Agricultores, moradores urbanos e visitantes se encontram para compartilhar saberes, dançar, experimentar comidas típicas e valorizar a diversidade.
            </p>
        </section>
        <section id="galeria" class="section">
            <h2>Galeria</h2>
            <div class="galeria">
                <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80" alt="Festa rural">
                <img src="https://images.unsplash.com/photo-1464983953574-0892a716854b?auto=format&fit=crop&w=400&q=80" alt="Cidade e campo">
                <img src="https://images.unsplash.com/photo-1519864600265-abb23847ef2c?auto=format&fit=crop&w=400&q=80" alt="Quadrilha">
            </div>
        </section>
        <section id="eventos" class="section">
            <h2>Próximos Eventos</h2>
            <ul>
                <li><strong>12/06:</strong> Quadrilha e Forró na Praça Central</li>
                <li><strong>13/06:</strong> Feira de Produtos Rurais e Urbanos</li>
                <li><strong>14/06:</strong> Oficina de Sabores: Receitas do Campo e da Cidade</li>
            </ul>
        </section>
        <section id="contato" class="section">
            <h2>Contato</h2>
            <p>Quer participar ou ser expositor? Envie um e-mail para <a href="mailto:contato@festacidadecampo.com.br">contato@festacidadecampo.com.br</a></p>
        </section>
    </div>
    <footer>
        &copy; 2025 Festejando a Conexão entre a Cidade e o Campo
    </footer>
</body>
</html>

