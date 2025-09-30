<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="google-adsense-account" content="ca-pub-3305836590830208">    
<title>Limpster Soluções em Limpeza - Residencial, Comercial e Pós-Obra</title>

<!-- SEO -->
<meta name="description" content="A Limpster oferece serviços de limpeza residencial, comercial e pós-obra em São Paulo. Atendimento rápido, profissional e com excelência.">
<meta name="keywords" content="limpeza, limpeza residencial, limpeza comercial, limpeza pós-obra, diarista, faxina, higienização, Limpster">
<meta name="author" content="Limpster">
<link rel="icon" href="ico.png" type="image/png">

<!-- Open Graph (para redes sociais) -->
<meta property="og:title" content="Limpster Soluções em Limpeza">
<meta property="og:description" content="Sua limpeza rápida e profissional. Deixe sua casa ou empresa brilhando com a Limpster.">
<meta property="og:image" content="comercial.png">
<meta property="og:url" content="https://leand90.github.io/serviceslimpster">
<meta property="og:type" content="Limpster Service e Qualidade">

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<style>

/* Card de Faxina Residencial */
#planos .service-card:nth-child(1) {
    background-image: url('https://media.istockphoto.com/id/870219332/pt/foto/cleaning-lady-with-a-bucket-and-cleaning-products.jpg?s=612x612&w=0&k=20&c=onJR8R7GYy3Zc9fw-d6m0NWevZbCJz_9p6GMaynMeX8='); /* Imagem Residencial */
    background-size: cover;
    background-position: center;
    color: white;
    
}

/* Card de Faxina Comercial */
#planos .service-card:nth-child(2) {
    background-image: url('https://media.istockphoto.com/id/2149432163/pt/foto/smiling-caucasian-female-construction-worker-on-the-site.jpg?s=612x612&w=0&k=20&c=p-W16aqCNtt68xNj3zXkZsaEMAWxEubSVIZr0Q4DdDc='); /* Imagem Comercial */
    background-size: cover;
    background-position: center;
    color: white;
}

/* Card de Faxina Pós-Obra */
#planos .service-card:nth-child(3) {
    background-image: url('https://plus.unsplash.com/premium_photo-1661662878810-67afdda3ef6f?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTAxfHxlcXVpcGFtZW50byUyMGxpbXBlemF8ZW58MHx8MHx8fDA%3D'); /* Imagem Pós-Obra */
    background-size: cover;
    background-position: center;
    color: white;
}




/* --- ESTILOS GLOBAIS --- */
body { 
    font-family: 'Segoe UI', Arial, sans-serif; 
    margin: 0; 
    line-height: 1.6;
    padding: 0;
    background: #fff;
    color: #333;
}

header { 
    background: #00ADEF; 
    color: white; 
    padding: 15px 20px;
    display: flex; 
    flex-wrap: wrap;
    justify-content: space-between; 
    align-items: center; 
    position: sticky;
    top: 0;
    z-index: 1000;
}

header h1 {
    margin: 0;
    font-size: 1.5em;
    font-weight: bold;
}

nav {
    display: flex;
    align-items: center;
}

nav a { 
    color: white; 
    margin: 0 10px; 
    text-decoration: none; 
    transition: 0.3s;
    font-weight: 500;
}
nav a:hover {
    color: #FFD700;
}

nav .btn-agendar {
    background: #FFD700;
    color: #333;
    padding: 8px 15px;
    border-radius: 5px;
    font-weight: bold;
    transition: 0.3s;
    margin-left: 10px;
    cursor: pointer;
}
nav .btn-agendar:hover {
    background: #3f75eb;
    color: #FFB800;
}


h1{color: #fdfcfc;  text-shadow: 
        1px 1px 0 #0c0c0c,  /* contorno amarelo */
        -2px 1px 0 #3485f0,
        1px -1px 0 #3485f0,
        -1px -1px 0 #FFD700,
        0px 0px 2px #fafaf8; /* brilho suave */
   }

/* HERO */
.hero { 
    background: linear-gradient(to right, #00ADEF, #00C9A7); 
    padding: 60px 20px; 
    text-align: center; 
    color: white;
}
.hero h2 {
    font-size: 2em;
    margin-bottom: 10px;
}
.hero p {
    font-size: 1.2em;
    margin-bottom: 20px;
}
.hero button { 
    background: #FFD700; 
    color: #333; 
    padding: 12px 25px;
    border: none; 
    cursor: pointer; 
    border-radius: 5px;
    font-size: 1.1em;
    font-weight: bold;
    transition: 0.3s;
    cursor: pointer;
}
.hero button:hover {
    background-color: #FFB800; 
    color: black;
    cursor: pointer;
}

/* CARROSSEL */
.carrossel { 
    position: relative; 
    max-width: 100%; 
    margin: auto; 
    overflow: hidden; 
}
.slides .slide {
    position: relative;
    display: none;
}
.slides img { 
    width: 100%; 
    max-height: 600px;
    object-fit: cover; 
    border-radius: 5px;
}
.caption {
    position: absolute;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);
    background: rgba(0,0,0,0.6);
    color: #fff;
    padding: 10px 20px;
    border-radius: 8px;
    text-align: center;
    width:900%;
}
.caption h3 {
    margin: 0;
    font-size: 1.5em;
    font-weight: bold;
    color: #FFD700;
}
.caption p {
    margin: 5px 0 0;
    font-size: 1em;
}
.prev, .next { 
    cursor: pointer; 
    position: absolute; 
    top: 50%; 
    padding: 12px; 
    color: white; 
    font-size: 22px; 
    border: none; 
    background-color: rgba(0,0,0,0.5); 
    transform: translateY(-50%); 
    z-index: 10;
    border-radius: 50%;
}
.prev { left: 15px; }
.next { right: 15px; }

