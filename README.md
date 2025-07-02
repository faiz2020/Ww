# Ww
html 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Faiz | DevOps Portfolio</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
</head>
<body>
  <header class="fade-in">
    <div class="container">
      <h1>Hello, I'm <span class="highlight">Faiz</span></h1>
      <p class="subtitle">DevOps Engineer | Cloud Enthusiast | Automation Explorer</p>
    </div>
  </header>

  <nav class="fade-in delay-1">
    <div class="container nav-links">
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <section id="about" class="card container fade-in delay-2">
    <h2>About Me</h2>
    <p>
      I’m a passionate DevOps learner currently working on cloud automation, CI/CD pipelines, and containerization. I thrive in solving real-world problems with scalable solutions.
    </p>
  </section>

  <section id="skills" class="card container fade-in delay-3">
    <h2>Skills</h2>
    <div class="skill-list">
      <span>Git</span>
      <span>Docker</span>
      <span>CI/CD</span>
      <span>Azure</span>
      <span>Linux</span>
      <span>Shell Scripting</span>
    </div>
  </section>

  <section id="projects" class="card container fade-in delay-4">
    <h2>Projects</h2>
    <div class="project-grid">
      <div class="project-card">
        <h3>🌐 Portfolio Website</h3>
        <p>Responsive HTML/CSS portfolio hosted on GitHub Pages.</p>
      </div>
      <div class="project-card">
        <h3>🐳 Dockerized App</h3>
        <p>Built and containerized a Node.js app to practice Docker fundamentals.</p>
      </div>
      <div class="project-card">
        <h3>☁️ Azure Pipeline</h3>
        <p>CI/CD setup using Azure DevOps for automated deployments.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="card container fade-in delay-5">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:faiz@example.com">faiz@example.com</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/yourname" target="_blank">linkedin.com/in/yourname</a></p>
  </section>

  <footer class="fade-in delay-6">
    <div class="container">
      <p>© 2025 Faiz | Designed with 💻 + ☁️</p>
    </div>
  </footer>
</body>
</html>


css
/* Font and Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', sans-serif;
  background: #f4f7fa;
  color: #222;
  line-height: 1.6;
  overflow-x: hidden;
}

.container {
  max-width: 1000px;
  margin: auto;
  padding: 20px;
}

header {
  background: linear-gradient(135deg, #6a11cb, #2575fc);
  color: white;
  text-align: center;
  padding: 70px 20px;
  animation: slideDown 1s ease-out;
}

h1 {
  font-size: 2.8rem;
  margin-bottom: 0.5rem;
}

.subtitle {
  font-size: 1.2rem;
  opacity: 0.9;
}

.highlight {
  color: #ffd700;
}

nav {
  background: white;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  position: sticky;
  top: 0;
  z-index: 10;
}

.nav-links {
  display: flex;
  justify-content: center;
  gap: 2rem;
  padding: 1rem 0;
}

nav a {
  text-decoration: none;
  color: #333;
  font-weight: 600;
  transition: color 0.3s;
}

nav a:hover {
  color: #2575fc;
}

.card {
  background: white;
  border-radius: 12px;
  padding: 2rem;
  margin-top: 2rem;
  box-shadow: 0 4px 20px rgba(0,0,0,0.06);
  opacity: 0;
  transform: translateY(20px);
  animation: fadeUp 0.6s forwards;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.5rem;
}

.project-card {
  background: #eef2f7;
  padding: 1.5rem;
  border-radius: 10px;
  border-left: 4px solid #2575fc;
  transition: transform 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  background: #dfe7f1;
}

.skill-list {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 1rem;
}

.skill-list span {
  background: #2575fc;
  color: white;
  padding: 8px 14px;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 600;
}

footer {
  background: #222;
  color: white;
  text-align: center;
  padding: 1.5rem 0;
  margin-top: 3rem;
}

/* Animations */
@keyframes fadeUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes slideDown {
  from {
    transform: translateY(-30px);
    opacity: 0;
  }
  to {
    transform: translateY(0);
    opacity: 1;
  }
}

/* Animation delays */
.fade-in {
  animation: fadeUp 0.6s ease-out forwards;
  opacity: 0;
  transform: translateY(20px);
}

.delay-1 { animation-delay: 0.2s; }
.delay-2 { animation-delay: 0.4s; }
.delay-3 { animation-delay: 0.6s; }
.delay-4 { animation-delay: 0.8s; }
.delay-5 { animation-delay: 1s; }
.delay-6 { animation-delay: 1.2s; }

/* Responsive */
@media (max-width: 600px) {
  h1 { font-size: 2rem; }
  .nav-links {
    flex-direction: column;
    gap: 1rem;
  }
}/* Font and Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', sans-serif;
  background: #f4f7fa;
  color: #222;
  line-height: 1.6;
  overflow-x: hidden;
}

.container {
  max-width: 1000px;
  margin: auto;
  padding: 20px;
}

header {
  background: linear-gradient(135deg, #6a11cb, #2575fc);
  color: white;
  text-align: center;
  padding: 70px 20px;
  animation: slideDown 1s ease-out;
}

h1 {
  font-size: 2.8rem;
  margin-bottom: 0.5rem;
}

.subtitle {
  font-size: 1.2rem;
  opacity: 0.9;
}

.highlight {
  color: #ffd700;
}

nav {
  background: white;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  position: sticky;
  top: 0;
  z-index: 10;
}

.nav-links {
  display: flex;
  justify-content: center;
  gap: 2rem;
  padding: 1rem 0;
}

nav a {
  text-decoration: none;
  color: #333;
  font-weight: 600;
  transition: color 0.3s;
}

nav a:hover {
  color: #2575fc;
}

.card {
  background: white;
  border-radius: 12px;
  padding: 2rem;
  margin-top: 2rem;
  box-shadow: 0 4px 20px rgba(0,0,0,0.06);
  opacity: 0;
  transform: translateY(20px);
  animation: fadeUp 0.6s forwards;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.5rem;
}

.project-card {
  background: #eef2f7;
  padding: 1.5rem;
  border-radius: 10px;
  border-left: 4px solid #2575fc;
  transition: transform 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  background: #dfe7f1;
}

.skill-list {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 1rem;
}

.skill-list span {
  background: #2575fc;
  color: white;
  padding: 8px 14px;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 600;
}

footer {
  background: #222;
  color: white;
  text-align: center;
  padding: 1.5rem 0;
  margin-top: 3rem;
}

/* Animations */
@keyframes fadeUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes slideDown {
  from {
    transform: translateY(-30px);
    opacity: 0;
  }
  to {
    transform: translateY(0);
    opacity: 1;
  }
}

/* Animation delays */
.fade-in {
  animation: fadeUp 0.6s ease-out forwards;
  opacity: 0;
  transform: translateY(20px);
}

.delay-1 { animation-delay: 0.2s; }
.delay-2 { animation-delay: 0.4s; }
.delay-3 { animation-delay: 0.6s; }
.delay-4 { animation-delay: 0.8s; }
.delay-5 { animation-delay: 1s; }
.delay-6 { animation-delay: 1.2s; }

/* Responsive */
@media (max-width: 600px) {
  h1 { font-size: 2rem; }
  .nav-links {
    flex-direction: column;
    gap: 1rem;
  }
}



git

git init
git remote add origin https://github.com/yourusername/my-portfolio.git
git add .
git commit -m "Initial portfolio"
git push -u origin master
