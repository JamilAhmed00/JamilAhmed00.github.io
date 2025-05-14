<!-- NAVBAR SECTION -->
<nav style="display: flex; justify-content: center; background-color: #f4f4f4; padding: 15px;">
  <a href="#about" style="margin: 0 20px; text-decoration: none; font-size: 18px;">About</a>
  <a href="#projects" style="margin: 0 20px; text-decoration: none; font-size: 18px;">Projects</a>
  <a href="#research" style="margin: 0 20px; text-decoration: none; font-size: 18px;">Research Experience</a>
  <a href="#achievements" style="margin: 0 20px; text-decoration: none; font-size: 18px;">Achievements</a>
  <a href="#problem-solving" style="margin: 0 20px; text-decoration: none; font-size: 18px;">Problem Solving</a>
  <a href="#skills" style="margin: 0 20px; text-decoration: none; font-size: 18px;">Skills</a>
  <a href="#contact" style="margin: 0 20px; text-decoration: none; font-size: 18px;">Contact</a>
</nav>

<!-- DYNAMIC GIF -->
<p align="center">
  <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExOWs3NDNhZ3VrbG9mYmxrZnpqZ2pjeHF6d2ZwZWZtdWkxOGJpdGJlMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/93UOscPyDH8cdRfSaT/giphy.gif" alt="Dynamic GIF" width="600" height="400">
</p>

<!-- HEADER SECTION -->
<div style="display: flex; align-items: center; justify-content: left; margin: 20px;">
  <div>
    <img src="https://i.imgur.com/WoSZQkn.png" alt="Jamil Ahmed" width="220" height="250" style="border-radius: 50%; margin-right: 20px;">
  </div>
  <div>
    <h1 style="margin: 0; padding-left: 20px;">Hi, I’m Jamil Ahmed 👋</h1>
    <h3 style="margin: 0; padding-left: 20px;">🚀 Backend Developer | 💡 AI Enthusiast | 🌍 Problem Solver</h3>
  </div>
</div>

<!-- About Section -->
<div id="about">
<h2>🌟 About Me</h2>
<p>- 🔭 Currently working on building robust backend systems using Python and FastAPI.</p>
<p>- 🌱 Exploring LLM-driven solutions with Azure OpenAI.</p>
<p>- 💻 Passionate about solving real-world problems with clean, maintainable code.</p>
<p>- 🌐 Active in competitive programming and AI-based development.</p>
<p>- 📫 Reach me at: jamilahmediiuc@gmail.com</p>
</div>

<!-- Projects Section -->
<div id="projects">
<h2>💻 Projects</h2>
<p>- 🚀 HandiCraft: A D2C platform connecting artisans with global customers.</p>
<p>- 🌊 HydroScholers: An educational platform visualizing global water issues.</p>
<p>- 📊 Automated Sports Data Scraper: A tool for collecting football match data.</p>
<p>- ✈️ SkillFlight: AI-driven platform for dynamic developer proficiency rating.</p>
</div>

<!-- Research Experience Section -->
<div id="research">
<h2>🔬 Research Experience</h2>
<p>- 🧠 HPE-HRNet: Human Pose Estimation using Parallel Architecture.</p>
<p>- Supervised by: Md. Khaliluzzaman, Assistant Professor, Dept. of CSE, IIUC.</p>
</div>

<!-- Achievements Section -->
<div id="achievements">
<h2>🏆 Achievements</h2>
<p>- 🌍 NASA Space Apps Challenge 2024: National Champion, Global Nominee.</p>
<p>- 💡 Generative AI for Educators - Google: Course completion.</p>
<p>- 🏅 Microsoft Imagine Cup 2025: MVP Submission Round.</p>
<p>- 🏆 BYLC CareerX29 Program Graduate.</p>
</div>

<!-- Problem Solving Section -->
<div id="problem-solving">
<h2>🧠 Problem Solving Profiles</h2>
<p>- CodeForces, LeetCode, VJudge.</p>
</div>

<!-- Skills Section -->
<div id="skills">
<h2>🔧 Skills & Technologies</h2>
<p>- Programming Languages: Python, C++</p>
<p>- Web Frameworks: FastAPI, Django</p>
<p>- AI & ML: Azure OpenAI, LLM</p>
<p>- Databases: PostgreSQL, SQLite, MySQL</p>
<p>- DevOps: Docker, GitHub Actions, SonarQube</p>
<p>- Monitoring: Sentry, Locust</p>
<p>- Version Control: Git, GitHub, GitLab</p>
</div>

<!-- Contact Section -->
<div id="contact">
<h2>🌐 Connect with Me</h2>
<p>Email: jamilahmediiuc@gmail.com</p>
<p>LinkedIn: linkedin.com/in/jamilahmed01</p>
<p>GitHub: github.com/JamilAhmed00</p>
</div>

<script>
// Smooth scroll functionality for navbar links
document.querySelectorAll('nav a').forEach(anchor => {
  anchor.addEventListener('click', function(e) {
    e.preventDefault();
    const target = document.querySelector(this.getAttribute('href'));
    if (target) {
      target.scrollIntoView({ behavior: 'smooth' });
    }
  });
});
</script>
