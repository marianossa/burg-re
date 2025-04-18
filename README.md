<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BURGÈRE</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
</head>
<body>

  <!-- AOS -->
  <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
  <script>AOS.init();</script>

  <header>
    
    <h1>BURGÈRE</h1>
    <nav>
      <a href="#menu">Menú</a>
      <a href="#nosotros">Nosotros</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="hero">
    <h2>HAMBURGUESAS QUE TE MANTIENEN ENTRETENIDO</h2>
    <p>Sabor unico, calidad inigualable</p>
  </section>

  <section id="menu">
    <div class="barra-titulo">MENÚ</div>

    <div class="item-menu" data-aos="fade-up" data-aos-delay="100">
      <img src="img/AURA HEAVY.jpg" alt="AURA HEAVY" />
      <p class="precio">PRÓXIMAMENTE</p>
    </div>

    <div class="menu-item">
      <img src="img/heavy.jpg" alt="HEAVY" />
      <div>
        <h3>HEAVY</h3>
        <p>Hamburguesa de carne de res de primera calidad, cebollas caramelizadas, tomates, lechuga, pepinillos y alioli BURGÈRE.</p>
        <p class="precio">$11.90</p>
      </div>
    </div>

    <div class="menu-item">
      <img src="img/alpha.jpg" alt="ALPHA" />
      <div>
        <h3>ALPHA</h3>
        <p>Hamburguesa de carne de res de primera calidad, tocino de res, queso cheddar canadiense, cebolla caramelizada, tomates, lechuga, pepinillos y alioli BURGÈRE.</p>
        <p class="precio">$10.50</p>
      </div>
    </div>

    <div class="menu-item">
      <img src="img/valka.jpg" alt="VALKA" />
      <div>
        <h3>VALKA</h3>
        <p>Hamburguesa de carne de res de primera calidad, queso cheddar canadiense, cebolla caramelizada, tomates, lechuga, pepinillos y alioli BURGÈRE</p>
        <p class="precio">$9.90</p>
      </div>
    </div>

    <div class="menu-item">
      <img src="img/fulgor.jpg" alt="FULGOR" />
      <div>
        <h3>FULGOR</h3>
        <p>Dos hamburguesas de carne de res de primera calidad, tocino de res, dos rebanadas de queso cheddar canadiense, cebolla caramelizada, tomates, lechuga, pepinillos y alioli BURGÈRE</p>
        <p class="precio">$10.99</p>
      </div>
    </div>

    <div class="menu-item">
      <img src="img/aura.jpg" alt="AURA" />
      <div>
        <h3>AURA</h3>
        <p>Dos hamburguesas de carne de res de primera calidad, dos rebanadas de queso cheddar canadiense, huevo frito, champiñones salteados, cebolla caramelizada, tomates, lechuga, pepinillos y alioli BURGÈRE.</p>
        <p class="precio">$12.50</p>
      </div>
    </div>

    <a href="https://wa.me/5492634335547" target="_blank" class="boton-pedir">Pedir por WhatsApp</a>
  </section>

  <section id="nosotros">
    <div class="barra-titulo">NOSOTROS</div>
    <div class="nosotros-contenido">
      <img src="img/nosotros.jpg" alt="El equipo de BURGÈRE" data-aos="zoom-in" />
      <div class="texto" data-aos="fade-left">
        <p>BURGÈRE nació del fuego, el humo y la pasión por las hamburguesas hechas como se debe: con actitud, calidad y sabor real.</p>
        <p>Desde el barrio, para el barrio, combinamos ingredientes premium con recetas explosivas que no se olvidan.</p>
        <p>Acá no se viene solo a comer... se viene a vivir la experiencia BURGÈRE.</p>
      </div>
    </div>
  </section>

  <section id="contacto">
    <div class="barra-titulo">CONTACTO</div>
    <div class="contacto-contenido">
      <div class="info">
        <p><strong>📍 Dirección:</strong> 3er B Jardín Mk Casa 4, Palmira, Mendoza</p>
        <p><strong>📞 WhatsApp:</strong> <a href="https://wa.me/5492634335547" target="_blank">+54 9 2634335547</a></p>
        <a href="https://wa.me/5492634335547" target="_blank" class="boton-wsp">Pedir por WhatsApp</a>
      </div>

      <div class="mapa">
        <iframe 
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d339.42110623345194!2d-68.5719361!3d-33.0547533!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMzPCsDAzJzE3LjEiUyA2OMKwMzQnMTguOSJX!5e0!3m2!1ses-419!2sar!4v1713033000000!5m2!1ses-419!2sar" 
          width="100%" 
          height="250" 
          style="border:0;" 
          allowfullscreen="" 
          loading="lazy" 
          referrerpolicy="no-referrer-when-downgrade">
        </iframe>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 BURGÈRE</p>
  </footer>
