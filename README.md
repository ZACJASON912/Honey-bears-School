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
    <p class="motto">"With God I Will"</p>
    <marquee>Education is Key, Education is Power</marquee>
    <nav>
      <ul>
        <li><a href="index.html" class="active">Home</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <img src="images/classroom.jpg" alt="Students in classroom">
    <div class="hero-text">
      <h2>Welcome to Honey Bears International School</h2>
      <p>Shaping young minds with excellence, faith, and love.</p>
    </div>
  </section>

  <section class="intro">
    <h2>Our Vision</h2>
    <p>To nurture intelligent, responsible, and God-fearing learners ready to lead and inspire in the modern world.</p>

    <h2>Our Mission</h2>
    <p>Providing a balanced education that blends academics, discipline, and moral values in a caring environment.</p>
  </section>

  <footer>
    <p>&copy; 2025 Honey Bears International School | Konge, Makindye Div., Kampala, Uganda | Call: 0700840483</p>
  </footer>
</body>
</html>
🟣 2️⃣ gallery.html
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
    <p class="motto">"With God I Will"</p>
    <marquee>Education is Key, Education is Power</marquee>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="gallery.html" class="active">Gallery</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="gallery">
    <h2>Our School in Pictures</h2>
    <div class="gallery-grid">
      <img src="images/classroom.jpg" alt="Classroom">
      <img src="images/playground.jpg" alt="Playground">
      <img src="images/dormitory.jpg" alt="Dormitory">
      <img src="images/students-hall.jpg" alt="Students in hall">
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Honey Bears International School | Konge, Makindye Div., Kampala, Uganda | Call: 0700840483</p>
  </footer>
</body>
</html>
🟠 3️⃣ about.html
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
    <p class="motto">"With God I Will"</p>
    <marquee>Education is Key, Education is Power</marquee>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="about.html" class="active">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="about">
    <h2>About Our School</h2>
    <p>Honey Bears International School is a Christian-based institution located in Konge, Makindye Division, Kampala. We are committed to nurturing academic excellence, moral discipline, and spiritual growth in our learners.</p>

    <h3>Our Core Values</h3>
    <ul>
      <li>Faith in God</li>
      <li>Excellence in Academics</li>
      <li>Respect and Responsibility</li>
      <li>Integrity and Discipline</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Honey Bears International School | Konge, Makindye Div., Kampala, Uganda | Call: 0700840483</p>
  </footer>
</body>
</html>
🔵 4️⃣ contact.html
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
    <p class="motto">"With God I Will"</p>
    <marquee>Education is Key, Education is Power</marquee>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html" class="active">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="contact">
    <h2>Contact Us</h2>
    <p><strong>Location:</strong> Konge, Makindye Division, Kampala, Uganda</p>
    <p><strong>Phone:</strong> 0700840483</p>
    <p><strong>Email:</strong> info@honeybearsschools.ug</p>

    <iframe 
      src="https://www.google.com/maps?q=Konge,+Makindye,+Kampala,+Uganda&output=embed"
      width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy">
    </iframe>
  </section>

  <footer>
    <p>&copy; 2025 Honey Bears International School | Konge, Makindye Div., Kampala, Uganda | Call: 0700840483</p>
  </footer>
</body>
</html>
💅 5️⃣ style.css
css
Copy code
body {
  font-family: 'Poppins', sans-serif;
  margin: 0;
  background: #f4f8fb;
  color: #333;
}

header {
  background-color: #003366;
  color: white;
  text-align: center;
  padding: 20px 10px;
}

header h1 {
  margin: 0;
  font-size: 28px;
}

.motto {
  font-style: italic;
  margin: 5px 0;
}

marquee {
  background-color: #ffd700;
  color: #000;
  font-weight: bold;
  padding: 5px 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin: 10px 0 0 0;
  display: flex;
  justify-content: center;
  background: #002244;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav ul li a.active, nav ul li a:hover {
  color: #ffd700;
}

.hero {
  position: relative;
}

.hero img {
  width: 100%;
  height: 400px;
  object-fit: cover;
}

.hero-text {
  position: absolute;
  bottom: 20px;
  left: 50%;
  transform: translateX(-50%);
  color: white;
  text-align: center;
  background: rgba(0,0,0,0.5);
  padding: 10px 20px;
  border-radius: 10px;
}

.intro, .about, .gallery, .contact {
  padding: 40px 20px;
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
  background: #003366;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
}
