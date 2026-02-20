<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>River North - Page 3</title>

<style>
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
}

/* Header */
header {
    background: #1f2937;
    color: white;
    padding: 20px;
    text-align: center;
}

/* Navigation */
nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin-top: 10px;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #38bdf8;
}

/* Hero */
.hero {
    background: url('https://images.unsplash.com/photo-1494526585095-c41746248156') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.hero h2 {
    font-size: 40px;
}

.hero p {
    font-size: 18px;
    margin-top: 10px;
}

/* Gallery */
.gallery {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 40px;
    flex-wrap: wrap;
}

.card {
    background: white;
    width: 300px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    overflow: hidden;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.card h3 {
    padding: 15px;
}

.card p {
    padding: 0 15px 15px;
    color: #555;
}

/* Footer */
footer {
    background: #1f2937;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}

/* Sections for Page 1 & 2 */
.section {
    padding: 60px 20px;
    text-align: center;
}

.section h2 {
    margin-bottom: 15px;
}
</style>

</head>
<body>

<header>
    <h1>River North District</h1>
    <nav>
        <ul>
            <li><a href="#home">Home (Page 1)</a></li>
            <li><a href="#about">About (Page 2)</a></li>
            <li><a href="#gallery">Gallery (Page 3)</a></li>
        </ul>
    </nav>
</header>

<!-- Page 1 -->
<section id="home" class="section">
    <h2>Welcome to River North</h2>
    <p>River North is known for its modern architecture, art galleries, and vibrant city lifestyle.</p>
</section>

<!-- Page 2 -->
<section id="about" class="section" style="background:#e5e7eb;">
    <h2>About River North</h2>
    <p>This district features fine dining restaurants, luxury apartments, creative spaces, and exciting nightlife experiences.</p>
</section>

<!-- Page 3 -->
<section id="gallery">
    <div class="hero">
        <h2>Explore River North</h2>
        <p>Discover the beauty and creativity of the city.</p>
    </div>

    <div class="gallery">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1508057198894-247b23fe5ade" alt="City Skyline">
            <h3>City Skyline</h3>
            <p>Modern skyline view of River North.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1491553895911-0055eca6402d" alt="Art Gallery">
            <h3>Art Galleries</h3>
            <p>Creative art galleries showcasing modern designs.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" alt="Night Life">
            <h3>Night Life</h3>
            <p>Enjoy vibrant nightlife and restaurants.</p>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2026 River North | All Rights Reserved</p>
</footer>

</body>
</html># rivernorth353
