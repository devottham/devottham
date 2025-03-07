<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Devottham D K | Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f0f0f0;
      color: #333;
    }
    .container {
      max-width: 900px;
      margin: auto;
      background-color: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }
    h1, h2, h3 {
      color: #2d89ef;
    }
    a {
      color: #2d89ef;
      text-decoration: none;
      margin-right: 10px;
    }
    ul {
      padding-left: 20px;
    }
    /* Snake Animation */
    .snake-loader {
      display: flex;
      justify-content: center;
      margin: 40px 0;
    }
    .snake {
      display: flex;
      gap: 5px;
    }
    .snake span {
      width: 15px;
      height: 15px;
      background-color: #2d89ef;
      border-radius: 50%;
      animation: snakeMove 1s infinite ease-in-out;
    }
    .snake span:nth-child(2) { animation-delay: 0.1s; }
    .snake span:nth-child(3) { animation-delay: 0.2s; }
    .snake span:nth-child(4) { animation-delay: 0.3s; }
    .snake span:nth-child(5) { animation-delay: 0.4s; }

    @keyframes snakeMove {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>👋 Hey, I'm Devottham D K!</h1>
    <p>Frontend Developer | UI/UX Enthusiast | Tech Blogger</p>

    <h2>🐍 Snake Animation</h2>
    <div class="snake-loader">
      <div class="snake">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>

    <h2>🚀 About Me</h2>
    <p>I am passionate about creating seamless web experiences through design and development. Currently enhancing my Java skills while working on real-world projects.</p>

    <h2>🛠️ Tech Stack</h2>
    <ul>
      <li><strong>Languages:</strong> Java (learning), Python</li>
      <li><strong>Frontend:</strong> HTML, CSS, JavaScript, Bootstrap</li>
      <li><strong>Database:</strong> MySQL</li>
      <li><strong>Tools:</strong> Figma, Git, VS Code</li>
    </ul>

    <h2>💡 What I Do</h2>
    <ul>
      <li>🎨 Frontend Development – Crafting responsive, modern websites.</li>
      <li>🖌️ UI/UX Design – Building user-centric interfaces.</li>
      <li>✍️ Blogging – Sharing knowledge on tech and design.</li>
      <li>🛠️ Projects – Currently developing <strong>EcoGuardian</strong>, a smart waste management system.</li>
    </ul>

    <h2>📂 Featured Projects</h2>
    <h3>🚧 Ongoing</h3>
    <p><strong>EcoGuardian</strong> – Smart waste management solution.</p>
    
    <h3>✅ Completed</h3>
    <ul>
      <li><strong>MedZ</strong> – Patient Engagement Platform.</li>
      <li><strong>WSA</strong> – Women Safety Analytics with AI-powered CCTV.</li>
      <li><strong>WATCH</strong> – Wildlife Alert System to prevent conflicts.</li>
    </ul>

    <h2>🌐 Let's Connect</h2>
    <p>
      <a href="mailto:your-email@example.com">Email</a>
      <a href="https://linkedin.com/in/yourprofile">LinkedIn</a>
      <a href="https://x.com/yourprofile">X</a>
      <a href="https://instagram.com/yourprofile">Instagram</a>
      <a href="https://github.com/yourusername">GitHub</a>
    </p>

    <h2>⚡ Fun Fact</h2>
    <p>Besides coding, I love drawing, playing cricket, and watching movies!</p>
  </div>

</body>
</html>
