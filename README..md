<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desenvolvedor Astronauta</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Desenvolvedor Astronauta</h1>
        <p>Explorando o universo do código 🚀</p>
    </header>

    <main>
        <section class="profile">
            <img src="astronaut.png" alt="Astronauta" class="astronaut">
            <h2>Olá, eu sou [Seu Nome]</h2>
            <p>Um desenvolvedor apaixonado por tecnologia, inovação e o vasto universo da programação.</p>
        </section>

        <section class="links">
            <h3>Minhas Constelações:</h3>
            <ul>
                <li><a href="https://github.com/seu-usuario" target="_blank">🌌 Meu GitHub</a></li>
                <li><a href="https://linkedin.com/in/seu-usuario" target="_blank">👨‍🚀 LinkedIn</a></li>
                <li><a href="https://meu-portifolio.com" target="_blank">🌠 Portfólio</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>Desenvolvido com ❤️ no cosmos. © 2024</p>
    </footer>
</body>
</html>

<style>

/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    color: #ffffff;
    background: radial-gradient(circle, #000428, #004e92);
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
}

/* Header */
header {
    text-align: center;
    margin-top: 2rem;
}

header h1 {
    font-size: 3rem;
    color: #ffdd00;
    text-shadow: 0 0 10px #ffdd00, 0 0 20px #ffdd00;
}

header p {
    font-size: 1.2rem;
    margin-top: 0.5rem;
    color: #ffffffcc;
}

/* Perfil */
.profile {
    text-align: center;
    margin: 2rem 0;
}

.profile .astronaut {
    width: 150px;
    animation: float 3s infinite ease-in-out;
}

.profile h2 {
    margin-top: 1rem;
    font-size: 2rem;
}

.profile p {
    font-size: 1.1rem;
    margin-top: 0.5rem;
    color: #c0c0c0;
}

/* Links */
.links {
    text-align: center;
}

.links h3 {
    font-size: 1.8rem;
    margin-bottom: 1rem;
    color: #ffdd00;
}

.links ul {
    list-style: none;
}

.links li {
    margin: 0.5rem 0;
}

.links a {
    text-decoration: none;
    color: #ffffff;
    font-size: 1.2rem;
    transition: color 0.3s;
}

.links a:hover {
    color: #ffdd00;
}

/* Footer */
footer {
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
    background: rgba(0, 0, 0, 0.8);
    width: 100%;
}

/* Animação */
@keyframes float {
    0%, 100% {
        transform: translateY(0);
    }
    50% {
        transform: translateY(-20px);
    }
}


</style>
