<!DOCTYPE html> 
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CMULS Web Guy</title>

  <style>
    /* ===== Base Layout ===== */
    body {
      background: url(https://images.hdqwalls.com/wallpapers/lamborghini-aventador-sv-2018-s4.jpg)
        no-repeat center center / cover;
      font-family: 'Inconsolata', monospace;
      margin: 0;
      padding: 40px 20px;
      color: white;

      /* PAGE GRID */
      display: grid;
      grid-template-rows: auto auto 1fr;
      gap: 40px;
    }

    h1 {
      font-size: 3rem;
      margin: 0;
    }

    h3 {
      font-size: 1.5rem;
      margin: 0;
    }

    a {
      color: red;
      text-decoration: none;
    }

    /* ===== Contact Section ===== */
    .contact {
      background: rgba(0, 0, 0, 0.6);
      padding: 25px;
      border-radius: 12px;
      max-width: 600px;
    }

    /* ===== Glass Container ===== */
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 40px;
      background: rgba(255, 255, 255, 0.08);
      border-radius: 15px;
      backdrop-filter: blur(12px);
      box-shadow: 0 8px 30px rgba(0, 0, 0, 0.6);
    }

    /* ===== Projects Grid (CSS GRID) ===== */
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
      margin-top: 30px;
    }

    .project-card {
      background: rgba(255, 255, 255, 0.1);
      padding: 30px;
      border-radius: 12px;
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .project-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 6px 20px rgba(255, 255, 255, 0.15);
    }

    /* ===== Buttons ===== */
    .cta-button {
      display: inline-block;
      background: linear-gradient(135deg, #1db954, #18a345);
      color: #000;
      padding: 12px 28px;
      font-weight: bold;
      border-radius: 10px;
      text-transform: uppercase;
      transition: transform 0.3s ease;
    }

    .cta-button:hover {
      transform: scale(1.08);
    }
    /* ===== About Section (2-Column Grid) ===== */
#about {
  padding: 40px 0;
}

.about-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 40px;
  align-items: center;
}

.about-text p {
  line-height: 1.6;
}

.about-skills ul {
  list-style: none;
  padding: 0;
}

.about-skills li {
  margin-bottom: 10px;
}
/* ===== Footer / Image Credit ===== */
.image-credit {
  text-align: center;
  font-size: 0.9rem;
  margin-top: 40px;
  opacity: 0.8;
}

.image-credit a {
  color: #1db954;
}


  </style>
</head>

<body>

  <!-- Header -->
  <header>
    <h1>👋 Hi, C David here — Web Guy</h1>
    <h3>Welcome to my “How to reach me” page</h3>
  </header>

  <!-- Contact -->
  <section class="contact">
    <h3>📫 How to reach me</h3>
    <p>
      <a href="mailto:mulengachibesa8@gmail.com">
        mulengachibesa8@gmail.com
      </a>
    </p>
  </section>
  <!-- About Section -->
<section id="about">
  <div class="container about-grid">
    
    <div class="about-text">
      <h3>About Me</h3>
      <p>
        I’m C David, a passionate web developer who enjoys building clean,
        modern, and responsive websites. I focus on HTML, CSS, and layout
        systems like Flexbox and CSS Grid to create visually appealing designs.
      </p>
      <p>
        I enjoy experimenting with glassmorphism, animations, and modern UI
        patterns while continuously improving my front-end skills.
      </p>
    </div>

    <div class="about-skills">
      <h3>Skills & Tools</h3>
      <ul>
        <li>✅ HTML5</li>
        <li>✅ CSS3 (Grid & Flexbox)</li>
        <li>✅ Responsive Design</li>
        <li>✅ UI Styling & Layout</li>
      </ul>
    </div>

  </div>
</section>


  <!-- Projects -->
  <section id="projects">
    <div class="container">
      <h3>My Projects</h3>

      <div class="projects-grid">
        <div class="project-card">
          <a href="https://cmuls.github.io/Galaxy-Webers/"
             target="_blank"
             class="cta-button"
             rel="noopener noreferrer">
            Frosted Glass Card
          </a>
        </div>

        <div class="project-card">
          <a href="https://cmuls.github.io/Galaxi-2/"
             target="_blank"
             class="cta-button"
             rel="noopener noreferrer">
            Black Hole Background
          </a>
        </div>

        <div class="project-card">
          <a href="https://cmuls.github.io/Cit-s-Cars/"
             target="_blank"
             class="cta-button"
             rel="noopener noreferrer">
            G-Wagon Page
          </a>
        </div> 
      </div>
    </div>
  </section>
  <footer class="image-credit">
  <p>
    Background image courtesy of
    <a href="https://images.hdqwalls.com/wallpapers/lamborghini-aventador-sv-2018-s4.jpg" target="_blank" rel="noopener noreferrer">
      HDQ Walls
    </a>
  </p>
</footer>

  

</body>
</html>

 
