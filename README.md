# criando-corpo-HTML
aula praticada no curso da PROZ TECH

# Aula HMTL Cursos PROZ Portal Tech criando pagina de turismo...
# Para podermos praticar o que foi ensinado na aula do dia...
# Assim podemos enteder como se cria um corpo de uma pagina em HTML...

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pontos Turísticos</title>
</head>
<body>
    <div class="header">
        <h1>Pontos Turísticos</h1>
        <p>Descubra os destinos mais incríveis ao redor do mundo</p>
        <nav>
            <a href="#canada">Canadá</a>
            <a href="#estados-unidos">Estados Unidos</a>
            <a href="#inglaterra">Inglaterra</a>
            <a href="#contato">Contato</a>
            <a href="#login">Login</a>
        </nav>
    </div>
    <div class="container">
        <h2 id="canada">Canadá</h2>
        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Niagara_Falls_Ontario_2012.jpg" alt="Cataratas do Niágara, Ontário">
            <h3>Cataratas do Niágara, Ontário</h3>
            <p>As Cataratas do Niágara são uma das maravilhas naturais mais espetaculares do mundo. Localizadas na fronteira entre o Canadá e os Estados Unidos, são um destino imperdível para quem visita a região.</p>
            <a href="#" class="btn">Reserve Agora</a>
        </div>
        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/4/45/Toronto_-_ON_-_Skyline_1.jpg" alt="CN Tower, Toronto">
            <h3>CN Tower, Toronto</h3>
            <p>A CN Tower é uma das estruturas mais altas do mundo e oferece uma vista panorâmica incrível da cidade de Toronto. É um símbolo icônico do Canadá e um lugar perfeito para quem gosta de altura.</p>
            <a href="#" class="btn">Reserve Agora</a>
        </div>
        <h2 id="estados-unidos">Estados Unidos</h2>
        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a1/Statue_of_Liberty_7.jpg" alt="Estátua da Liberdade, Nova York">
            <h3>Estátua da Liberdade, Nova York</h3>
            <p>A Estátua da Liberdade é um dos monumentos mais icônicos dos Estados Unidos. Localizada na Ilha da Liberdade, em Nova York, é um símbolo de liberdade e democracia, recebendo milhões de visitantes todos os anos.</p>
            <a href="#" class="btn">Reserve Agora</a>
        </div>
        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/ab/Grand_Canyon_National_Park_overlook%2C_2010.jpg" alt="Grand Canyon, Arizona">
            <h3>Grand Canyon, Arizona</h3>
            <p>O Grand Canyon é uma das formações geológicas mais impressionantes do mundo. Este desfiladeiro vasto e profundo no estado do Arizona oferece vistas de tirar o fôlego e é um destino popular para os amantes da natureza.</p>
            <a href="#" class="btn">Reserve Agora</a>
        </div>
        <h2 id="inglaterra">Inglaterra</h2>
        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Westminster_Abbey_from_the_North.jpg" alt="Abadia de Westminster, Londres">
            <h3>Abadia de Westminster, Londres</h3>
            <p>A Abadia de Westminster é uma das edificações mais importantes de Londres e um lugar de grande significado histórico. É conhecida por ser o local de coroação dos monarcas britânicos e por abrigar muitos túmulos de figuras notáveis.</p>
            <a href="#" class="btn">Reserve Agora</a>
        </div>
        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/e/e5/The_London_Eye.jpg" alt="London Eye, Londres">
            <h3>London Eye, Londres</h3>
            <p>O London Eye é uma roda-gigante gigantesca às margens do Rio Tâmisa. Oferece vistas panorâmicas espetaculares de Londres e é uma atração popular para visitantes de todas as idades.</p>
            <a href="#" class="btn">Reserve Agora</a>
        </div>
    </div>
    <div class="footer">
        <p id="contato">Entre em contato: contato@pontos-turisticos.com | Tel: (21) 1234-5678</p>
        <p id="login"><a href="#" class="btn">Login</a></p>
    </div>
</body>
</html>
# Esse e o corpo da nossa pagina em HTML...
