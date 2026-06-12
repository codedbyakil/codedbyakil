<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Animated Fluid Background */
@keyframes gradientShift {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}

@keyframes float {
  0%, 100% {
    transform: translateY(0px) translateX(0px);
  }
  25% {
    transform: translateY(-20px) translateX(10px);
  }
  50% {
    transform: translateY(-40px) translateX(-10px);
  }
  75% {
    transform: translateY(-20px) translateX(10px);
  }
}

@keyframes blur-in {
  0% {
    filter: blur(10px);
    opacity: 0;
  }
  100% {
    filter: blur(0px);
    opacity: 1;
  }
}

@keyframes glow {
  0%, 100% {
    text-shadow: 0 0 10px rgba(0, 217, 255, 0.5);
  }
  50% {
    text-shadow: 0 0 30px rgba(0, 217, 255, 1), 0 0 60px rgba(100, 200, 255, 0.8);
  }
}

@keyframes shimmer {
  0% {
    background-position: -1000px 0;
  }
  100% {
    background-position: 1000px 0;
  }
}

/* Glassmorphism Container */
.glass-container {
  background: rgba(255, 255, 255, 0.05);
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 20px;
  padding: 30px;
  margin: 20px auto;
  max-width: 900px;
  animation: float 6s ease-in-out infinite;
}

/* Text Animation */
.animated-text {
  background: linear-gradient(90deg, #00D9FF, #FF6B9D, #00D9FF, #FF6B9D);
  background-size: 300% 100%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  animation: gradientShift 8s ease infinite, glow 3s ease-in-out infinite;
  font-weight: 700;
}

/* Fluid Animated Background */
.fluid-bg {
  background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
  background-size: 400% 400%;
  animation: gradientShift 15s ease infinite;
  border-radius: 15px;
  padding: 2px;
  position: relative;
  overflow: hidden;
}

.fluid-bg-content {
  background: #0d1117;
  border-radius: 13px;
  padding: 25px;
  position: relative;
  z-index: 1;
}

/* Blur Effect */
.blur-text {
  animation: blur-in 1s ease-out forwards;
}

/* Shimmer Effect */
.shimmer-effect {
  background: linear-gradient(90deg, rgba(255,255,255,0) 0%, rgba(255,255,255,0.3) 50%, rgba(255,255,255,0) 100%);
  background-size: 1000px 100%;
  animation: shimmer 3s infinite;
}

/* Section Headers */
.section-header {
  display: inline-block;
  padding: 10px 20px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 50px;
  color: white;
  font-weight: 600;
  animation: blur-in 0.8s ease-out;
  margin: 20px 0;
}

/* Animated Border */
.animated-border {
  position: relative;
  overflow: hidden;
  border-radius: 10px;
  padding: 20px;
  margin: 15px 0;
}

.animated-border::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(0, 217, 255, 0.5), transparent);
  animation: shimmer 2s infinite;
}

.animated-border > * {
  position: relative;
  z-index: 1;
}

</style>

<div align="center">

<!-- Animated Fluid Background Header -->
<div class="fluid-bg" style="margin-bottom: 30px;">
  <div class="fluid-bg-content">
    <h1 class="animated-text" style="font-size: 3em; margin-bottom: 10px;">👋 Hey, I'm Akil</h1>
    <h2 class="animated-text" style="font-size: 2em; margin: 10px 0;">codedbyakil</h2>
  </div>
</div>

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=500&color=00D9FF&center=true&vCenter=true&width=900&height=60&lines=🚀+Android+%26+Web+Developer;Building+Modern+Apps+with+AI;Grade+12+%7C+Full-Stack+Enthusiast;Clean+Code+%7C+Modern+UI;Let's+Build+Something+Amazing!)

</div>

---

<div class="glass-container">
  <div align="center">
    <img src="https://media.giphy.com/media/SWoRKslHVtqjewMwod/giphy.gif" width="350" alt="coding animation" style="border-radius: 15px; box-shadow: 0 20px 60px rgba(0, 217, 255, 0.3);">
  </div>
</div>

---

<!-- Animated Section: About Me -->
<div class="fluid-bg" style="margin: 30px 0;">
  <div class="fluid-bg-content">
    <div class="section-header">💡 About Me</div>
    
