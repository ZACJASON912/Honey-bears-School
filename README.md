<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Honey Bears International School</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Honey Bears International School</h1>
    <p class="motto">With God I Will</p>
    <marquee>Education is Key, Education is Power</marquee>
    <nav>
      <a href="index.html">Home</a>
      <a href="gallery.html">Gallery</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <img src="images/classroom.jpg" alt="African children in a classroom wearing uniforms">
    <div class="hero-text">
      <h2>Welcome to Honey Bears International School</h2>
      <p>Building future leaders through quality education and Christian values.</p>
    </div>
  </section>

  <section class="intro">
    <h2>Our Mission</h2>
    <p>We aim to provide a holistic education that empowers learners academically, spiritually, and socially to shape a better future for themselves and the community.</p>
  </section>

  <footer>
    <p>&copy; 2025 Honey Bears International School | Konge, Makindye Div., Kampala, Uganda | Tel: 0700840483</p>
  </footer>
</body>
</html>
🖼️ gallery.html
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gallery - Honey Bears International School</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Honey Bears International School</h1>
    <p class="motto">With God I Will</p>
    <marquee>Education is Key, Education is Power</marquee>
    <nav>
      <a href="index.html">Home</a>
      <a href="gallery.html">Gallery</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="gallery">
    <h2>School Gallery</h2>
    <div class="gallery-grid">
      <img src="images/classroom.jpg" alt="Students in classroom">
      <img src="images/playground.jpg" alt="Children playing on playground">
      <img src="images/dormitory.jpg" alt="Dormitory">
      <img src="images/mainhall.jpg" alt="Main hall event">
      <img src="images/library.jpg" alt="School library">
      <img src="images/lab.jpg" alt="Science lab">
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Honey Bears International School | Konge, Makindye Div., Kampala, Uganda | Tel: 0700840483</p>
  </footer>
</body>
</html>
ℹ️ about.html
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About - Honey Bears International School</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Honey Bears International School</h1>
    <p class="motto">With God I Will</p>
    <marquee>Education is Key, Education is Power</marquee>
    <nav>
      <a href="index.html">Home</a>
      <a href="gallery.html">Gallery</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="about">
    <h2>About Us</h2>
    <p>Honey Bears International School was founded to provide quality Christian-based education that builds character, intelligence, and discipline. We believe that every child has a God-given purpose and potential waiting to be nurtured through knowledge and care.</p>
    <p>Our highly trained teachers guide students in academics, moral values, and creativity, ensuring each learner becomes a responsible global citizen.</p>
  </section>

  <footer>
    <p>&copy; 2025 Honey Bears International School | Konge, Makindye Div., Kampala, Uganda | Tel: 0700840483</p>
  </footer>
</body>
</html>
📞 contact.html
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Honey Bears International School</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Honey Bears International School</h1>
    <p class="motto">With God I Will</p>
    <marquee>Education is Key, Education is Power</marquee>
    <nav>
      <a href="index.html">Home</a>
      <a href="gallery.html">Gallery</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="contact">
    <h2>Contact Us</h2>
    <p><strong>Location:</strong> Konge, Makindye Division, Kampala, Uganda</p>
    <p><strong>Phone:</strong> 0700840483</p>
    <p><strong>Email:</strong> honeybearsinternationalschool@gmail.com</p>

    <iframe src="https://www.google.com/maps?q=Konge,+Makindye,+Kampala,+Uganda&output=embed"
      width="100%" height="350" style="border:0;"></iframe>
  </section>

  <footer>
    <p>&copy; 2025 Honey Bears International School | Konge, Makindye Div., Kampala, Uganda</p>
  </footer>
</body>
</html>
🎨 style.css
css
Copy code
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background-color: #f5f7fa;
  color: #333;
}

header {
  background-color: #004080;
  color: white;
  text-align: center;
  padding: 10px 0;
}

.motto {
  margin: 0;
  font-style: italic;
  font-size: 14px;
  color: #ffcc00;
}

marquee {
  background: #ffcc00;
  color: #000;
  font-weight: bold;
  padding: 5px 0;
}

nav {
  margin: 10px 0;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 15px;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

.hero {
  position: relative;
  text-align: center;
}

.hero img {
  width: 100%;
  height: 400px;
  object-fit: cover;
}

.hero-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
  background: rgba(0, 0, 0, 0.5);
  padding: 20px;
  border-radius: 10px;
}

section {
  padding: 30px;
  text-align: center;
}

.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 15px;
}

.gallery-grid img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

footer {
  background-color: #004080;
  color: white;
  text-align: center;
  padding: 10px 0;
  font-size: 14px;
}
