<!DOCTYPE html>
<html lang="id">
<head>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap" rel="stylesheet">
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Canel Musik - Link Hub</title>
  <style>
    :root {
      --bg: #1a1a1a;
      --bg-light: #ffffff;
      --text: #f0f0f0;
      --text-light: #222222;
      --container: #1f1f1f;
      --container-light: #f5f5f5;
      --btn: #2a2a2a;
      --btn-light: #e0e0e0;
      --btn-hover: #444444;
      --btn-hover-light: #cccccc;
    }
    body {
      font-family: Arial, sans-serif;
      background: var(--bg);
      margin: 0;
      padding: 0;
      color: var(--text);
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      transition: background 0.6s ease, color 0.6s ease;
    }
    .container {
      max-width: 600px;
      width: 100%;
      padding: 30px 20px;
      box-sizing: border-box;
      text-align: center;
      background: var(--container);
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border-radius: 12px;
      margin-top: 40px;
      transition: background 0.6s ease;
    }
    h1 {
      font-family: 'Montserrat', sans-serif;
      font-size: 32px;
      margin-bottom: 10px;
      text-shadow: 0 0 10px #00ffe1;
    }
    p.description {
      font-size: 16px;
      margin-bottom: 30px;
    }
    a.link-button {
      width: 100%;
      display: flex;
      align-items: center;
      justify-content: flex-start;
      background-color: var(--btn);
      color: var(--text);
      text-decoration: none;
      padding: 14px 20px;
      margin: 10px 0;
      border-radius: 8px;
      transition: all 0.3s ease;
      font-size: 16px;
      animation: glowPulse 5s infinite ease-in-out;
    transition: all 0.3s ease, transform 0.5s ease, opacity 0.5s ease; opacity: 0; transform: translateY(20px);}
    a.link-button.in-view {
      opacity: 1;
      transform: translateY(0);
    }
    a.link-button:hover {
      background-color: var(--btn-hover);
      box-shadow: 0 0 12px #00ffe1;
    }
    .link-button span {
      flex: 1;
      margin-left: 10px;
      text-align: center;
    }
    .footer {
      margin-top: 40px;
      font-size: 12px;
      color: #888;
    }
    .theme-toggle {
      position: fixed;
      top: 20px;
      right: 20px;
      background: #00ffe1;
      border: none;
      padding: 10px 16px;
      border-radius: 20px;
      cursor: pointer;
      font-weight: bold;
      color: #000;
      box-shadow: 0 0 10px #00ffe1;
    }
    @keyframes pulse {
      0% { box-shadow: 0 0 15px 4px rgba(0, 255, 225, 0.6); }
      50% { box-shadow: 0 0 25px 8px rgba(0, 255, 225, 0.8); }
      100% { box-shadow: 0 0 15px 4px rgba(0, 255, 225, 0.6); }
    }
    @keyframes glowPulse {
      0% { box-shadow: 0 0 5px rgba(0,255,225,0.2); }
      50% { box-shadow: 0 0 15px rgba(0,255,225,0.8); }
      100% { box-shadow: 0 0 5px rgba(0,255,225,0.2); }
    }
      @media (max-width: 480px) {
      h1 {
        font-size: 24px;
      }
      a.link-button {
        font-size: 14px;
        padding: 12px 16px;
      }
    }

    .link-button i {
      transition: transform 0.3s ease;
    }

    .link-button:hover i {
      transform: scale(1.2) rotate(10deg);
    }
      a.link-button {
      opacity: 0;
      transform: translateY(20px);
      animation: fadeSlideUp 0.6s ease forwards;
    }
    a.link-button:nth-child(1) { animation-delay: 0.1s; }
    a.link-button:nth-child(2) { animation-delay: 0.2s; }
    a.link-button:nth-child(3) { animation-delay: 0.3s; }
    a.link-button:nth-child(4) { animation-delay: 0.4s; }
    a.link-button:nth-child(5) { animation-delay: 0.5s; }

    @keyframes fadeSlideUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
    }
  </style>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
</head>
<body>
  <button class="theme-toggle" onclick="toggleTheme()">Dark/Light Mode</button>
  <div class="container">
    <img src="https://i.imgur.com/OEKeKBx.jpg" style="width: 150px; margin-bottom: 20px; border-radius: 50%; object-fit: cover; animation: pulse 5s infinite;">
    <h1>Canel Musik</h1>
    <p class="description">Band musik all-around yang siap meramaikan acara Anda!</p>

    <a class="link-button" href="https://instagram.com/canel.musicofficial" target="_blank">
      <i class="fab fa-instagram"></i><span>Instagram</span>
    </a>
    <a class="link-button" href="https://wa.me/6287781757297" target="_blank">
      <i class="fab fa-whatsapp"></i><span>Hubungi Kami!</span>
    </a>
    <a class="link-button" href="https://www.youtube.com/watch?v=x9bLfNOCiJo" target="_blank">
      <i class="fab fa-youtube"></i><span>YouTube</span>
    </a>
    <a class="link-button" href="https://tiktok.com" target="_blank">
      <i class="fab fa-tiktok"></i><span>TikTok</span>
    </a>
    <a class="link-button" href="https://drive.google.com/drive/folders/1LnmDr8GFfA3EkOBUvNMse_UaQ8Xd1N4w" target="_blank">
      <i class="fas fa-file-alt"></i><span>(Profil Canel)</span>
    </a>

    <div class="footer">&copy; 2025 Canel Musik</div>
  </div>
  <script>
    function toggleTheme() {
      const root = document.documentElement;
      const isDark = root.style.getPropertyValue('--bg') === '#1a1a1a';
      if (isDark) {
        root.style.setProperty('--bg', 'linear-gradient(to bottom right, #fffdf7, #f2f2f2)');
        root.style.setProperty('--text', '#222222');
        root.style.setProperty('--container', 'rgba(255, 255, 255, 0.9)');
        root.style.setProperty('--btn', '#ffffff');
        root.style.setProperty('--btn-hover', '#dddddd');
      } else {
        root.style.setProperty('--bg', '#1a1a1a');
        root.style.setProperty('--text', '#f0f0f0');
        root.style.setProperty('--container', '#1f1f1f');
        root.style.setProperty('--btn', '#2a2a2a');
        root.style.setProperty('--btn-hover', '#444444');
      }
    }
  </script>
<script>
    const buttons = document.querySelectorAll('.link-button');
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('in-view');
        }
      });
    }, { threshold: 0.1 });

    buttons.forEach(btn => observer.observe(btn));
  </script>
</body>
</html>
