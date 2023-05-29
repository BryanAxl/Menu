# Menu

<!DOCTYPE html>
<html>
<head>
  <title>Menú de Comida Mexichangos</title>
  <style>
    /* Estilos generales */
    body {
      font-family: impact, sans-serif;
    }
    
    /* Contenedor del menú */
    .menu-container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }
    
    /* Encabezado del menú */
    .menu-header {
      text-align: center;
      margin-bottom: 20px;
    }
    
    /* Estilos para cada plato */
    .menu-item {
      display: flex;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 4px;
      padding: 10px;
    }
    
    .menu-item img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 4px;
      margin-right: 10px;
    }
    
    .menu-item-details {
      flex-grow: 1;
    }
    
    .menu-item-title {
      font-size: 20px;
      font-weight: bold;
      margin: 0;
    }
    
    .menu-item-description {
      margin-top: 5px;
      color: #777;
    }
    
    /* Estilos adicionales */
    .menu-item-price {
      font-weight: bold;
    }
    
    .menu-item-vegetarian {
      color: green;
      font-weight: bold;
    }
    
    .menu-item-vegan {
      color: darkgreen;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="menú-container">
    <h1 class="menú-header">Menú de Comida Mexicana</h1>
  
    <div class="menu-item">
      <img src="taco.jpg" alt="Taco de Carnitas">
      <div class="menu-item-details">
        <h2 class="menu-item-title">Taco de Carnitas</h2>
        <p class="menu-item-description">Tortilla de maíz rellena de carnitas de cerdo.</p>
        <span class="menu-item-price">$5.99</span>
      </div>
    </div>
  
    <div class="menu-item">
      <img src="enchiladas.jpg" alt="Enchiladas Verdes">
      <div class="menu-item-details">
        <h2 class="menu-item-title">Enchiladas Verdes</h2>
        <p class="menu-item-description">Tortillas de maíz rellenas de pollo bañadas en salsa verde.</p>
        <span class="menu-item-price">$7.99</span>
      </div>
    </div>
  
    <div class="menu-item">
      <img src="tostadas.jpg" alt="Tostadas de Tinga">
      <div class="menu-item-details">
        <h2 class="menu-item-title">Tostadas de Tinga</h2>
        <p class="menu-item-description">Tostadas crujientes con pollo deshebrado en salsa de chipotle.</p>
        <span class="menu-item-price">$6.99</span>
      </div>
    </div>
  
    <div class="menu-item">
      <img src="pozole.jpg" alt="Pozole"><div class="menu-item-details">
        <h2 class="menu-item-title">Pozole</h2>
        <p class="menu-item-description">Sopa tradicional mexicana a base de maíz y carne de cerdo.</p>
        <span class="menu-item-price">$8.99</span>
        <span class="menu-item-vegetarian">Vegetariano</span>
      </div>
    </div>
  
    <div class="menu-item">
      <img src="chiles.jpg" alt="Chiles en Nogada">
      <div class="menu-item-details">
        <h2 class="menu-item-title">Chiles en Nogada</h2>
        <p class="menu-item-description">Chiles poblanos rellenos de picadillo y bañados en salsa de nuez.</p>
        <span class="menu-item-price">$10.99</span>
        <span class="menu-item-vegan">Vegano</span>
      </div>
    </div>
  </div>
</body>
</html>
