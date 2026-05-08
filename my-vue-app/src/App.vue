<template>
  <div class="site">
    <header class="hero-section">
      <nav class="nav">
        <ul class="navegagar-links">
          <li><a href="#" class="active">Home</a></li>
          <li><a href="#">Case Studies</a></li>
          <li><a href="#">Testimonials</a></li>
          <li><a href="#">Recent work</a></li>
          <li><a href="#">Get In Touch</a></li>
        </ul>
        <div class="nnavegar-social">
          <img :src="midias" alt="social media" />
        </div>
      </nav>

      <div class="hero">
        <div class="hero-texto">
          <h1>Your Name Here</h1>
          <p>Intro text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <button class="btn-cta">
            Let's get started
            <span class="chev">›</span>
          </button>
        </div>
        <div class="hero-photo">
          <img :src="homem" alt="Portrait" />
        </div>
      </div>

      <div class="worked-with">
        <span class="worked-label">Worked with</span>
        <div class="logos">
          <div class="logo-pill"><img :src="clickup" alt="ClickUp" /></div>
          <div class="logo-pill"><img :src="dropbox" alt="Dropbox" /></div>
          <div class="logo-pill"><img :src="paychex" alt="Paychex" /></div>
          <div class="logo-pill"><img :src="elastic" alt="elastic" /></div>
          <div class="logo-pill"><img :src="stripe" alt="stripe" /></div>
        </div>
      </div>
    </header>

    <section class="case-studies">
      <div class="cs-head">
        <h2>Case Studies</h2>
        <p>Solving user &amp; business problems since last 15+ years. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>

      <article class="cs-row">
        <div class="cs-text">
          <span class="tag tag-fintech">Fintech</span>
          <h3>Work name here</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. sed do eiusmod tempor incididunt ut labore et dolore magna.</p>
          <button class="btn-case btn-orange">View case study <span class="chev">›</span></button>
        </div>
        <div class="cs-image"><img :src="csImg1" alt="Fintech work" /></div>
      </article>

      <article class="cs-row reverse">
        <div class="cs-image"><img :src="csImg2" alt="EdTech work" /></div>
        <div class="cs-text">
          <span class="tag tag-edtech">EdTech</span>
          <h3>Work name here</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. sed do eiusmod tempor incididunt ut labore et dolore magna.</p>
          <button class="btn-case btn-blue">View case study <span class="chev">›</span></button>
        </div>
      </article>

      <article class="cs-row">
        <div class="cs-text">
          <span class="tag tag-pharma">Pharma</span>
          <h3>Work name here</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. sed do eiusmod tempor incididunt ut labore et dolore magna.</p>
          <button class="btn-case btn-mint">View case study <span class="chev">›</span></button>
        </div>
        <div class="cs-image"><img :src="csImg3" alt="Pharma work" /></div>
      </article>
    </section>

    <section class="testimonials">
      <div class="ts-head">
        <h2>Testimonials</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>
      <div class="ts-grid">
        <div class="ts-card">
          <span class="ts-quote">“</span>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <div class="ts-client"><img :src="client1" alt="Client" /><span>Client Name</span></div>
        </div>
        <div class="ts-card">
          <span class="ts-quote">“</span>
          <p>Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <div class="ts-client"><img :src="client2" alt="Client" /><span>Client Name</span></div>
        </div>
        <div class="ts-card">
          <span class="ts-quote">“</span>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <div class="ts-client"><img :src="client3" alt="Client" /><span>Client Name</span></div>
        </div>
        <div class="ts-card">
          <span class="ts-quote">“</span>
          <p>Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <div class="ts-client"><img :src="client4" alt="Client" /><span>Client Name</span></div>
        </div>
      </div>
    </section>

    <section class="recent-work">
      <div class="rw-head">
        <h2>Recent Work</h2>
        <p>Solving user &amp; business problems since last 15+ years. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>
      <div class="rw-carousel">
        <button class="rw-arrow rw-prev" aria-label="Previous">
          <img :src="rwPrev" alt="" />
        </button>
        <div class="rw-grid">
          <article class="rw-card">
            <div class="rw-image"><img :src="rwImg1" alt="Recent work 1" /></div>
            <h3>Work name here</h3>
            <p>Labore et dolore magna aliqua. sed do eiusmod tempor incididunt ut labore et dolore magna.</p>
            <button class="btn-know">Know more <span class="chev">›</span></button>
          </article>
          <article class="rw-card">
            <div class="rw-image"><img :src="rwImg2" alt="Recent work 2" /></div>
            <h3>Work name here</h3>
            <p>Rempor incididunt ut labore et dolore magna aliqua. sed do eiusmod tempor incididunt u</p>
            <button class="btn-know">Know more <span class="chev">›</span></button>
          </article>
        </div>
        <button class="rw-arrow rw-next" aria-label="Next">
          <img :src="rwNext" alt="" />
        </button>
      </div>
    </section>

    <section class="get-in-touch">
      <div class="git-inner">
        <h2>Get In Touch</h2>
        <p class="git-desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        <form class="git-form" @submit.prevent>
          <label for="git-email">Email</label>
          <input id="git-email" type="email" placeholder="Please enter your email" />
          <label for="git-mobile">Mobile</label>
          <input id="git-mobile" type="tel" placeholder="Enter mobile" />
          <label for="git-message">Message</label>
          <textarea id="git-message" rows="5" placeholder="Enter your message"></textarea>
          <button type="submit" class="btn-submit">Submit <span class="chev">›</span></button>
        </form>
      </div>
    </section>

    <footer class="site-footer">
      <p>Copyright text <span class="heart">❤️</span></p>
    </footer>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@700;800;900&family=Raleway:wght@700;800;900&display=swap');
