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
  <header>
    <div class="container">
      <h1>👋 Hi, I'm <span class="highlight">Faiz</span></h1>
      <p class="subtitle">DevOps Engineer • Cloud Learner • Automation Enthusiast</p>
    </div>
  </header>

  <nav>
    <div class="container nav-links">
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <section id="about" class="card container">
    <h2>About Me</h2>
    <p>
      I'm an aspiring DevOps engineer learning cloud, containers, CI/CD, and infrastructure automation.
      I love solving problems, working with cloud-native tools, and continuously improving systems.
    </p>
  </section>

  <section id="projects" class="card container">
    <h2>Featured Projects</h2>
    <div class="project-grid">
      <div class="project-card">
        <h3>🌐 Personal Portfolio</h3>
        <p>Modern portfolio website built with HTML & CSS and deployed on GitHub Pages.</p>
      </div>
      <div class="project-card">
        <h3>🐳 Dockerized Node.js App</h3>
        <p>Containerized and deployed a basic Node.js app using Docker.</p>
      </div>
      <div class="project-card">
        <h3>☁️ Azure CI/CD Pipeline</h3>
        <p>Configured Azure DevOps pipelines for building and deploying sample apps.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="card container">
    <h2>Get in Touch</h2>
    <p>Email: <a href="mailto:faiz@example.com">faiz@example.com</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/yourname" target="_blank">linkedin.com/in/yourname</a></p>
  </section>

  <footer>
    <div class="container">
      <p>© 2025 Faiz | Built with 💻 + ☁️</p>
    </div>
  </footer>
</body>
</html>

css

/* Google Font */
body {
  font-family: 'Inter', sans-serif;
  margin: 0;
  padding: 0;
  background: #f3f6fa;
  color: #222;
  line-height: 1.6;
}

.container {
  max-width: 1000px;
  margin: auto;
  padding: 20px;
}

header {
  background: linear-gradient(135deg, #4b6cb7, #182848);
  color: white;
  text-align: center;
  padding: 60px 20px;
}

header h1 {
  font-size: 2.8rem;
  margin-bottom: 0.5rem;
}

header .highlight {
  color: #ffce00;
}

.subtitle {
  font-size: 1.2rem;
  opacity: 0.9;
}

nav {
  background: white;
  box-shadow: 0 2px 4px rgba(0,0,0,0.08);
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
  transition: color 0.3s ease;
}

nav a:hover {
  color: #4b6cb7;
}

.card {
  background: white;
  border-radius: 12px;
  padding: 2rem;
  margin-top: 2rem;
  box-shadow: 0 4px 20px rgba(0,0,0,0.05);
}

h2 {
  margin-bottom: 1rem;
  color: #333;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
}

.project-card {
  background: #e9eef6;
  padding: 1.5rem;
  border-radius: 10px;
  transition: all 0.3s ease;
  border-left: 4px solid #4b6cb7;
}

.project-card:hover {
  transform: translateY(-5px);
  background: #dbe4f3;
  box-shadow: 0 8px 20px rgba(0,0,0,0.1);
}

a {
  color: #4b6cb7;
  text-decoration: none;
  font-weight: 600;
}

a:hover {
  text-decoration: underline;
}

footer {
  background: #182848;
  color: white;
  text-align: center;
  padding: 1.5rem 0;
  margin-top: 4rem;
  font-size: 0.9rem;
}

/* Responsive Improvements */
@media (max-width: 600px) {
  header h1 {
    font-size: 2rem;
  }

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
