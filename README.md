<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Salt & Synapse Wellness</title>
<style>
  /* Reset */
  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Arial', sans-serif;
    background-color: #F4F4F4; 
    color: #0B1D51; 
    line-height: 1.6;
    scroll-behavior: smooth; /* smooth scrolling for nav links */
  }

  a { text-decoration: none; }

  /* Sticky Navigation */
  nav {
    position: sticky;
    top: 0;
    background-color: #FFFFFF;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    z-index: 1000;
  }

  nav img.logo { width: 150px; }

  nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
  }

  nav ul li a {
    color: #0B1D51;
    font-weight: bold;
    transition: color 0.3s;
  }

  nav ul li a:hover {
    color: #3A6B35;
  }

  /* Buttons */
  .button {
    display: inline-block;
    background-color: #3A6B35; 
    color: #FFFFFF;
    padding: 15px 30px;
    border-radius: 50px;
    font-weight: bold;
    transition: all 0.3s ease;
  }

  .button:hover { background-color: #2E5529; }

  /* Hero Section */
  .hero {
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    min-height: 100vh;
    padding: 50px 20px;
    background: url('YOUR-BACKGROUND-IMAGE-URL.jpg') no-repeat center center/cover;
    color: #FFFFFF;
  }

  .hero::before {
    content: '';
    position: absolute;
    top:0; left:0;
    width: 100%; height: 100%;
    background: rgba(11,29,81,0.6); 
    z-index: 0;
  }

  .hero-content {
    position: relative;
    z-index: 1;
    max-width: 700px;
    opacity: 0;
    transform: translateY(30px);
    transition: all 1s ease-out;
  }

  .hero-content.show {
    opacity: 1;
    transform: translateY(0);
  }

  .hero img.logo {
    width: 220px;
    max-width: 80%;
    margin-bottom: 30px;
  }

  .hero h1 {
    font-size: 2.8rem;
    font-weight: bold;
    margin-bottom: 20px;
    line-height: 1.2;
  }

  .hero p.subheadline {
    font-size: 1.2rem;
    margin-bottom: 35px;
    line-height: 1.6;
  }

  /* Section styling */
  section {
    padding: 60px 20px;
  }

  .section-content {
    max-width: 900px;
    margin: 0 auto;
    text-align: center;
    opacity: 0;
    transform: translateY(30px);
    transition: all 1s ease-out;
  }

  .section-content.show {
    opacity: 1;
    transform: translateY(0);
  }

  .section-content h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #0B1D51;
  }

  .section-content p {
    font-size: 1rem;
    color: #0B1D51;
    margin-bottom: 30px;
    line-height: 1.6;
  }

  .card-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
  }

  .card {
    background-color: #FFFFFF;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    flex: 1 1 250px;
    max-width: 300px;
    text-align: center;
    opacity: 0;
    transform: translateY(30px);
    transition: all 1s ease-out;
  }

  .card.show {
    opacity: 1;
    transform: translateY(0);
  }

  .card h3 {
    margin-bottom: 15px;
    color: #0B1D51;
  }

  /* Footer */
  footer {
    background-color: #0B1D51;
    color: #FFFFFF;
    text-align: center;
    padding: 30px 20px;
  }

  /* Responsive */
  @media(max-width: 768px){
    .hero h1 { font-size: 2.2rem; }
    .hero p.subheadline { font-size: 1rem; }
    .hero img.logo { margin-bottom: 20px; }
    .card-container { flex-direction: column; align-items: center; }
    nav ul { flex-direction: column; gap: 10px; }
  }
</style>
</head>
<body>

<!-- Navigation -->
<nav>
  <img src="YOUR-LOGO-URL.png" alt="Salt & Synapse Wellness Logo" class="logo">
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#services">Services</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- Hero Section -->
<section class="hero">
  <div class="hero-content">
    <img src="YOUR-LOGO-URL.png" alt="Salt & Synapse Wellness Logo" class="logo">
    <h1>Salt of the earth. Spark of the mind.</h1>
    <p class="subheadline">
      A space where modern psychiatry meets the art of balance. Salt & Synapse honors the whole person—mind, body, and everything that connects the two.
    </p>
    <a href="#contact" class="button">Book a Free Discovery Call</a>
  </div>
</section>

<!-- About Section -->
<section id="about" style="background-color: #F4F4F4;">
  <div class="section-content">
    <h2>About Salt & Synapse Wellness</h2>
    <p>
      Through personalized psychiatry, nutrition, and lifestyle medicine, we help you restore clarity, calm, and connection within yourself. We go beyond symptoms to uncover what truly supports your wellness.
    </p>
  </div>
</section>

<!-- Services Section -->
<section id="services">
  <div class="section-content">
    <h2>Our Services</h2>
    <div class="card-container">
      <div class="card">
        <h3>Personalized Psychiatry</h3>
        <p>Comprehensive mental health care tailored to your unique needs.</p>
      </div>
      <div class="card">
        <h3>Nutrition Guidance</h3>
        <p>Support for mental and physical wellness through diet and lifestyle.</p>
      </div>
      <div class="card">
        <h3>Lifestyle Medicine</h3>
        <p>Holistic strategies to improve overall well-being and balance.</p>
      </div>
    </div>
  </div>
</section>

<!-- Contact Section -->
<section id="contact" style="background-color: #F4F4F4;">
  <div class="section-content">
    <h2>Book Your Free Discovery Call</h2>
    <p>Take the first step toward restoring clarity and connection. Schedule your consultation today.</p>
    <a href="mailto:contact@saltsynapse.com" class="button">Book Now</a>
  </div>
</section>

<!-- Footer -->
<footer>
  &copy; 2025 Salt & Synapse Wellness. All rights reserved.
</footer>

<script>
  // Animate sections on scroll
  const sections = document.querySelectorAll('.section-content, .card, .hero-content');

  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if(entry.isIntersecting){
        entry.target.classList.add('show');
      }
    });
  }, { threshold: 0.2 });

  sections.forEach(section => observer.observe(section));
</script>

</body>
</html>
