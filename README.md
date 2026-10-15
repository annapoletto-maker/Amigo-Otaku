<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Nakama Store | Anime e cultura geek</title>
<meta name="description" content="Action figures, mangás, camisetas e decoração dos animes que você ama.">
<link href="https://fonts.googleapis.com/css2?family=Dela+Gothic+One&family=Nunito:wght@700;800&display=swap" rel="stylesheet">
<style>
/* ===== Cores e configurações gerais ===== */
:root{--noite:#1B1340;--creme:#FFF8F0;--rosa:#FF3D7F;--azul:#12B5E5;--amarelo:#FFC800}
*,*::before,*::after{box-sizing:border-box}
body{margin:0;min-height:100vh;background-color:var(--noite);
  background-image:radial-gradient(rgba(255,248,240,.10) 2px,transparent 2.2px);background-size:16px 16px;
  color:var(--creme);font-family:'Nunito',system-ui,sans-serif;font-size:18px;line-height:1.5}
h1,h2{font-family:'Dela Gothic One',Impact,sans-serif;font-weight:400;margin:0;line-height:1.05}
.pagina{max-width:880px;margin:0 auto;padding:36px 22px 48px;display:flex;flex-direction:column;gap:32px}
:focus-visible{outline:3px solid var(--azul);outline-offset:3px}

/* ===== Topo ===== */
.topo{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap}
.logo{font-family:'Dela Gothic One',sans-serif;font-size:2rem}
.logo span{color:var(--rosa)}
.topo p{margin:0;font-weight:800}

/* ===== Balão de fala (título principal) ===== */
.balao{position:relative;background:var(--creme);color:var(--noite);border:6px solid var(--creme);
  border-radius:36px;padding:38px 34px 40px;box-shadow:12px 12px 0 var(--rosa)}
.balao h1{font-size:clamp(2.2rem,8vw,4.6rem);max-width:12em}
.balao p{font-weight:800;font-size:1.3rem;max-width:30em;margin:16px 0 26px}

/* ===== Botão que leva para o site de vendas ===== */
.botao{display:inline-block;background:var(--rosa);color:#fff;text-decoration:none;
  font-family:'Dela Gothic One',sans-serif;font-size:1.5rem;padding:16px 34px;
  border:4px solid var(--noite);border-radius:14px;box-shadow:6px 6px 0 var(--noite);
  transition:transform .1s,box-shadow .1s}
.botao:hover{transform:translate(3px,3px);box-shadow:3px 3px 0 var(--noite)}

/* ===== Painéis estilo mangá ===== */
.paineis{display:grid;grid-template-columns:1.15fr 1fr;grid-template-rows:1fr 1fr;gap:14px;min-height:360px}
.painel{border:6px solid var(--creme);display:flex;align-items:center;justify-content:center;
  gap:16px;color:var(--noite);padding:16px}
.painel h2{font-size:1.7rem}
.painel svg{flex:none}
.p1{grid-row:span 2;flex-direction:column;background:var(--rosa);transform:rotate(-1.2deg)}
.p1 h2{font-size:2.1rem;color:var(--creme)}
.p2{background:var(--azul);transform:rotate(1.2deg)}
.p3{background:var(--amarelo);transform:rotate(-.8deg)}

/* ===== Vantagens ===== */
.vantagens{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
.vantagens div{border:4px solid var(--creme);border-radius:12px;padding:14px 18px;font-weight:800}

/* ===== Chamada final ===== */
.final{background:var(--rosa);border:5px solid var(--creme);border-radius:16px;padding:22px 26px;
  display:flex;justify-content:space-between;align-items:center;gap:18px;flex-wrap:wrap}
.final h2{font-size:2rem;color:#fff}
.final .botao{background:var(--amarelo);color:var(--noite)}
.rodape{text-align:center;font-size:.9rem;opacity:.8}

/* ===== Celular ===== */
@media (max-width:700px){
  .paineis{grid-template-columns:1fr;grid-template-rows:auto}
  .p1{grid-row:auto;flex-direction:row}
  .vantagens{grid-template-columns:1fr}
  .balao{padding:28px 22px 32px}
}
@media (prefers-reduced-motion:reduce){*{transition:none!important}}
</style>
</head>
<body>
<main class="pagina">

  <!-- Topo com o nome da loja -->
  <header class="topo">
    <div class="logo">NAKAMA<span>STORE</span></div>
    <p>Anime e cultura geek</p>
  </header>

  <!-- Título principal + botão -->
  <section class="balao">
    <h1>Sua coleção começa aqui!</h1>
    <p>Figures, mangás, camisetas e decoração dos animes que você ama.</p>
    <!-- TROQUE o link abaixo pelo endereço do site de vendas -->
    <a class="botao" href="https://www.nakamastore.com.br" target="_blank" rel="noopener">Ir para a loja</a>
  </section>

  <!-- Categorias em painéis de mangá -->
  <section class="paineis" aria-label="Categorias">
    <div class="painel p1">
      <svg width="150" height="150" viewBox="0 0 120 120" aria-hidden="true">
        <polygon points="88,18 102,32 52,84 38,70" fill="#FFF8F0" stroke="#1B1340" stroke-width="5" stroke-linejoin="round"/>
        <polygon points="34,78 50,62 58,70 42,86" fill="#FFC800" stroke="#1B1340" stroke-width="5" stroke-linejoin="round"/>
        <line x1="40" y1="82" x2="22" y2="100" stroke="#1B1340" stroke-width="9" stroke-linecap="round"/>
      </svg>
      <h2>Action figures</h2>
    </div>
    <div class="painel p2">
      <svg width="84" height="84" viewBox="0 0 120 120" aria-hidden="true">
        <rect x="28" y="20" width="66" height="84" rx="4" fill="#FFF8F0" stroke="#1B1340" stroke-width="5"/>
        <line x1="44" y1="20" x2="44" y2="104" stroke="#1B1340" stroke-width="5"/>
        <line x1="56" y1="44" x2="82" y2="44" stroke="#1B1340" stroke-width="5" stroke-linecap="round"/>
        <line x1="56" y1="60" x2="76" y2="60" stroke="#1B1340" stroke-width="5" stroke-linecap="round"/>
      </svg>
      <h2>Mangás</h2>
    </div>
    <div class="painel p3">
      <svg width="84" height="84" viewBox="0 0 120 120" aria-hidden="true">
        <path d="M40 22 L18 40 L32 58 L44 49 L44 98 L76 98 L76 49 L88 58 L102 40 L80 22 Q60 38 40 22Z" fill="#FFF8F0" stroke="#1B1340" stroke-width="5" stroke-linejoin="round"/>
      </svg>
      <h2>Camisetas</h2>
    </div>
  </section>

  <!-- Vantagens -->
  <section class="vantagens" aria-label="Vantagens">
    <div>Produtos 100% originais</div>
    <div>Envio para todo o Brasil</div>
    <div>Compra segura</div>
  </section>

  <!-- Chamada final -->
  <section class="final">
    <h2>Compre agora</h2>
    <a class="botao" href="https://www.nakamastore.com.br" target="_blank" rel="noopener">Ir para a loja</a>
  </section>

  <footer class="rodape">© 2026 Nakama Store. Projeto acadêmico, loja fictícia.</footer>
</main>
</body>
</html>
