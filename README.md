<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bushra Ubaid | Portfolio</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #0e0e0e;
      color: #f1f1f1;
      line-height: 1.6;
      background-image: radial-gradient(circle at top left, #1a1a1a, #0e0e0e);
    }
    a { text-decoration: none; color: #a0c4ff; }
    .container { padding: 60px 20px; max-width: 1100px; margin: auto; }

    /* Hero */
    .hero {
      background: linear-gradient(135deg, #121212, #1f1f1f);
      text-align: center;
      padding: 100px 20px;
    }
    .hero h1 {
      font-size: 3.5rem;
      color: #ffffff;
    }
    .typing-text {
      font-size: 1.4rem;
      color: #a0c4ff;
      min-height: 40px;
      margin: 15px 0;
    }
    .hero p {
      max-width: 700px;
      margin: 20px auto;
      color: #cccccc;
    }
    .hero img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-top: 20px;
      object-fit: cover;
      border: 3px solid #a0c4ff;
    }

    /* Skills */
    .skills h2, .projects h2, .contact h2 {
      text-align: center;
      font-size: 2.5rem;
      margin-bottom: 40px;
      color: #a0c4ff;
    }
    .skill-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .skill-card {
      background: #191919;
      padding: 20px;
      border-radius: 10px;
      transition: 0.3s;
    }
    .skill-card:hover {
      background: #2a2a2a;
    }
    .skill-card h3 { color: #ffffff; margin-bottom: 10px; }
    .skill-card p { color: #bbbbbb; }

    /* Projects */
    .projects .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }
    .project-card {
      background: #191919;
      padding: 20px;
      border-radius: 10px;
      transition: 0.3s;
    }
    .project-card:hover {
      background: #2a2a2a;
    }
    .project-card h4 {
      color: #a0c4ff;
      margin-bottom: 10px;
    }
    .project-card img{
      width: 100%;
    }
    .project-card p { color: #bbbbbb; }

    /* Contact Info */
    .contact-info {
      background-color: #191919;
      padding: 40px;
      border-radius: 10px;
      text-align: center;
    }
    .contact-info p {
      margin: 10px 0;
      color: #cccccc;
    }
    .contact-info a {
      color: #a0c4ff;
      text-decoration: none;
    }

    .cv-link {
      text-align: center;
      margin-top: 30px;
    }
    .cv-link a {
      background: #a0c4ff;
      color: #000;
      padding: 10px 20px;
      border-radius: 5px;
      display: inline-block;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <section class="hero">
    <h1>Bushra Ubaid</h1>
    <div class="typing-text" id="typing"></div>
    <p>
      I’m a full-stack developer with a passion for clean, intuitive design and scalable code.
      With years of experience, I specialize in creating high-performance, client-centric applications
      that deliver exceptional user experiences.
    </p>
    <img src="./images/bushra.jpg" alt="Bushra Ubaid">
  </section>

  <section class="container skills">
    <h2>My Skills</h2>
    <div class="skill-grid">
      <div class="skill-card">
        <h3>UI/UX Design</h3>
        <p>Crafting intuitive user experiences using Figma and design systems.</p>
      </div>
      <div class="skill-card">
        <h3>Frontend Development</h3>
        <p>Expert in HTML, CSS, JavaScript, React, and animations.</p>
      </div>
      <div class="skill-card">
        <h3>Backend Development</h3>
        <p>Developing robust APIs and databases with Node.js and MongoDB.</p>
      </div>
      <div class="skill-card">
        <h3>Performance Optimization</h3>
        <p>Speeding up sites with performance audits and lazy loading.</p>
      </div>
      <div class="skill-card">
        <h3>Deployment & CI</h3>
        <p>Deploying apps with GitHub, Netlify, and CI/CD pipelines.</p>
      </div>
    </div>
  </section>

  <section class="container projects">
    <h2>Project Showcase</h2>
    <div class="project-grid">
      <div class="project-card">
        <h4>Spotify Clone</h4>
        <p>A clean, animated personal portfolio to showcase design and dev skills.</p>
      </div>
      <div class="project-card">
        <h4>E-Commerce App</h4>
        <img src="./images/ecomerce.png" alt="">
        <p>A fully responsive e-commerce frontend built with React and Redux.</p>
      </div>
      <div class="project-card">
        <h4>Resturant Web design</h4>
        <img src="/images/dining.png" alt="">
        <p>A blog management system with admin dashboard.</p>
      </div>
    </div>
    <div class="cv-link">
      <p>Download my CV</p>
      <a href="Bushra_Ubaid_CV.pdf" download>Download CV</a>
    </div>
  </section>

  <section class="container contact">
    <h2>Contact Me</h2>
    <div class="contact-info">
      <p><strong>Phone:</strong> +1 (773) 998-7418</p>
      <p><strong>Email:</strong> <a href="mailto:info.bushraubaid@gmail.com">info.bushraubaid@gmail.com</a></p>
      <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/bushra-ubaid-970540229" target="_blank">Bushra Ubaid</a></p>
      <p><strong>Instagram:</strong> <a href="https://www.instagram.com/be_bushraa" target="_blank">@be_bushraa</a></p>
    </div>
  </section>

  <script>
    const typing = document.getElementById("typing");
    const phrases = [
      "Creative Developer",
      "UI/UX Enthusiast",
      "Frontend & Backend Engineer",
      "Design-Led Coder"
    ];
    let i = 0, j = 0, currentPhrase = [], isDeleting = false;

    function typeLoop() {
      typing.innerHTML = currentPhrase.join("");
      if (!isDeleting && j < phrases[i].length) {
        currentPhrase.push(phrases[i][j++]);
      } else if (isDeleting && j > 0) {
        currentPhrase.pop();
        j--;
      } else if (!isDeleting && j === phrases[i].length) {
        isDeleting = true;
        setTimeout(typeLoop, 1000);
        return;
      } else if (isDeleting && j === 0) {
        isDeleting = false;
        i = (i + 1) % phrases.length;
      }
      setTimeout(typeLoop, isDeleting ? 50 : 100);
    }
    typeLoop();
  </script>
</body>
</html>
