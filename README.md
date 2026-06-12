<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
}

body {
  background: #0d1117;
  color: #c9d1d9;
}

@keyframes gradient-shift {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

@keyframes fade-in {
  from {
    opacity: 0;
    transform: translateY(10px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes slide-in {
  from {
    opacity: 0;
    transform: translateX(-20px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

.hero {
  background: linear-gradient(135deg, rgba(100, 200, 255, 0.1) 0%, rgba(100, 150, 255, 0.05) 100%);
  border-bottom: 1px solid rgba(100, 200, 255, 0.2);
  padding: 80px 40px;
  text-align: center;
  animation: fade-in 1s ease-out;
}

.hero h1 {
  font-size: 48px;
  font-weight: 700;
  letter-spacing: -1.5px;
  margin-bottom: 12px;
  background: linear-gradient(90deg, #58a6ff 0%, #79c0ff 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  animation: fade-in 0.8s ease-out;
}

.hero p {
  font-size: 18px;
  font-weight: 400;
  letter-spacing: 0.5px;
  color: #8b949e;
  animation: fade-in 1s ease-out 0.2s backwards;
}

.subtitle {
  font-size: 16px;
  color: #8b949e;
  margin-top: 8px;
  font-weight: 300;
  letter-spacing: 0.3px;
}

.container {
  max-width: 1000px;
  margin: 0 auto;
  padding: 60px 40px;
}

.section {
  margin-bottom: 80px;
  animation: fade-in 1.2s ease-out;
}

.section-title {
  font-size: 28px;
  font-weight: 600;
  letter-spacing: -0.5px;
  margin-bottom: 32px;
  padding-bottom: 16px;
  border-bottom: 1px solid rgba(100, 200, 255, 0.2);
  color: #f0f6fc;
}

.subsection {
  margin-bottom: 32px;
}

.subsection-title {
  font-size: 14px;
  font-weight: 600;
  letter-spacing: 0.5px;
  text-transform: uppercase;
  color: #58a6ff;
  margin-bottom: 16px;
}

.tech-list {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 16px;
}

.tech-item {
  padding: 8px 16px;
  background: rgba(58, 166, 255, 0.1);
  border: 1px solid rgba(58, 166, 255, 0.3);
  border-radius: 6px;
  font-size: 14px;
  font-weight: 500;
  color: #79c0ff;
  transition: all 0.3s ease;
  animation: fade-in 0.8s ease-out backwards;
}

.tech-item:nth-child(1) { animation-delay: 0s; }
.tech-item:nth-child(2) { animation-delay: 0.1s; }
.tech-item:nth-child(3) { animation-delay: 0.2s; }
.tech-item:nth-child(4) { animation-delay: 0.3s; }
.tech-item:nth-child(5) { animation-delay: 0.4s; }
.tech-item:nth-child(6) { animation-delay: 0.5s; }

.tech-item:hover {
  background: rgba(58, 166, 255, 0.2);
  border-color: rgba(58, 166, 255, 0.5);
  transform: translateY(-2px);
}

.project-card {
  background: rgba(30, 30, 30, 0.5);
  border: 1px solid rgba(100, 200, 255, 0.15);
  border-radius: 8px;
  padding: 24px;
  margin-bottom: 16px;
  transition: all 0.3s ease;
  animation: fade-in 1s ease-out;
}

.project-card:hover {
  background: rgba(30, 30, 30, 0.8);
  border-color: rgba(100, 200, 255, 0.3);
  transform: translateY(-4px);
}

.project-title {
  font-size: 16px;
  font-weight: 600;
  color: #f0f6fc;
  margin-bottom: 8px;
}

.project-desc {
  font-size: 14px;
  color: #8b949e;
  margin-bottom: 12px;
  line-height: 1.5;
}

.project-link {
  font-size: 14px;
  color: #58a6ff;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s ease;
}

.project-link:hover {
  color: #79c0ff;
  text-decoration: underline;
}

.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 24px;
}

.stat-card {
  background: rgba(30, 30, 30, 0.5);
  border: 1px solid rgba(100, 200, 255, 0.15);
  border-radius: 8px;
  padding: 20px;
  text-align: center;
  animation: fade-in 1s ease-out;
}

.stat-number {
  font-size: 28px;
  font-weight: 700;
  color: #58a6ff;
  margin-bottom: 8px;
}

.stat-label {
  font-size: 13px;
  color: #8b949e;
  font-weight: 500;
  letter-spacing: 0.3px;
}

.link-group {
  display: flex;
  gap: 16px;
  margin-top: 20px;
  flex-wrap: wrap;
}

.link-button {
  padding: 10px 20px;
  background: rgba(58, 166, 255, 0.1);
  border: 1px solid rgba(58, 166, 255, 0.3);
  border-radius: 6px;
  color: #58a6ff;
  text-decoration: none;
  font-size: 14px;
  font-weight: 500;
  transition: all 0.3s ease;
  display: inline-block;
}

.link-button:hover {
  background: rgba(58, 166, 255, 0.2);
  border-color: rgba(58, 166, 255, 0.5);
  transform: translateY(-2px);
}

.divider {
  height: 1px;
  background: linear-gradient(90deg, transparent, rgba(100, 200, 255, 0.2), transparent);
  margin: 60px 0;
}

.footer {
  text-align: center;
  padding: 40px;
  border-top: 1px solid rgba(100, 200, 255, 0.1);
  color: #8b949e;
  font-size: 14px;
  animation: fade-in 1.5s ease-out;
}

.footer p {
  margin: 8px 0;
  font-weight: 300;
  letter-spacing: 0.3px;
}

@media (max-width: 768px) {
  .hero {
    padding: 60px 20px;
  }
  
  .hero h1 {
    font-size: 36px;
  }
  
  .container {
    padding: 40px 20px;
  }
  
  .section-title {
    font-size: 24px;
  }
}

</style>

<div class="hero">
  <h1>Akil</h1>
  <p class="subtitle">Android & Web Developer</p>
  <p>Building modern applications with clean code and modern architecture</p>
</div>

<div class="container">

<div class="section">
  <div class="section-title">About</div>
  <p style="font-size: 15px; line-height: 1.6; color: #c9d1d9;">
I'm a full-stack developer focused on creating modern, high-performance applications. Currently in Grade 12 while actively developing Android and web applications with emphasis on clean architecture, modern design patterns, and user experience.
  </p>
  <p style="font-size: 15px; line-height: 1.6; color: #8b949e; margin-top: 16px;">
My approach combines traditional software engineering principles with modern development practices, using tools like AI for optimization while maintaining focus on code quality and architectural excellence.
  </p>
</div>

<div class="divider"></div>

<div class="section">
  <div class="section-title">Technical Skills</div>
  
  <div class="subsection">
    <div class="subsection-title">Mobile Development</div>
    <div class="tech-list">
      <div class="tech-item">Kotlin</div>
      <div class="tech-item">Android</div>
      <div class="tech-item">Jetpack Compose</div>
      <div class="tech-item">MVVM Architecture</div>
      <div class="tech-item">Room Database</div>
      <div class="tech-item">Firebase</div>
    </div>
  </div>
  
  <div class="subsection">
    <div class="subsection-title">Web Development</div>
    <div class="tech-list">
      <div class="tech-item">React</div>
      <div class="tech-item">JavaScript</div>
      <div class="tech-item">HTML5</div>
      <div class="tech-item">CSS3</div>
      <div class="tech-item">Tailwind CSS</div>
      <div class="tech-item">Responsive Design</div>
    </div>
  </div>
  
  <div class="subsection">
    <div class="subsection-title">Tools & Infrastructure</div>
    <div class="tech-list">
      <div class="tech-item">Git</div>
      <div class="tech-item">GitHub</div>
      <div class="tech-item">VS Code</div>
      <div class="tech-item">Android Studio</div>
      <div class="tech-item">Figma</div>
      <div class="tech-item">CLI Tools</div>
    </div>
  </div>
</div>

<div class="divider"></div>

<div class="section">
  <div class="section-title">Featured Projects</div>
  
  <div class="project-card">
    <div class="project-title">Tamil TV</div>
    <div class="project-desc">
      An IPTV streaming application built with Kotlin and Jetpack Compose. Features modern UI with smooth performance optimization and user-centric design.
    </div>
    <a href="https://github.com/codedbyakil/Tamil-TV" class="project-link">View on GitHub</a>
  </div>
  
  <div class="project-card">
    <div class="project-title">Your Project Name</div>
    <div class="project-desc">
      Web application built with modern technologies. Add your project details here with description and features.
    </div>
    <a href="https://github.com/codedbyakil" class="project-link">View on GitHub</a>
  </div>
</div>

<div class="divider"></div>

<div class="section">
  <div class="section-title">Learning & Development</div>
  
  <div class="subsection">
    <div class="subsection-title">Currently Focused On</div>
    <p style="font-size: 14px; line-height: 1.6; color: #c9d1d9; margin-bottom: 16px;">
      Advanced Jetpack Compose patterns and animations, MVVM and Clean Architecture implementation, React hooks and state management, Performance optimization for mobile and web applications
    </p>
  </div>
  
  <div class="subsection">
    <div class="subsection-title">Next Learning Goals</div>
    <p style="font-size: 14px; line-height: 1.6; color: #8b949e;">
      Backend development fundamentals, System design and architecture, Advanced security practices, DevOps and deployment strategies, Machine learning integration
    </p>
  </div>
</div>

<div class="divider"></div>

<div class="section">
  <div class="section-title">Statistics</div>
  
  <div style="margin-top: 24px;">
    <a href="https://github.com/codedbyakil" style="text-decoration: none;">
      <img src="https://github-readme-stats.vercel.app/api?username=codedbyakil&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&bg_color=0d1117&border_color=30363d&title_color=58a6ff&text_color=8b949e&icon_color=79c0ff&hide_border=true" alt="GitHub Stats" style="width: 100%; max-width: 500px; border-radius: 8px; margin-bottom: 20px;">
    </a>
    
    <a href="https://github.com/codedbyakil" style="text-decoration: none;">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=codedbyakil&layout=compact&theme=tokyonight&bg_color=0d1117&border_color=30363d&title_color=58a6ff&text_color=8b949e&hide_border=true" alt="Top Languages" style="width: 100%; max-width: 500px; border-radius: 8px;">
    </a>
  </div>
</div>

<div class="divider"></div>

<div class="section">
  <div class="section-title">Connect</div>
  
  <p style="font-size: 15px; color: #c9d1d9; margin-bottom: 24px;">
    Get in touch or follow my work across different platforms.
  </p>
  
  <div class="link-group">
    <a href="https://codedbyakil.github.io" class="link-button">Portfolio</a>
    <a href="https://instagram.com/justdeploy" class="link-button">Instagram</a>
    <a href="mailto:akilaskan@gmail.com" class="link-button">Email</a>
    <a href="https://github.com/codedbyakil" class="link-button">GitHub</a>
  </div>
</div>

</div>

<div class="footer">
  <p>Building modern applications with clean code</p>
  <p style="font-size: 13px; margin-top: 12px;">Grade 12 Student | Full-Stack Developer | June 2026</p>
</div>
