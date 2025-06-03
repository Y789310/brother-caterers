<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Brother Caterers</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- Header -->
    <section class="header">
      <h1>Brother Caterers</h1>
      <p>Pure Veg Catering Services in Surat</p>
      <a href="https://wa.me/919016838388" target="_blank">
        <button class="whatsapp-btn">Book on WhatsApp</button>
      </a>
    </section>

    <!-- About Us -->
    <section class="section about">
      <h2>About Us</h2>
      <p>
        At Brother Caterers, we specialize in pure vegetarian catering for weddings, birthdays,
        corporate events, and more. Based in Surat, we bring delicious flavors, professional
        service, and memorable experiences to every event.
      </p>
    </section>

    <!-- Menu -->
    <section class="section menu">
      <h2>Our Menu</h2>
      <div class="cards">
        <div class="card">
          <h3>Gujarati Thali</h3>
          <p>Dhokla, Undhiyu, Kadhi, Thepla, Gulab Jamun</p>
        </div>
        <div class="card">
          <h3>Punjabi Platter</h3>
          <p>Paneer Tikka, Dal Makhani, Naan, Gajar Halwa</p>
        </div>
        <div class="card">
          <h3>South Indian</h3>
          <p>Idli, Dosa, Sambhar, Coconut Chutney</p>
        </div>
      </div>
    </section>

    <!-- Gallery -->
    <section class="section gallery">
      <h2>Gallery</h2>
      <div class="gallery-grid">
        <img src="images/food1.jpg" alt="Dish 1" />
        <img src="images/food2.jpg" alt="Dish 2" />
        <img src="images/food3.jpg" alt="Dish 3" />
      </div>
    </section>

    <!-- Contact -->
    <section class="section contact">
      <h2>Contact & Booking</h2>
      <p>Call us: <strong>+91-9016838388</strong> or message us on WhatsApp</p>
      <a href="https://wa.me/919016838388" target="_blank">
        <button class="whatsapp-btn">WhatsApp Us</button>
      </a>
    </section>
  </body>
</html>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  color: #000;
  background-color: #fff;
}

.section {
  padding: 60px 20px;
  text-align: center;
}

.header {
  background: #000;
  color: #fff;
  padding: 60px 20px;
}

h1, h2, h3 {
  margin-bottom: 10px;
}

p {
  margin-bottom: 20px;
}

.cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.card {
  background: #f2f2f2;
  padding: 20px;
  border-radius: 12px;
  width: 300px;
}

.gallery-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.gallery-grid img {
  width: 300px;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.contact {
  background: #000;
  color: #fff;
}

.whatsapp-btn {
  background: #25D366;
  color: #fff;
  border: none;
  padding: 12px 24px;
  border-radius: 8px;
  cursor: pointer;
  font-size: 16px;
}
brother-caterers-site/
│
├── index.html
├── style.css
└── images/
    ├── food1.jpg
    ├── food2.jpg
    └── food3.jpg
