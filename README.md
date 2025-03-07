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
      background-color: #f5f5f5;
      color: #333;
    }
    h1, h2, h3 {
      color: #2d89ef;
    }
    a {
      color: #2d89ef;
      text-decoration: none;
      margin-right: 10px;
    }
    .container {
      max-width: 900px;
      margin: auto;
      background: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .badge a {
      display: inline-block;
      padding: 8px 12px;
      margin: 5px 5px 0 0;
      border-radius: 5px;
      background-color: #ddd;
    }
    .tech-stack, .projects {
      margin: 20px 0;
    }
    /* Snake Loader */
    .snake-loader {
      display: flex;
      justify-content: center;
      margin: 40px 0;
    }
    .snake {
      width: 200px;
      height: 20px;
      display: flex;
    }
    .snake span {
      width: 20px;
      height: 20px;
      margin: 0 2px;
      background-color: #2d89ef;
      animation: move 1s infinite;
    }
    .snake span:nth-child(2) { animation-delay: 0.1s; }
    .snake span:nth-child(3) { animation-delay: 0.2s; }
    .snake span:nth-child(4) { animation-delay: 0.3s; }
    .snake span:nth-child(5) { animation-delay: 0.4s; }

    @keyframes move {
      0% { transform: translateY(0); }
      50% { transform: translateY(-15px); }
      100% { transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>👋 Hi there, I'm Devottham D K!</h1>
    <p><strong>Frontend Developer | UI/UX Enthusiast | Tech Blogger</strong></p>
    <p>Welcome to my portfolio! I'm passionate about creating seamless and dynamic web experiences with a keen eye for design and usability.</p>

    <h2>🐍 Watch the Snake in Action!</h2>
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
    <p>I'm a <strong>Frontend Developer</strong> and <strong>UI/UX Designer</strong> who loves turning ideas into reality through code and design. I'm currently leveling up my Java skills and building impactful projects that solve real-world problems.</p>

    <h2>🛠️ Tech Stack</h2>
    <div class="tech-stack">
      <ul>
        <li><strong>Languages:</strong> Java (Learning), Python</li>
        <li><strong>Frontend:</strong> HTML, CSS, JavaScript, Bootstrap</li>
        <li><strong>Database:</strong> MySQL</li>
        <li><strong>Tools:</strong> Figma, Git, VS Code</li>
      </ul>
    </div>

    <h2>💡 What I Do</h2>
    <ul>
      <li>🎨 Frontend Development – Building responsive, modern websites.</li>
      <li>🖌️ UI/UX Design – Crafting user-friendly and beautiful interfaces.</li>
      <li>✍️ Blogging – Sharing insights on tech, coding, and design.</li>
      <li>🛠️ Project Development – Currently working on <strong>EcoGuardian</strong> – a smart waste management system.</li>
    </ul>

    <h2>📂 Featured Projects</h2>
    <div class="projects">
      <h3>🚧 Under Development</h3>
      <p><strong>EcoGuardian</strong> – Smart Waste Management<br>A next-gen solution for efficient waste handling and sustainability.</p>

      <h3>✅ Completed Projects</h3>
      <ul>
        <li><strong>MedZ</strong> – Patient Engagement Platform (Connecting patients, doctors, and hospitals)</li>
        <li><strong>WSA</strong> – Women Safety Analytics (AI-powered CCTV surveillance)</li>
        <li><strong>WATCH</strong> – Wildlife Alert System (AI-driven detection to prevent conflicts)</li>
      </ul>
    </div>

    <h2>🌐 Let's Connect!</h2>
    <div class="badge">
      <a href="mailto:your-email@example.com">Email</a>
      <a href="https://linkedin.com/in/yourprofile">LinkedIn</a>
      <a href="https://x.com/yourprofile">X</a>
      <a href="https://instagram.com/yourprofile">Instagram</a>
      <a href="https://github.com/yourusername">GitHub</a>
    </div>

    <h2>⚡ Fun Fact</h2>
    <p>When I'm not coding, you can find me drawing, playing cricket, or watching movies!</p>
  </div>
</body>
</html>