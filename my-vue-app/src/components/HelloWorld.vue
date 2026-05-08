<template>
  <div class="page">
    <header>
      <nav class="nav">
        <ul class="nav-link">
          <li><a href="#">Home</a></li>
          <li><a href="#">Case Studies</a></li>
          <li><a href="#">Testimonials</a></li>
          <li><a href="#">Recent work</a></li>
          <li><a href="#">Get In Touch</a></li>
        </ul>
        <div class="social-icons">
          <a href="#"><i class="fab fa-linkedin-in"></i></a>
          <a href="#"><i class="fab fa-behance"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
        </div>
      </nav>
    </header>

    <main class="container">
      <section class="hero">
        <div class="texto-esquerda">
          <h1>Your Name Here</h1>
          <p>Intro text: Lorem ipsum dolor sit amet, consectetur adipiscing elit,
             sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <button class="btn-verde">Let's get started ›</button>
        </div>

        <div class="client-photo">
          <img src="../components/imgs/Photo here.png" alt="Foto">
        </div>
      </section>

      <section class="worked-with">
        <p class="worked-title">Worked with</p>
        <div class="logos">
          <div class="logo-box">⚙ ClickUp</div>
          <div class="logo-box">❄ Dropbox</div>
          <div class="logo-box">PAYCHEX</div>
          <div class="logo-box">✿ elastic</div>
          <div class="logo-box">stripe</div>
        </div>
      </section>
    </main>
  </div>
</template>

<script>
export default { name: 'HelloWorld' }
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono&family=Raleway:wght@800&display=swap');
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css');

* { box-sizing: border-box; }

body {
  background-color: #080808;
  margin: 0;
  font-family: 'IBM Plex Mono', monospace;
  color: #fff;
}

.page { min-height: 100vh; }

/* ===== NAVBAR colada no topo ===== */
.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 60px;
  background: #1a1a1a;
  margin: 0 60px;          /* sem margin-top, fica colada no topo */
  padding: 0 40px;
  border-bottom-left-radius: 14px;
  border-bottom-right-radius: 14px;
}

.nav-link {
  display: flex;
  gap: 50px;
  list-style: none;
  margin: 0;
  padding: 0;
}

.nav-link a {
  color: #9C9C9C;
  text-decoration: none;
  font-size: 14px;
}

.social-icons { display: flex; gap: 20px; }
.social-icons a { color: #9C9C9C; font-size: 16px; text-decoration: none; }

/* ===== Container centralizado (alinha hero e logos) ===== */
.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 40px;
}

/* ===== HERO centralizado verticalmente ===== */
.hero {
  display: flex;
  align-items: center;        /* centraliza vertical texto x foto */
  justify-content: space-between;
  gap: 80px;
  min-height: calc(100vh - 60px - 200px); /* tela - navbar - área dos logos */
  padding: 40px 0;
}

.texto-esquerda { max-width: 420px; }

.texto-esquerda h1 {
  font-family: 'Raleway', sans-serif;
  font-weight: 800;
  font-size: 44px;
  margin: 0 0 20px 0;
}

.texto-esquerda p {
  color: #9C9C9C;
  font-size: 14px;
  line-height: 1.7;
  margin-bottom: 30px;
}

.btn-verde {
  font-family: 'IBM Plex Mono', monospace;
  background-color: #5BC236;
  color: #fff;
  border: none;
  padding: 16px 32px;
  font-size: 14px;
  font-weight: bold;
  border-radius: 4px;
  cursor: pointer;
}

.client-photo img {
  width: 280px;
  height: 280px;
  border-radius: 50%;
  object-fit: cover;
}

/* ===== WORKED WITH (mesmo alinhamento do hero, via .container) ===== */
.worked-with { padding-bottom: 60px; }

.worked-title {
  font-size: 13px;
  margin: 0 0 20px 0;
}

.logos { display: flex; gap: 16px; }

.logo-box {
  flex: 1;
  border: 1px solid #2a2a2a;
  border-radius: 8px;
  padding: 22px 0;
  text-align: center;
  color: #9C9C9C;
  font-size: 14px;
}
</style>
