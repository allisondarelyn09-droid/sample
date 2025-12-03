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
      line-height: 1.6;
      background-color: #F4F4F4; /* light gray page background */
      color: #0B1D51; /* navy text default */
    }

    a { text-decoration: none; }

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

    /* Dark overlay for readability */
    .hero::before {
      content: '';
      position: absolute;
      top:0; left:0;
      width: 100%; height: 100%;
      background: rgba(11,29,81,0.6); /* navy overlay */
      z-index: 0;
    }

    .hero-content {
      position: relative;
      z-index: 1;
      max-width: 700px;
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

    .hero a.button {
      display: inline-block;
      background-color: #3A6B35; /* greenery */
      color: #FFFFFF;
      padding: 18px 35px;
      border-radius: 50px;
      font-weight: bold;
      font-size: 1rem;
      transition: all 0.3s ease;
    }

    .hero a.button:hover {
      background-color: #2E5529;
    }

    /* Content Section */
    .content {
      max-width: 700px;
      margin: 50px auto;
      background-color: #FFFFFF; /* white content box */
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      text-align: center;
    }

    .content p {
      font-size: 1rem;
      color: #0B1D51;
      line-height: 1.6;
    }

    /* Responsive */
    @media(max-width: 768px){
      .hero h1 { font-size: 2.2rem; }
      .hero p.subheadline { font-size: 1rem; }
      .hero img.logo { margin-bottom: 20px; }
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <img src="YOUR-LOGO-URL.png" alt="Salt & Synapse Wellness Logo" class="logo">
      <h1>Salt of the earth. Spark of the mind.</h1>
      <p class="subheadline">
        A space where modern psychiatry meets the art of balance. Salt & Synapse honors the whole person—mind, body, and everything that connects the two.
      </p>
      <a href="#book" class="button">Book a Free Discovery Call</a>
    </div>
  </section>

  <!-- Additional Content -->
  <section class="content">
    <p>
      Through personalized psychiatry, nutrition, and lifestyle medicine, the goal is 
      to help you restore clarity, calm, and connection within yourself. 
      Here, we go beyond symptoms to uncover what truly supports your wellness— 
      from the salt of the earth to the synapse of the mind.
    </p>
  </section>

</body>
</html>
