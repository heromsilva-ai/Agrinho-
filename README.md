Agro forte, futuro sustentável: equilíbrio entre produção e meio ambiente
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agro Forte, Futuro Sustentável</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
    scroll-behavior:smooth;
}

body{
    background:#f5f5f5;
    color:#333;
    line-height:1.6;
}

header{
    background:#2e7d32;
    padding:15px 8%;
    position:sticky;
    top:0;
    z-index:1000;
    box-shadow:0 2px 10px rgba(0,0,0,.2);
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    color:white;
    font-size:1.6rem;
    font-weight:bold;
}

nav ul{
    display:flex;
    list-style:none;
    gap:25px;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
    transition:.3s;
}

nav a:hover{
    color:#c8e6c9;
}

.hero{
    height:90vh;
    background:
    linear-gradient(rgba(0,0,0,.5), rgba(0,0,0,.5)),
    url('https://images.unsplash.com/photo-1500937386664-56d1dfef3854?auto=format&fit=crop&w=1400&q=80');
    background-size:cover;
    background-position:center;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
    padding:20px;
}

.hero-content{
    max-width:800px;
}

.hero h1{
    font-size:3.5rem;
    margin-bottom:20px;
}

.hero p{
    font-size:1.3rem;
    margin-bottom:30px;
}

.hero button{
    background:#4caf50;
    color:white;
    border:none;
    padding:15px 30px;
    font-size:1rem;
    border-radius:6px;
    cursor:pointer;
    transition:.3s;
}

.hero button:hover{
    background:#388e3c;
}

section{
    padding:80px 10%;
}

.titulo{
    text-align:center;
    margin-bottom:40px;
    color:#2e7d32;
}

.sobre{
    text-align:center;
}

.sobre p{
    max-width:900px;
    margin:auto;
    font-size:1.1rem;
}

.pilares{
    background:white;
}

.cards{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:25px;
}

.card{
    background:#e8f5e9;
    width:320px;
    padding:30px;
    border-radius:12px;
    text-align:center;
    transition:.3s;
    box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    color:#2e7d32;
    margin-bottom:15px;
}

.estatisticas{
    background:#2e7d32;
    color:white;
    text-align:center;
}

.numeros{
    display:flex;
    justify-content:center;
    gap:70px;
    flex-wrap:wrap;
    margin-top:30px;
}

.numero span{
    font-size:3rem;
    font-weight:bold;
    display:block;
}

.beneficios{
    background:#f9fff9;
}

.lista-beneficios{
    max-width:900px;
    margin:auto;
}

.lista-beneficios li{
    margin:15px 0;
    font-size:1.1rem;
}

.contato{
    text-align:center;
}

form{
    max-width:550px;
    margin:auto;
    display:flex;
    flex-direction:column;
    gap:15px;
}

input, textarea{
    padding:14px;
    border:1px solid #ccc;
    border-radius:6px;
    font-size:1rem;
}

textarea{
    min-height:120px;
    resize:none;
}

form button{
    background:#2e7d32;
    color:white;
    border:none;
    padding:14px;
    border-radius:6px;
    cursor:pointer;
    font-size:1rem;
}

form button:hover{
    background:#1b5e20;
}

footer{
    background:#1b5e20;
    color:white;
    text-align:center;
    padding:20px;
}

@media(max-width:768px){

    nav{
        flex-direction:column;
        gap:15px;
    }

    nav ul{
        flex-wrap:wrap;
        justify-content:center;
    }

    .hero h1{
        font-size:2.2rem;
    }

    .hero p{
        font-size:1rem;
    }

    .numeros{
        flex-direction:column;
        gap:30px;
    }
}
</style>
</head>
<body>

<header>
    <nav>
        <div class="logo">🌱 Agro Forte</div>

        <ul>
            <li><a href="#inicio">Início</a></li>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#pilares">Pilares</a></li>
            <li><a href="#beneficios">Benefícios</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>
</header>

