<!-- ==================== MODERN DEVELOPER TERMINAL BANNER ==================== -->
<p align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 280" width="100%" height="280">
    <defs>
      <!-- Background Gradients -->
      <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#090d16" />
        <stop offset="50%" stop-color="#0f172a" />
        <stop offset="100%" stop-color="#050811" />
      </linearGradient>

      <!-- Text Glow & Gradient -->
      <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#38bdf8" />
        <stop offset="50%" stop-color="#818cf8" />
        <stop offset="100%" stop-color="#c084fc" />
      </linearGradient>

      <linearGradient id="borderGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#38bdf8" stop-opacity="0.8" />
        <stop offset="50%" stop-color="#c084fc" stop-opacity="0.2" />
        <stop offset="100%" stop-color="#38bdf8" stop-opacity="0.8" />
      </linearGradient>

      <!-- Glow Effect Filter -->
      <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="10" result="blur" />
        <feMerge>
          <feMergeNode in="blur" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>

      <!-- Embedded CSS Animations -->
      <style>
        @keyframes pulseGlow {
          0% { filter: drop-shadow(0 0 15px rgba(56, 189, 248, 0.4)); }
          50% { filter: drop-shadow(0 0 25px rgba(192, 132, 252, 0.7)); }
          100% { filter: drop-shadow(0 0 15px rgba(56, 189, 248, 0.4)); }
        }
        @keyframes cursorBlink {
          0%, 100% { opacity: 1; }
          50% { opacity: 0; }
        }
        @keyframes scanline {
          0% { transform: translateY(-100%); }
          100% { transform: translateY(100%); }
        }
        .main-title {
          font-family: 'Fira Code', 'JetBrains Mono', Consolas, monospace;
          font-weight: 800;
          font-size: 52px;
          fill: url(#textGrad);
          animation: pulseGlow 4s infinite ease-in-out;
        }
        .code-text {
          font-family: 'Fira Code', 'JetBrains Mono', Consolas, monospace;
          font-size: 16px;
          fill: #94a3b8;
        }
        .keyword { fill: #f43f5e; font-weight: bold; }
        .string { fill: #38bdf8; }
        .variable { fill: #a855f7; }
        .cursor { animation: cursorBlink 1s infinite; fill: #38bdf8; }
      </style>
    </defs>

    <!-- Main Container Card -->
    <rect x="5" y="5" width="990" height="270" rx="16" fill="url(#bgGrad)" stroke="url(#borderGrad)" stroke-width="2" />

    <!-- Terminal Window Top Bar -->
    <rect x="5" y="5" width="990" height="40" rx="16" fill="#020617" fill-opacity="0.6" />
    <circle cx="30" cy="25" r="6" fill="#ef4444" />
    <circle cx="50" cy="25" r="6" fill="#eab308" />
    <circle cx="70" cy="25" r="6" fill="#22c55e" />
    <text x="500" y="29" text-anchor="middle" font-family="'Fira Code', monospace" font-size="13" fill="#64748b">abdullah-naeem ~ zsh — 100x28</text>

    <!-- Glowing Grid Accent Background -->
    <path d="M0,80 L1000,80 M0,140 L1000,140 M0,200 L1000,200" stroke="#1e293b" stroke-width="1" stroke-dasharray="4 4" />

    <!-- Developer Main Name -->
    <text x="50" y="125" class="main-title">ABDULLAH NAEEM</text>

    <!-- Terminal Code Block Style Subtitle -->
    <g transform="translate(50, 165)">
      <text class="code-text" x="0" y="0">
        <tspan class="keyword">const</tspan> <tspan class="variable">developer</tspan> = {
      </text>
      <text class="code-text" x="20" y="25">
        role: <tspan class="string">'Full Stack MERN Developer'</tspan>,
      </text>
      <text class="code-text" x="20" y="50">
        passion: <tspan class="string">'Building Scalable Systems &amp; Modern UI'</tspan>
      </text>
      <text class="code-text" x="0" y="75">
        }; <rect class="cursor" x="35" y="63" width="10" height="18" />
      </text>
    </g>
  </svg>
</p>

<!-- ==================== TYPING SUBTITLE ==================== -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=38BDF8&center=true&vCenter=true&width=600&lines=Full+Stack+MERN+Developer+Student;Databases+%26+Cloud+Architect;Open+Source+Contributor" />
</p>

<!-- ==================== BADGES & VISITOR COUNTER ==================== -->
<p align="center">
  <a href="mailto:abdullahnaem102005@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=abdullahnaeem102005-hash&label=Profile%20Views&color=007ACC&style=for-the-badge" />
  <img src="https://img.shields.io/github/followers/abdullahnaeem102005-hash?label=Followers&style=for-the-badge&color=blueviolet" />
</p>

<br />

<!-- ==================== ABOUT ME ==================== -->
**👨‍💻 About Me**

* 🎓 **Education:** Pursuing **Modern Web Development (Full Stack MERN)**
* 💡 **Focus Areas:** Scalable Web Apps, Modern Frontend UI/UX, RESTful APIs, & Cloud Databases
* 🛠️ **Current Focus:** Data Structures, JavaScript Logic, & Full-Stack System Architecture
* 🎯 **Goal:** Building production-grade Web Applications & contributing to Open Source

<br />

<!-- ==================== COMPLETE TECH STACK ==================== -->
**🛠️ Complete Tech Stack & Ecosystem**

**Frontend Engineering:**
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
</p>

**Backend Development & Databases:**
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/REST_API-005571?style=for-the-badge&logo=postman&logoColor=white" />
</p>

**Tools, DevOps & Environment:**
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" />
</p>

<br />

<!-- ==================== GITHUB ANALYTICS ==================== -->
**📊 My GitHub Journey & Activity**

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=abdullahnaeem102005-hash&show_icons=true&theme=dracula&hide_border=true&count_private=true" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdullahnaeem102005-hash&layout=compact&theme=dracula&hide_border=true" />
</p>

<p align="center">
  <img width="98%" src="https://github-readme-streak-stats.herokuapp.com/?user=abdullahnaeem102005-hash&theme=dracula&hide_border=true" />
</p>

<br />

<!-- ==================== FOOTER ==================== -->
<p align="center">
  <img src="https://github-readme-joke-post.vercel.app/api?theme=dracula" />
</p>

<p align="center">
  <sub>⚡ <i>Building scalable Full Stack MERN applications, one commit at a time!</i></sub>
</p>
