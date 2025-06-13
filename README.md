<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Menú | Restaurante El Buen Sabor</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    * { box-sizing: border-box; }

    body {
      font-family: 'Montserrat', sans-serif;
      margin: 100px;
      background-color: #fff7f0;
      color: #333;
    }

    header {
      background: linear-gradient(to right, #e74c3c, #c0392b);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 3em;
    }

    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    .menu-section {
      padding: 40px 20px;
    }

    .menu-section h2 {
      font-size: 2em;
      margin-bottom: 20px;
      border-bottom: 3px solid #e74c3c;
      display: inline-block;
    }

    .menu-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .menu-card {
      display: flex;
      flex-direction: row;
      background-color: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      transition: transform 0.5s;
    }

    .menu-card:hover {
      transform: scale(1.12);
    }

    .menu-card img {
      width: 200px;
      height: 150px;
      object-fit: cover;
    }

    .menu-card-content {
      padding: 15px;
      flex: 1;
    }

    .menu-card-content h3 {
      margin-top: 0;
      color: #c0392b;
    }

    .menu-card-content p {
      margin: 5px 0;
      color: #666;
    }

    .price {
      font-weight: bold;
      color: #e67e22;
    }

    @media (max-width: 600px) {
      .menu-card {
        flex-direction: column;
        align-items: center;
      }

      .menu-card img {
        width: 100%;
        height: 200px;
      }

      .menu-card-content {
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Restaurante El Buen Sabor</h1>
    <p>¡Deléitate con nuestras especialidades del día!</p>
  </header>

  <!-- Entradas -->
  <div class="menu-section">
    <h2>Entradas</h2>
    <div class="menu-grid">
      <!-- Puedes repetir y personalizar con tus platos -->
      <div class="menu-card"><img src="empanadas.jpg" alt="Empanadas"><div class="menu-card-content"><h3>Empanadas de Queso</h3><p>Crujientes y doradas.</p><p class="price">$3.50</p></div></div>
      <div class="menu-card"><img src="sopa.jpg" alt="Sopa"><div class="menu-card-content"><h3>Sopa de Verduras</h3><p>Caldo casero y vegetales frescos.</p><p class="price">$4.00</p></div></div>
      <div class="menu-card"><img src="ensalada.jpg" alt="Ensalada Mixta"><div class="menu-card-content"><h3>Ensalada Mixta</h3><p>Con aderezo de la casa.</p><p class="price">$3.80</p></div></div>
      <div class="menu-card"><img src="ceviche.jpg" alt="Ceviche"><div class="menu-card-content"><h3>Ceviche de Camarón</h3><p>Con limón y cilantro.</p><p class="price">$5.50</p></div></div>
      <div class="menu-card"><img src="patacones.jpg" alt="Patacones"><div class="menu-card-content"><h3>Patacones con Queso</h3><p>Fritos y crocantes.</p><p class="price">$3.00</p></div></div>
      <div class="menu-card"><img src="tostones.jpg" alt="Tostones"><div class="menu-card-content"><h3>Tostones con Guacamole</h3><p>Perfectos para compartir.</p><p class="price">$4.20</p></div></div>
      <div class="menu-card"><img src="queso_frito.jpg" alt="Queso Frito"><div class="menu-card-content"><h3>Queso Frito</h3><p>Con mermelada de tomate.</p><p class="price">$3.50</p></div></div>
      <div class="menu-card"><img src="croquetas.jpg" alt="Croquetas"><div class="menu-card-content"><h3>Croquetas de Pollo</h3><p>Suaves por dentro, crujientes por fuera.</p><p class="price">$4.00</p></div></div>
      <div class="menu-card"><img src="arepas.jpg" alt="Arepas"><div class="menu-card-content"><h3>Arepas Rellenas</h3><p>De queso o carne.</p><p class="price">$4.20</p></div></div>
      <div class="menu-card"><img src="bruschetta.jpg" alt="Bruschetta"><div class="menu-card-content"><h3>Bruschetta</h3><p>Con tomate y albahaca fresca.</p><p class="price">$3.90</p></div></div>
    </div>
  </div>

  <!-- Platos Principales -->
  <div class="menu-section">
    <h2>Platos Principales</h2>
    <div class="menu-grid">
      <div class="menu-card"><img src="pollo.jpg" alt="Pollo"><div class="menu-card-content"><h3>Pollo a la Parrilla</h3><p>Con arroz y ensalada.</p><p class="price">$8.50</p></div></div>
      <div class="menu-card"><img src="paella.jpg" alt="Paella"><div class="menu-card-content"><h3>Paella Mixta</h3><p>Mariscos, pollo y verduras.</p><p class="price">$11.50</p></div></div>
      <div class="menu-card"><img src="lomo.jpg" alt="Lomo"><div class="menu-card-content"><h3>Lomo Saltado</h3><p>Con papas y arroz.</p><p class="price">$9.50</p></div></div>
      <div class="menu-card"><img src="lasagna.jpg" alt="Lasaña"><div class="menu-card-content"><h3>Lasaña de Carne</h3><p>Gratinada al horno.</p><p class="price">$9.00</p></div></div>
      <div class="menu-card"><img src="pescado.jpg" alt="Pescado"><div class="menu-card-content"><h3>Pescado Frito</h3><p>Con patacones.</p><p class="price">$10.00</p></div></div>
      <div class="menu-card"><img src="hamburguesa.jpg" alt="Hamburguesa"><div class="menu-card-content"><h3>Hamburguesa Especial</h3><p>Con papas y bebida.</p><p class="price">$7.50</p></div></div>
      <div class="menu-card"><img src="tacos.jpg" alt="Tacos"><div class="menu-card-content"><h3>Tacos de Carne</h3><p>Con pico de gallo.</p><p class="price">$8.00</p></div></div>
      <div class="menu-card"><img src="arroz_marisco.jpg" alt="Arroz con Mariscos"><div class="menu-card-content"><h3>Arroz con Mariscos</h3><p>Plato clásico costero.</p><p class="price">$11.00</p></div></div>
      <div class="menu-card"><img src="spaghetti.jpg" alt="Spaghetti"><div class="menu-card-content"><h3>Spaghetti Boloñesa</h3><p>Con queso parmesano.</p><p class="price">$7.80</p></div></div>
      <div class="menu-card"><img src="canelones.jpg" alt="Canelones"><div class="menu-card-content"><h3>Canelones de Espinaca</h3><p>Con salsa bechamel.</p><p class="price">$8.30</p></div></div>
    </div>
  </div>

  <!-- Postres -->
  <div class="menu-section">
    <h2>Postres</h2>
    <div class="menu-grid">
      <div class="menu-card"><img src="flan.jpg" alt="Flan"><div class="menu-card-content"><h3>Flan de Caramelo</h3><p>Suave y dulce.</p><p class="price">$3.00</p></div></div>
      <div class="menu-card"><img src="tarta.jpg" alt="Tarta"><div class="menu-card-content"><h3>Tarta de Manzana</h3><p>Con helado de vainilla.</p><p class="price">$4.50</p></div></div>
      <div class="menu-card"><img src="brownie.jpg" alt="Brownie"><div class="menu-card-content"><h3>Brownie con Helado</h3><p>Caliente y cremoso.</p><p class="price">$4.80</p></div></div>
      <div class="menu-card"><img src="tiramisu.jpg" alt="Tiramisú"><div class="menu-card-content"><h3>Tiramisú</h3><p>Clásico italiano.</p><p class="price">$4.70</p></div></div>
      <div class="menu-card"><img src="cheesecake.jpg" alt="Cheesecake"><div class="menu-card-content"><h3>Cheesecake de Fresa</h3><p>Con salsa casera.</p><p class="price">$4.90</p></div></div>
      <div class="menu-card"><img src="helado.jpg" alt="Helado"><div class="menu-card-content"><h3>Helado Artesanal</h3><p>Sabores variados.</p><p class="price">$3.50</p></div></div>
      <div class="menu-card"><img src="pastel.jpg" alt="Pastel"><div class="menu-card-content"><h3>Pastel de Chocolate</h3><p>Relleno de mousse.</p><p class="price">$4.60</p></div></div>
      <div class="menu-card"><img src="frutas.jpg" alt="Frutas"><div class="menu-card-content"><h3>Copa de Frutas</h3><p>Frescas y jugosas.</p><p class="price">$3.20</p></div></div>
      <div class="menu-card"><img src="mousse.jpg" alt="Mousse"><div class="menu-card-content"><h3>Mousse de Maracuyá</h3><p>Refrescante y ligero.</p><p class="price">$4.10</p></div></div>
      <div class="menu-card"><img src="creme_brulee.jpg" alt="Crème brûlée"><div class="menu-card-content"><h3>Crème brûlée</h3><p>Con costra caramelizada.</p><p class="price">$4.30</p></div></div>
    </div>
  </div>

  <!-- Bebidas -->
  <div class="menu-section">
    <h2>Bebidas</h2>
    <div class="menu-grid">
      <div class="menu-card"><img src="jugo_naranja.jpg" alt="Jugo"><div class="menu-card-content"><h3>Jugo de Naranja</h3><p>Natural recién exprimido.</p><p class="price">$2.50</p></div></div>
      <div class="menu-card"><img src="limonada.jpg" alt="Limonada"><div class="menu-card-content"><h3>Limonada</h3><p>Con hierbabuena.</p><p class="price">$2.00</p></div></div>
      <div class="menu-card"><img src="coca.jpg" alt="Coca-Cola"><div class="menu-card-content"><h3>Coca-Cola</h3><p>Botella 350 ml.</p><p class="price">$1.80</p></div></div>
      <div class="menu-card"><img src="agua.jpg" alt="Agua"><div class="menu-card-content"><h3>Agua Mineral</h3><p>Con o sin gas.</p><p class="price">$1.50</p></div></div>
      <div class="menu-card"><img src="cerveza.jpg" alt="Cerveza"><div class="menu-card-content"><h3>Cerveza Nacional</h3><p>Bien fría.</p><p class="price">$3.00</p></div></div>
      <div class="menu-card"><img src="cerveza.jpg" alt="fernet"><div class="menu-card-content"><h3>fernet</h3><p>Bien fría.</p><p class="price">$3.00</p></div></div>
       <div class="menu-card"><img src="jugo_naranja.jpg" alt="Jugo"><div class="menu-card-content"><h3>vino</h3><p>Natural recién exprimido.</p><p class="price">$2.50</p></div></div>
    </div>
  </div>

</body>
</html>
