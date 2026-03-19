<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Grind Den Restaurant</title> 
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #111;
        color: #fff;
    }

  header {
        text-align: center;
        padding: 20px;
        background: #000;
        font-size: 28px;
        letter-spacing: 2px;
    }

  .menu-container {
        display: grid;
        grid-template-columns: repeat(4, 1fr); /* 4 columns */
        gap: 15px;
        padding: 20px;
    }
    .menu-item {
        background: #1a1a1a;
        border-radius: 10px;
        overflow: hidden;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

   .menu-item:hover {
        transform: scale(1.05);
        box-shadow: 0 0 15px rgba(255, 165, 0, 0.6);
    }

   .menu-item img {
        width: 100%;
        height: 180px;
        object-fit: cover;
    }

  .menu-info {
        padding: 10px;
        text-align: center;
    }

   .menu-info h3 {
        margin: 5px 0;
        font-size: 16px;
    }

  .menu-info p {
        margin: 0;
        color: #ffa500;
        font-weight: bold;
    }

  footer {
        text-align: center;
        padding: 15px;
        background: #000;
        margin-top: 20px;
        font-size: 14px;
    }

  /* Responsive */
    @media (max-width: 900px) {
        .menu-container {
            grid-template-columns: repeat(2, 1fr);
        }
    }

  @media (max-width: 500px) {
        .menu-container {
            grid-template-columns: repeat(1, 1fr);
        }
    }
</style>
</head>

<body>

<header>
    🍽️ Grind Den Restaurant
</header>

<section class="menu-container">

  
  <div class="menu-item">
        <img src="https://source.unsplash.com/300x200/?burger" alt="Meal">
        <div class="menu-info">
            <h3>Classic Burger</h3>
            <p>R85</p>
        </div>
    </div>

  <div class="menu-item">
        <img src="https://source.unsplash.com/300x200/?pizza" alt="Meal">
        <div class="menu-info">
            <h3>Cheese Pizza</h3>
            <p>R120</p>
        </div>
    </div>

  <div class="menu-item">
        <img src="https://source.unsplash.com/300x200/?steak" alt="Meal">
        <div class="menu-info">
            <h3>Grilled Steak</h3>
            <p>R180</p>
        </div>
    </div>

  <div class="menu-item">
        <img src="https://source.unsplash.com/300x200/?pasta" alt="Meal">
        <div class="menu-info">
            <h3>Creamy Pasta</h3>
            <p>R95</p>
        </div>
    
        
   <div class="menu-item">
        <img src="https://source.unsplash.com/300x200/?chicken" alt="Meal">
        <div class="menu-info">
            <h3>Fried Chicken</h3>
            <p>R90</p>
        </div>
    </div>

   <div class="menu-item">
        <img src="https://source.unsplash.com/300x200/?salad" alt="Meal">
        <div class="menu-info">
            <h3>Fresh Salad</h3>
            <p>R60</p>
        </div>
    </div>

   <div class="menu-item">
        <img src="https://source.unsplash.com/300x200/?sushi" alt="Meal">
        <div class="menu-info">
            <h3>Sushi Combo</h3>
            <p>R140</p>
        </div>
    </div>

   <div class="menu-item">
        <img src="https://source.unsplash.com/300x200/?fries" alt="Meal">
        <div class="menu-info">
            <h3>Loaded Fries</h3>
            <p>R70</p>
        </div>
    </div>

</section>

<footer>
    © 2026 Grind Den Hub | Eat. Chill. Connect.
</footer>

</body>
</html>