<div style="margin-top: 20px; line-height: 1.8; color: #c9d1d9;">

```kotlin
✨ class Developer {
    🎯 val name = "Akil"
    🌍 val location = "Tamil Nadu, India"
    📱 val specialization = "Android & Web Development"
    🎨 val passion = "Creating Beautiful, Modern Experiences"
    
    💼 fun currentFocus() {
        return listOf(
            "Jetpack Compose 🎬",
            "MVVM Architecture 🏗️",
            "Material Design 3 🎨",
            "React Modern Patterns ⚛️"
        )
    }
    
    🤖 fun myAIPhilosophy() {
        // AI optimizes my workflow
        // I focus on Architecture & Design
        return "AI is my co-pilot, not replacement"
    }
}
```

</div>

**What I Do:**
- 📱 **Android Development** → Kotlin, Jetpack Compose, MVVM, Clean Architecture
- 🌐 **Web Development** → React, JavaScript, Modern CSS, Responsive Design
- 🎨 **UI/UX Design** → Material Design 3, Animations, User Experience
- 🤖 **AI Integration** → Code generation, optimization, learning acceleration
- 📚 **Continuous Learning** → Design patterns, best practices, new technologies

  </div>
</div>

---

<!-- Tech Stack with Animated Section -->
<div class="fluid-bg" style="margin: 30px 0;">
  <div class="fluid-bg-content">
    <div class="section-header">🔥 Tech Stack</div>

<div align="center" style="margin-top: 25px;">

### 📱 Mobile Development
<div style="margin: 15px 0; animation: blur-in 0.8s ease-out;">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white&labelColor=1F1F1F" alt="Kotlin" style="margin: 5px;">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white&labelColor=1F1F1F" alt="Android" style="margin: 5px;">
  <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=android&logoColor=white&labelColor=1F1F1F" alt="Compose" style="margin: 5px;">
  <img src="https://img.shields.io/badge/Room%20DB-00A86B?style=for-the-badge&logo=sqlite&logoColor=white&labelColor=1F1F1F" alt="Room" style="margin: 5px;">
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black&labelColor=1F1F1F" alt="Firebase" style="margin: 5px;">
  <img src="https://img.shields.io/badge/Coroutines-FF6B6B?style=for-the-badge&logo=kotlin&logoColor=white&labelColor=1F1F1F" alt="Coroutines" style="margin: 5px;">
</div>

### 💻 Web Development
<div style="margin: 15px 0; animation: blur-in 0.9s ease-out;">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black&labelColor=1F1F1F" alt="React" style="margin: 5px;">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=1F1F1F" alt="JavaScript" style="margin: 5px;">
  <img src="https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white&labelColor=1F1F1F" alt="HTML5" style="margin: 5px;">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&labelColor=1F1F1F" alt="CSS3" style="margin: 5px;">
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white&labelColor=1F1F1F" alt="Tailwind" style="margin: 5px;">
</div>

### 🛠️ Tools & Platforms
<div style="margin: 15px 0; animation: blur-in 1s ease-out;">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=1F1F1F" alt="Git" style="margin: 5px;">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=1F1F1F" alt="GitHub" style="margin: 5px;">
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=1F1F1F" alt="VS Code" style="margin: 5px;">
  <img src="https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android&logoColor=white&labelColor=1F1F1F" alt="Android Studio" style="margin: 5px;">
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white&labelColor=1F1F1F" alt="Figma" style="margin: 5px;">
</div>

</div>

  </div>
</div>

---

<!-- Featured Projects Section -->
<div class="fluid-bg" style="margin: 30px 0;">
  <div class="fluid-bg-content">
    <div class="section-header">🎯 Featured Projects</div>

<div style="margin-top: 20px;">

