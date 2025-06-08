# plskillrida.github.io
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rida Fatima - Cyberpunk Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
      html {
        scroll-behavior: smooth;
      }
      body {
        background: linear-gradient(180deg, #000000 0%, #0a0f0a 100%);
        color: #00ff9c;
        font-family: 'Courier New', Courier, monospace;
        overflow-x: hidden;
      }
      a {
        color: #00ff9c;
        transition: all 0.3s;
        text-decoration: none;
      }
      a:hover {
        text-shadow: 0 0 5px #00ff9c, 0 0 10px #00ff9c;
        transform: scale(1.05);
      }
      .cyber-border {
        border: 1px solid #00ff9c;
        box-shadow: 0 0 10px #00ff9c44, 0 0 20px #00ff9c22;
      }
      .glow-text {
        text-shadow: 0 0 5px #00ff9c, 0 0 10px #00ff9c;
      }
      .matrix-bg {
        position: fixed;
        top: 0;
        left: 0;
        z-index: -1;
        width: 100vw;
        height: 100vh;
        background: black;
        overflow: hidden;
      }
      canvas {
        display: block;
      }
      nav {
        background: rgba(0, 0, 0, 0.85);
        backdrop-filter: blur(6px);
      }
    </style>
  </head>
  <body>
    <div class="matrix-bg">
      <canvas id="matrixCanvas"></canvas>
    </div>

    <nav class="fixed top-0 left-0 w-full shadow z-50">
      <div class="max-w-6xl mx-auto px-4 py-3 flex justify-between items-center">
        <h1 class="text-lg font-bold glow-text">Rida Fatima</h1>
        <div class="space-x-4 text-sm">
          <a href="#home">Home</a>
          <a href="#about">About</a>
          <a href="#skills">Skills</a>
          <a href="#projects">Projects</a>
          <a href="#education">Education</a>
          <a href="#contact">Contact</a>
        </div>
      </div>
    </nav>

    <section id="home" class="h-screen flex flex-col justify-center items-center text-center px-6 pt-24">
      <h1 class="text-5xl font-bold glow-text">Hi, I'm Rida Fatima</h1>
      <p class="mt-4 text-xl glow-text">Aspiring Data Analyst & Game Developer</p>
      <div class="mt-6 space-x-4">
        <a href="https://www.linkedin.com/in/rida-fatima-4b5230330" target="_blank">LinkedIn</a>
        <a href="https://github.com/plskillrida" target="_blank">GitHub</a>
        <a href="https://x.com/cimmerianbat" target="_blank">Twitter</a>
      </div>
      <a href="#projects" class="mt-6 inline-block px-6 py-2 border border-green-500 rounded glow-text">View Projects</a>
    </section>

    <section id="about" class="py-16 px-6 max-w-4xl mx-auto">
      <h2 class="text-3xl font-semibold text-center mb-4 glow-text">About Me</h2>
      <p class="text-center text-lg">I'm a B.E. student in Information Science at Dr. Ambedkar Institute of Technology with a passion for data analysis and game development. I love building meaningful projects and leading community events that empower others through technology.</p>
    </section>

    <section id="skills" class="py-16 px-6">
      <h2 class="text-3xl font-semibold text-center mb-6 glow-text">Skills</h2>
      <div class="grid grid-cols-2 md:grid-cols-3 gap-4 text-center">
        <div class="cyber-border p-2">Python, Lua, Java (Beginner), C (Beginner)</div>
        <div class="cyber-border p-2">MySQL, SQL</div>
        <div class="cyber-border p-2">Roblox Studio, Unity, Unreal Engine 5</div>
        <div class="cyber-border p-2">Pandas, NumPy, Matplotlib, Seaborn</div>
        <div class="cyber-border p-2">Scikit-learn, Jupyter, Colab</div>
        <div class="cyber-border p-2">Canva, Figma, Adobe Illustrator</div>
        <div class="cyber-border p-2">Microsoft Office Suite</div>
        <div class="cyber-border p-2">Languages: English, Hindi, Urdu, Spanish (Beg.), Greek (Beg.), German (Beg.), Kannada (Limited)</div>
      </div>
    </section>

    <section id="projects" class="py-16 px-6 max-w-5xl mx-auto">
      <h2 class="text-3xl font-semibold text-center mb-6 glow-text">Projects</h2>
      <div class="grid md:grid-cols-2 gap-6">
        <div class="cyber-border p-6 rounded">
          <h3 class="text-xl font-bold glow-text">Uncharted Hollow (2025)</h3>
          <p class="mt-2">Horror-adventure Roblox game using Lua. Built immersive cave environment, traps, and monster AI. Objective: retrieve an amulet while avoiding dangers.</p>
        </div>
        <div class="cyber-border p-6 rounded">
          <h3 class="text-xl font-bold glow-text">Indra – Weather App (2023-24)</h3>
          <p class="mt-2">Python backend, Bootstrap UI, MySQL DB. Live data from OpenWeatherAPI and user-friendly historical query system.</p>
        </div>
        <div class="cyber-border p-6 rounded">
          <h3 class="text-xl font-bold glow-text">Valetudo – Health App (2022)</h3>
          <p class="mt-2">Python-based health tracker with diagnostic tools and calculators. A foundational prototype with health feedback system.</p>
        </div>
      </div>
    </section>

    <section id="education" class="py-16 px-6">
      <h2 class="text-3xl font-semibold text-center mb-6 glow-text">Education & Leadership</h2>
      <div class="max-w-4xl mx-auto space-y-6">
        <div class="cyber-border p-4">
          <h3 class="font-bold text-lg glow-text">Dr. Ambedkar Institute of Technology, Bengaluru</h3>
          <p>B.E. in Information Science Engineering (Expected 2028), 1st Sem SGPA: 8.95</p>
        </div>
        <div class="cyber-border p-4">
          <h3 class="font-bold text-lg glow-text">Shishya BEML Public School</h3>
          <p>Grade 11-12 (CBSE), 82.4% | PCMC Stream</p>
        </div>
        <div class="cyber-border p-4">
          <h3 class="font-bold text-lg glow-text">Baldwin Girls’ High School</h3>
          <p>ICSE 96%, LKG–10th Standard</p>
        </div>
        <div class="cyber-border p-4">
          <h3 class="font-bold text-lg glow-text">Leadership & Activities</h3>
          <ul class="list-disc ml-6 mt-2">
            <li>Campus Outreach Officer – 10X Club, Dr. AIT</li>
            <li>GDG On-Campus Volunteer & Bootcamp Quiz Finalist</li>
            <li>Certified: Google GenAI Study Jams 2024</li>
            <li>Poster/reel design for school & college fests</li>
            <li>School dance team, choir, literary club & bulletin board head</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="contact" class="py-16 px-6">
      <h2 class="text-3xl font-semibold text-center mb-6 glow-text">Contact</h2>
      <div class="text-center space-y-3">
        <p>Email: <a href="mailto:rida.fatima6657@gmail.com">rida.fatima6657@gmail.com</a></p>
        <p>Phone: <a href="tel:+919036521510">+91 9036521510</a></p>
        <div class="flex justify-center space-x-6 mt-4">
          <a href="https://www.linkedin.com/in/rida-fatima-4b5230330" target="_blank">LinkedIn</a>
          <a href="https://github.com/plskillrida" target="_blank">GitHub</a>
          <a href="https://x.com/cimmerianbat" target="_blank">Twitter</a>
        </div>
      </div>
    </section>

    <footer class="text-center text-sm py-4 border-t border-green-500 mt-8">
      &copy; 2025 Rida Fatima. All rights reserved.
    </footer>

    <script>
      const canvas = document.getElementById("matrixCanvas");
      const ctx = canvas.getContext("2d");
      canvas.height = window.innerHeight;
      canvas.width = window.innerWidth;
      const letters = "01";
      const fontSize = 14;
      const columns = canvas.width / fontSize;
      const drops = new Array(Math.floor(columns)).fill(1);
      function drawMatrix() {
        ctx.fillStyle = "rgba(0, 0, 0, 0.05)";
        ctx.fillRect(0, 0, canvas.width, canvas.height);
        ctx.fillStyle = "#00ff9c";
        ctx.font = `${fontSize}px Courier New`;
        for (let i = 0; i < drops.length; i++) {
          const text = letters[Math.floor(Math.random() * letters.length)];
          ctx.fillText(text, i * fontSize, drops[i] * fontSize);
          if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
            drops[i] = 0;
          }
          drops[i]++;
        }
      }
      setInterval(drawMatrix, 33);
      window.addEventListener("resize", () => {
        canvas.height = window.innerHeight;
        canvas.width = window.innerWidth;
      });
    </script>
  </body>
</html>