/* SERVICES */
.services {
    background: #F5F5F5;
    padding: 50px 20px;
    display: grid; 
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); 
    gap: 25px; 
    text-align: center; 
}

.service-card {
    background: white;
    padding: 25px; 
    border-radius: 12px; 
    box-shadow: 0 4px 12px rgba(0,0,0,0.1); 
    transition: 0.3s ease;
}
.service-card:hover {
    transform: translateY(-5px); 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2);
}
.service-icon {
    font-size: 40px; 
    color: white; 
    width: 70px; 
    height: 70px;
    line-height: 70px; 
    display: inline-block; 
    margin-bottom: 15px; 
    border-radius: 50%; 
    background-color: #00ADEF; 
}

.service-card h3 {
    color: #00ADEF; 
    margin-top: 0;
}
.service-card p {
    color: #555; 
    font-size: 0.95em;
}

/* ABOUT */
#Sobre {
    padding: 50px 20px; 
    text-align: center;
}

/* CONTACT */
#Contato {
    padding: 50px 20px; 
    background: #F5F5F5; 
    text-align: center;
}
#Contato p {
    font-size: 1.1em;
}

/* TESTIMONIALS */
.testimonials { 
    padding: 50px 20px; 
    background: white; 
    text-align: center;
}
.testimonial-card {
    background: #f9f9f9;
    padding: 20px;
    margin: 15px auto;
    border-radius: 10px;
    max-width: 600px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    font-style: italic;
}

/* FOOTER */
footer { 
    background: #00ADEF; 
    color: white; 
    padding: 20px 10px;
    text-align: center; 
}
footer p {
    margin: 5px 0;
}
.social-icons a {
    text-decoration: none;
    margin: 0 8px;
    display: inline-block;
    color: white;
}
.social-icon {
    font-size: 24px; 
    transition: 0.3s;
}
.social-icon:hover {
    color: #FFD700; 
}

/* RESPONSIVO */
@media (max-width: 768px) {
    header {
        flex-direction: column;
        text-align: center;
    }
    nav {
        flex-direction: column;
    }
    nav a, nav .btn-agendar {
        margin: 8px 0;
    }
    .hero {
        padding: 40px 15px;
    }
    .slides img {
        height: auto;
    }
}


</style>
</head>
<body>
<header>
    <h1>Limpster</h1>
    <nav>
        <a href="index.html">Home</a> 
        <a href="#Sobre">Sobre Nós</a>   
        <a href="#servicos">Serviços</a> 
        <a href="#Contato">Contato</a>
        <a href="https://wa.me/5511961413348?text=Olá! Tudo bem?! Gostaria de agendar um serviço com a Limpster - Serviços e Qualidade!" class="btn-agendar" target="_blank">
            <i class="fa-brands fa-whatsapp"></i> Agendar
        </a>
    </nav>
</header>

<section class="carrossel">
    <div class="slides">
        <div class="slide">
            <img src="comercial.png" alt="Limpeza Residencial">
            <div class="caption">
                <h3>LIMPEZA CASA & APARTAMENTO</h3>
                <p>Conforto e higiene para sua família.</p>
            </div>
        </div>
        <div class="slide">
            <img src="comercial.png" alt="Limpeza Comercial">
            <div class="caption">
                <h3>PARA A SUA EMPRESA</h3>
                <p>Ambiente limpo para mais produtividade.</p>
            </div>
        </div>
        <div class="slide">
            <img src="comercial.png" alt="Limpeza Pós-Obra">
            <div class="caption">
                <h3>PARA A SUA OBRA</h3>
                <p>Deixe tudo pronto após a reforma.</p>
            </div>
        </div>
    </div>
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
</section>

<!--- CARDS PREÇOS-->

