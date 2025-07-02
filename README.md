# Ww
html 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Hi, I'm Faiz</h1>
    <p>DevOps Learner | Freelancer | Tech Enthusiast</p>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>I am learning DevOps and exploring cloud & automation tools.</p>
  </section>

  <section class="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>Project 1:</strong> Static Website with GitHub Pages</li>
      <li><strong>Project 2:</strong> Dockerized Node.js App (in progress)</li>
    </ul>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Email: faiz@example.com</p>
    <p>LinkedIn: linkedin.com/in/yourname</p>
  </section>

  <footer>
    <p>© 2025 Faiz</p>
  </footer>
</body>
</html>

css

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f4f4f4;
  color: #333;
}

header {
  background: #007bff;
  color: white;
  padding: 2rem;
  text-align: center;
}

section {
  padding: 2rem;
  margin: 1rem;
  background: white;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

footer {
  text-align: center;
  padding: 1rem;
  background: #222;
  color: white;
  position: fixed;
  bottom: 0;
  width: 100%;
}

git

git init
git remote add origin https://github.com/yourusername/my-portfolio.git
git add .
git commit -m "Initial portfolio"
git push -u origin master
