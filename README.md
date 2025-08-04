Welcome to my QQ space
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CAO XIRU</title>
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      background: linear-gradient(to bottom, #f7f8fa, #ffffff);
      color: #2b2b2b;
      font-family: 'Helvetica Neue', 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
    }
    nav {
      background-color: #00441f;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
      flex-wrap: wrap;
      position: sticky;
      top: 0;
      z-index: 10;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 12px 0;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #ffffff;
      font-weight: 500;
      font-size: 16px;
    }
    nav a:hover {
      color: #a8d5ba;
    }
    nav .lang {
      margin-left: 15px;
      font-size: 14px;
      cursor: pointer;
      color: #e0e0e0;
    }
    .container {
      text-align: center;
      padding: 80px 20px 40px;
    }
    .avatar {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      object-fit: cover;
      margin: 20px 0;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    h1 {
      font-size: 32px;
      margin: 10px 0 5px;
      color: #00441f;
    }
    p.subtitle {
      font-size: 14px;
      color: #666;
      margin: 5px 0 20px;
    }
    .icons a {
      margin: 0 10px;
      text-decoration: none;
      color: #444;
      font-size: 22px;
    }
    section {
      background: #ffffff;
      margin: 20px auto;
      padding: 40px 25px;
      max-width: 750px;
      border-radius: 12px;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.04);
    }
    section h2 {
      color: #00441f;
      font-size: 20px;
      margin-bottom: 10px;
    }
    section p {
      color: #444;
      line-height: 1.6;
      font-size: 15px;
    }
    footer {
      color: #00441f;
      text-align: center;
      font-size: 14px;
      padding: 30px;
    }
  </style>
  <script>
    function changeLang(lang) {
      const data = {
        en: {
          about: "I'm a master's student at Hokkaido University, researching sensory experience design and tourism. I love exploring how VR, scent, and emotion can enhance storytelling in travel.",
          projects: "Projects include: VR x Tourism experience design, olfactory storytelling, and community-based international exhibition planning.",
          contact: `📧 Email: caoxiru5@gmail.com<br>📷 Instagram: <a href='https://www.instagram.com/SOO_SOOOSO' target='_blank'>@SOO_SOOOSO</a><br>🐙 GitHub: <a href='https://github.com/caoxiru' target='_blank'>caoxiru</a>`
        },
        ja: {
          about: "北海道大学の修士課程に在籍し、感性体験デザインと観光を研究しています。VRや香り、感情がどのように旅のストーリーテリングを豊かにできるかを探求しています。",
          projects: "研究プロジェクト：VR×観光体験設計、嗅覚ストーリーテリング、国際展覧会の企画など。",
          contact: `📧 メール: caoxiru5@gmail.com<br>📷 インスタ: <a href='https://www.instagram.com/SOO_SOOOSO' target='_blank'>@SOO_SOOOSO</a><br>🐙 GitHub: <a href='https://github.com/caoxiru' target='_blank'>caoxiru</a>`
        },
        zh: {
          about: "我是北海道大学的硕士生，研究感官体验设计与旅游，探索如何通过VR、气味与情感增强旅行中的叙事体验。",
          projects: "我的项目包括VR×旅游体验设计、嗅觉叙事、以及基于社区的国际展会策划等。",
          contact: `📧 邮箱: caoxiru5@gmail.com<br>📷 Instagram: <a href='https://www.instagram.com/SOO_SOOOSO' target='_blank'>@SOO_SOOOSO</a><br>🐙 GitHub: <a href='https://github.com/caoxiru' target='_blank'>caoxiru</a>`
        }
      };
      document.getElementById("about-text").innerHTML = data[lang].about;
      document.getElementById("projects-text").innerHTML = data[lang].projects;
      document.getElementById("contact-text").innerHTML = data[lang].contact;
    }
  </script>
</head>
<body>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
    <div class="lang" onclick="changeLang('en')">EN</div>
    <div class="lang" onclick="changeLang('ja')">JP</div>
    <div class="lang" onclick="changeLang('zh')">中文</div>
  </nav>
  <div class="container">
    <h1 style="font-size: 36px; margin-bottom: 5px;">Welcome</h1>
    <p class="subtitle" id="typewriter" style="font-style: italic; color: #555; white-space: nowrap; overflow: hidden; border-right: 2px solid #888;"></p>
    <script>
      const text = "Welcome to my QQ space";
      let i = 0;
      const speed = 120;
      function typeWriter() {
        if (i < text.length) {
          document.getElementById("typewriter").textContent += text.charAt(i);
          i++;
          setTimeout(typeWriter, speed);
        } else {
          document.getElementById("typewriter").style.borderRight = "none";
        }
      }
      window.addEventListener('load', typeWriter);
    </script>
    <img src="WechatIMG1021.jpg" alt="CAO XIRU's Avatar" class="avatar" />
    <h1 style="font-size: 32px; font-weight: 600; letter-spacing: 1px;">CAO XIRU</h1>
    <p class="subtitle">Media & Tourism Researcher, Sensory Experience Designer</p>
    <div class="icons">
      <a href="https://github.com/caoxiru" target="_blank">🐙</a>
      <a href="https://www.instagram.com/SOO_SOOOSO" target="_blank">📷</a>
      <a href="mailto:caoxiru5@gmail.com">✉️</a>
    </div>
  </div>
  <section id="about">
    <h2>About</h2>
    <p id="about-text">I'm a master's student at Hokkaido University, researching sensory experience design and tourism. I love exploring how VR, scent, and emotion can enhance storytelling in travel.</p>
  </section>
  <section id="projects">
    <h2>Projects</h2>
    <p id="projects-text">Projects include: VR x Tourism experience design, olfactory storytelling, and community-based international exhibition planning.</p>
  </section>
  <section id="contact">
    <h2>Contact</h2>
    <p id="contact-text">
      📧 Email: caoxiru5@gmail.com<br>
      📷 Instagram: <a href="https://www.instagram.com/SOO_SOOOSO" target="_blank">@SOO_SOOOSO</a><br>
      🐙 GitHub: <a href="https://github.com/caoxiru" target="_blank">caoxiru</a>
    </p>
  </section>
  <footer>
    Feel free to contact me
  </footer>
</body>
</html>