<section id="planos" class="services">
    <!-- Card de Faxina Residencial -->
    <div class="service-card">
        <div class="card-overlay"></div>
        <div class="card-content">
           
            <h1>Escolha Faxina Apenas Dia</h1>
            <button  id="btn-agendar"  onclick="enviarWhatsApp('Faxina Apenas Dia')" style="background:#FFD700;color:#333;padding:10px 20px;border:none;border-radius:5px;">
                ORÇAMENTO
            </button>
        </div>
    </div>

    <!-- Card de Faxina Comercial -->
    <div class="service-card">
        <div class="card-overlay"></div>
        <div class="card-content">
            
            <h1>Escolha Faxina para a Semana</h1>
                <button onclick="enviarWhatsApp('Faxina Semana')" style="background:#FFD700;color:#333;padding:10px 20px;border:none;border-radius:5px;">
                    ORÇAMENTO
            </button>
        </div>
    </div>

    <!-- Card de Faxina Pós-Obra -->
    <div class="service-card">
        <div class="card-overlay"></div>
        <div class="card-content">
            
            <h1>Escolha Faxina para o Mês</h1>
            <button onclick="enviarWhatsApp('Faxina Mensal')" style="background:#FFD700;color:#333;padding:10px 20px;border:none;border-radius:5px;">
                ORÇAMENTO
            </button>
        </div>
    </div>
</section>





<!-- FIM -->
<section class="hero">
    <center><img src="ico_02.png" width="120" height="120" title="Limpster - Serviços de Limpeza!"></center>
    <h2>Sua limpeza rápida e profissional</h2>
    <p>Deixe sua casa brilhando com a Limpster</p>
    <button id="btn-agendar">Agende Agora</button>
</section>

<section id="servicos" class="services">
    <div class="service-card">
        <i class="fa-solid fa-house-chimney service-icon"></i> 
        <h3>Faxina Residencial</h3>
        <p>Limpeza detalhada de casas e apartamentos, focada no seu conforto e bem-estar.</p>
    </div>
    <div class="service-card">
        <i class="fa-solid fa-building service-icon"></i> 
        <h3>Faxina Comercial</h3>
        <p>Soluções de limpeza eficientes para escritórios, lojas e espaços corporativos.</p>
    </div>
    <div class="service-card">
        <i class="fa-solid fa-hard-hat service-icon"></i> 
        <h3>Limpeza Pós-Obra</h3>
        <p>Remoção completa de resíduos e poeira após reformas e construções.</p>
    </div>
</section>

<section id="Sobre">
    <h2>Sobre Nós</h2>
    <p>Somos a Limpster, referência em limpeza residencial e comercial. Nossa missão é entregar um serviço impecável com agilidade, qualidade e confiança.</p>
</section>

<section id="Contato">
    <h2>Entre em Contato</h2>
    <p>📧 ldsantana692@mail.com | 📞 +55 (11)96141-3348  <br> 
    <a href="https://wa.me/5511961413348" target="_blank" style="color:#00ADEF;font-weight:bold;">
        <i class="fa-brands fa-whatsapp"></i> Fale no WhatsApp
    </a></p>
</section>

<section class="testimonials">
    <h3>Depoimentos</h3>
    <div class="testimonial-card">
        <p>Contratei a Limpster para a limpeza pós-obra e fiquei impressionado com o cuidado e a qualidade. Minha casa nunca esteve tão impecável!” — João P., São Paulo</p>
    </div>
    <div class="testimonial-card">
     <p>"Excelente serviço! Atendimento rápido, equipe simpática e resultado perfeito. Recomendo!” — Maria L., São Paulo</p>
    </div>
</section>

<footer>
    <p>© Limpster — Soluções em Limpeza. Todos os direitos reservados.</p>
</footer>

<script>
/* Botão Agendar do HERO */
document.getElementById("btn-agendar").addEventListener("click", function() {
    let numero = "5511961413348"; 
    let mensagem = "Olá! tudo bem?! Gostaria de agendar um serviço com a Limpster - Serviços e Qualidade!";
    let url = `https://wa.me/${numero}?text=${encodeURIComponent(mensagem)}`;
    window.open(url, "_blank");
});

/* Carrossel */
let slideIndex = 1; 
let timer;
showSlides(slideIndex);

function plusSlides(n) {
    clearTimeout(timer);
    showSlides(slideIndex += n);
}
function showSlides(n) {
    let i;
    let slides = document.querySelectorAll(".slides .slide");
    if (n > slides.length) { slideIndex = 1 }    
    if (n < 1) { slideIndex = slides.length }
    for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";  
    }
    slides[slideIndex - 1].style.display = "block";
    clearTimeout(timer);
    timer = setTimeout(() => {
        slideIndex++;
        showSlides(slideIndex);
    }, 5000); 
}
</script>

<script>
    function enviarWhatsApp(plano) {
    let numero = "5511961413348";
    let mensagem = `Olá! Tudo Bom?! Quero um orçamento para o plano: ${plano} com a Limpster.`;
    let url = `https://wa.me/${numero}?text=${encodeURIComponent(mensagem)}`;
    window.open(url, "_blank");
    }
    </script>
</body>
</html>
