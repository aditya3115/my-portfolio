<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Aditya's Portfolio</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="style2.css" />
  </head>
  <body>
    <header>
      <img src="aadi.jpeg" alt="error" width="200px" />
      <h1>Aaditya Dhiman</h1>

      <p>Web Developer & Front-End Enthusiast</p>
      <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section id="about">
      <h2>About Me</h2>
      <div class="card">
        <p>
          Hi! I'm Aditya, a passionate web developer who loves building clean
          and user-friendly websites. I'm always learning and improving.
        </p>
      </div>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <div class="skills">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">React</div>
        <div class="skill">Git</div>
      </div>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="projects">
        <div class="project-card">
          <h3>Portfolio Website</h3>
          <p>
            A personal portfolio website built using HTML, CSS, and JavaScript.
          </p>
        </div>
        <div class="project-card">
          <h3>Currently Working on</h3>

          <p>Thinking</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <div class="card">
        <p>Email: adityaachalachh143@gmail.com</p>
        <p>LinkedIn: linkedin.com/in/aditya</p>
        <p>GitHub: github.com/aditya3115</p>
      </div>
    </section>

    <footer>
      <p>&copy; 2025 Aditya. All rights reserved.</p>
    </footer>
  </body>
</html>


body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #f8f9fa;
    color: #343a40;
  }
  
  header {
    text-align: center;
    padding: 4rem 1rem;
    background-color: #ffffff;
  }
  header img{
    border-radius: 50%;
    position: relative;
    z-index: 8;
    box-shadow: inset;
  }
  
  h1 {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
  }
  
  header p {
    font-size: 1.2rem;
    color: #6c757d;
  }
  
  nav a {
    margin: 0 10px;
    text-decoration: none;
    color: #007bff;
    font-weight: 500;
  }
  
  section {
    padding: 3rem 1rem;
    max-width: 1000px;
    margin: auto;
  }
  
  h2 {
    font-size: 2rem;
    margin-bottom: 1.5rem;
  }
  
  .card {
    background-color: #ffffff;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    padding: 1.5rem;
    margin-bottom: 2rem;
  }
  
  .skills {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
  }
  
  .skill {
    background-color: #e9ecef;
    padding: 0.5rem 1rem;
    border-radius: 20px;
    font-size: 0.9rem;
  }
  
  .projects {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
  }
  
  .project-card {
    background: #ffffff;
    padding: 1rem;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
  }
  
  footer {
    text-align: center;
    padding: 2rem 1rem;
    background-color: #ffffff;
    color: #6c757d;
    font-size: 0.9rem;
  }
  
