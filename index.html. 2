<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Morris Digital Store | Earn Online Worldwide</title>
  <style>
    :root {
      --primary: #000;
      --secondary: #b59410;
      --accent: #ffd700;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background: #111;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background: var(--primary);
      color: var(--accent);
      text-align: center;
      padding: 1.5rem;
      font-size: 1.5rem;
      font-weight: 700;
      letter-spacing: 1px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.4);
    }
    nav {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
      background: #222;
      padding: 10px;
    }
    nav button {
      background: var(--secondary);
      border: none;
      color: #000;
      padding: 8px 15px;
      border-radius: 20px;
      cursor: pointer;
      transition: 0.3s;
    }
    nav button:hover {
      background: var(--accent);
    }
    main {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
      padding: 2rem;
    }
    .product-card {
      background: #1a1a1a;
      border-radius: 15px;
      padding: 1rem;
      text-align: center;
      transition: 0.3s;
      border: 1px solid #333;
    }
    .product-card:hover {
      transform: scale(1.03);
      border-color: var(--accent);
      box-shadow: 0 0 20px rgba(255, 215, 0, 0.3);
    }
    .product-card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
      border-radius: 10px;
    }
    .product-card h3 {
      font-size: 1.1rem;
      margin: 10px 0 5px;
      color: var(--accent);
    }
    .product-card p {
      font-size: 0.9rem;
      color: #ddd;
    }
    .price {
      color: var(--secondary);
      font-weight: 600;
    }
    .buy-btn {
      display: inline-block;
      margin-top: 10px;
      background: var(--accent);
      color: #000;
      padding: 10px 20px;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    .buy-btn:hover {
      background: #fff;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #000;
      color: #aaa;
      border-top: 1px solid #333;
    }
  </style>
</head>
<body>
  <header>
    Morris Digital Store 💰 <br />
    <small>Earn Online Worldwide</small>
  </header>

  <nav>
    <button onclick="filterByCategory('all')">All</button>
    <button onclick="filterByCategory('fitness')">Fitness</button>
    <button onclick="filterByCategory('crypto')">Crypto</button>
    <button onclick="filterByCategory('business')">Business</button>
    <button onclick="filterByCategory('software')">Software</button>
  </nav>

  <main id="product-grid"></main>

  <footer>© 2025 Morris Digital Store. All Rights Reserved.</footer>

  <script>
  const productGrid = document.getElementById("product-grid");

  const demoProducts = [
    {
      title: "Crypto Mastery Course",
      description: "Learn cryptocurrency trading from scratch and earn passive income.",
      category: "crypto",
      priceText: "$49.99",
      commissionPct: "50",
      affiliateLink: "https://www.digistore24.com/redir/12345/Morrismbuvi",
      image: "https://via.placeholder.com/300x180?text=Crypto+Course"
    },
    {
      title: "Fitness Transformation Program",
      description: "12-week online fitness coaching to get you in the best shape.",
      category: "fitness",
      priceText: "$39.00",
      commissionPct: "60",
      affiliateLink: "https://www.digistore24.com/redir/23456/Morrismbuvi",
      image: "https://via.placeholder.com/300x180?text=Fitness+Program"
    },
    {
      title: "Affiliate Marketing Blueprint",
      description: "Step-by-step training to build your online business fast.",
      category: "business",
      priceText: "$59.00",
      commissionPct: "75",
      affiliateLink: "https://www.digistore24.com/redir/34567/Morrismbuvi",
      image: "https://via.placeholder.com/300x180?text=Affiliate+Blueprint"
    },
    {
      title: "AI Business Automation Tool",
      description: "Use AI to automate your marketing and increase sales.",
      category: "software",
      priceText: "$79.00",
      commissionPct: "40",
      affiliateLink: "https://www.digistore24.com/redir/45678/Morrismbuvi",
      image: "https://via.placeholder.com/300x180?text=AI+Software"
    }
  ];

  function loadProducts() {
    productGrid.innerHTML = demoProducts.map(p => `
      <div class="product-card" data-category="${p.category}">
        <img src="${p.image}" alt="${p.title}">
        <h3>${p.title}</h3>
        <p>${p.description}</p>
        <p class="price">${p.priceText} | ${p.commissionPct}% Commission</p>
        <a href="${p.affiliateLink}" target="_blank" class="buy-btn">View Offer</a>
      </div>
    `).join("");
  }

  function filterByCategory(cat) {
    const cards = document.querySelectorAll(".product-card");
    cards.forEach(card => {
      const match = cat === 'all' || card.dataset.category === cat;
      card.style.display = match ? "block" : "none";
    });
  }

  loadProducts();
  </script>
</body>
</html>

