<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Soo kijo</title>
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #ffffff;
      color: #111;
      margin: 0;
      padding: 0;
    }
    nav {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px 0;
      background-color: #fff;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
      flex-wrap: wrap;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #444;
      font-weight: 500;
    }
    nav a:hover {
      color: #007acc;
    }
    nav .lang {
      margin-left: 20px;
      font-size: 14px;
      cursor: pointer;
      color: #666;
    }
    .container {
      text-align: center;
      padding: 60px 20px;
    }
    .avatar {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 20px;
    }
    h1 {
      font-size: 28px;
      margin: 0;
    }
    p.subtitle {
      font-size: 16px;
      color: #666;
      margin: 8px 0 30px;
    }
    .icons a {
      margin: 0 8px;
      text-decoration: none;
      color: #444;
      font-size: 20px;
    }
    section {
      padding: 40px 20px;
      max-width: 700px;
      margin: 0 auto;
    }
    section h2 {
      margin-bottom: 10px;
      font-size: 22px;
      color: #2c3e50;
    }
    section p {
      font-size: 16px;
      color: #555;
    }
  </style>
  <script>
    const content = {
      en: {
        about: "I'm a master's student at Hokkaido University, researching sensory experience design and tourism. I love exploring how VR, scent, and emotion can enhance storytelling in travel.",
        projects: "Projects include: VR x Tourism experience design, olfactory storytelling, and community-based international exhibition planning.",
        contact: `📧 Email: sooxiru@gmail.com<br>📷 Instagram: <a href='https://www.instagram.com/SOO_SOOOSO' target='_blank'>@SOO_SOOOSO</a><br>🐙 GitHub: <a href='https://github.com/caoxiru' target='_blank'>caoxiru</a>`
      },
      ja: {
        about: "北海道大学の修士課程に在籍し、感性体験デザインと観光を研究しています。VRや香り、感情がどのように旅のストーリーテリングを豊かにできるかを探求しています。",
        projects: "研究プロジェクト：VR×観光体験設計、嗅覚ストーリーテリング、国際展覧会の企画など。",
        contact: `📧 メール: sooxiru@gmail.com<br>📷 インスタ: <a href='https://www.instagram.com/SOO_SOOOSO' target='_blank'>@SOO_SOOOSO</a><br>🐙 GitHub: <a href='https://github.com/caoxiru' target='_blank'>caoxiru</a>`
      },
      zh: {
        about: "我是北海道大学的硕士生，研究感官体验设计与旅游，探索如何通过VR、气味与情感增强旅行中的叙事体验。",
        projects: "我的项目包括VR×旅游体验设计、嗅觉叙事、以及基于社区的国际展会策划等。",
        contact: `📧 邮箱: sooxiru@gmail.com<br>📷 Instagram: <a href='https://www.instagram.com/SOO_SOOOSO' target='_blank'>@SOO_SOOOSO</a><br>🐙 GitHub: <a href='https://github.com/caoxiru' target='_blank'>caoxiru</a>`
      }
    };
    function changeLang(lang) {
      document.getElementById("about-text").innerHTML = content[lang].about;
      document.getElementById("projects-text").innerHTML = content[lang].projects;
      document.getElementById("contact-text").innerHTML = content[lang].contact;
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
    <img src="WechatIMG1021.jpg" alt="Soo's Avatar" class="avatar" />
    <h1>Soo (Cao Xiru)</h1>
    <p class="subtitle">Media & Tourism Researcher, Sensory Experience Designer</p>
    <div class="icons">
      <a href="https://github.com/caoxiru" target="_blank">🐙</a>
      <a href="https://www.instagram.com/SOO_SOOOSO" target="_blank">📷</a>
      <a href="mailto:sooxiru@gmail.com">✉️</a>
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
</body>
</html>
