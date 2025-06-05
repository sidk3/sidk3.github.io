---
layout: default
title: Home
---

<link rel="stylesheet" href="assets/style.css">

<header>
  <h1>Mutyala Siddhartha Koushik</h1>
  <p>Full-Stack Developer | AR/VR | ML Enthusiast</p>
</header>

<nav>
  <a href="#" onclick="showSection('home')">Home</a>
  <a href="#" onclick="showSection('projects')">Projects</a>
  <a href="#" onclick="showSection('about')">About</a>
  <a href="#" onclick="showSection('contact')">Contact</a>
</nav>

<!-- Sections -->
<main>
  <section id="home" class="content-section">
    <h2>Hello, I'm Siddhartha Koushik 👋</h2>
    <p>A self-motivated Computer Science student with hands-on experience in AR/VR, full-stack development, and data engineering...</p>
  </section>

  <section id="projects" class="content-section" style="display:none;">
    <h2>Projects</h2>
    <h3>🔧 Smart Factory Resource Manager</h3>
    <p>A C-based multithreaded system managing robotic arms with deadlock prevention.</p>
    <h3>🌐 MERN Portfolio</h3>
    <p>Personal portfolio site built using MongoDB, Express.js, React, and Node.js.</p>
    <h3>🧠 Federated Learning Platform</h3>
    <p>Implemented FedAvg, FedCDA on TensorFlow with socket-based communication.</p>
  </section>

  <section id="about" class="content-section" style="display:none;">
    <h2>About Me</h2>
    <p>🎓 B.Tech in CSE @ SASTRA — CGPA: 9.20/10<br>
    💼 Intern at Roche, PwC, Matrimony.com<br>
    🛠️ Skilled in MERN, Unity, ML, and more</p>
  </section>

  <section id="contact" class="content-section" style="display:none;">
    <h2>Contact</h2>
    <ul>
      <li>Email: sidkoushik3@gmail.com</li>
      <li>GitHub: <a href="https://github.com/sidk3">sidk3</a></li>
      <li>LinkedIn: <a href="https://linkedin.com/in/siddhartha-koushik-mutyala">Mutyala Siddhartha Koushik</a></li>
    </ul>
  </section>
</main>

<footer>
  © 2025 Siddhartha Koushik
</footer>

<script>
  function showSection(id) {
    const sections = document.querySelectorAll('.content-section');
    sections.forEach(section => section.style.display = 'none');
    document.getElementById(id).style.display = 'block';
  }
</script>
