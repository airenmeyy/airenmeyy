<div align="center">
<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- 🏰  RENAISSANCE DARK GOTH BANNER — animated cathedral SVG        -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<svg width="800" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0D0A0B"/>
      <stop offset="50%" style="stop-color:#1A1423"/>
      <stop offset="100%" style="stop-color:#0D0A0B"/>
    </linearGradient>
    <linearGradient id="gold" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#8B6914"/>
      <stop offset="50%" style="stop-color:#D4A843"/>
      <stop offset="100%" style="stop-color:#8B6914"/>
    </linearGradient>
    <linearGradient id="blood" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#6B1C23"/>
      <stop offset="100%" style="stop-color:#3D0C10"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softglow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Flicker animation for candles -->
    <animate xlink:href="#flame1" attributeName="opacity" values="0.7;1;0.6;0.9;0.7" dur="2s" repeatCount="indefinite"/>
    <animate xlink:href="#flame2" attributeName="opacity" values="0.9;0.6;1;0.7;0.9" dur="2.5s" repeatCount="indefinite"/>
  </defs>
  <!-- Background -->
  <rect width="800" height="220" fill="url(#bg)" rx="12"/>
  <!-- Gothic arch frame -->
  <path d="M 80 210 L 80 70 Q 80 20 130 20 L 670 20 Q 720 20 720 70 L 720 210" 
        fill="none" stroke="#3D2B1F" stroke-width="2" opacity="0.5"/>
  <path d="M 100 210 L 100 80 Q 100 35 145 35 L 655 35 Q 700 35 700 80 L 700 210" 
        fill="none" stroke="#6B1C23" stroke-width="1" opacity="0.3"/>
  <!-- Rose window (gothic circle) -->
  <circle cx="400" cy="55" r="20" fill="none" stroke="#D4A843" stroke-width="0.8" opacity="0.4"/>
  <circle cx="400" cy="55" r="14" fill="none" stroke="#6B1C23" stroke-width="0.5" opacity="0.5"/>
  <circle cx="400" cy="55" r="8" fill="#6B1C23" opacity="0.3"/>
  <!-- Rose petals in window -->
  <line x1="400" y1="35" x2="400" y2="75" stroke="#D4A843" stroke-width="0.5" opacity="0.3"/>
  <line x1="380" y1="55" x2="420" y2="55" stroke="#D4A843" stroke-width="0.5" opacity="0.3"/>
  <line x1="386" y1="41" x2="414" y2="69" stroke="#D4A843" stroke-width="0.3" opacity="0.25"/>
  <line x1="414" y1="41" x2="386" y2="69" stroke="#D4A843" stroke-width="0.3" opacity="0.25"/>
  <!-- Candle left -->
  <rect x="140" y="150" width="6" height="30" rx="2" fill="#3D2B1F"/>
  <ellipse id="flame1" cx="143" cy="148" rx="4" ry="7" fill="#D4A843" filter="url(#glow)" opacity="0.8">
    <animate attributeName="ry" values="7;8;6;7" dur="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;1;0.6;0.9;0.7" dur="2s" repeatCount="indefinite"/>
  </ellipse>
  <!-- Candle right -->
  <rect x="654" y="150" width="6" height="30" rx="2" fill="#3D2B1F"/>
  <ellipse id="flame2" cx="657" cy="148" rx="4" ry="7" fill="#D4A843" filter="url(#glow)" opacity="0.8">
    <animate attributeName="ry" values="6;7;8;6" dur="1.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.9;0.6;1;0.7;0.9" dur="2.5s" repeatCount="indefinite"/>
  </ellipse>
  <!-- Stars / dust particles -->
  <circle cx="180" cy="50" r="1" fill="#D4A843" opacity="0.4">
    <animate attributeName="opacity" values="0.2;0.6;0.2" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="300" cy="30" r="0.8" fill="#D4A843" opacity="0.3">
    <animate attributeName="opacity" values="0.1;0.5;0.1" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="550" cy="45" r="1.2" fill="#6B1C23" opacity="0.5">
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="620" cy="30" r="0.7" fill="#D4A843" opacity="0.3">
    <animate attributeName="opacity" values="0.2;0.5;0.2" dur="2.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="70" r="0.9" fill="#D4A843" opacity="0.2">
    <animate attributeName="opacity" values="0.1;0.4;0.1" dur="5s" repeatCount="indefinite"/>
  </circle>
  <!-- Ornamental cross/fleur -->
  <text x="400" y="55" font-size="8" fill="#D4A843" text-anchor="middle" opacity="0.6">✝</text>
  <!-- Title -->
  <text x="400" y="110" font-family="Georgia, 'Palatino Linotype', serif" font-size="36" font-weight="bold" fill="url(#gold)" text-anchor="middle" filter="url(#glow)" letter-spacing="6">⚜ runnie ⚜</text>
  <!-- Subtitle -->
  <text x="400" y="140" font-family="Georgia, 'Palatino Linotype', serif" font-size="14" fill="#6B1C23" text-anchor="middle" letter-spacing="8" filter="url(#softglow)">@airenmeyy</text>
  <!-- Bottom ornament line -->
  <line x1="250" y1="165" x2="350" y2="165" stroke="#3D2B1F" stroke-width="0.8"/>
  <text x="400" y="169" font-size="10" fill="#D4A843" text-anchor="middle" opacity="0.5">⸸</text>
  <line x1="450" y1="165" x2="550" y2="165" stroke="#3D2B1F" stroke-width="0.8"/>
  <!-- Latin motto -->
  <text x="400" y="195" font-family="Georgia, serif" font-size="11" fill="#4A3728" text-anchor="middle" font-style="italic" letter-spacing="3">per aspera ad astra</text>
