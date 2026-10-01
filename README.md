# -apymi-
<header>
<h1>ÑAPYMI</h1>
<p>Equipe de Robótica Subaquática - ROV Tridente</p>
<nav>
<a href="#conceito">Conceito</a>
<a href="#identidade">Identidade</a>
<a href="#patrocinio">Patrocínio</a>
<a href="#estrutura">Estrutura</a>
<a href="#site">Site</a>
</nav>
</header>

<section id="conceito">
<h2>1 - Conceito</h2>
<p>ÑAPYMI vem de [significado de vocês] - equipe que une mar e tecnologia. Nosso ROV se chama Tridente.</p>
</section>

<section id="identidade">
<h2>2 - Identidade Visual</h2>
<p>Azul marinho antichamas #0A1931, azul claro #4CC9F0 e dourado. Mascote: Siri azul com boné e óculos.</p>
</section>

<section id="patrocinio">
<h2>3 e 4 - Growth - Captação e Visibilidade</h2>
<p>Patrocinadores: Governo do Estado do Rio de Janeiro, 1001 Transportes, Monster Energy, PaleBlue. Plano de visibilidade: uniforme, site, Instagram.</p>
</section>

<section id="estrutura">
<h2>5 e 8 - Pessoas e Cultura + Estrutura Organizacional</h2>
<p><b>Pessoas e Cultura:</b> diversidade, ciclo do membro, treinamento de novatos<br>
<b>Núcleo Técnico do Submarino (Tridente):</b> Mecânica, Elétrica, Software<br>
<b>Operações Financeiras:</b> diagnóstico 12 meses<br>
<b>Marca e Design:</b> ÑAPYMI Racing Team</p>
</section>


*{margin:0;padding:0;box-sizing:border-box}
body{font-family:Arial,sans-serif;background:#eef5ff;color:#0A1931}
header{background:#0A1931;color:white;text-align:center;padding:40px 20px}
.logo{font-size:48px;font-weight:900;letter-spacing:3px;color:#4CC9F0;border:3px solid #D4AF37;display:inline-block;padding:10px 30px;border-radius:50px}

console.log("ÑAPYMI no ar");
document.querySelectorAll('nav a').forEach(link=>{
  link.addEventListener('click', e=>{
    e.preventDefault();
    document.querySelector(link.getAttribute('href')).scrollIntoView({behavior:'smooth'});
  });
});
nav{margin-top:20px}
nav a{color:#4CC9F0;margin:0 12px;text-decoration:none;font-weight:bold}
section{background:white;margin:25px auto;max-width:900px;padding:25px;border-radius:14px;box-shadow:0 4px 12px rgba(0,0,0,0.1)}
h2{border-left:6px solid #4CC9F0;padding-left:12px;margin-bottom:15px}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:15px}
.card{border:1px solid #cce0ff;padding:15px;border-radius:10px}
.card.destaque{grid-column:span 2;background:#0A1931;color:white}
footer{background:#0A1931;color:white;text-align:center;padding:20px;margin-top:30px}


