<template>
  <div class="portfolio">
    <!-- ===================== HERO ===================== -->
    <header class="hero-section">
      <nav class="main-nav">
        <ul class="main-nav__links">
          <li><a href="#" class="is-active">Home</a></li>
          <li><a href="#">Case Studies</a></li>
          <li><a href="#">Testimonials</a></li>
          <li><a href="#">Recent work</a></li>
          <li><a href="#">Get In Touch</a></li>
        </ul>
        <div class="main-nav__social">
          <img src="./assets/pag1-midias.svg" alt="social media" />
        </div>
      </nav>
      <div class="hero">
        <div class="hero__content">
          <h1>Your Name Here</h1>
          <p>Intro text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <button class="button button--primary">
            Let's get started
            <span class="button__chevron">›</span>
          </button>
        </div>
        <div class="hero__portrait">
          <img src="./assets/pag1-Homem-principal.png" alt="Portrait" />
        </div>
      </div>
      <div class="clients-strip">
        <span class="clients-strip__label">Worked with</span>
        <div class="clients-strip__logos">
          <div class="client-logo"><img src="./assets/pag1-clickup.png" alt="ClickUp" /></div>
          <div class="client-logo"><img src="./assets/pag1-Dropbox.png" alt="Dropbox" /></div>
          <div class="client-logo"><img src="./assets/pag1-paychex.png" alt="Paychex" /></div>
          <div class="client-logo"><img src="./assets/pag1-elastic.png" alt="elastic" /></div>
          <div class="client-logo"><img src="./assets/pag1-Stripe.png" alt="stripe" /></div>
        </div>
      </div>
    </header>
    <!-- ===================== CASE STUDIES ===================== -->
    <section class="case-studies">
      <div class="section-heading">
        <h2>Case Studies</h2>
        <p>Solving user &amp; business problems since last 15+ years. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>
      <article class="case-study">
        <div class="case-study__content">
          <span class="category-tag category-tag--fintech">Fintech</span>
          <h3>Work name here</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. sed do eiusmod tempor incididunt ut labore et dolore magna.</p>
          <button class="button button--orange">View case study <span class="button__chevron">›</span></button>
        </div>
        <div class="case-study__image"><img src="./assets/pag2-imagem1.png" alt="Fintech work" /></div>
      </article>
      <article class="case-study case-study--reversed">
        <div class="case-study__image"><img src="./assets/pag2-imagem2.png" alt="EdTech work" /></div>
        <div class="case-study__content">
          <span class="category-tag category-tag--edtech">EdTech</span>
          <h3>Work name here</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. sed do eiusmod tempor incididunt ut labore et dolore magna.</p>
          <button class="button button--blue">View case study <span class="button__chevron">›</span></button>
        </div>
      </article>
      <article class="case-study">
        <div class="case-study__content">
          <span class="category-tag category-tag--pharma">Pharma</span>
          <h3>Work name here</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. sed do eiusmod tempor incididunt ut labore et dolore magna.</p>
          <button class="button button--mint">View case study <span class="button__chevron">›</span></button>
        </div>
        <div class="case-study__image"><img src="./assets/pag2-imagem3.png" alt="Pharma work" /></div>
      </article>
    </section>
    <!-- ===================== TESTIMONIALS ===================== -->
    <section class="testimonials">
      <div class="section-heading section-heading--light">
        <h2>Testimonials</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>
      <div class="testimonials__grid">
        <div class="testimonial-card">
          <span class="testimonial-card__quote">“</span>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <div class="testimonial-card__author"><img src="./assets/pag3-client-name1.png" alt="Client" /><span>Client Name</span></div>
        </div>
        <div class="testimonial-card">
          <span class="testimonial-card__quote">“</span>
          <p>Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <div class="testimonial-card__author"><img src="./assets/pag3-client-name2.png" alt="Client" /><span>Client Name</span></div>
        </div>
        <div class="testimonial-card">
          <span class="testimonial-card__quote">“</span>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <div class="testimonial-card__author"><img src="./assets/pag3-client-name3.png" alt="Client" /><span>Client Name</span></div>
        </div>
        <div class="testimonial-card">
          <span class="testimonial-card__quote">“</span>
          <p>Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <div class="testimonial-card__author"><img src="./assets/pag3-client-name4.png" alt="Client" /><span>Client Name</span></div>
        </div>
      </div>
    </section>
    <!-- ===================== RECENT WORK ===================== -->
    <section class="recent-work">
      <div class="section-heading">
        <h2>Recent Work</h2>
        <p>Solving user &amp; business problems since last 15+ years. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>
      <div class="work-carousel">
        <button class="work-carousel__arrow work-carousel__arrow--prev" aria-label="Previous">
          <img src="./assets/pag4-anterior.svg" alt="" />
        </button>
        <div class="work-carousel__grid">
          <article class="work-card">
            <div class="work-card__image"><img src="./assets/pag4-imagem1.png" alt="Recent work 1" /></div>
            <h3>Work name here</h3>
            <p>Labore et dolore magna aliqua. sed do eiusmod tempor incididunt ut labore et dolore magna.</p>
            <button class="button button--primary button--sm">Know more <span class="button__chevron">›</span></button>
          </article>
          <article class="work-card">
            <div class="work-card__image"><img src="./assets/pag4-imagem2.png" alt="Recent work 2" /></div>
            <h3>Work name here</h3>
            <p>Rempor incididunt ut labore et dolore magna aliqua. sed do eiusmod tempor incididunt u</p>
            <button class="button button--primary button--sm">Know more <span class="button__chevron">›</span></button>
          </article>
        </div>
        <button class="work-carousel__arrow work-carousel__arrow--next" aria-label="Next">
          <img src="./assets/pag4-proximo.svg" alt="" />
        </button>
      </div>
    </section>
    <!-- ===================== CONTACT ===================== -->
    <section class="contact-section">
      <div class="contact-section__inner">
        <h2>Get In Touch</h2>
        <p class="contact-section__description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        <form class="contact-form" @submit.prevent>
          <label for="email">Email</label>
          <input id="email" type="email" placeholder="you@example.com" />
          <label for="mobile">Mobile</label>
          <input id="mobile" type="tel" placeholder="+1 555 000 0000" />
          <label for="message">Message</label>
          <textarea id="message" placeholder="Tell me about your project..."></textarea>
          <button type="submit" class="button button--primary button--submit">
            Submit <span class="button__chevron">›</span>
          </button>
        </form>
      </div>
    </section>
    <!-- ===================== FOOTER ===================== -->
    <footer class="site-footer">
      Copyright text <span class="site-footer__heart">❤️</span>
    </footer>
  </div>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Raleway:wght@700;800;900&family=IBM+Plex+Mono:wght@400;700&display=swap');
