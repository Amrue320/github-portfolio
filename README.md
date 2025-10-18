<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Amruthesh SP — Portfolio</title>

  <!-- Bootstrap 5 CSS via CDN -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
    crossorigin="anonymous"
  />

  <style>
    :root { --accent: #0d6efd; }
    body { scroll-behavior: smooth; }
    .navbar-brand { font-weight: 600; }
    .hero { padding: 6rem 0 4rem; background: linear-gradient(180deg,#f8f9fa 0%,#ffffff 100%); }
    .tag { display:inline-block; padding:.25rem .5rem; border:1px solid #dee2e6; border-radius:999px; font-size:.85rem; margin:.25rem .25rem 0 0; }
    .project-card img { width:100%; height:180px; object-fit:cover; border-top-left-radius:.5rem; border-top-right-radius:.5rem; background:#f1f3f5; }
    .footer { border-top:1px solid #e9ecef; }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg bg-white border-bottom sticky-top">
    <div class="container">
      <a class="navbar-brand" href="#top">Amruthesh SP</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav"
              aria-controls="nav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="nav" class="collapse navbar-collapse">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#education">Education</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <header id="top" class="hero">
    <div class="container">
      <div class="row align-items-center g-4">
        <div class="col-12 col-lg-7">
          <h1 class="display-5 fw-bold mb-2">Amruthesh SP</h1>
          <p class="lead text-muted mb-3">
            MCA (pursuing) and BSc graduate with strong skills in Python and Java, building clean, practical software and learning continuously.
          </p>
          <div class="mb-4">
            <span class="tag">Python</span>
            <span class="tag">Java</span>
            <span class="tag">Django</span>
            <span class="tag">REST APIs</span>
            <span class="tag">SQL</span>
            <span class="tag">Git/GitHub</span>
          </div>
          <a href="#projects" class="btn btn-primary me-2">View Projects</a>
          <a href="#contact" class="btn btn-outline-secondary">Contact</a>
        </div>
        <div class="col-12 col-lg-5">
          <div class="card shadow-sm">
            <div class="card-body">
              <h2 class="h5 mb-2">Profile Summary</h2>
              <p class="mb-2">
                Focused on writing readable, maintainable code with an emphasis on problem‑solving, fundamentals, and real‑world application.
              </p>
              <ul class="mb-0">
                <li>Hands‑on with Python/Java projects and REST services</li>
                <li>Comfortable with Git workflows and documentation</li>
                <li>Open to internships, projects, and collaborations</li>
              </ul>
            </div>
          </div>
        </div>
      </div><!-- /row -->
    </div>
  </header>

  <!-- About -->
  <section id="about" class="py-5">
    <div class="container">
      <h2 class="h3 mb-3">About</h2>
      <p class="text-muted">
        Enthusiastic developer skilled in Python and Java, exploring backend development and data‑driven applications while pursuing MCA and applying BSc foundations to build reliable, user‑centric solutions.
      </p>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="py-5 bg-light">
    <div class="container">
      <h2 class="h3 mb-3">Skills</h2>
      <div class="row g-3">
        <div class="col-6 col-md-3"><div class="tag w-100 text-center">Python</div></div>
        <div class="col-6 col-md-3"><div class="tag w-100 text-center">Java</div></div>
        <div class="col-6 col-md-3"><div class="tag w-100 text-center">Django</div></div>
        <div class="col-6 col-md-3"><div class="tag w-100 text-center">Flask</div></div>
        <div class="col-6 col-md-3"><div class="tag w-100 text-center">REST APIs</div></div>
        <div class="col-6 col-md-3"><div class="tag w-100 text-center">SQL</div></div>
        <div class="col-6 col-md-3"><div class="tag w-100 text-center">Git/GitHub</div></div>
        <div class="col-6 col-md-3"><div class="tag w-100 text-center">HTML/CSS</div></div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-5">
    <div class="container">
      <h2 class="h3 mb-4">Projects</h2>
      <div class="row g-4">
        <!-- Project 1 -->
        <div class="col-12 col-md-6 col-lg-4">
          <div class="card h-100 shadow-sm project-card">
            <img src="https://via.placeholder.com/600x400" alt="Movie Recommendation App preview" />
            <div class="card-body d-flex flex-column">
              <h3 class="h5">Movie Recommendation App</h3>
              <p class="text-muted mb-2">
                Single‑page frontend with Bootstrap calling a Python backend that returns JSON recommendations.
              </p>
              <div class="mb-3">
                <span class="tag">Python</span>
                <span class="tag">Django/Flask</span>
                <span class="tag">Bootstrap</span>
              </div>
              <div class="mt-auto">
                <a href="#" class="btn btn-sm btn-outline-primary me-2">Live</a>
                <a href="#" class="btn btn-sm btn-outline-secondary">Code</a>
              </div>
            </div>
          </div>
        </div>
        <!-- Project 2 -->
        <div class="col-12 col-md-6 col-lg-4">
          <div class="card h-100 shadow-sm project-card">
            <img src="https://via.placeholder.com/600x400" alt="Java REST API preview" />
            <div class="card-body d-flex flex-column">
              <h3 class="h5">Java REST API Service</h3>
              <p class="text-muted mb-2">
                CRUD API with validation and pagination, documented with clear endpoints and examples.
              </p>
              <div class="mb-3">
                <span class="tag">Java</span>
                <span class="tag">Spring Boot</span>
                <span class="tag">PostgreSQL</span>
              </div>
              <div class="mt-auto">
                <a href="#" class="btn btn-sm btn-outline-primary me-2">Live</a>
                <a href="#" class="btn btn-sm btn-outline-secondary">Code</a>
              </div>
            </div>
          </div>
        </div>
        <!-- Project 3 -->
        <div class="col-12 col-md-6 col-lg-4">
          <div class="card h-100 shadow-sm project-card">
            <img src="https://via.placeholder.com/600x400" alt="Algorithm Practice preview" />
            <div class="card-body d-flex flex-column">
              <h3 class="h5">Algorithm Practice</h3>
              <p class="text-muted mb-2">
                Python and Java exercises: arrays, strings, recursion, and common interview problems.
              </p>
              <div class="mb-3">
                <span class="tag">Python</span>
                <span class="tag">Java</span>
                <span class="tag">DSA</span>
              </div>
              <div class="mt-auto">
                <a href="#" class="btn btn-sm btn-outline-primary me-2">Docs</a>
                <a href="#" class="btn btn-sm btn-outline-secondary">Code</a>
              </div>
            </div>
          </div>
        </div>
      </div><!-- /row -->
    </div>
  </section>

  <!-- Education -->
  <section id="education" class="py-5 bg-light">
    <div class="container">
      <h2 class="h3 mb-3">Education</h2>
      <div class="row g-4">
        <div class="col-12 col-lg-6">
          <div class="card h-100 shadow-sm">
            <div class="card-body">
              <h3 class="h5 mb-1">MCA (Pursuing)</h3>
              <p class="text-muted mb-2">Coursework in software engineering, databases, and systems.</p>
              <ul class="mb-0">
                <li>Backend development with Python/Java</li>
                <li>Data management and SQL</li>
                <li>Team projects and presentations</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-12 col-lg-6">
          <div class="card h-100 shadow-sm">
            <div class="card-body">
              <h3 class="h5 mb-1">BSc (Completed)</h3>
              <p class="text-muted mb-2">Strong CS fundamentals and problem‑solving foundation.</p>
              <ul class="mb-0">
                <li>Programming principles and OOP</li>
                <li>Data structures and algorithms</li>
                <li>Software lifecycle and documentation</li>
              </ul>
            </div>
          </div>
        </div>
      </div><!-- /row -->
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-5">
    <div class="container">
      <h2 class="h3 mb-3">Contact</h2>
      <p class="text-muted">Open to internships, junior roles, and project collaborations.</p>
      <div class="d-flex flex-wrap align-items-center gap-2">
        <a href="mailto:your.email@example.com" class="btn btn-primary">Email</a>
        <a href="#" class="btn btn-outline-secondary">LinkedIn</a>
        <a href="#" class="btn btn-outline-secondary">GitHub</a>
        <a href="#" class="btn btn-outline-secondary">Resume</a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer py-4 bg-white">
    <div class="container text-center small text-muted">
      © <span id="year"></span> Amruthesh SP — Built with Bootstrap 5
    </div>
  </footer>

  <!-- Bootstrap JS Bundle (includes Popper) via CDN -->
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
    crossorigin="anonymous"></script>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>

