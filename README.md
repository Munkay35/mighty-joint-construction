<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mighty Joint Construction</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"/>
  <link rel="stylesheet" href="assets/css/style.css"/>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand d-flex align-items-center" href="#">
      <img src="assets/images/logo.png" alt="Mighty Joint Construction Logo" height="40" class="me-2"/>
      <span class="text-limegreen">Mighty Joint Construction</span>
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active" href="index.html">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
        <li class="nav-item"><a class="nav-link" href="services.html">Services</a></li>
        <li class="nav-item"><a class="nav-link" href="portfolio.html">Portfolio</a></li>
        <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<header class="hero text-white text-center d-flex align-items-center">
  <div class="container">
    <h1 class="display-4">Welcome to <span class="text-orange">Mighty Joint Construction</h1>
    <p class="lead">Together We Can Build Anything</p>
    <a href="services.html" class="btn btn-lg btn-outline-light mt-3">Explore Services</a>
  </div>
</header>

<!-- About Section -->
<section class="about-section py-5">
  <div class="container text-center">
    <h2 class="mb-4 text-limegreen">About Us</h2>
    <p>We specialize in both residential and commercial construction projects. With years of experience, we guarantee the highest quality work.</p>
  </div>
</section>

<!-- Footer -->
<footer class="footer bg-dark text-white py-4">
  <div class="container text-center">
    <img src="assets/images/logo.png" alt="Mighty Joint Construction Logo" height="60" class="mb-3"/>
    <p class="mb-1">&copy; 2025 <span class="text-orange">Mighty Joint Construction</span>. All Rights Reserved.</p>
    <p class="mb-1">📞 980-327-2803</p>
    <p>📧 <a href="mailto:mightyjointconstruction@gmail.com" class="text-white">mightyjointconstruction@gmail.com</a></p>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
<script src="assets/js/main.js"></script>
</body>
</html>
/* Global Styles */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f4f4f4;
  color: #333;
}

/* Custom Colors */
.text-limegreen {
  color: limegreen;
}

.text-orange {
  color: orange;
}

/* Hero Section */
.hero {
  background: linear-gradient(to right, #333, #000);
  height: 80vh;
  padding: 60px 0;
}

/* Button Style */
.hero .btn {
  border-color: limegreen;
  color: limegreen;
}
.hero .btn:hover {
  background-color: limegreen;
  color: #fff;
}

/* Logo */
.navbar-brand img {
  max-height: 40px;
}
.footer img {
  max-height: 60px;
}

/* Navbar Hover */
.navbar a.nav-link:hover {
  color: orange !important;
}
/mighty-joint-construction
├── assets/
│   ├── images/
│   │   └── logo.png      ← Your uploaded logo here
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
├── index.html

