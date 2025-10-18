<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amruthesh  | Portfolio</title>
  <link rel="stylesheet" href="css/styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
  <!-- Fixed Navigation -->
  <nav class="navbar">
    <div class="nav-brand">Amruthesh S P</div>
    <ul class="nav-links">
      <li><a href="#about">About</a></li>
      <li><a href="#portfolio">Portfolio</a></li>
      <li><a href="#contact">Contact</a></li>
      <li><button id="darkModeToggle" aria-label="Toggle dark mode">🌙</button></li>
      <li><a href="assets/resume.pdf" download class="resume-btn">Resume</a></li>
    </ul>
  </nav>

  <!-- About Section -->
  <section id="about" class="section about-section">
    <img src="assets/profile.jpeg" alt="Profile Photo" class="profile-photo">
    <div class="about-content">
      <h1>Hello, I'm Amruthesh S P</h1>
      <p>About:
MCA student with skills in programming, front-end development. Proficient in HTML, CSS, JavaScript, Python, Java, and SQL with hands-on project experience in secure web applications. Passionate about solving problems through technology while exploring data-driven insights. Aspiring to build a career as a Front-End Developer</p>
      <ul class="skills-list">
        <li>HTML5</li>
        <li>CSS3</li>
        <li>JavaScript</li>
      </ul>
    </div>
  </section>
<div class="info-card">
  <div class="info-row">
    <div class="info-label">Name</div>
    <div class="info-value"><strong>Adwaid P</strong></div>
    <div class="info-label">Phone</div>
    <div class="info-value"><strong>+91-80758-01015</strong></div>
  </div>
  <div class="info-row">
    <div class="info-label">Age</div>
    <div class="info-value"><strong>21 Years</strong></div>
    <div class="info-label">Email</div>
    <div class="info-value"><strong>itzmeamru@amru@gmail.com</strong></div>
  </div>
  <div class="info-row">
    <div class="info-label">Qualification</div>
    <div class="info-value"><strong>Degree(BCA)</strong></div>
    <div class="info-label">Nationality</div>
    <div class="info-value"><strong>Indian</strong></div>
  </div>
</div>



  <!-- Portfolio Section -->
  <section id="portfolio" class="section portfolio-section">
    <h2>Selected Projects</h2>
    <div class="projects-grid">
      <!-- Example Project Card -->
      <div class="project-card">
        <img src="assets/project1.jpeg" alt="Project 1" class="project-image">
        <div class="project-info">
          <h3>Project Title</h3>
          <p>Short description of the project goes here. Highlight your role and technologies used.</p>
          <a href="https://github.com/yourusername/project1" target="_blank" class="project-link">View Project</a>
        </div>
      </div>
      <!-- Add more project cards as needed -->
    </div>
  </section>
  <!-- Contact Section -->
  <section id="contact" class="section contact-section">
    <h2>Contact Me</h2>

    <form id="contactForm" class="contact-form" action="https://formspree.io/f/mwpryjar" method="POST">
      <input type="hidden" name="_subject" value="New message from portfolio site">
      <input type="hidden" name="_next" value="/?submitted=true">

      <label for="name">Your Name</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Your Email</label>
      <input type="email" id="email" name="_replyto" required>

      <label for="message">Your Message</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <div class="form-actions" style="display:flex;gap:.5rem;align-items:center">
        <button type="submit" id="contactSubmit">Send Message</button>
        <div id="formStatus" role="status" aria-live="polite" style="font-size:.95rem;color:inherit"></div>
      </div>
    </form>

    <p class="contact-email">Or email me at <a href="mailto:adwaidp08@gmail.com">adwaidp08@gmail.com</a></p>
    <div class="social-buttons">
        <a href="www.linkedin.com/in/amruthesh-s-p-09016a246 class="social-btn linkedin" target="_blank" aria-label="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
        <a href="https://github.com/Amrue320" class="social-btn github" target="_blank" aria-label="GitHub"><i class="fab fa-github"></i></a>
    </div>

  </section>

  <script src="js/main.js"></script>
  <script src="js/contact.js"></script>
</body>
</html>
<!-- ...existing code... -->