/* --- Reset --- */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    background-color: #4B2E1A;
    font-family: 'Inter', sans-serif;
    color: #F0F0F0;
    line-height: 1.6;
    scroll-behavior: smooth;
  }
  
  /* --- Encabezado --- */
  header {
    background-color: #3A2413;
    color: #F9D17D;
    padding: 1em;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 2px 10px rgba(0,0,0,0.4);
    font-family: 'Space Grotesk', sans-serif;
    position: sticky;
    top: 0;
    z-index: 1000;
  }
  
  nav a {
    color: #F9D17D;
    margin-left: 1em;
    text-decoration: none;
    font-weight: bold;
  }
  
  /* --- Hero / Parallax --- */
  .parallax {
    background-image: url('img/parallax.jpg');
    min-height: 80vh;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .parallax-text {
    background-color: rgba(0,0,0,0.5);
    padding: 2em;
    color: #fff;
    font-size: 2em;
    font-weight: bold;
    text-align: center;
  }
  
  /* --- Secciones --- */
  section {
    padding: 60px 20px;
    text-align: center;
  }
  
  .barra-titulo {
    font-size: 2rem;
    color: #F9D17D;
    border-bottom: 3px solid #F9D17D;
    display: inline-block;
    padding-bottom: 10px;
    margin-bottom: 2em;
    font-family: 'Space Grotesk', sans-serif;
  }
  
  /* --- Menú --- */
  #menu {
    background-color: #60391F;
  }
  
  .menu-item {
    display: flex;
    align-items: center;
    gap: 1.5em;
    background: #7A4B28;
    padding: 1em;
    margin: 2em auto;
    max-width: 800px;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    opacity: 0;
    transform: translateY(30px);
    animation: fadeUp 0.8s ease forwards;
  }
  
  .menu-item:nth-child(2) { animation-delay: 0.2s; }
  .menu-item:nth-child(3) { animation-delay: 0.4s; }
  
  .menu-item img {
    width: 180px;
    height: 180px;
    object-fit: cover;
    border-radius: 10px;
  }
  
  .menu-item h3 {
    margin: 0;
    color: #F9D17D;
    font-size: 1.5em;
    font-family: 'Space Grotesk', sans-serif;
  }
  
  .precio {
    font-weight: bold;
    color: #fff;
  }
  
  .boton-pedir {
    display: inline-block;
    margin-top: 2em;
    padding: 1em 2em;
    background-color: #D2492A;
    color: white;
    text-decoration: none;
    border-radius: 10px;
    font-weight: bold;
    transition: background 0.3s ease;
  }
  
  .boton-pedir:hover {
    background-color: #b93e24;
  }
  
  /* --- Animación Menú --- */
  @keyframes fadeUp {
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  
  /* --- Nosotros --- */
  #nosotros {
    background-color: #5E3A24;
    color: #F0F0F0;
  }
  
  .nosotros-contenido {
    display: flex;
    flex-wrap: wrap;
    gap: 2em;
    max-width: 1000px;
    margin: auto;
    justify-content: center;
    align-items: center;
  }
  
  .nosotros-contenido img {
    width: 100%;
    max-width: 400px;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.3);
  }
  
  .texto {
    flex: 1;
    min-width: 280px;
    text-align: left;
  }
  
  .texto p {
    font-size: 1.1rem;
    line-height: 1.6;
  }
  
  /* --- Contacto --- */
  #contacto {
    background-color: #3A2413;
    color: #F0F0F0;
  }
  
  .contacto-contenido {
    display: flex;
    flex-wrap: wrap;
    gap: 2em;
    max-width: 900px;
    margin: auto;
    justify-content: space-between;
  }
  
  .info {
    flex: 1;
    min-width: 250px;
    text-align: left;
  }
  
  .mapa {
    flex: 1;
    min-width: 300px;
  }
  
  .mapa iframe {
    width: 100%;
    border-radius: 10px;
  }
  
  /* --- Reseñas --- */
  #reseñas {
    background-color: #4B2E1A;
    padding: 3em 1em;
  }
  
  .reseñas {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  
    