| 📺 Project | 🛠️ Tech | 📝 Description | 🔗 Link |
|-----------|--------|-------------|--------|
| **Tamil TV** | Kotlin, Android | IPTV streaming app with modern UI | [View →](https://github.com/codedbyakil/Tamil-TV) |
| **Your Project** | React, JS | Web application | [View →](https://github.com/codedbyakil) |

</div>

  </div>
</div>

---

<!-- GitHub Stats Section -->
<div class="glass-container" style="margin: 40px auto;">
  <div class="section-header">📊 GitHub Statistics</div>
  
<div align="center" style="margin-top: 25px;">

<a href="https://github.com/codedbyakil">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=codedbyakil&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&bg_color=0d1117&border_color=30363d&title_color=58a6ff&text_color=8b949e&icon_color=79c0ff&border_radius=15" style="border-radius: 15px; box-shadow: 0 20px 60px rgba(0, 217, 255, 0.2);" />
</a>

<a href="https://github.com/codedbyakil">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=codedbyakil&layout=compact&theme=tokyonight&bg_color=0d1117&border_color=30363d&title_color=58a6ff&text_color=8b949e&border_radius=15" style="border-radius: 15px; box-shadow: 0 20px 60px rgba(0, 217, 255, 0.2);" />
</a>

</div>

<a href="https://github.com/codedbyakil">
  <img width="100%" src="https://github-readme-streak-stats.herokuapp.com/?user=codedbyakil&theme=tokyonight&background=0d1117&border=30363d&ring=58a6ff&fire=ff7b54&currStreakNum=8b949e&currStreakLabel=58a6ff&sideNums=8b949e&sideLabels=58a6ff&dates=8b949e&hide_border=true" style="border-radius: 15px; margin-top: 20px; box-shadow: 0 20px 60px rgba(0, 217, 255, 0.2);" />
</a>

</div>

---

<!-- Learning Journey -->
<div class="fluid-bg" style="margin: 30px 0;">
  <div class="fluid-bg-content">
    <div class="section-header">🚀 Learning Journey</div>

<div style="margin-top: 20px; color: #c9d1d9;">

**Currently Mastering** 📖
- ✅ Jetpack Compose & Modern Android UI
- ✅ MVVM & Clean Architecture
- ✅ React Hooks & State Management
- 🔄 Advanced Coroutines & Flow
- 🔄 Testing & Quality Assurance

**Next Frontier** 🎯
- 🎯 Backend Development
- 🎯 System Design Patterns
- 🎯 Performance Optimization
- 🎯 Advanced Security
- 🎯 DevOps & Deployment

</div>

  </div>
</div>

---

<!-- Contact Section -->
<div class="fluid-bg" style="margin: 30px 0;">
  <div class="fluid-bg-content">
    <div class="section-header" align="center">🌐 Let's Connect</div>

<div align="center" style="margin-top: 25px; display: flex; justify-content: center; gap: 15px; flex-wrap: wrap;">

<a href="https://codedbyakil.github.io">
  <img src="https://img.shields.io/badge/Portfolio-FF6B6B?style=for-the-badge&logo=About.me&logoColor=white&labelColor=1F1F1F" alt="Portfolio">
</a>

<a href="https://instagram.com/justdeploy">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=1F1F1F" alt="Instagram">
</a>

<a href="mailto:akilaskan@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1F1F1F" alt="Email">
</a>

<a href="https://github.com/codedbyakil">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=1F1F1F" alt="GitHub">
</a>

</div>

  </div>
</div>

---

<!-- Footer -->
<div class="glass-container" align="center" style="margin: 40px auto; border: 2px solid rgba(0, 217, 255, 0.3);">
  <img src="https://media.giphy.com/media/QTfX9Ejfra3ZmadRrr/giphy.gif" width="180" alt="celebrating" style="border-radius: 10px;">
  
  <h2 class="animated-text" style="margin-top: 20px; font-size: 1.5em;">Thanks for Visiting! 🌟</h2>
  
  <p style="color: #8b949e; margin-top: 15px; font-size: 0.95em;">
    Making the web & mobile world better, one commit at a time<br>
    <strong>Built with ❤️ by Akil | Grade 12 Developer | 2026</strong>
  </p>
  
  <div style="margin-top: 20px;">
    <img src="https://komarev.com/ghpvc/?username=codedbyakil&color=0D9FFF&style=flat-square&label=Profile+Views" alt="Profile Views">
  </div>
</div>

---

<div align="center" style="margin-top: 30px; color: #58a6ff; font-size: 0.9em;">

⭐ If you like my work, please consider **starring** my repositories!

</div>