</svg>
<br/>
```
𓂀 ˚ ⚜ . she who weaves code in the cathedral of night . ⚜ ˚ 𓂀
```
<br/>
<!-- Typing animation — Renaissance Goth style quotes -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=IM+Fell+English+SC&size=20&duration=3500&pause=1200&color=D4A843&center=true&vCenter=true&width=600&lines=i+like+the+way+you+kiss+me+%F0%9F%96%A4;ex+tenebris%2C+lux+—+from+darkness%2C+light+%E2%9C%A7;building+cathedrals+with+lines+of+code+%E2%9B%AA;memento+mori+—+remember+to+ship+%F0%9F%92%80;html%2C+css%2C+js+—+the+sacred+grimoire+%F0%9F%93%9C)](https://git.io/typing-svg)
</div>
<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- 🗡️  GOTHIC ORNAMENTAL DIVIDER                                    -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0D0A0B&height=1&section=header" width="100%"/>
```
─────────── ⸸ ✦ ⸸ ───────────
```
</div>
<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- 📜  ABOUT THE ARTIST                                              -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<div align="center">
### ⚜ about the artist ⚜
</div>
```js
const runnie = {
  // ─── The Renaissance Portrait ─────────────────────────────
  alias     : "airenmeyy 🌙",
  origin    : "Indonesia 🕯️",
  craft     : ["Frontend Artisan", "UI/UX Alchemist", "Web Architect"],
  grimoire  : ["HTML", "CSS", "JavaScript", "PHP", "TailwindCSS"],
  relics    : ["MySQL", "Git", "VS Code", "Figma"],
  currently : "illuminating manuscripts in code...",
  philosophy: "beauty in darkness, elegance in structure",
  mantra    : "i like the way you kiss me 🖤",
  // ─── Fin ──────────────────────────────────────────────────
};
```
<div align="center">
```
─────────── ⸸ ✦ ⸸ ───────────
```
</div>
<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- 🏛️  FEATURED WORKS — Gallery of Grand Works                      -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<div align="center">
### 🏛️ gallery of grand works
</div>
<table align="center">
<tr>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/⚜-OPUS_I-0D0A0B?style=for-the-badge&labelColor=6B1C23" />
**🌿 [SayurMart](https://github.com/airenmeyy/sayurmart)**
<br/>
*an e-commerce — verdant & alive*
<br/>
`HTML` `TailwindCSS` `JS`
</td>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/⚜-OPUS_II-0D0A0B?style=for-the-badge&labelColor=6B1C23" />
**☕ [Warcoff](https://github.com/airenmeyy/warcoff)**
<br/>
*a digital warung kopi*
<br/>
`PHP` `MySQL`
</td>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/⚜-OPUS_III-0D0A0B?style=for-the-badge&labelColor=6B1C23" />
**🧠 [Wellnest](https://github.com/airenmeyy/wellnest-app)**
<br/>
*mental health & emotion journal*
<br/>
`JavaScript`
</td>
</tr>
</table>
<div align="center">
```
─────────── ⸸ ✦ ⸸ ───────────
```
</div>
<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ⚗️  ENCHANTMENTS & SACRED TOOLS                                  -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<div align="center">
### ⚗️ enchantments & sacred tools
<br/>
<!-- Row 1: Languages -->
![HTML5](https://img.shields.io/badge/HTML5-%230D0A0B?style=for-the-badge&logo=html5&logoColor=D4A843)
![CSS3](https://img.shields.io/badge/CSS3-%231A1423?style=for-the-badge&logo=css3&logoColor=6B1C23)
![JavaScript](https://img.shields.io/badge/JavaScript-%230D0A0B?style=for-the-badge&logo=javascript&logoColor=D4A843)
![PHP](https://img.shields.io/badge/PHP-%231A1423?style=for-the-badge&logo=php&logoColor=6B1C23)
<!-- Row 2: Frameworks & Tools -->
![TailwindCSS](https://img.shields.io/badge/Tailwind-%230D0A0B?style=for-the-badge&logo=tailwind-css&logoColor=D4A843)
![MySQL](https://img.shields.io/badge/MySQL-%231A1423?style=for-the-badge&logo=mysql&logoColor=D4A843)
![Git](https://img.shields.io/badge/Git-%230D0A0B?style=for-the-badge&logo=git&logoColor=6B1C23)
![VSCode](https://img.shields.io/badge/VSCode-%231A1423?style=for-the-badge&logo=visual-studio-code&logoColor=D4A843)
![Figma](https://img.shields.io/badge/Figma-%230D0A0B?style=for-the-badge&logo=figma&logoColor=6B1C23)
</div>
<div align="center">
```
─────────── ⸸ ✦ ⸸ ───────────
```
</div>
<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- 📊  GITHUB STATS — Illuminated Manuscript Style                  -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<div align="center">
### 📊 the illuminated manuscript
<br/>
<!-- GitHub Stats -->
<a href="https://github.com/airenmeyy">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=airenmeyy&show_icons=true&theme=github_dark&bg_color=0D0A0B&title_color=D4A843&text_color=8B7355&icon_color=6B1C23&border_color=3D2B1F&hide_border=false&count_private=true" />
</a>
&nbsp;&nbsp;
<a href="https://github.com/airenmeyy">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=airenmeyy&layout=compact&theme=github_dark&bg_color=0D0A0B&title_color=D4A843&text_color=8B7355&border_color=3D2B1F&hide_border=false&langs_count=6" />
</a>
<br/><br/>
<!-- Streak Stats -->
<a href="https://github.com/airenmeyy">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=airenmeyy&theme=dark&background=0D0A0B&ring=D4A843&fire=6B1C23&currStreakLabel=D4A843&sideLabels=8B7355&currStreakNum=D4A843&sideNums=6B1C23&dates=3D2B1F&stroke=3D2B1F&border=3D2B1F" />
</a>
<br/><br/>
<!-- Activity Graph -->
<a href="https://github.com/airenmeyy">
  <img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=airenmeyy&bg_color=0D0A0B&color=D4A843&line=6B1C23&point=D4A843&area_color=1A1423&area=true&hide_border=false&custom_title=⚜%20Codex%20Activity%20⚜&title_color=D4A843&border_color=3D2B1F" />
</a>
</div>
<div align="center">
```
─────────── ⸸ ✦ ⸸ ───────────
```
</div>
<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- 🕯️  CONTRIBUTION SNAKE                                           -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<div align="center">
### 🐍 the serpent of contributions
<br/>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/airenmeyy/airenmeyy/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/airenmeyy/airenmeyy/output/github-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/airenmeyy/airenmeyy/output/github-snake-dark.svg" />
</picture>
</div>
<div align="center">
```
─────────── ⸸ ✦ ⸸ ───────────
```
</div>
<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- 🎵  NOW PLAYING — Spotify                                         -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<div align="center">
### 🎵 the chamber music
<br/>
[![spotify-github-profile](https://spotify-github-profile.kittinanx.com/api/view?uid=31bupebhoyqcwz37hxc4j524v7ey&cover_image=true&theme=natemoo-re&show_offline=true&background_color=0d0a0b&interchange=true&bar_color=6b1c23&bar_color_cover=true)](https://spotify-github-profile.kittinanx.com/api/view?uid=31bupebhoyqcwz37hxc4j524v7ey&redirect=true)
</div>
<div align="center">
```
─────────── ⸸ ✦ ⸸ ───────────
```
</div>
<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- 🕯️  CONNECT — Social Links                                       -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<div align="center">
### 🕯️ summon me
<br/>
[![Instagram](https://img.shields.io/badge/Instagram-%230D0A0B?style=for-the-badge&logo=instagram&logoColor=D4A843)](https://instagram.com/airenmeyy)
[![GitHub](https://img.shields.io/badge/GitHub-%231A1423?style=for-the-badge&logo=github&logoColor=D4A843)](https://github.com/airenmeyy)
[![Gmail](https://img.shields.io/badge/Gmail-%230D0A0B?style=for-the-badge&logo=gmail&logoColor=6B1C23)](mailto:airenmeyy@gmail.com)
</div>
<div align="center">
```
─────────── ⸸ ✦ ⸸ ───────────
```
</div>
<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- 🏰  PROFILE VIEWS & FOOTER                                       -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<div align="center">
<br/>
![Profile Views](https://komarev.com/ghpvc/?username=airenmeyy&color=6B1C23&style=for-the-badge&label=VISITORS+TO+THE+CATHEDRAL)
<br/><br/>
<!-- Footer SVG -->
<svg width="800" height="100" viewBox="0 0 800 100" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerbg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0D0A0B;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#1A1423"/>
      <stop offset="100%" style="stop-color:#0D0A0B;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <rect width="800" height="100" fill="url(#footerbg)" rx="8"/>
  <text x="400" y="35" font-family="Georgia, serif" font-size="12" fill="#3D2B1F" text-anchor="middle" font-style="italic" letter-spacing="4">the cathedral remembers those who code at midnight</text>
  <line x1="200" y1="55" x2="350" y2="55" stroke="#3D2B1F" stroke-width="0.5"/>
  <text x="400" y="60" font-size="12" fill="#6B1C23" text-anchor="middle" opacity="0.6">☩</text>
  <line x1="450" y1="55" x2="600" y2="55" stroke="#3D2B1F" stroke-width="0.5"/>
  <text x="400" y="82" font-family="Georgia, serif" font-size="10" fill="#4A3728" text-anchor="middle" letter-spacing="2">
    ✦ may your bugs be few &amp; your commits be many ✦
  </text>
</svg>
<br/>
*⚜ crafted with devotion by [@airenmeyy](https://github.com/airenmeyy) ⚜*
</div>