* { box-sizing: border-box; margin: 0; padding: 0; }
.portfolio {
  width: 100%;
  background: #000;
  color: #fff;
  font-family: 'IBM Plex Mono', ui-monospace, monospace;
  overflow-x: hidden;
}
/* ---------- Reusable button ---------- */
.button {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  border: none;
  color: #fff;
  font-family: 'IBM Plex Mono', monospace;
  font-weight: 700;
  font-size: 14px;
  padding: 16px 28px;
  border-radius: 4px;
  cursor: pointer;
}
.button--sm      { padding: 12px 22px; }
.button--primary { background: #3F8E00; box-shadow: 0 8px 30px rgba(63, 142, 0, 0.3); }
.button--orange  { background: #FFA217; border-radius: 8px; box-shadow: 0 8px 24px rgba(243, 154, 31, 0.35); }
.button--blue    { background: #000AFF; border-radius: 8px; box-shadow: 0 8px 24px rgba(31, 75, 255, 0.35); }
.button--mint    { background: #2AB090; border-radius: 8px; box-shadow: 0 8px 24px rgba(79, 203, 160, 0.35); }
.button--submit  { margin-top: 20px; padding: 14px 22px; justify-content: center; }
.button__chevron { font-size: 16px; line-height: 1; }
/* ---------- Section headings ---------- */
.section-heading { text-align: center; max-width: 720px; margin: 0 auto 80px; }
.section-heading h2 {
  font-size: 36px;
  font-weight: 800;
  margin-bottom: 18px;
  color: #000;
  font-family: 'Raleway', sans-serif;
}
.section-heading p { color: #9C9C9C; font-size: 14px; line-height: 1.7; }
.section-heading--light h2 { color: #fff; letter-spacing: -0.5px; }
/* ===================== HERO ===================== */
.hero-section {
  width: 100%;
  min-height: 100vh;
  background: #080808;
  padding: 0 0 60px;
}
.main-nav {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0 96px;
  height: 70px;
  gap: 44px;
  background: #1a1a1a;
  margin: 0 85px 70px;
  border-bottom-left-radius: 14px;
  border-bottom-right-radius: 14px;
}
.main-nav__links {
  list-style: none;
  display: flex;
  gap: 70px;
  flex: 1;
  margin: 0;
  padding: 0;
}
.main-nav__links a {
  color: #9C9C9C;
  text-decoration: none;
  font-size: 14px;
  line-height: 18px;
  font-family: 'IBM Plex Mono', monospace;
}
.main-nav__links a.is-active { color: #9C9C9C; }
.main-nav__social img { height: 16px; display: block; opacity: .85; }
.hero {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 60px;
  align-items: center;
  padding: 30px 12vw 90px;
}
.hero__content h1 {
  font-size: 48px;
  font-weight: 800;
  margin-bottom: 26px;
  line-height: 1.15;
  font-family: 'Raleway', sans-serif;
}
.hero__content p {
  line-height: 1.7;
  color: #9C9C9C;
  margin-bottom: 36px;
  max-width: 420px;
  font-size: 14px;
}
.hero__portrait { display: flex; justify-content: center; }
.hero__portrait img {
  width: 360px;
  height: 360px;
  border-radius: 50%;
  object-fit: cover;
  background: #222;
}
/* ---------- Clients strip ---------- */
.clients-strip { padding: 20px 12vw 0; }
.clients-strip__label {
  display: block;
  font-size: 13px;
  color: #fff;
  margin-bottom: 22px;
}
.clients-strip__logos {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 18px;
}
.client-logo {
  border: 1px solid #2a2a2a;
  border-radius: 4px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.client-logo img { max-height: 22px; width: auto; opacity: .9; }
/* ===================== CASE STUDIES ===================== */
.case-studies {
  background: #fff;
  color: #000;
  padding: 90px 12vw 100px;
}
.case-study {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 80px;
  align-items: center;
  margin-bottom: 90px;
}
.case-study--reversed .case-study__content { order: 2; }
.case-study--reversed .case-study__image   { order: 1; }
.case-study__image img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 2px;
  background: #eee;
  aspect-ratio: 4/3;
  object-fit: cover;
}
.case-study__content h3 {
  font-size: 26px;
  font-weight: 800;
  margin-bottom: 18px;
  font-family: 'Raleway', sans-serif;
}
.case-study__content p {
  color: #9C9C9C;
  font-size: 14px;
  line-height: 1.85;
  margin-bottom: 30px;
  max-width: 460px;
}
.category-tag {
  display: inline-block;
  padding: 6px 14px;
  border-radius: 25px;
  font-size: 12px;
  font-weight: 400;
  margin-bottom: 22px;
}
.category-tag--fintech { background: #FFF6E9; color: #FFA217; }
.category-tag--edtech  { background: #D0E6FF; color: #000AFF; }
.category-tag--pharma  { background: #E0FFF8; color: #2AB090; }
/* ===================== TESTIMONIALS ===================== */
.testimonials {
  background: #080808;
  color: #fff;
  padding: 90px 12vw 100px;
}
.testimonials__grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px 50px;
}
.testimonial-card {
  padding: 30px 30px 28px;
  position: relative;
  border-radius: 16px;
  background: #080808;
}
.testimonial-card::before {
  content: "";
  position: absolute;
  inset: 0;
  border-radius: 16px;
  padding: 1px;
  background: linear-gradient(to right, #484848, rgba(72, 72, 72, 0) 80%);
  -webkit-mask: linear-gradient(#000 0 0) content-box, linear-gradient(#000 0 0);
          mask: linear-gradient(#000 0 0) content-box, linear-gradient(#000 0 0);
  -webkit-mask-composite: xor;
          mask-composite: exclude;
  pointer-events: none;
}
.testimonial-card__quote {
  position: absolute;
  top: -18px;
  left: 26px;
  color: #fff;
  font-size: 56px;
  line-height: 1;
  padding: 0 8px;
  font-family: Georgia, serif;
  font-weight: 700;
  background: #080808;
}
.testimonial-card > p {
  color: #9C9C9C;
  font-size: 14px;
  line-height: 1.85;
  margin-bottom: 28px;
}
.testimonial-card__author { display: flex; align-items: center; gap: 14px; }
.testimonial-card__author img {
  width: 44px;
  height: 44px;
  border-radius: 50%;
  object-fit: cover;
  background: #333;
}
.testimonial-card__author span {
  font-weight: 800;
  font-size: 15px;
  font-family: 'Raleway', sans-serif;
}
/* ===================== RECENT WORK ===================== */
.recent-work {
  background: #fff;
  color: #000;
  padding: 90px 12vw 100px;
}
.work-carousel { display: flex; align-items: center; gap: 60px; }
.work-carousel__arrow {
  background: transparent;
  border: none;
  padding: 0;
  cursor: pointer;
  flex-shrink: 0;
}
.work-carousel__arrow img { width: 30px; height: 30px; display: block; }
.work-carousel__grid {
  flex: 1;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 60px;
}
.work-card { display: flex; flex-direction: column; }
.work-card__image { width: 100%; margin-bottom: 12px; }
.work-card__image img {
  width: 100%;
  aspect-ratio: 445 / 300;
  object-fit: cover;
  display: block;
  border-radius: 10px;
  background: #eee;
}
.work-card h3 {
  font-size: 22px;
  font-weight: 800;
  margin-bottom: 10px;
  color: #000;
  font-family: 'Raleway', sans-serif;
}
.work-card > p {
  color: #9C9C9C;
  font-size: 14px;
  line-height: 1.85;
  margin-bottom: 16px;
}
/* ===================== CONTACT ===================== */
.contact-section {
  background: #080808;
  color: #fff;
  padding: 90px 12vw 100px;
}
.contact-section__inner { max-width: 640px; margin: 0 auto; text-align: center; }
.contact-section h2 {
  font-size: 36px;
  font-weight: 800;
  margin-bottom: 18px;
  color: #fff;
  font-family: 'Raleway', sans-serif;
}
.contact-section__description {
  color: #9C9C9C;
  font-size: 14px;
  line-height: 1.7;
  margin-bottom: 40px;
}
.contact-form {
  display: flex;
  flex-direction: column;
  gap: 8px;
  text-align: left;
  max-width: 420px;
  margin: 0 auto;
}
.contact-form label {
  font-size: 13px;
  font-weight: 700;
  color: #fff;
  margin-top: 14px;
}
.contact-form input,
.contact-form textarea {
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
.contact-form textarea { resize: vertical; min-height: 120px; }
.contact-form input::placeholder,
.contact-form textarea::placeholder { color: #b5b5b5; }
/* ===================== FOOTER ===================== */
.site-footer {
  background: #1a1a1a;
  color: #c9c9c9;
  text-align: center;
  padding: 22px 12vw;
  font-size: 14px;
}
.site-footer__heart { color: #ff3b3b; }
/* ===================== RESPONSIVE ===================== */
@media (max-width: 1200px) {
  .main-nav { margin: 0 6vw 70px; padding: 0 6vw; }
}
@media (max-width: 900px) {
  .main-nav { margin: 0 3vw 40px; padding: 18px 20px; height: auto; flex-wrap: wrap; }
  .main-nav__links { flex-wrap: wrap; gap: 16px; justify-content: center; }
  .hero { grid-template-columns: 1fr; gap: 40px; padding: 24px 6vw 40px; }
  .hero__content h1 { font-size: 36px; }
  .hero__portrait img { width: 240px; height: 240px; }
  .clients-strip { padding: 20px 6vw 0; }
  .clients-strip__logos { grid-template-columns: repeat(2, 1fr); }
  .case-studies, .testimonials, .recent-work, .contact-section { padding: 60px 6vw; }
  .case-study { grid-template-columns: 1fr; gap: 30px; margin-bottom: 60px; }
  .case-study--reversed .case-study__content { order: 2; }
  .case-study--reversed .case-study__image   { order: 1; }
  .testimonials__grid { grid-template-columns: 1fr; gap: 36px; }
  .work-carousel { gap: 20px; }
  .work-carousel__grid { grid-template-columns: 1fr; gap: 36px; }
}
</style>