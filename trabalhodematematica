z<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anti Poluição</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        /* Estilo do corpo */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #e3f2fd;
            color: #333;
            line-height: 1.6;
            overflow-x: hidden;
        }
        /* Estilo do cabeçalho */
        .header {
            background: linear-gradient(135deg, #1e88e5, #039be5);
            color: #fff;
            text-align: center;
            padding: 60px 20px;
            position: relative;
            z-index: 10;
            border-bottom: 5px solid #01579b;
        }
        .header h1 {
            font-size: 3.5em;
            margin: 0;
            text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.3);
        }
        .header p {
            font-size: 1.5em;
            margin-top: 10px;
        }
        /* Estilo do menu de navegação */
        .menu {
            background: #01579b;
            color: #fff;
            display: flex;
            justify-content: center;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .menu a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2em;
            padding: 10px 20px;
            transition: background-color 0.3s, transform 0.3s;
        }
        .menu a:hover,
        .menu a.active {
            background-color: #0288d1;
            transform: scale(1.1);
        }
        /* Estilo do contêiner principal */
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
        }
        /* Estilo das seções */
        .section {
            margin-bottom: 50px;
            padding: 20px;
            border-radius: 15px;
            background-color: #ffffff;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
            transition: background-color 0.3s, transform 0.3s;
        }
        .section:hover {
            background-color: #e0f7fa;
            transform: scale(1.02);
        }
        .section h2 {
            color: #01579b;
            font-size: 2.5em;
            margin-bottom: 15px;
            font-weight: bold;
            text-align: center;
        }
        .section p {
            font-size: 1.2em;
            margin-bottom: 20px;
            text-align: justify;
        }
        .section img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 20px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .section img:hover {
            transform: scale(1.05);
        }
        /* Estilo dos ícones circulares de navegação */
        .icon-menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px 0;
        }
        .icon-menu .icon-item {
            background: #ffffff;
            border-radius: 50%;
            width: 120px;
            height: 120px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s, background-color 0.3s;
            text-align: center;
            cursor: pointer;
            overflow: hidden;
            position: relative;
        }
        .icon-menu .icon-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
            top: 0;
            left: 0;
            border-radius: 50%;
            z-index: 1;
            transition: opacity 0.3s;
        }
        .icon-menu .icon-item span {
            font-size: 1.2em;
            color: #01579b;
            position: relative;
            z-index: 2;
            padding: 10px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 50%;
        }
        .icon-menu .icon-item:hover {
            transform: scale(1.1);
            background-color: #e0f2f1;
        }
        .icon-menu .icon-item:hover img {
            opacity: 0.3;
        }
        /* Estilo do rodapé */
        .footer {
            background: #01579b;
            color: #fff;
            text-align: center;
            padding: 30px 20px;
            position: relative;
            bottom: 0;
            width: 100%;
            border-top: 5px solid #002f6c;
        }
        .footer p {
            margin: 0;
            font-size: 1.1em;
        }
        /* Estilo do botão de scroll para o topo */
        .scroll-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #01579b;
            color: #fff;
            border: none;
            border-radius: 50%;
            width: 60px;
            height: 60px;
            text-align: center;
            line-height: 60px;
            font-size: 1.8em;
            cursor: pointer;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: background-color 0.3s, transform 0.3s;
        }
        .scroll-to-top:hover {
            background-color: #002f6c;
            transform: scale(1.1);
        }
        /* Estilo dos formulários */
        .form-group {
            margin-bottom: 20px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form-group textarea {
            height: 100px;
            resize: vertical;
        }
        .form-group button {
            background-color: #01579b;
            color: #fff;
            border: none;
            border-radius: 5px;
            padding: 10px 20px;
            font-size: 1.1em;
            cursor: pointer;
            transition: background-color 0.3s, transform 0.3s;
        }
        .form-group button:hover {
            background-color: #002f6c;
            transform: scale(1.05);
        }
        /* Responsividade */
        @media (max-width: 768px) {
            .menu {
                flex-direction: column;
            }
            .menu a {
                padding: 15px;
                font-size: 1em;
            }
            .container {
                padding: 10px;
            }
            .section h2 {
                font-size: 2em;
            }
            .icon-menu {
                flex-direction: column;
            }
            .icon-menu .icon-item {
                width: 100px;
                height: 100px;
            }
            .icon-menu .icon-item img {
                width: 100%;
                height: 100%;
            }
            .scroll-to-top {
                width: 50px;
                height: 50px;
                font-size: 1.5em;
            }
        }
    </style>
</head>
<body>
    <!-- Cabeçalho -->
    <div class="header">
        <h1>Anti Poluição</h1>
        <p>Conscientize-se e ajude a preservar o meio ambiente.</p>
    </div>

    <!-- Menu de Navegação -->
    <div class="menu">
        <a href="#introducao" class="nav-link">Introdução</a>
        <a href="#causas" class="nav-link">Causas</a>
        <a href="#solucoes" class="nav-link">Soluções</a>
        <a href="#impacto" class="nav-link">Impacto</a>
        <a href="#contato" class="nav-link">Contato</a>
    </div>

    <!-- Container Principal -->
    <div class="container">
        <!-- Menu de Ícones -->
        <div class="icon-menu">
            <div class="icon-item" onclick="scrollToSection('introducao')">
                <img src="https://images.pexels.com/photos/1161642/pexels-photo-1161642.jpeg" alt="Ícone Introdução">
                <span>Introdução</span>
            </div>
            <div class="icon-item" onclick="scrollToSection('causas')">
                <img src="https://images.pexels.com/photos/1608472/pexels-photo-1608472.jpeg" alt="Ícone Causas">
                <span>Causas</span>
            </div>
            <div class="icon-item" onclick="scrollToSection('solucoes')">
                <img src="https://images.pexels.com/photos/569459/pexels-photo-569459.jpeg" alt="Ícone Soluções">
                <span>Soluções</span>
            </div>
            <div class="icon-item" onclick="scrollToSection('impacto')">
                <img src="https://images.pexels.com/photos/3831994/pexels-photo-3831994.jpeg" alt="Ícone Impacto">
                <span>Impacto</span>
            </div>
            <div class="icon-item" onclick="scrollToSection('contato')">
                <img src="https://images.pexels.com/photos/3807790/pexels-photo-3807790.jpeg" alt="Ícone Contato">
                <span>Contato</span>
            </div>
        </div>

        <!-- Seções -->
        <div id="introducao" class="section">
            <h2>Introdução</h2>
            <p>A poluição é um problema ambiental global que afeta a saúde dos seres humanos e o equilíbrio dos ecossistemas. A conscientização e a ação são essenciais para enfrentar esse desafio. A poluição afeta a qualidade do ar, água e solo, e pode ter efeitos devastadores sobre a biodiversidade e a saúde humana.</p>
            <img src="https://images.pexels.com/photos/1176741/pexels-photo-1176741.jpeg" alt="Poluição do Ar">
        </div>

        <div id="causas" class="section">
            <h2>Causas da Poluição</h2>
            <p>A poluição é causada por uma série de atividades humanas, incluindo a queima de combustíveis fósseis, a emissão de gases industriais, o descarte inadequado de resíduos e a utilização excessiva de produtos químicos. Essas atividades liberam poluentes no ar, na água e no solo, prejudicando o meio ambiente e a saúde.</p>
            <img src="https://images.pexels.com/photos/1862146/pexels-photo-1862146.jpeg" alt="Poluição Industrial">
        </div>

        <div id="solucoes" class="section">
            <h2>Soluções para a Poluição</h2>
            <p>Para combater a poluição, é fundamental adotar práticas sustentáveis, como o uso de energias renováveis, a redução de resíduos e a promoção de transporte sustentável. Além disso, políticas públicas e iniciativas comunitárias podem ajudar a reduzir a poluição e promover um ambiente mais saudável.</p>
            <img src="https://images.pexels.com/photos/1111363/pexels-photo-1111363.jpeg" alt="Energia Solar">
        </div>

        <div id="impacto" class="section">
            <h2>Impacto da Poluição na Saúde</h2>
            <p>A poluição pode causar uma série de problemas de saúde, incluindo doenças respiratórias, cardiovasculares e até câncer. A exposição a poluentes atmosféricos, como partículas finas e gases tóxicos, pode afetar a qualidade de vida e aumentar a mortalidade. A poluição da água e do solo também pode causar problemas de saúde a longo prazo.</p>
            <img src="https://images.pexels.com/photos/3755562/pexels-photo-3755562.jpeg" alt="Saúde e Poluição">
        </div>

        <div id="contato" class="section">
            <h2>Contato</h2>
            <p>Para mais informações sobre como você pode ajudar a combater a poluição, entre em contato conosco:</p>
            <form action="#" method="post">
                <div class="form-group">
                    <label for="nome">Nome:</label>
                    <input type="text" id="nome" name="nome" required>
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="mensagem">Mensagem:</label>
                    <textarea id="mensagem" name="mensagem" required></textarea>
                </div>
                <div class="form-group">
                    <button type="submit">Enviar</button>
                </div>
            </form>
        </div>
    </div>

    <!-- Rodapé -->
    <div class="footer">
        <p>&copy; 2024 Anti Poluição. Todos os direitos reservados. Desenvolvido por [Seu Nome]</p>
    </div>

    <!-- Botão de Scroll para o Topo -->
    <button class="scroll-to-top" onclick="scrollToTop()">↑</button>

    <!-- Scripts -->
    <script>
        // Função para rolar suavemente até o topo da página
        function scrollToTop() {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        }

        // Função para rolar até uma seção específica
        function scrollToSection(id) {
            const element = document.getElementById(id);
            window.scrollTo({
                top: element.offsetTop - document.querySelector('.menu').offsetHeight,
                behavior: 'smooth'
            });
        }

        // Adicionar e remover a classe 'active' nos links do menu
        document.addEventListener('DOMContentLoaded', function() {
            const links = document.querySelectorAll('.nav-link');
            links.forEach(link => {
                link.addEventListener('click', function(e) {
                    e.preventDefault();
                    const targetId = this.getAttribute('href').substring(1);
                    scrollToSection(targetId);
                    links.forEach(link => link.classList.remove('active'));
                    this.classList.add('active');
                });
            });
        });

        // Destaque do link do menu baseado na rolagem da página
        window.addEventListener('scroll', function() {
            const sections = document.querySelectorAll('.section');
            const scrollPos = document.documentElement.scrollTop || document.body.scrollTop;
            sections.forEach(section => {
                if (section.offsetTop <= scrollPos + 100 && (section.offsetTop + section.offsetHeight) > scrollPos) {
                    document.querySelectorAll('.nav-link').forEach(link => {
                        link.classList.remove('active');
                        if (link.getAttribute('href').substring(1) === section.id) {
                            link.classList.add('active');
                        }
                    });
                }
            });
        });

        // Animação de fade-in nas seções
        document.addEventListener('DOMContentLoaded', function() {
            const sections = document.querySelectorAll('.section');
            sections.forEach(section => {
                section.style.opacity = 0;
                section.style.transition = 'opacity 1s ease-in-out';
            });

            function revealSections() {
                sections.forEach(section => {
                    const sectionTop = section.getBoundingClientRect().top;
                    const viewportHeight = window.innerHeight;
                    if (sectionTop < viewportHeight - 100) {
                        section.style.opacity = 1;
                    }
                });
            }

            window.addEventListener('scroll', revealSections);
            revealSections();
        });
    </script>
</body>
</html>
