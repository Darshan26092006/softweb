# Ex.07 Restuarant Website
## Date:10/11/2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Maaran Parotta Kadai</title>
  <link rel="stylesheet" href="style.css">

</head>
<body>
  <header>
    <h1>Maaran Parotta Kadai</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
   <h2>Spicy Kothu Parotta</h2>
    <p>Dig into the chaos of taste — crispy parotta tossed with rich masala and pure love.</p>
    <a href="menu.html" class="btn">Explore Menu</a>
  </section>

  <footer>
    <p>© Maaran Parotta Kadai | Designed by AKASH CT</p>
  </footer>
</body>
</html>
```
### GALLERY.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gallery - Maaran Parotta Kadai</title>
  <link rel="stylesheet" href="style.css">


</head>
<body>
  <header>
    <h1>Our Gallery</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="gallery">
    <h2>Delicious Moments Captured</h2>
    <div class="gallery-grid">
      <img src="BUN.png" alt="Bun Parotta">
      <img src="KUTTU-PORATTA.jpg" alt="KOTHU PAROTTA">
      <img src="download.jpg" alt="VEG FRIED RICE">
      <img src="whole-grilled-chicken.jpg" alt="Grilled Chicken">
    </div>
  </section>

  <footer>
    <p>© MAARAN PAROTTA KADAI</p>
  </footer>
</body>
</html>

```
### About.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About - Parotta Maaran Kadai</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>About Us</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="about">
    <h2>Welcome to Parotta Maaran Kadai</h2>
   <p>We’re passionate about serving hot, flavorful Kothu Parotta that brings people together.  
    Our chefs mix soft parotta, rich masala, and fresh ingredients to craft pure comfort in every bite.</p>  
    <p>From spicy street-style vibes to homely warmth, every plate tells the story of flavor and fun.  
    Come, taste the rhythm of Kothu made with love.</p>
  </section>

  <footer>
    <p>© Maaran Parotta Kadai</p>
  </footer>
</body>
</html>

```
### Menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - Maaran Parotta Kadai</title>
  <link rel="stylesheet" href="style.css">


</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="menu">
    <div class="menu-item">
      <h3>Grilled Chicken</h3>
      <p>Served with garlic sauce and fries — ₹250</p>
    </div>
    <div class="menu-item">
      <h3>Parotta</h3>
      <p>Parotta softer than the sponge — ₹150</p>
    </div>
    <div class="menu-item">
      <h3>Veg Fried Rice</h3>
      <p>Spicy and flavorful rice loaded with veggies — ₹150</p>
    </div>
    <div class="menu-item">
      <h3>Kothu Parotta</h3>
      <p>Messy, spicy, and downright addictive — that’s Kothu Parotta for you— ₹180</p>
    </div>
  </section>

  <footer>
    <p>MAARAN PAROTTA KADAI © All Rights Reserverd</p>
  </footer>
</body>
</html>

```
### Contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Maaran Paraotta Kadai</title>
  <link rel="stylesheet" href="style.css">

</head>
<body>
  <header>
    <h1>Contact Us</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="gallery.html">Gallery</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="contact">
    <h2>Get in Touch</h2>
    <p>📍 Location: Address: 79K, PERIYA KOVIL VASAL, Kalugumalai, KOVILPATTI, Tamil Nadu 628552</p>
    <p>📞 Phone: +91 88702 45049</p>
    <p>✉️ Email: info@maaran.nale.parotta.dhan.com</p>

    <h3>Reserve a Table</h3>
    <form class="reservation-form">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Email Address" required>
      <input type="tel" placeholder="Phone Number" required>
      <input type="date" required>
      <input type="time" required>
      <textarea placeholder="Special Requests"></textarea>
      <button type="submit">Book Now</button>
    </form>
  </section>

  <footer>
    <p>© Maaran Parotta Kadai</p>
  </footer>
</body>
</html>