<section class="hero" id="inicio">
    <div class="hero-content">
        <h1>Agro Forte, Futuro Sustentável</h1>
        <p>
            Equilíbrio entre produção e meio ambiente para garantir alimentos,
            desenvolvimento econômico e preservação dos recursos naturais.
        </p>

        <button onclick="irParaSobre()">
            Conheça o Projeto
        </button>
    </div>
</section>

<section id="sobre" class="sobre">
    <h2 class="titulo">Sobre o Tema</h2>

    <p>
        O agronegócio sustentável representa a união entre tecnologia,
        produtividade e responsabilidade ambiental. O objetivo é produzir
        alimentos de forma eficiente, preservando solos, recursos hídricos,
        florestas e a biodiversidade. Com inovação e boas práticas, o campo
        pode crescer sem comprometer o futuro das próximas gerações.
    </p>
</section>

<section id="pilares" class="pilares">
    <h2 class="titulo">Pilares da Sustentabilidade no Agro</h2>

    <div class="cards">

        <div class="card">
            <h3>🌳 Preservação Ambiental</h3>
            <p>
                Conservação de florestas, rios e ecossistemas através
                de práticas agrícolas responsáveis.
            </p>
        </div>

        <div class="card">
            <h3>🚜 Produção Eficiente</h3>
            <p>
                Uso de tecnologia, agricultura de precisão e inovação
                para aumentar a produtividade.
            </p>
        </div>

        <div class="card">
            <h3>👨‍🌾 Desenvolvimento Social</h3>
            <p>
                Valorização dos produtores rurais e fortalecimento
                das comunidades do campo.
            </p>
        </div>

    </div>
</section>

<section class="estatisticas">
    <h2>Impactos Positivos</h2>

    <div class="numeros">

        <div class="numero">
            <span id="contador1">0</span>
            <p>Hectares Recuperados</p>
        </div>

        <div class="numero">
            <span id="contador2">0</span>
            <p>Produtores Sustentáveis</p>
        </div>

        <div class="numero">
            <span id="contador3">0</span>
            <p>Projetos Ambientais</p>
        </div>

    </div>
</section>

<section id="beneficios" class="beneficios">
    <h2 class="titulo">Benefícios da Agricultura Sustentável</h2>

    <ul class="lista-beneficios">
        <li>✅ Redução do impacto ambiental.</li>
        <li>✅ Preservação da biodiversidade.</li>
        <li>✅ Uso consciente da água.</li>
        <li>✅ Maior eficiência produtiva.</li>
        <li>✅ Segurança alimentar para a população.</li>
        <li>✅ Desenvolvimento econômico e social.</li>
    </ul>
</section>

<section id="contato" class="contato">
    <h2 class="titulo">Participe Dessa Transformação</h2>

    <form onsubmit="enviarMensagem(event)">
        <input type="text" placeholder="Seu nome" required>
        <input type="email" placeholder="Seu e-mail" required>

        <textarea
        placeholder="Digite sua mensagem"></textarea>

        <button type="submit">Enviar Mensagem</button>
    </form>
</section>

<footer>
    <p>
        © 2026 Agro Forte - Futuro Sustentável |
        Produção e preservação caminhando juntas.
    </p>
</footer>

<script>
function irParaSobre(){
    document
    .getElementById("sobre")
    .scrollIntoView({behavior:"smooth"});
}

function contador(id, valorFinal){
    let valor = 0;
    let elemento = document.getElementById(id);

    let intervalo = setInterval(() => {

        valor += Math.ceil(valorFinal / 100);

        if(valor >= valorFinal){
            valor = valorFinal;
            clearInterval(intervalo);
        }

        elemento.textContent = valor.toLocaleString();

    }, 20);
}

window.onload = function(){
    contador("contador1", 5000);
    contador("contador2", 1200);
    contador("contador3", 350);
}

function enviarMensagem(event){
    event.preventDefault();
    alert("Mensagem enviada com sucesso! 🌱");
}
</script>

</body>
</html>
