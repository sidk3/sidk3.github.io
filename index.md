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

<main>
  <section id="home" class="content-section">
    <h2>Hello, I'm Siddhartha Koushik 👋</h2>
    <p>A self-motivated Computer Science student with hands-on experience in AR/VR, full-stack development, and data engineering.</p>
    <p>I've built real-world projects using Angular, Node.js, Python, and SQL, and contributed to impactful solutions at Roche and PwC. I enjoy solving complex problems through clean, efficient code and constantly seek opportunities to learn, collaborate, and create technology that drives real-world impact.</p>
  </section>

  <section id="projects" class="content-section" style="display:none;">
    <h2>Projects</h2>
    <div class="project-card">
      <h3>Food Delivery Management App</h3>
      <p>Built using Angular 16, Node.js, MySQL 8.</p>
      <p>Developed 10+ REST APIs, schema with JSON fields, tested by 50+ users.</p>
    </div>
    <div class="project-card">
      <h3>Stock Market Research Agent</h3>
      <p>Built LLM-powered research agent with news sentiment, technicals, and real-time updates.</p>
      <p>Increased update speed by 30% with real-time integration.</p>
    </div>
    <div class="project-card">
      <h3>Federated Learning for Human Activity Recognition</h3>
      <p>Built privacy-focused HAR system with CNN/LSTM on 8 clients using FedAvg, FedMA, FedPA.</p>
      <p>Achieved 15% boost in accuracy with efficient preprocessing pipeline.</p>
    </div>
  </section>

  <section id="about" class="content-section" style="display:none;">
    <h2>About Me</h2>
    
    <div class="education">
        <h3>🎓 Education</h3>
        <ul>
            <li><strong>SASTRA Deemed University</strong> – B.Tech in Computer Science and Engineering (Oct 2022 - May 2026)<br>
            CGPA: 9.20/10</li>
            <li><strong>Vignan Junior College, Telangana</strong> – Intermediate (July 2020 - June 2022)<br>
            Score: 98.8%</li>
        </ul>
    </div>

    <div class="experience">
        <h3>💼 Experience</h3>
        <div class="job">
            <h4>Roche — Immersive Engineering Intern <em>(Oct 2024 - Present)</em></h4>
            <ul>
                <li>Developed and implemented AR/VR solutions in Unity, increasing user satisfaction by 15%.</li>
                <li>Conducted user testing, leading to iterative improvements that reduced user errors by 10%.</li>
            </ul>
        </div>
        <div class="job">
            <h4>PwC — Launchpad Analytics Insights <em>(Feb 2025 - June 2025)</em></h4>
            <ul>
                <li>Designed SQL schemas and queries in Oracle RDBMS, improving accuracy.</li>
                <li>Automated data manipulation with Python, reducing manual effort by 25%.</li>
            </ul>
        </div>
        <div class="job">
            <h4>Matrimony.com — Matrimorphosis Programme <em>(Dec 2024 - May 2025)</em></h4>
            <ul>
                <li>Completed curriculum in Angular.js & TypeScript with 95% project success.</li>
                <li>Collaborated on capstone project scored for functionality and innovation.</li>
            </ul>
        </div>
    </div>

    <div class="projects">
        <h3>🔧 Projects</h3>
        <div class="project">
            <h4>Food Delivery Management App</h4>
            <ul>
                <li>Built using Angular 16, Node.js, MySQL 8.</li>
                <li>Developed 10+ REST APIs, schema with JSON fields, tested by 50+ users.</li>
            </ul>
        </div>
        <div class="project">
            <h4>Stock Market Research Agent</h4>
            <ul>
                <li>Built LLM-powered research agent with news sentiment, technicals, and real-time updates.</li>
                <li>Increased update speed by 30% with real-time integration.</li>
            </ul>
        </div>
        <div class="project">
            <h4>Federated Learning for Human Activity Recognition</h4>
            <ul>
                <li>Built privacy-focused HAR system with CNN/LSTM on 8 clients using FedAvg, FedMA, FedPA.</li>
                <li>Achieved 15% boost in accuracy with efficient preprocessing pipeline.</li>
            </ul>
        </div>
    </div>

    <div class="skills">
        <h3>🛠️ Skills</h3>
        <ul>
            <li><strong>Languages:</strong> C, C++, Java, Python, HTML, CSS, JavaScript, TypeScript</li>
            <li><strong>Frameworks/Libraries:</strong> Angular, React, Node.js, Express, Tailwind CSS, Bootstrap</li>
            <li><strong>Databases:</strong> MongoDB, SQL</li>
            <li><strong>CS Fundamentals:</strong> OOPS, DBMS, Networks</li>
            <li><strong>Others:</strong> Machine Learning, DSA</li>
        </ul>
    </div>

    <div class="extracurricular">
        <h3>📌 Co-Curricular</h3>
        <p><strong>DAKSH Organizer, SASTRA University</strong><br>
        - Boosted merchandise sales by 25% and fundraising by 30% via targeted marketing.</p>
    </div>

    <div class="certifications">
        <h3>📜 Certifications</h3>
        <ul>
            <li><strong>DSA:</strong> Mastering Data Structures & Algorithms by Abdul Bari</li>
            <li><strong>ML:</strong> Machine Learning A-Z by Udemy (2025 edition)</li>
        </ul>
    </div>
  </section>

  <section id="contact" class="content-section" style="display:none;">
    <h2>Contact</h2>
    <ul>
      <li>📧 Email: <a href="mailto:sidkoushik3@gmail.com">sidkoushik3@gmail.com</a></li>
      <li>💻 GitHub: <a href="https://github.com/sidk3" target="_blank">github.com/sidk3</a></li>
      <li>👔 LinkedIn: <a href="https://linkedin.com/in/mutyala-siddhartha-koushik" target="_blank">linkedin.com/in/mutyala-siddhartha-koushik</a></li>
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
    
    // Update active nav link
    const navLinks = document.querySelectorAll('nav a');
    navLinks.forEach(link => link.style.backgroundColor = 'transparent');
    event.currentTarget.style.backgroundColor = '#4b5563';
  }
  
  // Show home section by default
  document.addEventListener('DOMContentLoaded', function() {
    showSection('home');
  });
</script>