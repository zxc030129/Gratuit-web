<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Gratuit</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      color: #000;
      background-color: #fff;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      border-bottom: 1px solid #ccc;
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      letter-spacing: 2px;
    }

    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #000;
      font-weight: 500;
    }

    section {
      padding: 80px 40px;
      max-width: 900px;
      margin: auto;
    }

    .hero {
      text-align: center;
      padding: 100px 20px;
      background: #f5f5f5;
    }

    .hero h1 {
      font-size: 40px;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 18px;
      max-width: 600px;
      margin: 0 auto;
    }

    .cta-button {
      display: inline-block;
      margin-top: 30px;
      padding: 12px 24px;
      border: 1px solid #000;
      background: none;
      cursor: pointer;
      font-size: 16px;
      transition: background 0.3s ease;
    }

    .cta-button:hover {
      background: #000;
      color: #fff;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 30px;
      margin-top: 40px;
    }

    .product-card {
      border: 1px solid #eee;
      padding: 20px;
      text-align: center;
    }

    footer {
      text-align: center;
      padding: 40px;
      font-size: 14px;
      border-top: 1px solid #ccc;
      margin-top: 80px;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">Gratuit</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#product">Product</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Action starts here.</h1>
    <p>Indoor or outdoor, style is self-defined. Discover the lifestyle brand that moves with you.</p>
    <a href="#product" class="cta-button">Explore Products</a>
  </section>

  <section id="about">
    <h2>About Gratuit</h2>
    <p>Gratuit 是我們兩位熱愛滑雪與露營的創辦人創立的品牌，將戶外冒險精神與居家生活美感融合，打造一種自由、行動、設計感並存的生活方式。</p>
    <p>我們相信：「只要願意做，沒什麼做不到。」</p>
  </section>

  <section id="product">
    <h2>Our Products</h2>
    <div class="product-grid">
      <div class="product-card">
        <h3>Soft Serve Lamp</h3>
        <p>可更換口味的霜淇淋燈，融入戶外氛圍。</p>
      </div>
      <div class="product-card">
        <h3>Foldable Silicone Shade</h3>
        <p>收納方便的矽膠燈罩，輕巧又具風格。</p>
      </div>
      <div class="product-card">
        <h3>Mini Camp Side Table</h3>
        <p>戶外用的不鏽鋼小邊桌，結構精緻。</p>
      </div>
    </div>
  </section>

  <footer>
    Copyright © Gratuit<br>
    Created life style myself.
  </footer>

</body>
</html>