```
### Style.css
```
/* ====== General Styles ====== */
body {
  font-family: 'Poppins', sans-serif;
  margin: 0;
  background: linear-gradient(135deg, #1b1b1b, #2b2b2b, #3a3a3a);
  color: #fefefe;
  overflow-x: hidden;
  scroll-behavior: smooth;
}

/* ====== Header ====== */
header {
  background: linear-gradient(90deg, #f1c40f, #c0392b);
  color: #000;
  padding: 20px 0;
  text-align: center;
  letter-spacing: 1px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.3);
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline-block;
  margin: 0 20px;
}

nav ul li a {
  color: #000;
  text-decoration: none;
  font-weight: 600;
  font-size: 1.1em;
  position: relative;
  transition: all 0.3s ease;
}

nav ul li a::after {
  content: "";
  position: absolute;
  width: 0%;
  height: 2px;
  background: #000;
  bottom: -5px;
  left: 0;
  transition: width 0.3s ease;
}

nav ul li a:hover {
  color: #c0392b;
}

nav ul li a:hover::after {
  width: 100%;
}

/* ====== Hero Section ====== */
.hero {
  text-align: center;
  padding: 100px 20px;
  background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
    url('BUN.png') no-repeat center center/cover;
  background-size: cover;
  background-position: center;
  color: #f1c40f;
  box-shadow: inset 0 0 80px rgba(0, 0, 0, 0.6);
}


.hero h2 {
  font-size: 3em;
  margin-bottom: 15px;
  color: #f1c40f;
  text-shadow: 0 0 10px rgba(255,255,255,0.6);
}

.hero p {
  font-size: 1.3em;
  margin-bottom: 25px;
  color: #222;
}

.btn {
  background: linear-gradient(90deg, #f1c40f, #e74c3c);
  color: #000;
  padding: 12px 25px;
  text-decoration: none;
  border-radius: 30px;
  font-weight: 600;
  transition: all 0.3s ease;
  box-shadow: 0 0 10px rgba(241,196,15,0.4);
}

.btn:hover {
  transform: scale(1.05);
  box-shadow: 0 0 25px rgba(231,76,60,0.6);
}

/* ====== Menu Section ====== */
.menu {
  padding: 60px 20px;
  text-align: center;
  background: #fffaf0;
  color: #000;
}

.menu h2 {
  color: #c0392b;
  font-size: 2.4em;
  margin-bottom: 40px;
  text-shadow: 0 0 8px rgba(241,196,15,0.6);
}

.menu-item {
  background: rgba(255, 230, 150, 0.2);
  border: 1px solid rgba(241, 196, 15, 0.5);
  color: #222;
  margin: 20px auto;
  padding: 25px;
  width: 70%;
  border-radius: 15px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.15);
  transition: all 0.3s ease;
}

.menu-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 0 25px rgba(241,196,15,0.6);
}

/* ====== Gallery Section ====== */
.gallery {
  padding: 60px 20px;
  background: linear-gradient(180deg, #fffdf7, #fef4e8);
  text-align: center;
}

.gallery h2 {
  margin-bottom: 30px;
  color: #c0392b;
  text-shadow: 0 0 8px rgba(241,196,15,0.5);
}

.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin: 0 auto;
  max-width: 1000px;
}

.gallery-grid img {
  width: 100%;
  height: 230px;
  object-fit: cover;
  border-radius: 15px;
  transition: transform 0.4s ease, box-shadow 0.4s ease;
  border: 2px solid rgba(192, 57, 43, 0.2);
}

.gallery-grid img:hover {
  transform: scale(1.08);
  box-shadow: 0 0 20px rgba(241,196,15,0.5);
}

/* ====== About Section ====== */
.about {
  padding: 50px;
  text-align: center;
  width: 80%;
  margin: 50px auto;
  background: #fffaf0;
  border-radius: 20px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.15);
  color: #000;
}

/* ====== Contact Section ====== */
.contact {
  padding: 60px;
  text-align: center;
  background: #fff8e1;
  color: #000;
}

.contact h2 {
  color: #c0392b;
  margin-bottom: 30px;
  text-shadow: 0 0 8px rgba(241,196,15,0.5);
}

.reservation-form {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 60%;
  margin: 0 auto;
}

.reservation-form input,
.reservation-form textarea {
  width: 100%;
  padding: 12px;
  margin: 10px 0;
  border-radius: 10px;
  border: 1px solid rgba(192, 57, 43, 0.4);
  background: #fffef6;
  color: #000;
  font-size: 1em;
}

.reservation-form input:focus,
.reservation-form textarea:focus {
  border-color: #f1c40f;
  outline: none;
}

.reservation-form button {
  background: linear-gradient(90deg, #f1c40f, #c0392b);
  color: #000;
  border: none;
  padding: 12px 25px;
  border-radius: 30px;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s ease;
}

.reservation-form button:hover {
  transform: scale(1.05);
  box-shadow: 0 0 20px rgba(241,196,15,0.5);
}

/* ====== Footer ====== */
footer {
  background: linear-gradient(90deg, #f1c40f, #c0392b);
  color: #000;
  text-align: center;
  padding: 15px;
  font-weight: 600;
  letter-spacing: 1px;
  box-shadow: 0 -2px 15px rgba(0,0,0,0.3);
}

```


## OUTPUT:
<img width="1919" height="1084" alt="image" src="https://github.com/user-attachments/assets/059a4044-f76c-4375-9a4a-d37e89011089" />
<img width="1919" height="1059" alt="image-1" src="https://github.com/user-attachments/assets/699d42d7-d6da-41fe-a4ed-79e307d5861d" />
<img width="1919" height="1087" alt="image-2" src="https://github.com/user-attachments/assets/8d98a85c-15a4-48d0-abaf-f8af74cd4885" />
<img width="1919" height="1094" alt="image-3" src="https://github.com/user-attachments/assets/eb80f3cd-3be8-4d06-ab73-c366a0b9d11e" />
<img width="1715" height="991" alt="Screenshot 2025-11-10 092011" src="https://github.com/user-attachments/assets/64c2099c-07ac-49f6-9a2e-852e1f690b92" />

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
