<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Craftsmetic</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
    }

    body{
      background:#000;
      color:#fff;
      font-family:Arial, sans-serif;
    }

    header{
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:20px 50px;
      border-bottom:1px solid #333;
      position:sticky;
      top:0;
      background:#000;
    }

    .logo{
      display:flex;
      align-items:center;
      gap:10px;
    }

    .logo img{
      width:60px;
      height:60px;
      border-radius:50%;
    }

    .logo h1{
      font-size:28px;
      letter-spacing:2px;
    }

    nav ul{
      display:flex;
      list-style:none;
      gap:30px;
    }

    nav ul li{
      cursor:pointer;
      transition:0.3s;
    }

    nav ul li:hover{
      color:gray;
    }

    .hero{
      height:90vh;
      display:flex;
      flex-direction:column;
      justify-content:center;
      align-items:center;
      text-align:center;
      padding:20px;
    }

    .hero h2{
      font-size:60px;
      margin-bottom:20px;
    }

    .hero p{
      max-width:700px;
      line-height:1.7;
      color:#ccc;
      margin-bottom:30px;
    }

    .hero button{
      padding:15px 35px;
      border:none;
      background:#fff;
      color:#000;
      font-size:16px;
      cursor:pointer;
      transition:0.3s;
    }

    .hero button:hover{
      background:#ccc;
    }

    .products{
      padding:80px 40px;
    }

    .products h2{
      text-align:center;
      margin-bottom:50px;
      font-size:40px;
    }

    .product-grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:30px;
    }

    .card{
      background:#111;
      border:1px solid #333;
      border-radius:15px;
      overflow:hidden;
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-10px);
    }

    .card img{
      width:100%;
      height:250px;
      object-fit:cover;
    }

    .card-content{
      padding:20px;
    }

    .card-content h3{
      margin-bottom:10px;
    }

    .card-content p{
      color:#bbb;
      font-size:14px;
      line-height:1.5;
    }

    footer{
      text-align:center;
      padding:30px;
      border-top:1px solid #333;
      color:#888;
      margin-top:50px;
    }

    @media(max-width:768px){

      header{
        flex-direction:column;
        gap:20px;
      }

      .hero h2{
        font-size:40px;
      }

      nav ul{
        gap:15px;
        flex-wrap:wrap;
        justify-content:center;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">
      <img src="logo.jpg" alt="logo">
      <h1>CRAFTSMETIC</h1>
    </div>

    <nav>
      <ul>
        <li>Home</li>
        <li>About</li>
        <li>Products</li>
        <li>Collections</li>
        <li>Contact</li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>BLACK & WHITE CRAFT STORE</h2>

    <p>
      Handmade creativity, aesthetic crafts, unique collections,
      and artistic products made with passion.
    </p>

    <button>Explore Now</button>
  </section>

  <section class="products">

    <h2>Product Collections</h2>

    <div class="product-grid">

      <div class="card">
        <img src="https://images.unsplash.com/photo-1513475382585-d06e58bcb0ff?q=80&w=1000" alt="">
        <div class="card-content">
          <h3>Handmade Art</h3>
          <p>Creative handmade aesthetic craft collection.</p>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1455390582262-044cdead277a?q=80&w=1000" alt="">
        <div class="card-content">
          <h3>DIY Crafts</h3>
          <p>Minimal black and white DIY creative products.</p>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1515378791036-0648a3ef77b2?q=80&w=1000" alt="">
        <div class="card-content">
          <h3>Premium Collection</h3>
          <p>Elegant artistic premium handmade designs.</p>
        </div>
      </div>

    </div>
  </section>

  <footer>
    © 2026 Craftsmetic | All Rights Reserved
  </footer>

</body>
</html>