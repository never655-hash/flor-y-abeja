<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Flor y Abeja del Rincón Tarijeño</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #fdfbf6;
  color: #3f2a1d;
}

header {
  background: #f7d774;
  text-align: center;
  padding: 40px 20px;
}

header img {
  max-width: 250px;
}

section {
  max-width: 1000px;
  margin: auto;
  padding: 40px 20px;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.card {
  background: white;
  padding: 20px;
  border-radius: 16px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.08);
  text-align: center;
}

.contact {
  background: #fef1c7;
  padding: 30px;
  border-radius: 20px;
  text-align: center;
}

footer {
  background: #4b2e1f;
  color: white;
  text-align: center;
  padding: 15px;
}

.whatsapp-float {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #25d366;
  color: white;
  width: 64px;
  height: 64px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 32px;
  text-decoration: none;
  box-shadow: 0 6px 16px rgba(0,0,0,0.2);
}
</style>
</head>

<body>

<header>
  <img src="logo-flor-y-abeja.png" alt="Flor y Abeja del Rincón Tarijeño">
  <h1>Flor y Abeja del Rincón Tarijeño</h1>
  <p>Miel natural • Tradición • Dulzura del campo</p>
</header>

<section>
  <h2>Nuestros Productos</h2>
  <div class="cards">
    <div class="card">
      <h3>🍯 Miel Pura</h3>
      <p>Miel 100% natural y artesanal.</p>
    </div>
    <div class="card">
      <h3>🌿 Propóleo</h3>
      <p>Producto natural para el bienestar.</p>
    </div>
  </div>
</section>

<section>
  <h2>Sobre Nosotros</h2>
  <p>
    Productores artesanales del Rincón de la Victoria – Tarija,
    cuidando las abejas y la naturaleza.
  </p>
</section>

<section class="contact">
  <h2>Contacto</h2>
  <p>📞 WhatsApp:
    <a href="https://wa.me/59178242270" target="_blank">
      +591 78242270
    </a>
  </p>
  <p>📍 Rincón de la Victoria – Tarija</p>
</section>

<footer>
  © 2025 Flor y Abeja del Rincón Tarijeño
</footer>

<a class="whatsapp-float" href="https://wa.me/59178242270" target="_blank">💬</a>

</body>
</html>
