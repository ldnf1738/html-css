# html-css
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inova Basic Cabelereiro</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Inova Basic Cabelereiro</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#equipe">Equipe</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="banner">
        <h2>Bem-vindo à Inova Basic Cabelereiro</h2>
        <p>O seu destino para um estilo impecável e um atendimento excepcional</p>
    </section>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Na Inova Basic Cabelereiro, levamos o atendimento ao cliente e satisfação a sério...
      <p>Nossa equipe é bastante experientes e talentosos,</p>
            <p>estamos comprometidos em proporcionar a você uma experiência única com nossos serviços.</p> 
</section>

    <section id="servicos">
        <h2>Serviços</h2>
        <ul>
            <li>Corte de Cabelo Masculino</li>
            <li>Corte de Cabelo Feminino</li>
            <li>Corte de Cabelo Infantil</li>
            <li>Barba</li>
            <li>Diversos Tipos de Tratamento Capilar</li>
            <li>Manicure e Pedicure</li>
            <li>Depilação</li>
        </ul>
        
    </section>

    <section id="equipe">
        <h2>Equipe</h2>
        <ul>
            <li>Johne</li>
            <li>Nilva</li>
            
        </ul>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p>Agende seu horário:</p>
        <p>Telefone:<a href="tel:(34)3223-9875">(34) 343223-98758</a></p>
        <p>Email: <a href="mailto:inovabasiccabelereiro.com.br">inovabasiccabelereiro.com.br</a></p>
      
        <section id="localizacao">
            <h2>Localização</h2>
            <p>Endereço: R. João Augusto Lopes, 336 - Alvorada - Uberlândia, MG</p>
            <p><a href="https://www.google.com/maps/search/?api=1&query=Rua+João Augusto Lopes+336+Uberlândia+MG" target="_blank">Ver no Google Maps</a></p>
            <div id="map"></div>
        </section>
        
    </section>


    <footer>
        <p>&copy; 2023 Inova Basic. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

/*css*/

body {
    background-image: url('img/img.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

/* Reset de estilos para garantir uma base consistente */
#body, h1{
text-align: center;
}


body, h2, p, ul, li {
    margin: 0;
    padding: 0;
    color: #fff;
}

/* Estilos globais */
body {
    font-family: Arial, sans-serif;
    font-size: 16px;
    
}

header {
    background-color: #000000;
    padding: 20px;
    color: #fff;
   
}

header h1 {
    font-size: 24px;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline-block;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 40px;
}

section h2 {
    font-size: 24px;
    margin-bottom: 20px;
}

ul {
    list-style: disc;
    margin-left: 20px;
}

footer {
    background-color: #060606;
    color: #fff;
    padding: 20px;
    text-align: center;
}
#contato {
    text-align: center;
}
