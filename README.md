<!DOCTYPE html>
<html>
<head>
  <title>Joki MLBB Ade</title>
  <style>
    body {
      background: linear-gradient(135deg, black, #111);
      color: white;
      font-family: Arial;
      margin: 0;
      overflow-x: hidden;
    }

    .container {
      text-align: center;
      padding: 50px 20px;
      animation: fadeIn 1.5s ease;
    }

    h1 {
      color: gold;
      font-size: 30px;
      text-shadow: 0 0 10px gold;
    }

    p {
      color: #ccc;
    }

    .card {
      background-color: #111;
      margin: 20px;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 0 15px rgba(255,215,0,0.3);
      transition: 0.3s;
      animation: fadeUp 1s ease;
    }

    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 25px gold;
    }

    button {
      background-color: gold;
      color: black;
      padding: 12px 20px;
      border: none;
      border-radius: 10px;
      font-weight: bold;
      margin-top: 10px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background-color: orange;
      transform: scale(1.1);
    }

    .footer {
      text-align: center;
      font-size: 12px;
      color: gray;
      margin-top: 40px;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    @keyframes fadeUp {
      from {opacity: 0; transform: translateY(30px);}
      to {opacity: 1; transform: translateY(0);}
    }

    .stars {
      position: fixed;
      width: 100%;
      height: 100%;
      z-index: -1;
    }

    .stars span {
      position: absolute;
      width: 2px;
      height: 2px;
      background: white;
      animation: animStar 5s linear infinite;
    }

    @keyframes animStar {
      from {transform: translateY(0);}
      to {transform: translateY(100vh);}
    }
  </style>
</head>
<body>

<div class="stars">
  <span style="left:10%;animation-delay:0s;"></span>
  <span style="left:30%;animation-delay:2s;"></span>
  <span style="left:50%;animation-delay:1s;"></span>
  <span style="left:70%;animation-delay:3s;"></span>
  <span style="left:90%;animation-delay:4s;"></span>
</div>

<div class="container">
  <h1>JASA JOKI MLBB 🔥</h1>
  <p>Fast • Aman • Trusted</p>

  <div class="card">
    <h2>Push Rank</h2>
    <p>Dikerjakan serius & fokus win</p>

    <a href="https://wa.me/6282287091291?text=Halo%20saya%20mau%20order%20joki%20rank">
      <button>ORDER</button>
    </a>
  </div>

  <div class="card">
    <h2>LIST HARGA ⭐</h2>
    <p>Epic → Legend : 4K / star</p>
    <p>Legend → Mythic : 6K / star</p>
    <p>Mythic : 8K / star</p>

    <a href="https://wa.me/6282287091291?text=Halo%20saya%20mau%20order%20joki%20MLBB">
      <button>ORDER SEKARANG</button>
    </a>
  </div>

</div>

<div class="footer">
  © 2026 Joki MLBB by Ade
</div>

</body>
</html>
