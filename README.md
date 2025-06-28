<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Garden Store</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      background: #f7f7f7;
      color: #333;
    }
    header {
      background-color: #70c96f;
      color: white;
      padding: 1rem;
      text-align: center;
      font-size: 1.8rem;
      font-weight: bold;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      padding: 1rem;
    }
    .product {
      background: white;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      display: flex;
      flex-direction: column;
    }
    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .product-content {
      padding: 1rem;
      flex: 1;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .product h3 {
      font-size: 1.2rem;
      margin: 0 0 0.5rem;
    }
    .product p {
      margin: 0.5rem 0;
      font-weight: bold;
      color: #60a75e;
    }
    .buy-btn {
      background-color: #60a75e;
      color: white;
      padding: 0.7rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .buy-btn:hover {
      background-color: #4b864a;
    }
  </style>
</head>
<body>
  <header>
    Garden Store 🌱
  </header>
  <section class="products">
    <div class="product">
      <img src="https://cdn.awsli.com.br/600x450/2586/2586733/produto/258302582/cce7b58e6a.jpg" alt="Kit Jardim">
      <div class="product-content">
        <h3>Kit Crescer um Jardim</h3>
        <p>R$ 29,90</p>
        <button class="buy-btn">Comprar</button>
      </div>
    </div>
    <div class="product">
      <img src="https://cdn.awsli.com.br/600x450/2586/2586733/produto/258302582/c27d7e5eaa.jpg" alt="Planta mágica">
      <div class="product-content">
        <h3>Planta Mágica (Surpresa)</h3>
        <p>R$ 19,90</p>
        <button class="buy-btn">Comprar</button>
      </div>
    </div>
    <div class="product">
      <img src="https://cdn.awsli.com.br/600x450/2586/2586733/produto/258302582/b6e0a8e0a3.jpg" alt="Mini Vaso">
      <div class="product-content">
        <h3>Mini Vaso Decorativo</h3>
        <p>R$ 14,90</p>
        <button class="buy-btn">Comprar</button>
      </div>
    </div>
  </section>
</body>
</html>
