<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Servidor IPTV Premium</title>

  <style>
    *{box-sizing:border-box;}
    body{
      margin:0;
      font-family:"Segoe UI", Arial, sans-serif;
      background:linear-gradient(180deg,#0f2027,#203a43,#2c5364);
      color:#f1f1f1;
      display:flex;
      flex-direction:column;
      align-items:center;
    }
    header{
      width:100%;
      max-width:900px;
      text-align:center;
      padding:30px 15px 20px;
    }
    header h1{color:#00ffd5;margin:10px 0;}
    header p{opacity:0.9;}

    section{width:100%;max-width:900px;padding:25px 15px;}

    .hero{text-align:center;}
    .hero img{
      width:100%;max-width:360px;border-radius:22px;
      box-shadow:0 12px 28px rgba(0,0,0,.55);
    }

    .beneficios{
      background:rgba(255,255,255,0.06);
      border-radius:22px;
    }
    .beneficios h2,.planos h2{color:#00ffd5;text-align:center;}
    .beneficios ul{list-style:none;padding:0;max-width:520px;margin:auto;}
    .beneficios li{
      background:rgba(0,0,0,.35);
      margin-bottom:12px;padding:14px;border-radius:14px;text-align:center;
    }

    .cards{
      display:grid;grid-template-columns:1fr;gap:18px;
      max-width:420px;margin:auto;text-align:center;
    }
    .card{
      background:rgba(0,0,0,.45);
      border-radius:24px;padding:24px 18px;
      box-shadow:0 10px 25px rgba(0,0,0,.5);
    }
    .price{font-size:1.8em;color:#00ffd5;margin:12px 0;}

    .btn{
      display:block;margin-top:16px;padding:14px;
      background:linear-gradient(135deg,#25D366,#1ebe5d);
      color:#fff;text-decoration:none;border-radius:30px;font-weight:bold;
    }
    .btn-ano{
      background:linear-gradient(135deg,#ffd700,#ffae00);
      color:#000;font-size:1.05em;
    }

    .whatsapp-fixo{
      position:fixed;bottom:18px;right:18px;
      background:linear-gradient(135deg,#25D366,#1ebe5d);
      color:#fff;padding:15px 17px;border-radius:50%;
      font-size:22px;text-decoration:none;
      box-shadow:0 6px 20px rgba(0,0,0,.6);
    }

    @media(min-width:768px){
      .cards{grid-template-columns:repeat(2,1fr);max-width:720px;}
    }
  </style>
</head>
<body>

<header>
  <a class="btn" style="max-width:200px;margin:0 auto 15px;background:linear-gradient(135deg,#00ffd5,#00bfa5);color:#003333;font-size:.85em;"
     href="https://wa.me/5585981743736?text=Olá,%20quero%20um%20TESTE%20GRÁTIS%20do%20IPTV">🎁 Teste Grátis</a>
  <h1>🔥 Servidor IPTV Premium 🔥</h1>
  <p>Qualidade máxima, estabilidade total e entretenimento sem limites</p>
</header>

<section class="hero">
  <img src="https://images.unsplash.com/photo-1524985069026-dd778a71c7b4" alt="IPTV Streaming">
</section>

<section class="beneficios">
  <h2>🚀 Benefícios do Servidor</h2>
  <ul>
    <li>✔ +10.000 canais, filmes e séries</li>
    <li>✔ Qualidade HD, Full HD e 4K</li>
    <li>✔ Alta estabilidade, sem travamentos</li>
    <li>✔ Funciona em TV, celular, TV Box e PC</li>
    <li>✔ Suporte direto pelo WhatsApp</li>
  </ul>
</section>

<section class="planos">
  <h2>💰 Planos Disponíveis</h2>
  <div class="cards">

    <div class="card">
      <h3>1 Mês</h3>
      <div class="price">R$ 25</div>
      <a href="#" class="btn" onclick="mostrarPix('1 Mês'); return false;">PIX: 85 99664-0269</a>
    </div>

    <div class="card">
      <h3>2 Meses</h3>
      <div class="price">R$ 50</div>
      <a href="#" class="btn" onclick="mostrarPix('2 Meses'); return false;">PIX: 85 99664-0269</a>
    </div>

    <div class="card">
      <h3>3 Meses</h3>
      <div class="price">R$ 75</div>
      <a href="#" class="btn" onclick="mostrarPix('3 Meses'); return false;">PIX: 85 99664-0269</a>
    </div>

    <div class="card">
      <h3>4 Meses</h3>
      <div class="price">R$ 100</div>
      <a href="#" class="btn" onclick="mostrarPix('4 Meses'); return false;">PIX: 85 99664-0269</a>
    </div>

    <div class="card" style="border:2px solid #00ffd5;">
      <h3>🔥 1 Ano 🔥</h3>
      <div class="price">R$ 250</div>
      <p>Plano mais vantajoso</p>
      <a href="#" class="btn btn-ano" onclick="mostrarPix('Plano Anual'); return false;">PIX: 85 99664-0269</a>
    </div>

  </div>
</section>

<a class="whatsapp-fixo"
   href="https://wa.me/5585981743736?text=Olá,%20preciso%20de%20AJUDA%20com%20o%20IPTV"
   title="Suporte">🛠️</a>

<footer>
  <p>© 2025 Servidor IPTV Premium</p>
</footer>

<script>
  function mostrarPix(plano){
    alert(
      'Plano escolhido: ' + plano + '\n\nPIX (Telefone): 85 99664-0269\n\nApós o pagamento você será direcionado ao WhatsApp.'
    );

    window.location.href =
      'https://wa.me/5585981743736?text=' +
      encodeURIComponent('Olá, realizei o pagamento do ' + plano + ' via PIX (85 99664-0269) e quero ativar meu IPTV');
  }
</script>

</body>
</html>
