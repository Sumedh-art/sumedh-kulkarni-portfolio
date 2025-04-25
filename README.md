# sumedh-kulkarni-portfolio
Personal digital portfolio showcasing my engineering projects, CAD skills, and more.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sumedh Kulkarni | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet" />
  <style>
    :root {
      --bg-beige: #f5f5dc;
      --text-dark: #1e1e1e;
      --accent: #444;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: var(--bg-beige);
      color: var(--text-dark);
    }

    header {
      background: #e0dbc0;
      color: var(--text-dark);
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3em;
      animation: slideInDown 1.5s ease-in-out;
    }

    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    .profile-pic {
      width: 280px;
      height: 280px;
      border-radius: 50%;
      object-fit: cover;
      border: 6px solid var(--text-dark);
      display: block;
      margin: 40px auto;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
      animation: zoomIn 1.2s ease-in-out;
    }

    section {
      margin-bottom: 50px;
    }

    h2, h3 {
      color: var(--text-dark);
      margin-bottom: 15px;
      font-size: 2em;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    li {
      margin-bottom: 8px;
    }

    .social-icons a {
      margin-right: 15px;
      font-size: 1.2em;
      color: var(--text-dark);
      text-decoration: none;
      transition: transform 0.3s ease;
    }

    .social-icons a:hover {
      transform: scale(1.2);
      color: var(--accent);
    }

    .project-img {
      width: 100%;
      max-width: 600px;
      height: auto;
      border-radius: 12px;
      margin-top: 15px;
      border: 3px solid var(--text-dark);
      display: block;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #e0dbc0;
      color: var(--text-dark);
      font-size: 0.9em;
    }

    /* Animations */
    @keyframes slideInDown {
      0% { transform: translateY(-50px); opacity: 0; }
      100% { transform: translateY(0); opacity: 1; }
    }

    @keyframes zoomIn {
      from { transform: scale(0.5); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }
  </style>
</head>
<body>

<header>
  <h1>Hi, I'm Sumedh Kulkarni</h1>
  <p>Welcome to my Digital Portfolio. I am a Mechanical Engineering Student | CAD & Programming Enthusiast</p>
</header>

<div class="container">

  <img src="Sumedh-2.jpg" alt="Portrait of Sumedh Kulkarni" class="profile-pic" />

  <section>
    <h2>About Me</h2>
    <p>Hello! I'm Sumedh Kulkarni, a passionate, curious and motivated first-year BTech Mechanical Engineering student with a strong foundation in CAD tools and programming languages. I love building innovative designs and writing efficient code. I enjoy learning new things and bringing ideas to life through creative problem solving and hands-on projects. My digital portfolio showcases the work I have done in areas like CAD models, EV models. I aim to approach every challenge with creativity and precision.</p>
  </section>

  <section>
    <h2>Skills</h2>
    <ul>
      <li>AutoCAD & Fusion 360 (Expert, hands-on experience)</li>
      <li>C, C++, Python, HTML</li>
      <li>Problem-solving and logical thinking</li>
    </ul>
  </section>

  <section>
    <h2>Education</h2>
    <ul>
      <li>BTech in Mechanical Engineering (1st Year)</li>
      <li>12th Grade - 84%</li>
      <li>10th Grade - 88%</li>
    </ul>
  </section>

  <section>
    <h2>Projects</h2>
    <h3>Arduino Robot Car Model</h3>
    <p>I built an Arduino-powered robot car model that can be controlled wirelessly. It uses ultrasonic sensors for obstacle detection and can follow a path using IR sensors.</p>
    <img src="Arduino image.jpg" alt="Arduino Robot Car Model" class="project-img" />
  </section>

  <section>
    <h2>Contact</h2>
    <p>Feel free to reach out to me through these platforms:</p>
    <div class="social-icons">
      <a href="https://twitter.com/KSumedh1609" target="_blank">🐦 @KSumedh1609</a>
      <a href="mailto:sumedhk283@gmail.com">✉️ sumedhk283@gmail.com</a>
    </div>
  </section>

</div>

<footer>
  © 2025 Sumedh Kulkarni | All rights reserved
</footer>

</body>
</html>
