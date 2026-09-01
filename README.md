# namoru-village
Namoru Village — South Santo, Vanuatu
<section id="accueil" class="hero">
  <div class="hero-overlay"></div>

  <div class="hero-content">

    <!-- LOGO NAMORU -->
    <div class="logo-center">
      <img src="logo-namoru.png" alt="Logo officiel de Namoru">
    </div>

    <p class="tag">SUD DE SANTO • VANUATU</p>

    <h1>Bienvenue à <span>Namoru</span></h1>

    <p class="intro">
      Un village, une culture, une communauté et une histoire
      à transmettre aux générations futures.
    </p>

    <a class="btn" href="#village">
      Découvrir Namoru ↓
    </a>

  </div>
</section>
2. Modifier style.css

Ouvre style.css → ✏️ Edit.

À la fin du fichier, ajoute exactement ceci :

/* ================================
   LOGO CENTRAL DE NAMORU
================================ */

.logo-center {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 25px;
}

/* Cercle professionnel autour du logo */
.logo-center img {
