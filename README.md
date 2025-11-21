<div align="center">

<!-- Animated Name with Multiple Effects -->
<div align="center">
  <svg width="700" height="140" viewBox="0 0 700 140" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- Animated gradient with more colors -->
      <linearGradient id="gradient" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#ff6b6b;stop-opacity:1">
          <animate attributeName="stop-color" values="#ff6b6b;#4ecdc4;#45b7d1;#96ceb4;#ffeaa7;#f093fb;#4facfe;#43e97b;#fa709a;#fee140;#ff6b6b" dur="4s" repeatCount="indefinite"/>
        </stop>
        <stop offset="25%" style="stop-color:#4ecdc4;stop-opacity:1">
          <animate attributeName="stop-color" values="#4ecdc4;#45b7d1;#96ceb4;#ffeaa7;#f093fb;#4facfe;#43e97b;#fa709a;#fee140;#ff6b6b;#4ecdc4" dur="4s" repeatCount="indefinite"/>
        </stop>
        <stop offset="50%" style="stop-color:#45b7d1;stop-opacity:1">
          <animate attributeName="stop-color" values="#45b7d1;#96ceb4;#ffeaa7;#f093fb;#4facfe;#43e97b;#fa709a;#fee140;#ff6b6b;#4ecdc4;#45b7d1" dur="4s" repeatCount="indefinite"/>
        </stop>
        <stop offset="75%" style="stop-color:#96ceb4;stop-opacity:1">
          <animate attributeName="stop-color" values="#96ceb4;#ffeaa7;#f093fb;#4facfe;#43e97b;#fa709a;#fee140;#ff6b6b;#4ecdc4;#45b7d1;#96ceb4" dur="4s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" style="stop-color:#ffeaa7;stop-opacity:1">
          <animate attributeName="stop-color" values="#ffeaa7;#f093fb;#4facfe;#43e97b;#fa709a;#fee140;#ff6b6b;#4ecdc4;#45b7d1;#96ceb4;#ffeaa7" dur="4s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>
      
      <!-- Enhanced glow filter -->
      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      
      <!-- Shadow filter -->
      <filter id="shadow" x="-50%" y="-50%" width="200%" height="200%">
        <feDropShadow dx="0" dy="0" stdDeviation="8" flood-color="#4ECDC4" flood-opacity="0.8">
          <animate attributeName="flood-color" values="#4ECDC4;#FF6B6B;#45B7D1;#96CEB4;#FFEAA7;#4ECDC4" dur="3s" repeatCount="indefinite"/>
        </feDropShadow>
      </filter>
      
      <!-- Radial gradient for extra glow -->
      <radialGradient id="radialGlow" cx="50%" cy="50%">
        <stop offset="0%" style="stop-color:#fff;stop-opacity:0.8">
          <animate attributeName="stop-opacity" values="0.8;0.3;0.8" dur="2s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" style="stop-color:#4ecdc4;stop-opacity:0">
          <animate attributeName="stop-color" values="#4ecdc4;#ff6b6b;#45b7d1;#4ecdc4" dur="3s" repeatCount="indefinite"/>
        </stop>
      </radialGradient>
    </defs>
    
    <!-- Background glow circle -->
    <circle cx="350" cy="70" r="60" fill="url(#radialGlow)" opacity="0.5">
      <animate attributeName="r" values="60;75;60" dur="3s" repeatCount="indefinite"/>
    </circle>
    
    <!-- Main text with multiple effects -->
    <text x="350" y="75" font-family="Arial, sans-serif" font-size="56" font-weight="bold" 
          text-anchor="middle" dominant-baseline="middle" 
          fill="url(#gradient)" 
          filter="url(#glow)"
          stroke="url(#gradient)" 
          stroke-width="0.5"
          opacity="1">
      <animate attributeName="opacity" values="0.7;1;0.9;1;0.7" dur="2.5s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" 
                        type="scale" 
                        values="1;1.05;1;1.03;1" 
                        dur="3s" 
                        repeatCount="indefinite"/>
      <animateTransform attributeName="transform" 
                        type="rotate" 
                        values="0 350 75;-2 350 75;2 350 75;-2 350 75;0 350 75" 
                        dur="4s" 
                        repeatCount="indefinite"
                        additive="sum"/>
      Joseph Hudak
    </text>
    
    <!-- Additional text shadow layer for depth -->
    <text x="350" y="75" font-family="Arial, sans-serif" font-size="56" font-weight="bold" 
          text-anchor="middle" dominant-baseline="middle" 
          fill="none" 
          stroke="#000" 
          stroke-width="2" 
          opacity="0.3"
          filter="url(#shadow)">
      <animateTransform attributeName="transform" 
                        type="scale" 
                        values="1;1.05;1;1.03;1" 
                        dur="3s" 
                        repeatCount="indefinite"/>
      <animateTransform attributeName="transform" 
                        type="rotate" 
                        values="0 350 75;-2 350 75;2 350 75;-2 350 75;0 350 75" 
                        dur="4s" 
                        repeatCount="indefinite"
                        additive="sum"/>
      Joseph Hudak
    </text>
  </svg>
</div>

<!-- Subtitle -->
<h3>🚀 Full Stack Developer | Problem Solver | Product Engineer </h3>

<!-- Most Used Languages -->
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hudakjoseph28&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=4ECDC4&text_color=FFFFFF" alt="Most Used Languages" height="180"/>

<!-- Animated divider -->
<img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />

<!-- Tech Stack -->
<h2>🛠️ Tech Stack</h2>

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white)

<!-- Contact -->
<h2>📫 Connect with me</h2>

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hudakjoseph28)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joeyhudak2028/)

</div>