* { box-sizing: border-box; margin: 0; padding: 0; }
html, body, #app {
  width: 100%;
  background: #000;
  color: #fff;
  font-family: 'IBM Plex Mono', ui-monospace, monospace;
  overflow-x: hidden;
}
.site { width: 100%; }

.hero-section {
  width: 100%;
  min-height: 100vh;
  background: #080808;
  padding: 0 0 60px;
}

/* NAV */
.nav {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0 96px;
  height: 70px;
  flex-wrap: wrap;
  gap: 44px;
  background: #1a1a1a;
  margin-bottom: 70px;
  margin-left: 85px;
  margin-right: 85px;
  border-bottom-left-radius: 14px;
  border-bottom-right-radius: 14px;
}
.navegagar-links {
  list-style: none;
  display: flex;
  gap: 70px;
  flex: 1;
  margin: 0;
  padding-right: 0;
}
@media (max-width: 1200px) {
  .nav { margin-left: 6vw; margin-right: 6vw; padding: 0 6vw; }
}
@media (max-width: 700px) {
  .nav { margin-left: 3vw; margin-right: 3vw; padding: 18px 20px; height: auto; }
  .navegagar-links { flex-wrap: wrap; gap: 16px; padding-right: 0; justify-content: center; }
}
.navegagar-links a {
  color: #9C9C9C;
  text-decoration: none;
  font-size: 14px;
  line-height: 18px;
  opacity: 1;
  font-family: 'IBM Plex Mono', monospace;
}
.navegagar-links a.active { color: #9C9C9C; }
.nnavegar-social img { height: 16px; display: block; opacity: .85; }

.hero, .worked-with { padding-left: 12vw; padding-right: 12vw; }

/* HERO */
.hero {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 60px;
  align-items: center;
  padding: 30px 12vw 90px;
}
.hero-texto h1 {
  font-size: 48px;
  font-weight: 800;
  margin-bottom: 26px;
  line-height: 1.15;
  font-family: 'Raleway', sans-serif;
}
.hero-texto p {
  line-height: 1.7;
  color: #9C9C9C;
  margin-bottom: 36px;
  max-width: 420px;
  font-size: 14px;
}
.btn-cta {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background: #3F8E00;
  border: 1px solid #3F8E00;
  color: #fff;
  font-family: 'IBM Plex Mono', monospace;
  font-weight: 700;
  font-size: 14px;
  padding: 16px 28px;
  border-radius: 4px;
  cursor: pointer;
  box-shadow: 0 8px 30px rgba(63, 142, 0, 0.3);
}
.btn-cta .chev { font-size: 16px; line-height: 1; }

.hero-photo { display: flex; justify-content: center; }
.hero-photo img {
  width: 360px;
  height: 360px;
  border-radius: 50%;
  object-fit: cover;
}

/* WORKED WITH */
.worked-with { padding-top: 20px; }
.worked-label {
  display: block;
  font-size: 13px;
  color: #fff;
  margin-bottom: 22px;
  font-family: 'IBM Plex Mono', monospace;
}
.logos {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 18px;
}
.logo-pill {
  border: 1px solid #2a2a2a;
  border-radius: 4px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: transparent;
}
.logo-pill img {
  max-height: 22px;
  width: auto;
  opacity: .9;
}

@media (max-width: 900px) {
  .hero-section { padding: 24px 6vw 40px; }
  .divider { margin: 0 -6vw 40px; }
  .hero { grid-template-columns: 1fr; gap: 40px; }
  .hero-texto h1 { font-size: 36px; }
  .hero-photo img { width: 240px; height: 240px; }
  .navegagar-links { gap: 18px; flex-wrap: wrap; justify-content: center; }
  .logos { grid-template-columns: repeat(2, 1fr); }
}

/* CASE STUDIES */
.case-studies {
  background: #fff;
  color: #000;
  padding: 90px 12vw 100px;
  font-family: 'IBM Plex Mono', monospace;
}
.cs-head { text-align: center; max-width: 720px; margin: 0 auto 80px; }
.cs-head h2 {
  font-size: 36px;
  font-weight: 800;
  margin-bottom: 18px;
  color: #000;
  font-family: 'Raleway', sans-serif;
}
.cs-head p {
  color: #9C9C9C;
  font-size: 14px;
  line-height: 1.7;
}
.cs-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 80px;
  align-items: center;
  margin-bottom: 90px;
}
.cs-row.reverse .cs-text { order: 2; }
.cs-row.reverse .cs-image { order: 1; }
.cs-image img { width: 100%; height: auto; display: block; border-radius: 2px; }
.cs-text .tag {
  display: inline-block;
  padding: 6px 14px;
  border-radius: 25px;
  font-size: 12px;
  font-weight: 400;
  margin-bottom: 22px;
  font-family: 'IBM Plex Mono', monospace;
}
.tag-fintech { background: #FFF6E9; color: #FFA217; }
.tag-edtech { background: #D0E6FF; color: #000AFF; }
.tag-pharma { background: #E0FFF8; color: #2AB090; }
.cs-text h3 {
  font-size: 26px;
  font-weight: 800;
  margin-bottom: 18px;
  font-family: 'Raleway', sans-serif;
}
.cs-text p {
  color: #9C9C9C;
  font-size: 14px;
  line-height: 1.85;
  margin-bottom: 30px;
  max-width: 460px;
}
.btn-case {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 14px 22px;
  border: none;
  border-radius: 8px;
  color: #fff;
  font-family: 'IBM Plex Mono', monospace;
  font-weight: 700;
  font-size: 14px;
  cursor: pointer;
}
.btn-case .chev { font-size: 16px; line-height: 1; }
.btn-orange { background: #FFA217; box-shadow: 0 8px 24px rgba(243, 154, 31, 0.35); }
.btn-blue   { background: #000AFF; box-shadow: 0 8px 24px rgba(31, 75, 255, 0.35); }
.btn-mint   { background: #2AB090; box-shadow: 0 8px 24px rgba(79, 203, 160, 0.35); }

@media (max-width: 900px) {
  .case-studies { padding: 60px 6vw; }
  .cs-row { grid-template-columns: 1fr; gap: 30px; margin-bottom: 60px; }
  .cs-row.reverse .cs-text { order: 2; }
  .cs-row.reverse .cs-image { order: 1; }
}

/* TESTIMONIALS */
.testimonials {
  background: #080808;
  color: #fff;
  padding: 90px 12vw 100px;
  font-family: 'IBM Plex Mono', monospace;
}
.ts-head { text-align: center; max-width: 720px; margin: 0 auto 70px; }
.ts-head h2 { font-size: 36px; font-weight: 800; margin-bottom: 18px; color: #fff; font-family: 'Raleway', sans-serif; letter-spacing: -0.5px; }
.ts-head p { color: #9C9C9C; font-size: 14px; line-height: 1.7; font-family: 'IBM Plex Mono', monospace; }
.ts-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px 50px;
}
.ts-card {
  padding: 30px 30px 28px;
  position: relative;
  border-radius: 16px;
  background: #080808;
}
.ts-card::before {
  content: "";
  position: absolute;
  inset: 0;
  border-radius: 16px;
  padding: 1px;
  background: linear-gradient(to right, #484848, rgba(72,72,72,0) 80%);
  -webkit-mask: linear-gradient(#000 0 0) content-box, linear-gradient(#000 0 0);
          mask: linear-gradient(#000 0 0) content-box, linear-gradient(#000 0 0);
  -webkit-mask-composite: xor;
          mask-composite: exclude;
  pointer-events: none;
}
.ts-quote {
  position: absolute;
  top: -18px;
  left: 26px;
  background: transparent;
  color: #fff;
  font-size: 56px;
  line-height: 1;
  padding: 0 8px;
  font-family: Georgia, serif;
  font-weight: 700;
}
.ts-card > p {
  color: #9C9C9C;
  font-size: 14px;
  line-height: 1.85;
  margin-bottom: 28px;
  font-family: 'IBM Plex Mono', monospace;
}
.ts-client { display: flex; align-items: center; gap: 14px; }
.ts-client img { width: 44px; height: 44px; border-radius: 50%; object-fit: cover; }
.ts-client span { font-weight: 800; font-size: 15px; font-family: 'Raleway', sans-serif; }

@media (max-width: 900px) {
  .testimonials { padding: 60px 6vw; }
  .ts-grid { grid-template-columns: 1fr; gap: 36px; }
}

/* RECENT WORK */
.recent-work {
  background: #fff;
  color: #000;
  padding: 90px 12vw 100px;
  font-family: 'IBM Plex Mono', monospace;
}
.rw-head { text-align: center; max-width: 720px; margin: 0 auto 70px; }
.rw-head h2 { font-size: 36px; font-weight: 800; margin-bottom: 18px; color: #000; font-family: 'Raleway', sans-serif; }
.rw-head p { color: #9C9C9C; font-size: 14px; line-height: 1.7; }
.rw-carousel {
  display: flex;
  align-items: center;
  gap: 60px;
}
.rw-arrow {
  background: transparent;
  border: none;
  padding: 0;
  cursor: pointer;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: center;
}
.rw-arrow img { width: 30px; height: 30px; display: block; }
.rw-grid {
  flex: 1;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 60px;
}
.rw-card { display: flex; flex-direction: column; }
.rw-image { width: 100%; margin-bottom: 12px; }
.rw-image img { width: 100%; aspect-ratio: 445 / 300; height: auto; object-fit: cover; display: block; border-radius: 10px; }
.rw-card h3 {
  font-size: 22px;
  font-weight: 800;
  margin-bottom: 10px;
  color: #000;
  font-family: 'Raleway', sans-serif;
}
.rw-card > p {
  color: #9C9C9C;
  font-size: 14px;
  line-height: 1.85;
  margin-bottom: 16px;
}
.btn-know {
  align-self: flex-start;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  background: #3F8E00;
  border: none;
  color: #fff;
  font-family: 'IBM Plex Mono', monospace;
  font-weight: 700;
  font-size: 14px;
  padding: 12px 22px;
  border-radius: 4px;
  cursor: pointer;
  box-shadow: 0 8px 24px rgba(63, 142, 0, 0.3);
}
.btn-know .chev { font-size: 16px; line-height: 1; }

@media (max-width: 900px) {
  .recent-work { padding: 60px 6vw; }
  .rw-grid { grid-template-columns: 1fr; gap: 36px; }
}

/* GET IN TOUCH */
.get-in-touch {
  background: #080808;
  color: #fff;
  padding: 90px 12vw 100px;
  font-family: 'IBM Plex Mono', monospace;
}
.git-inner { max-width: 640px; margin: 0 auto; text-align: center; }
.get-in-touch h2 {
  font-size: 36px;
  font-weight: 800;
  margin-bottom: 18px;
  color: #fff;
  font-family: 'Raleway', sans-serif;
}
.git-desc {
  color: #9C9C9C;
  font-size: 14px;
  line-height: 1.7;
  margin-bottom: 40px;
}
.git-form {
  display: flex;
  flex-direction: column;
  gap: 8px;
  text-align: left;
  max-width: 420px;
  margin: 0 auto;
}
.git-form label {
  font-size: 13px;
  font-weight: 700;
  color: #fff;
  margin-top: 14px;
}
.git-form input,
.git-form textarea {
  background: #f5f5f5;
  border: none;
  border-radius: 4px;
  padding: 12px 14px;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 14px;
  color: #333;
  outline: none;
  width: 100%;
}
.git-form textarea { resize: vertical; min-height: 120px; }
.git-form input::placeholder,
.git-form textarea::placeholder { color: #b5b5b5; }
.btn-submit {
  margin-top: 20px;
  background: #3F8E00;
  border: none;
  color: #fff;
  font-family: 'IBM Plex Mono', monospace;
  font-weight: 700;
  font-size: 14px;
  padding: 14px 22px;
  border-radius: 4px;
  cursor: pointer;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  box-shadow: 0 8px 24px rgba(63, 142, 0, 0.3);
}
.btn-submit .chev { font-size: 16px; line-height: 1; }

/* FOOTER */
.site-footer {
  background: #1a1a1a;
  color: #c9c9c9;
  text-align: center;
  padding: 22px 12vw;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 14px;
}
.site-footer .heart { color: #ff3b3b; }

@media (max-width: 900px) {
  .get-in-touch { padding: 60px 6vw; }
}
</style>

<script>
import homem from './assets/Homem.png'
import midias from './assets/midias.svg'
import clickup from './assets/clickup.png'
import dropbox from './assets/Dropbox.png'
import paychex from './assets/paychex.png'
import elastic from './assets/elastic.png'
import stripe from './assets/Stripe.png'
import csImg1 from './assets/cadernos.png'
import csImg2 from './assets/tela.png'
import csImg3 from './assets/tela2.png'
import client1 from './assets/client1.png'
import client2 from './assets/client2.png'
import client3 from './assets/client3.png'
import client4 from './assets/client4.png'
import rwImg1 from './assets/imagem.png'
import rwImg2 from './assets/imagem2.png'
import rwPrev from './assets/voltar.svg'
import rwNext from './assets/proximo.svg'

export default {
  name: 'App',
  data() {
    return { homem, midias, clickup, dropbox, paychex, elastic, stripe, csImg1, csImg2, csImg3, client1, client2, client3, client4, rwImg1, rwImg2, rwPrev, rwNext }
  }
}
</script>