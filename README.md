# mighty-joint-construction
/mighty-joint-construction
    /assets
        /images        # Store your logos and project images here
        /css           # Custom CSS or Bootstrap files
        /js            # Any JS files (like form handling, animations)
    /index.html        # Home page
    /about.html        # About page
    /services.html     # Services page
    /portfolio.html    # Portfolio/Projects page
    /contact.html      # Contact page (with a form)
    /css/style.css     # Your custom styles
    /js/main.js        # Any additional scripts
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mighty Joint Construction</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Mighty Joint Construction</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="index.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="services.html">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="portfolio.html">Portfolio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="hero bg-dark text-white text-center py-5">
        <div class="container">
            <h1>Welcome to Mighty Joint Construction</h1>
            <p>Together We Can Build Anything</p>
            <a href="services.html" class="btn btn-primary">Our Services</a>
        </div>
    </header>

    <!-- About Section -->
    <section class="about py-5">
        <div class="container">
            <h2 class="text-center">About Us</h2>
            <p class="text-center">We specialize in both residential and commercial construction projects. With years of experience, we guarantee the highest quality work.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2025 Mighty Joint Construction. All Rights Reserved.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
    <script src="assets/js/main.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us | Mighty Joint Construction</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Mighty Joint Construction</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="index.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="about.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="services.html">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="portfolio.html">Portfolio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- About Us Section -->
    <section class="about py-5">
        <div class="container">
            <h2 class="text-center">Who We Are</h2>
            <p class="text-center">Mighty Joint Construction is a leading construction company that specializes in both residential and commercial projects. With years of expertise, we deliver results with precision and care.</p>
            <!-- More content here -->
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2025 Mighty Joint Construction. All Rights Reserved.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
    <script src="assets/js/main.js"></script>
</body>
</html>
<!-- Same as previous HTML structure, just include your specific services content -->
<!-- Same structure; display images of past projects with descriptions -->
<!-- Include a simple contact form here -->
/* Add your color scheme and general styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
}

.hero {
    background-color: #000;
    color: #fff;
}

.navbar {
    background-color: #333;
}

.navbar a {
    color: #fff;
}

.navbar a:hover {
    color: #FFD700;
}

/* Custom colors */
.primary-color {
    color: limegreen;
}

.secondary-color {
    color: orange;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}
// You can add form functionality or any interactive features here
console.log("Mighty Joint Construction website is live!");
git add .
git commit -m "Initial commit of construction website"
git push origin main
