<svg width="100%" height="400" viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes gradientShift {
        0% { stop-color: #3a8fff; }
        50% { stop-color: #79c0ff; }
        100% { stop-color: #3a8fff; }
      }
      @keyframes blur-glow {
        0%, 100% { opacity: 0.3; }
        50% { opacity: 0.7; }
      }
      .glow-text { animation: blur-glow 3s ease-in-out infinite; }
      .title-text { font-size: 56px; font-weight: 700; fill: url(#grad); letter-spacing: -2px; }
      .subtitle-text { font-size: 18px; fill: #8b949e; font-weight: 300; letter-spacing: 1px; }
    </style>
    <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3a8fff;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#79c0ff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#3a8fff;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="bg-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#010409;stop-opacity:1" />
    </linearGradient>
    <filter id="blur-effect">
      <feGaussianBlur in="SourceGraphic" stdDeviation="0.5" />
    </filter>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Animated Background -->
  <rect width="1200" height="400" fill="url(#bg-grad)"/>
  
  <!-- Animated Gradient Circles (Glass effect) -->
  <circle cx="200" cy="100" r="150" fill="none" stroke="#3a8fff" stroke-width="2" opacity="0.2" filter="url(#glow)">
    <animate attributeName="r" from="100" to="200" dur="4s" repeatCount="indefinite" />
    <animate attributeName="opacity" from="0.3" to="0.1" dur="4s" repeatCount="indefinite" />
  </circle>
  
  <circle cx="1000" cy="300" r="150" fill="none" stroke="#79c0ff" stroke-width="2" opacity="0.2" filter="url(#glow)">
    <animate attributeName="r" from="100" to="200" dur="5s" repeatCount="indefinite" />
    <animate attributeName="opacity" from="0.3" to="0.1" dur="5s" repeatCount="indefinite" />
  </circle>
  
  <!-- Animated Glass Container Background -->
  <rect x="150" y="80" width="900" height="240" rx="20" fill="rgba(30,30,30,0.3)" stroke="rgba(58,166,255,0.3)" stroke-width="1" opacity="0.6" filter="url(#blur-effect)">
    <animate attributeName="opacity" from="0.4" to="0.7" dur="3s" repeatCount="indefinite" />
  </rect>
  
  <!-- Main Text -->
  <text x="600" y="160" text-anchor="middle" class="title-text">Akil</text>
  <text x="600" y="200" text-anchor="middle" class="subtitle-text">Android & Web Developer</text>
  <text x="600" y="240" text-anchor="middle" class="subtitle-text" style="font-size: 14px;">Modern Applications • Clean Code • Professional Architecture</text>
  
  <!-- Animated Line -->
  <line x1="300" y1="280" x2="900" y2="280" stroke="url(#grad)" stroke-width="2" opacity="0.5">
    <animate attributeName="opacity" from="0.3" to="0.7" dur="2s" repeatCount="indefinite" />
  </line>
</svg>

---

## About

I'm a full-stack developer focused on creating modern, high-performance applications. Currently in Grade 12 while actively developing Android and web applications with emphasis on clean architecture, modern design patterns, and user experience.

My approach combines traditional software engineering principles with modern development practices, using tools like AI for optimization while maintaining focus on code quality and architectural excellence.

---

<svg width="100%" height="60" viewBox="0 0 1200 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="section-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgba(58,166,255,0);stop-opacity:1" />
      <stop offset="50%" style="stop-color:rgba(58,166,255,0.4);stop-opacity:1" />
      <stop offset="100%" style="stop-color:rgba(58,166,255,0);stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect x="0" y="25" width="1200" height="1" fill="url(#section-grad)"/>
</svg>

## Technical Skills

### Mobile Development

<svg width="100%" height="50" viewBox="0 0 600 50" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="tech-blur">
      <feGaussianBlur in="SourceGraphic" stdDeviation="1" />
    </filter>
  </defs>
  <g id="tech-items">
    <rect x="10" y="10" width="80" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2s" repeatCount="indefinite" />
    </rect>
    <text x="50" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">Kotlin</text>
    
    <rect x="100" y="10" width="80" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.2s" repeatCount="indefinite" />
    </rect>
    <text x="140" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">Android</text>
    
    <rect x="190" y="10" width="120" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.4s" repeatCount="indefinite" />
    </rect>
    <text x="250" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">Jetpack Compose</text>
    
    <rect x="320" y="10" width="100" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.6s" repeatCount="indefinite" />
    </rect>
    <text x="370" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">MVVM Arch</text>
    
    <rect x="430" y="10" width="80" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.8s" repeatCount="indefinite" />
    </rect>
    <text x="470" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">Firebase</text>
  </g>
</svg>

### Web Development

<svg width="100%" height="50" viewBox="0 0 600 50" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="tech-blur2">
      <feGaussianBlur in="SourceGraphic" stdDeviation="1" />
    </filter>
  </defs>
  <g id="tech-items2">
    <rect x="10" y="10" width="80" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur2)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2s" repeatCount="indefinite" />
    </rect>
    <text x="50" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">React</text>
    
    <rect x="100" y="10" width="100" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur2)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.2s" repeatCount="indefinite" />
    </rect>
    <text x="150" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">JavaScript</text>
    
    <rect x="210" y="10" width="80" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur2)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.4s" repeatCount="indefinite" />
    </rect>
    <text x="250" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">HTML5</text>
    
    <rect x="300" y="10" width="80" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur2)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.6s" repeatCount="indefinite" />
    </rect>
    <text x="340" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">CSS3</text>
    
    <rect x="390" y="10" width="120" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur2)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.8s" repeatCount="indefinite" />
    </rect>
    <text x="450" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">Tailwind CSS</text>
  </g>
</svg>

### Tools & Infrastructure

<svg width="100%" height="50" viewBox="0 0 600 50" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="tech-blur3">
      <feGaussianBlur in="SourceGraphic" stdDeviation="1" />
    </filter>
  </defs>
  <g id="tech-items3">
    <rect x="10" y="10" width="80" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur3)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2s" repeatCount="indefinite" />
    </rect>
    <text x="50" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">Git</text>
    
    <rect x="100" y="10" width="80" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur3)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.2s" repeatCount="indefinite" />
    </rect>
    <text x="140" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">GitHub</text>
    
    <rect x="190" y="10" width="80" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur3)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.4s" repeatCount="indefinite" />
    </rect>
    <text x="230" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">VS Code</text>
    
    <rect x="280" y="10" width="120" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur3)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.6s" repeatCount="indefinite" />
    </rect>
    <text x="340" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">Android Studio</text>
    
    <rect x="410" y="10" width="80" height="30" rx="6" fill="rgba(58,166,255,0.15)" stroke="rgba(58,166,255,0.4)" stroke-width="1" filter="url(#tech-blur3)">
      <animate attributeName="fill" from="rgba(58,166,255,0.15)" to="rgba(58,166,255,0.25)" dur="2.8s" repeatCount="indefinite" />
    </rect>
    <text x="450" y="30" text-anchor="middle" font-size="12" font-weight="600" fill="#79c0ff">Figma</text>
  </g>
