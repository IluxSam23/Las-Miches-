<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Las Miches</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background: #fff8f0;
      color: #333;
    }
    header {
      background-color: #e63946;
      color: white;
      padding: 20px 40px;
      text-align: center;
    }
    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin-top: 10px;
    }
    nav {
      text-align: center;
      margin-top: 10px;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #e63946;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1603052875538-753d29237b57') no-repeat center center/cover;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 8px black;
      font-size: 2.5em;
    }
    .content {
      padding: 40px;
      text-align: center;
    }
    .social {
      margin: 20px 0;
    }
    .social a {
      display: inline-block;
      margin: 0 10px;
      font-size: 1.2em;
      text-decoration: none;
      color: #e63946;
    }
    footer {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Las Miches</h1>
    <img src="https://scontent.fptx1-1.fna.fbcdn.net/v/t39.30808-1/460917021_122136668204334131_4281809640452194261_n.jpg?stp=dst-jpg_s200x200_tt6&_nc_cat=109&ccb=1-7&_nc_sid=2d3e12&_nc_ohc=oVjen47mQzEQ7kNvwHCdOQI&_nc_oc=AdlEftGBpXLGSfA6oiKU5kHgD5U3Nu6cAZ9Ssu0ywr-AxVekA7ntk_nG9FAEcD6VmJE&_nc_zt=24&_nc_ht=scontent.fptx1-1.fna&_nc_gid=RX2RJ2Fdn4RwOuI7-Z-hkA&oh=00_AfISUXi2IkLQjp-HlrdChGoElMYKK2XRRmWy3m8oPSCfBQ&oe=682D4EA0" alt="Logo Las Miches">
    <p>¡Las mejores micheladas en Isnos, Huila!</p>
  </header>

  <nav>
    <a href="#nosotros">Nosotros</a>
    <a href="#menu">Menú</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section class="hero">
    <div style="color: #f566ff;">¡Disfruta cada sorbo!</div>
  </section>

  <section class="content" id="nosotros">
    <h2>¿Quiénes somos?</h2>
    <p>Somos "Las Miches", un emprendimiento apasionado por las micheladas únicas, deliciosas y con todo el sabor de Isnos. Ven y vive una experiencia diferente.</p>
  </section>

  <section class="content" id="menu">
    <h2>Menú</h2>
    <p>Ofrecemos una gran variedad de micheladas con diferentes sabores, presentaciones y niveles de picante.</p>
    <ul>
      <li>
        <img src="https://scontent.fptx1-1.fna.fbcdn.net/v/t39.30808-6/497460341_122178600944334131_4831938967848997900_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=669761&_nc_ohc=k_xgAoYmr0MQ7kNvwGdEOKQ&_nc_oc=Adkc1pezpji-yw0W3CoFZo-IUUzPNEbrC8wltqq4L0BiRtBn94d_wL5oTqz12gojxec&_nc_zt=23&_nc_ht=scontent.fptx1-1.fna&_nc_gid=SSmjRM6tQCT5I5LmtGQ_NA&oh=00_AfKgKbeAgIc2fMOBAjIQ8vBpyrAiJc5-oXfztKsbsWpa1Q&oe=682D6CD4" alt="Michelada">
      </li>
    </ul>
  </section>

  <section class="content" id="contacto">
    <h2>¡Síguenos en redes!</h2>
    <div class="social">
      <a href="https://www.instagram.com/las_miches.isnos" target="_blank">Instagram: @las_miches.isnos</a><br>
      <a href="https://www.facebook.com/profile.php?id=100063651458354" target="_blank">Facebook: Las Miches</a>
    </div>
    <p>📍 Isnos, Huila</p>
    <p>📲 Contáctanos por DM para pedidos y reservas</p>
    <p>📞 314 4133627 - 318 4188017</p>
  </section>

  <footer>
    <p>&copy; 2025 Las Miches - Todos los derechos reservados</p>
  </footer>

</body>
</html>
