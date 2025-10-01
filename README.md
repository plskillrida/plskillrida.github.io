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
        /* Adjusted background for better depth */
        background: linear-gradient(180deg, #000000 0%, #050505 100%);
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
        transition: box-shadow 0.3s ease-in-out, transform 0.3s ease-in-out;
      }
      .cyber-border:hover {
        box-shadow: 0 0 15px #00ff9c, 0 0 30px #00ff9c88; /* Stronger glow on hover */
        transform: translateY(-2px);
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
      /* Ensuring the contact links also have that active cyberpunk feel */
      .contact-link:hover {
        text-shadow: 0 0 8px #00ff9c;
      }
      /* Override general link hover for project cards to prevent double hover effects */
      .project-link:hover {
        text-shadow: none;
        transform: none;
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

    <!-- HOME SECTION -->
    <section id="home" class="h-screen flex flex-col justify-center items-center text-center px-6 pt-24">
      <h1 class="text-5xl font-bold glow-text">Hi, I'm Rida Fatima</h1>
      <p class="mt-4 text-xl glow-text">Aspiring Data Analyst & Game Developer</p>
      <div class="mt-6 space-x-4">
        <a href="https://www.linkedin.com/in/rida-fatima-4b5230330" target="_blank">LinkedIn</a>
        <a href="https://github.com/plskillrida" target="_blank">GitHub</a>
        <a href="https://x.com/cimmerianbat" target="_blank">Twitter</a>
      </div>
      <a href="#projects" class="mt-6 inline-block px-6 py-2 border border-green-500 rounded glow-text hover:shadow-lg hover:shadow-[#00ff9c88]">View Projects</a>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about" class="py-16 px-6 max-w-4xl mx-auto">
      <h2 class="text-3xl font-semibold text-center mb-4 glow-text">About Me</h2>
      <p class="text-center text-lg">I'm a B.E. student in Information Science at Dr. Ambedkar Institute of Technology with a passion for data analysis, design and game development. I love building meaningful projects and leading community events that empower others through technology.</p>
    </section>

    <!-- SKILLS SECTION -->
    <section id="skills" class="py-16 px-6">
      <h2 class="text-3xl font-semibold text-center mb-6 glow-text">Skills</h2>
      <div class="grid grid-cols-2 md:grid-cols-3 gap-4 text-center max-w-6xl mx-auto">
        <!-- Programming & Core -->
        <div class="cyber-border p-4 rounded-md">Python, Lua, Java (Beginner), C (Beginner)</div>
        <!-- Data & BI Tools -->
        <div class="cyber-border p-4 rounded-md">MySQL, SQL, Power BI, Tableau</div>
        <!-- Game Development -->
        <div class="cyber-border p-4 rounded-md">Roblox Studio, Unity, Unreal Engine 5</div>
        <!-- Data Science Libraries -->
        <div class="cyber-border p-4 rounded-md">Pandas, NumPy, Matplotlib, Seaborn</div>
        <!-- Web Development & Analytics -->
        <div class="cyber-border p-4 rounded-md">CSS, JavaScript, Scikit-learn, Jupyter, Colab</div>
        <!-- Design & Marketing -->
        <div class="cyber-border p-4 rounded-md">Canva, Figma, Adobe Illustrator, Digital Marketing, Social Media Management</div>
        <!-- Office & General -->
        <div class="cyber-border p-4 rounded-md">Microsoft Office Suite</div>
        <!-- Languages -->
        <div class="cyber-border p-4 rounded-md col-span-2 md:col-span-1">Languages: English, Hindi, Urdu, Spanish (Beg.), Greek (Beg.), German (Beg.), Kannada (Limited)</div>
      </div>
    </section>

    <!-- PROJECTS SECTION -->
    <section id="projects" class="py-16 px-6 max-w-5xl mx-auto">
      <h2 class="text-3xl font-semibold text-center mb-6 glow-text">Projects</h2>
      <div class="grid md:grid-cols-2 gap-6">
        
        <!-- InstaCheck (LINKED) -->
        <div class="cyber-border project-link p-6 rounded-lg">
          <a href="https://plskillrida.github.io/InstaCheck/" target="_blank" class="block h-full">
            <h3 class="text-xl font-bold glow-text">InstaCheck – Instagram Data Analytics App (2025)</h3>
            <p class="mt-2">A web app for Instagram data analytics, built using JavaScript, Tailwind CSS, and Python to provide insights into user engagement and trends.</p>
          </a>
        </div>
        
        <!-- Uncharted Hollow (LINKED) -->
        <div class="cyber-border project-link p-6 rounded-lg">
          <a href="https://www.roblox.com/games/137386204168748/Uncharted-Hollow" target="_blank" class="block h-full">
            <h3 class="text-xl font-bold glow-text">Uncharted Hollow (2025)</h3>
            <p class="mt-2">Horror-adventure Roblox game using Lua. Built immersive cave environment, traps, and monster AI. Objective: retrieve an amulet while avoiding dangers.</p>
          </a>
        </div>
        
        <!-- Indra (UNLINKED) -->
        <div class="cyber-border p-6 rounded-lg">
          <h3 class="text-xl font-bold glow-text">Indra – Weather App (2023-24)</h3>
          <p class="mt-2">Python backend, Bootstrap UI, MySQL DB. Live data from OpenWeatherAPI and user-friendly historical query system.</p>
        </div>
        
        <!-- Valetudo (UNLINKED) -->
        <div class="cyber-border p-6 rounded-lg">
          <h3 class="text-xl font-bold glow-text">Valetudo – Health App (2022)</h3>
          <p class="mt-2">Python-based health tracker with diagnostic tools and calculators. A foundational prototype with health feedback system.</p>
        </div>
      </div>
    </section>

    <!-- EDUCATION SECTION -->
    <section id="education" class="py-16 px-6">
      <h2 class="text-3xl font-semibold text-center mb-6 glow-text">Education & Leadership</h2>
      <div class="max-w-4xl mx-auto space-y-6">
        <div class="cyber-border p-4 rounded-lg">
          <h3 class="font-bold text-lg glow-text">Dr. Ambedkar Institute of Technology, Bengaluru</h3>
          <p>B.E. in Information Science Engineering (Expected 2028)</p>
        </div>
        <div class="cyber-border p-4 rounded-lg">
          <h3 class="font-bold text-lg glow-text">Shishya BEML Public School</h3>
          <p>Grade 11-12 (CBSE) | PCMC Stream</p>
        </div>
        <div class="cyber-border p-4 rounded-lg">
          <h3 class="font-bold text-lg glow-text">Baldwin Girls’ High School</h3>
          <p>ICSE, LKG–10th Standard</p>
        </div>
        <div class="cyber-border p-4 rounded-lg">
          <h3 class="font-bold text-lg glow-text">Leadership & Activities</h3>
          <ul class="list-disc ml-6 mt-2">
            <li>Campus Outreach Officer – 10X Club, Dr. AIT</li>
            <li>GDG On-Campus Volunteer & Bootcamp Quiz Finalist</li>
            <li>Certified: Google GenAI Study Jams 2024</li>
            <li>Social Media Content Creation</li>
            <li>Digital Marketing through Instagram</li>
            <li>Poster/reel design for school & college fests</li>
            <li>School dance team, choir, literary club & bulletin board head</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- CONTACT SECTION -->
    <section id="contact" class="py-16 px-6">
      <h2 class="text-3xl font-semibold text-center mb-6 glow-text">Contact</h2>
      <div class="text-center space-y-3">
        <p>Email: <a href="mailto:rida.fatima6657@gmail.com" class="contact-link">rida.fatima6657@gmail.com</a></p>
        <p>Phone: <a href="tel:+919036521510" class="contact-link">+91 9036521510</a></p>
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

    <!-- MATRIX RAIN JAVASCRIPT -->
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
        // Subtle fade effect
        ctx.fillStyle = "rgba(0, 0, 0, 0.05)";
        ctx.fillRect(0, 0, canvas.width, canvas.height);
        
        ctx.fillStyle = "#00ff9c"; // Green characters
        ctx.font = `${fontSize}px Courier New`;
        
        for (let i = 0; i < drops.length; i++) {
          const text = letters[Math.floor(Math.random() * letters.length)];
          // Draw the character
          ctx.fillText(text, i * fontSize, drops[i] * fontSize);
          
          // Reset drop if it hits the bottom with a 2.5% chance
          if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
            drops[i] = 0;
          }
          
          // Move the drop down
          drops[i]++;
        }
      }
      
      // Run the animation
      setInterval(drawMatrix, 33); // 30 FPS
      
      // Handle resize events
      window.addEventListener("resize", () => {
        canvas.height = window.innerHeight;
        canvas.width = window.innerWidth;
        // Recalculate columns for the new width
        columns = canvas.width / fontSize;
        drops.length = Math.floor(columns);
        drops.fill(1);
      });
    </script>
  </body>
</html>

