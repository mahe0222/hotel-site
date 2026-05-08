<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- MENU -->
    <nav class="menu">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#sobre">Sobre nós</a></li>
            <li><a href="#quartos">Quartos</a></li>
            <li><a href="#localizacao">Localização</a></li>
            <li><a href="#agendamento">Agendamento</a></li>
        </ul>
    </nav>

    <!-- HOME -->
    <header id="home" class="hero fade-in">
        <div class="hero-content slide-up">
            <h1>Nome do Hotel</h1>
            <p>Slogan ou frase de impacto aqui.</p>
        </div>
    </header>

    <!-- SOBRE NÓS -->
    <section id="sobre" class="container fade-section">
        <h2 class="section-title">Sobre Nós</h2>
        <p class="texto">
            Texto sobre o hotel. Fale sobre conforto, localização, história, diferenciais,
            atendimento, missão e o que mais desejar.
        </p>
    </section>

    <!-- QUARTOS -->
    <section id="quartos" class="container fade-section">
        <h2 class="section-title">Quartos</h2>

        <div class="quartos-grid">

            <!-- QUARTO 1 -->
            <div class="quarto-card zoom-in">
                <img src="quarto1.jpg" alt="Quarto 1">
                <h3>Quarto Luxo</h3>
                <p>Descrição breve do quarto.</p>
                <span class="preco">R$ 250 / noite</span>
                <a class="btn-whats" data-msg="Quero reservar o Quarto Luxo">Reservar pelo WhatsApp</a>
            </div>

            <!-- QUARTO 2 -->
            <div class="quarto-card zoom-in">
                <img src="quarto2.jpg" alt="Quarto 2">
                <h3>Quarto Família</h3>
                <p>Descrição breve do quarto.</p>
                <span class="preco">R$ 350 / noite</span>
                <a class="btn-whats" data-msg="Quero reservar o Quarto Família">Reservar pelo WhatsApp</a>
            </div>

            <!-- QUARTO 3 -->
            <div class="quarto-card zoom-in">
                <img src="quarto3.jpg" alt="Quarto 3">
                <h3>Suíte Premium</h3>
                <p>Descrição breve do quarto.</p>
                <span class="preco">R$ 480 / noite</span>
                <a class="btn-whats" data-msg="Quero reservar a Suíte Premium">Reservar pelo WhatsApp</a>
            </div>

        </div>
    </section>

    <!-- LOCALIZAÇÃO -->
    <section id="localizacao" class="container fade-section">
        <h2 class="section-title">Localização</h2>

        <div class="mapa slide-up">
            <iframe 
                src="https://www.google.com/maps/embed?pb=!1m18..."
                width="100%" height="300" style="border:0;" allowfullscreen loading="lazy">
            </iframe>
        </div>
    </section>

    <!-- AGENDAMENTO -->
    <section id="agendamento" class="container fade-section">
        <h2 class="section-title">Agendamento</h2>
        <p class="texto">Clique abaixo para falar com um atendente e reservar sua estadia.</p>

        <a class="btn-whats grande pulse" data-msg="Olá! Quero fazer uma reserva.">
            Falar com Atendente
        </a>
    </section>

    <footer>
        <p>© 2026 — Nome do Hotel. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
