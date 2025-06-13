<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Luxury Auction Methodology</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">


  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      background: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #111;
      color: #fff;
      padding: 1rem 2rem;
      position: sticky;
      top: 0;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 1.8rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1503264116251-35a269479413?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
    }

    .hero h2 {
      font-size: 3rem;
      font-family: 'Playfair Display', serif;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
    }

    .section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }

    .section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      border-left: 5px solid #111;
      padding-left: 1rem;
      font-family: 'Playfair Display', serif;
    }

    .section p {
      font-size: 1rem;
      line-height: 1.6;
    }

    .cards {
      display: flex;
      gap: 2rem;
      flex-wrap: wrap;
      margin-top: 2rem;
    }

    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
      padding: 2rem;
      flex: 1 1 calc(33% - 2rem);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    footer {
      text-align: center;
      padding: 2rem;
      background: #111;
      color: white;
    }

    @media (max-width: 768px) {
      .cards {
        flex-direction: column;
      }

      .card {
        flex: 1 1 100%;
      }
    }

    .floating-icon {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #111;
  color: #fff;
  font-size: 1.5rem;
  padding: 15px;
  border-radius: 50%;
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
  z-index: 999;
  text-align: center;
  transition: background 0.3s ease;
  text-decoration: none;
}

.floating-icon:hover {
  background: #444;
}

  </style>
</head>
<body>
  <header>
    <h1>Luxury Auctions</h1>
    <nav>
      <a href="#marketing">Marketing</a>
      <a href="#sourcing">Sourcing</a>
      <a href="#auction">Auction</a>
    </nav>
  </header>
  
  <!-- Floating Help Icon -->
<a href="#contact" class="floating-icon" title="Need Help?">
  <i class="fas fa-comment-dots"></i>
</a>


  <section class="hero">
    <h2>Our Auction Methodology</h2>
    <p>Global reach. Competitive bidding. Premium results. Discover how we sell luxury real estate faster and smarter.</p>
  </section>

<section class="section" id="marketing">
  <h2>Global & Local Marketing Campaigns</h2>
  <p>Our strategy includes international PR, SEO, digital ads, and targeted marketing campaigns that reach high-net-worth buyers across the globe.</p>
  <div class="cards">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1523217582562-09d0def993a6?auto=format&fit=crop&w=400&q=80" alt="SEO & Digital Ads" style="width:100%; border-radius: 8px 8px 0 0; margin-bottom: 1rem;" />
      <h3>SEO & Digital Ads</h3>
      <p>We drive traffic using search engine campaigns and precision-targeted ads across multiple platforms.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=400&q=80" alt="Print & PR" style="width:100%; border-radius: 8px 8px 0 0; margin-bottom: 1rem;" />
      <h3>Print & PR</h3>
      <p>Premium magazine placements, newspapers, and global PR exposure ensure maximum visibility.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1521790366326-59546b50bc9e?auto=format&fit=crop&w=400&q=80" alt="Personalized Strategy" style="width:100%; border-radius: 8px 8px 0 0; margin-bottom: 1rem;" />
      <h3>Personalized Strategy</h3>
      <p>Custom marketing tailored to each property’s unique features and potential buyer pool.</p>
    </div>
  </div>
</section>

<section class="section" id="sourcing">
  <h2>Bidder Sourcing</h2>
  <p>Through our extensive network of buyers, brokers, and real estate professionals, we bring highly qualified, motivated bidders to each auction.</p>
  <div class="cards">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1542224566-39b1650ff27f?auto=format&fit=crop&w=400&q=80" alt="Global Network" style="width:100%; border-radius: 8px 8px 0 0; margin-bottom: 1rem;" />
      <h3>Global Network</h3>
      <p>Over 850,000 contacts and counting, including UHNWIs and investment groups.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1522098543979-ffc7f79d2293?auto=format&fit=crop&w=400&q=80" alt="Local Brokers" style="width:100%; border-radius: 8px 8px 0 0; margin-bottom: 1rem;" />
      <h3>Local Brokers</h3>
      <p>Partnerships with top-tier agents and brokers help us tap into local market intelligence.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=400&q=80" alt="VIP Events" style="width:100%; border-radius: 8px 8px 0 0; margin-bottom: 1rem;" />
      <h3>VIP Events</h3>
      <p>Private showings and exclusive previews drive competitive urgency before auction day.</p>
    </div>
  </div>
</section>

<!-- Decorative banner image between sourcing and auction -->
<div style="max-width: 1000px; margin: 3rem auto;">
  <img src="https://images.unsplash.com/photo-1494526585095-c41746248156?auto=format&fit=crop&w=1000&q=80" alt="Auction Event" style="width: 100%; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.2);" />
</div>

<section class="section" id="auction">
  <h2>Live & Online Auctions</h2>
  <p>We combine real-time competition with secure, transparent processes—online or in person—for the most efficient luxury property sales available today.</p>
  <div class="cards">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1521791055366-0d553872125f?auto=format&fit=crop&w=400&q=80" alt="2-Week Campaigns" style="width:100%; border-radius: 8px 8px 0 0; margin-bottom: 1rem;" />
      <h3>2-Week Campaigns</h3>
      <p>Each property is showcased during a focused 2-week window leading up to auction day.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=400&q=80" alt="Transparent Bidding" style="width:100%; border-radius: 8px 8px 0 0; margin-bottom: 1rem;" />
      <h3>Transparent Bidding</h3>
      <p>All bids are monitored and verified in real-time for buyer confidence and seller security.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1549924231-f129b911e442?auto=format&fit=crop&w=400&q=80" alt="Global Participation" style="width:100%; border-radius: 8px 8px 0 0; margin-bottom: 1rem;" />
      <h3>Global Participation</h3>
      <p>Bidders can join from anywhere in the world through our secure auction platform.</p>
    </div>
  </div>
</section>


  <footer>
    <p>&copy; 2025 Luxury Auctions • Crafted with precision. All rights reserved.</p>
  </footer>
</body>
</html>

