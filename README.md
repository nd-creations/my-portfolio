<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", sans-serif;
      background: linear-gradient(135deg, #f0f4f8, #d9e2ec);
      color: #333;
    }
    header {
      background: linear-gradient(90deg, #222, #444);
      color: #fff;
      padding: 2rem;
      text-align: center;
      position: relative;
    }
    header h1 { margin: 0; font-size: 2.5rem; }
    header p { margin-top: .5rem; font-size: 1.2rem; }

    .profile-pic {
      position: absolute;
      top: 20px;
      right: 30px;
      width: 80px;
      height: 80px;
      border-radius: 50%;
      border: 3px solid #fff;
      object-fit: cover;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    nav {
      background: #555;
      text-align: center;
      padding: 1rem;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 3rem 10%;
    }
    .about, .projects, .contact {
      margin-bottom: 3rem;
    }
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .project-card {
      background: #fff;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .project-card:hover { transform: translateY(-5px); }
    footer {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 1rem;
    }
    button {
      background: #007BFF;
      border: none;
      padding: 10px 20px;
      color: white;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 10px;
    }
    button:hover { background: #0056b3; }

    /* Social buttons */
    .social-links {
      margin-top: 15px;
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
    }
    .btn {
      text-decoration: none;
      padding: 8px 15px;
      border-radius: 5px;
      color: white;
      font-weight: bold;
      display: inline-block;
      transition: background 0.3s ease;
    }
    .linkedin { background: #0077b5; }
    .linkedin:hover { background: #005582; }

    .github { background: #333; }
    .github:hover { background: #000; }

    .instagram { background: #e4405f; }
    .instagram:hover { background: #b7324b; }

    .whatsapp { background: #25D366; }
    .whatsapp:hover { background: #1ebe57; }
  </style>
</head>
<body>

  <header>
    <h1>Naveen ND</h1>
    <p>Web Developer | Designer | Programmer</p>
    <img src="king.jpg" alt="Profile Photo" class="profile-pic">
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      Hi, I’m <strong>Naveen</strong> — a passionate web developer with a strong interest in creating 
      modern, responsive, and user-friendly websites. I enjoy turning complex problems into simple, 
      beautiful, and intuitive solutions.
    </p>
    <p>
      My skill set includes <b>HTML, CSS, JavaScript, and basic frameworks</b>. I also explore 
      creative designs, interactive UI elements, and clean coding practices. Apart from development, 
      I have a keen eye for design which helps me bring ideas to life with both functionality and aesthetics.
    </p>
    <p>
      I’m constantly learning new technologies to improve my work and stay up-to-date with the 
      latest industry trends. I believe in continuous growth, teamwork, and innovation. 
    </p>
    <p>
      Outside of coding, I love exploring new tech tools, building mini-projects like games & apps, 
      and sharing knowledge with friends. 🚀
    </p>
  </section>

  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="projects-grid">
      <div class="project-card">
        <h3>Portfolio Website</h3>
        <p>A responsive personal portfolio built with HTML, CSS, and JavaScript.</p>
      </div>
      <div class="project-card">
        <h3>Car Game</h3>
        <p>A fun top-down car racing game coded in JavaScript & Canvas.</p>
      </div>
      <div class="project-card">
        <h3>AI Chatbot</h3>
        <p>A simple chatbot powered by natural language processing APIs.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:naveendevihosur107@gmail.com">naveendevihosur107@gmail.com</a></p>
    <p>Mobile: <a href="tel:+919876543210">+91-8088046932</a></p>

    
<div class="social-links">
  <a href="https://www.linkedin.com/in/naveen-devihosur-a94728362/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank" class="btn linkedin">💼 LinkedIn</a>
  <a href="https://github.com/nd-creations" target="_blank" class="btn github">💻 GitHub</a>
  <a href="https://www.instagram.com/naveen_devihosur?igsh=MXJlYTNrYXFnN2Jt" target="_blank" class="btn instagram">📷 Instagram</a>
  <a href="https://wa.me/919876543210" target="_blank" class="btn whatsapp">💬 WhatsApp</a>
</div>

    <button onclick="alert('Thanks for reaching out!')">Say Hi 👋</button>
  </section>

  <footer>
    <p>© 2025 Naveen ND. All Rights Reserved.</p>
  </footer>

</body>
</html> ineed  about me ,projects ,contents different pages
