# agrotec-sustentavel
Projeto Agrinho 2026 - Agro forte, futuro sustentável.
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agrinho 2026 - Agro Forte, Futuro Sustentável</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background:#f4f9f4;
    color:#333;
}

header{
    background:linear-gradient(135deg,#2e7d32,#66bb6a);
    color:white;
    text-align:center;
    padding:60px 20px;
}

header h1{
    font-size:3rem;
}

header p{
    margin-top:15px;
    font-size:1.2rem;
}

nav{
    background:#1b5e20;
    padding:15px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:bold;
}

section{
    padding:50px 10%;
}

.card{
    background:white;
    padding:25px;
    margin:20px 0;
    border-radius:15px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

h2{
    color:#2e7d32;
    margin-bottom:15px;
}

.galeria{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.galeria img{
    width:100%;
    border-radius:10px;
}

footer{
    background:#1b5e20;
    color:white;
    text-align:center;
    padding:20px;
}
</style>

</head>
<body>

<header>
    <h1>🌱 Agrinho 2026</h1>
    <p>Agro Forte, Futuro Sustentável</p>
</header>

<nav>
    <a href="#sobre">Sobre</a>
    <a href="#sustentabilidade">Sustentabilidade</a>
    <a href="#tecnologia">Tecnologia</a>
    <a href="#contato">Contato</a>
</nav>

<section id="sobre">
    <div class="card">
        <h2>Sobre o Projeto</h2>
        <p>
            Este projeto foi desenvolvido para o Agrinho 2026 com o objetivo
            de mostrar como o agronegócio pode crescer de forma sustentável,
            preservando o meio ambiente e utilizando novas tecnologias.
        </p>
    </div>
</section>

<section id="sustentabilidade">
    <div class="card">
        <h2>🌿 Sustentabilidade no Campo</h2>
        <p>
            A sustentabilidade ajuda a preservar a água, o solo e a biodiversidade.
            Práticas como irrigação inteligente, energia solar e reciclagem
            contribuem para um futuro melhor.
        </p>
    </div>
</section>

<section id="tecnologia">
    <div class="card">
        <h2>🚜 Tecnologia no Agro</h2>
        <p>
            Drones, sensores, inteligência artificial e robótica auxiliam os
            produtores a aumentar a produtividade reduzindo impactos ambientais.
        </p>
    </div>

    <div class="galeria">
        <img src="https://images.unsplash.com/photo-1500937386664-56d1dfef3854?w=800" alt="Plantação">
        <img src="https://images.unsplash.com/photo-1500382017468-9049fed747ef?w=800" alt="Campo">
        <img src="https://images.unsplash.com/photo-1464226184884-fa280b87c399?w=800" alt="Agricultura">
    </div>
</section>

<section id="contato">
    <div class="card">
        <h2>📧 Contato</h2>
        <p>Email: seuemail@escola.com</p>
        <p>Escola: Nome da sua escola</p>
        <p>Cidade: Sua cidade</p>
    </div>
</section>

<footer>
    <p>© 2026 Projeto Agrinho - Desenvolvido para GitHub Pages</p>
</footer>

</body>
</html>
