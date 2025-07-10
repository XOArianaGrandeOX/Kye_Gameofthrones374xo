<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>KyomiHQ</title>
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: #0d001a;
      color: #e0d4ff;
      overflow-x: hidden;
    }

    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');

    header {
      background: linear-gradient(90deg, #7f00ff, #e100ff);
      padding: 2rem;
      text-align: center;
      animation: glitch-bg 5s infinite alternate;
    }

    header h1 {
      font-size: 3rem;
      text-shadow: 0 0 5px #fff, 0 0 15px #9d4edd, 0 0 25px #5a189a;
      animation: glitch-text 1.5s infinite;
    }

    nav {
      text-align: center;
      background: #1a001f;
      padding: 1rem;
    }

    nav a {
      color: #bb86fc;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 3rem 2rem;
      max-width: 900px;
      margin: auto;
    }

    .section-title {
      font-size: 2rem;
      border-bottom: 2px solid #bb86fc;
      margin-bottom: 1rem;
    }

    .glow-box {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid #7f00ff;
      border-radius: 10px;
      padding: 1.5rem;
      box-shadow: 0 0 10px #7f00ff50;
    }

    footer {
      text-align: center;
      padding: 2rem;
      background: #14001c;
      font-size: 0.9rem;
      color: #999;
    }

    @keyframes glitch-text {
      0% { text-shadow: 2px 0 red; }
      20% { text-shadow: -2px 2px blue; }
      40% { text-shadow: 2px -2px lime; }
      60% { text-shadow: -2px -1px magenta; }
      80% { text-shadow: 1px 2px cyan; }
      100% { text-shadow: 0 0 5px #fff; }
    }

    @keyframes glitch-bg {
      0% { background: linear-gradient(90deg, #7f00ff, #e100ff); }
      100% { background: linear-gradient(90deg, #5a189a, #9d4edd); }
    }
  </style>
</head>
<body>

  <header>
    <h1>KyomiHQ</h1>
    <p>Welcome to the glitchy core of the Stitchverse</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#schedule">Schedule</a>
    <a href="#merch">Merch</a>
    <a href="#community">Community</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <div class="section-title">About Kyomi</div>
    <div class="glow-box">
      <p>KyomiHQ is the digital home of chaos, creativity, and community. Whether you're tuning in for glitchy adventures or cozy tea-time chaos, this is where it all begins. Welcome to the stream hub of KyesAStitch and the world of Kyomi.</p>
    </div>
  </section>

  <section id="schedule">
    <div class="section-title">Stream Schedule</div>
    <div class="glow-box">
      <ul>
        <li><strong>Minecraft Mondays</strong></li>
        <li><strong>Cuppa Tea Tuesdays</strong></li>
        <li><strong>Way of the Force Wednesdays</strong></li>
        <li><strong>Anything Can Happen Thursdays</strong></li>
        <li><strong>Fortnite Fridays</strong></li>
        <li><strong>Survival Saturdays</strong></li>
        <li><strong>Solo Sundays</strong></li>
      </ul>
    </div>
  </section>

  <section id="merch">
    <div class="section-title">Merch</div>
    <div class="glow-box">
      <p><strong>Coming Soon:</strong> Glitched-out KyomiHQ merch drops! Stay tuned for exclusive gear designed to match the chaos. 👕✨</p>
    </div>
  </section>

  <section id="community">
    <div class="section-title">Join the Community</div>
    <div class="glow-box">
      <p>🎮 <a href="https://twitch.tv/KyesAStitch" target="_blank">Watch the stream</a></p>
      <p>💬 <a href="https://discord.gg/27689QcWS4" target="_blank">Join the Discord</a></p>
      <p>📸 <a href="https://instagram.com/KyesAStitch" target="_blank">Follow on Instagram</a></p>
    </div>
  </section>

  <section id="contact">
    <div class="section-title">Contact & Links</div>
    <div class="glow-box">
      <p>Email: <a href="mailto:kyomihq@example.com">kyomihq@example.com</a></p>
      <p>Also on: Twitch, YouTube, TikTok</p>
    </div>
  </section>

  <footer>
    &copy; 2025 KyomiHQ — All rights glitched ✨
  </footer>

</body>
</html>
