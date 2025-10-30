<!-- 🌊 Animated Skill Showcase Header (No GIF / No Emoji) -->
<svg viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg" style="width:100%; max-width:1200px; display:block; margin:auto; font-family:'Segoe UI', Roboto, sans-serif;">
  <defs>
    <!-- Gradient for background and text -->
    <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00b4d8">
        <animate attributeName="stop-color" values="#00b4d8;#0077b6;#00b4d8" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#90e0ef">
        <animate attributeName="stop-color" values="#90e0ef;#48cae4;#90e0ef" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <!-- Wave Path -->
    <path id="wavePath" d="M0,200 C300,260 600,140 900,200 C1050,230 1200,180 1200,180 L1200,400 L0,400 Z" />

    <!-- Floating text animation -->
    <style>
      .float {
        animation: float 3s ease-in-out infinite;
      }
      @keyframes float {
        0%, 100% { transform: translateY(0); }
        50% { transform: translateY(-10px); }
      }
      .skill {
        font-size: 16px;
        font-weight: 600;
        letter-spacing: 0.5px;
      }
    </style>
  </defs>

  <!-- Animated gradient background -->
  <rect width="1200" height="400" fill="url(#grad)" opacity="0.15"/>

  <!-- Animated wave -->
  <use href="#wavePath" fill="url(#grad)">
    <animateTransform attributeName="transform" type="translate" from="0 0" to="-120 0" dur="6s" repeatCount="indefinite" />
  </use>

  <!-- Central Name / Title -->
  <text x="50%" y="90" text-anchor="middle" fill="#023e8a" font-size="38" font-weight="bold">
    Nishwan — Software Developer
  </text>
  <text x="50%" y="125" text-anchor="middle" fill="#03045e" font-size="16">
    Crafting clean backends & interactive frontends
  </text>

  <!-- Floating Skill Icons/Texts -->
  <text x="200" y="230" fill="#03045e" class="skill float">Java</text>
  <text x="340" y="210" fill="#03045e" class="skill float" style="animation-delay:0.2s;">Spring Boot</text>
  <text x="500" y="240" fill="#03045e" class="skill float" style="animation-delay:0.4s;">React</text>
  <text x="660" y="210" fill="#03045e" class="skill float" style="animation-delay:0.6s;">MySQL</text>
  <text x="780" y="240" fill="#03045e" class="skill float" style="animation-delay:0.8s;">Three.js</text>
  <text x="930" y="220" fill="#03045e" class="skill float" style="animation-delay:1s;">Node.js</text>

  <!-- Bottom subtle wave -->
  <use href="#wavePath" fill="url(#grad)" opacity="0.3">
    <animateTransform attributeName="transform" type="translate" from="0 0" to="-60 0" dur="4s" repeatCount="indefinite" />
  </use>
</svg>

---

## 👋 About Me
Hi, I'm **Nishwan**, a Java Full Stack Developer passionate about clean backend architecture and dynamic frontends.

- 💻 Working on **EduAdmin ERP** — Admin, Staff, Student dashboards  
- ⚙️ Tech Stack: Java, Spring Boot, React, MySQL, Servlets, JSP  
- 🎯 Focus: Building scalable, interactive systems  
- 🌐 Portfolio: [your-portfolio-link]

---

## 🚀 Current Projects
- **EduAdmin ERP** — Academic & financial management system  
- **RNX Digital** — Business web app (React + Node)  
- **3D Portfolio** — React + Three.js interactive profile showcase  

---

## 🧩 Skills
| Backend | Frontend | Tools | Database |
|----------|-----------|--------|-----------|
| Java | React | Git, Docker | MySQL |
| Spring Boot | TypeScript | Postman | Hibernate |
| Servlets & JSP | HTML, CSS, JS | Maven | — |

---

## 📫 Let's Connect
[LinkedIn](#) • [GitHub](#) • [Portfolio](#)

---

<footer>
<sub>✨ This README is fully animated using only SVG and CSS — lightweight, no GIFs required.</sub>
</footer>