</svg>

---

<svg width="100%" height="60" viewBox="0 0 1200 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="section-grad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgba(58,166,255,0);stop-opacity:1" />
      <stop offset="50%" style="stop-color:rgba(58,166,255,0.4);stop-opacity:1" />
      <stop offset="100%" style="stop-color:rgba(58,166,255,0);stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect x="0" y="25" width="1200" height="1" fill="url(#section-grad2)"/>
</svg>

## Featured Projects

### Tamil TV
**Android Application** | Kotlin, Jetpack Compose

An IPTV streaming application built with Kotlin and Jetpack Compose. Features modern UI with smooth performance optimization and user-centric design.

[View on GitHub](https://github.com/codedbyakil/Tamil-TV)

### Your Project Name
**Web Application** | React, JavaScript

Web application built with modern technologies. Add your project details here with description and features.

[View on GitHub](https://github.com/codedbyakil)

---

<svg width="100%" height="60" viewBox="0 0 1200 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="section-grad3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgba(58,166,255,0);stop-opacity:1" />
      <stop offset="50%" style="stop-color:rgba(58,166,255,0.4);stop-opacity:1" />
      <stop offset="100%" style="stop-color:rgba(58,166,255,0);stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect x="0" y="25" width="1200" height="1" fill="url(#section-grad3)"/>
</svg>

## Learning & Development

**Currently Focused On**

Advanced Jetpack Compose patterns and animations, MVVM and Clean Architecture implementation, React hooks and state management, Performance optimization for mobile and web applications

**Next Learning Goals**

Backend development fundamentals, System design and architecture, Advanced security practices, DevOps and deployment strategies, Machine learning integration

---

<svg width="100%" height="60" viewBox="0 0 1200 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="section-grad4" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgba(58,166,255,0);stop-opacity:1" />
      <stop offset="50%" style="stop-color:rgba(58,166,255,0.4);stop-opacity:1" />
      <stop offset="100%" style="stop-color:rgba(58,166,255,0);stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect x="0" y="25" width="1200" height="1" fill="url(#section-grad4)"/>
</svg>

## Statistics

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=codedbyakil&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&bg_color=0d1117&border_color=30363d&title_color=58a6ff&text_color=8b949e&icon_color=79c0ff&hide_border=true)](https://github.com/codedbyakil)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=codedbyakil&layout=compact&theme=tokyonight&bg_color=0d1117&border_color=30363d&title_color=58a6ff&text_color=8b949e&hide_border=true)](https://github.com/codedbyakil)

---

<svg width="100%" height="60" viewBox="0 0 1200 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="section-grad5" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgba(58,166,255,0);stop-opacity:1" />
      <stop offset="50%" style="stop-color:rgba(58,166,255,0.4);stop-opacity:1" />
      <stop offset="100%" style="stop-color:rgba(58,166,255,0);stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect x="0" y="25" width="1200" height="1" fill="url(#section-grad5)"/>
</svg>

## Connect

[Portfolio](https://codedbyakil.github.io) | [Instagram](https://instagram.com/justdeploy) | [Email](mailto:akilaskan@gmail.com) | [GitHub](https://github.com/codedbyakil)

---

Building modern applications with clean code  
Grade 12 Student | Full-Stack Developer | 2026
