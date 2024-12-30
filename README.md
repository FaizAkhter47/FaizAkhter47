<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Faiz Akhter's Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #282c34;
      color: #fff;
      padding: 0 20px;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 40px 0;
      border-bottom: 2px solid #fff;
    }
    h1 {
      font-size: 36px;
      color: #61dafb;
      text-align: center;
    }
    .nav-links {
      list-style-type: none;
      display: flex;
      gap: 20px;
    }
    .nav-links li {
      font-size: 18px;
      cursor: pointer;
      transition: all 0.3s;
    }
    .nav-links li:hover {
      color: #61dafb;
    }
    .hero {
      text-align: center;
      padding: 50px 0;
    }
    .hero h2 {
      font-size: 48px;
    }
    .skills-section {
      margin-top: 50px;
      text-align: center;
    }
    .skills-section h2 {
      font-size: 36px;
    }
    .skills-list {
      display: flex;
      justify-content: center;
      gap: 40px;
      margin-top: 20px;
      flex-wrap: wrap;
    }
    .skills-list div {
      padding: 10px 20px;
      background-color: #444;
      border-radius: 10px;
      transition: all 0.3s;
    }
    .skills-list div:hover {
      transform: translateY(-10px);
    }
    footer {
      text-align: center;
      padding: 20px;
      margin-top: 50px;
      font-size: 16px;
      background-color: #333;
    }
    /* Animations */
    .fade-in {
      animation: fadeIn 1.5s ease-in-out;
    }
    .slide-in {
      animation: slideIn 1.5s ease-in-out;
    }
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }
    @keyframes slideIn {
      from {
        transform: translateX(100%);
      }
      to {
        transform: translateX(0);
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Faiz Akhter</h1>
    <ul class="nav-links">
      <li>Home</li>
      <li>DevOps Skills</li>
      <li>About</li>
    </ul>
  </header>

  <section class="hero fade-in">
    <h2>Welcome to My Portfolio</h2>
    <p>DevOps Engineer | Passionate about Automation and Cloud Technologies</p>
  </section>

  <section class="skills-section slide-in">
    <h2>DevOps Skills</h2>
    <div class="skills-list">
      <div>
        <img src="https://media.giphy.com/media/l1J9Rk5zH2N8A6c9g/giphy.gif" alt="CI/CD GIF" style="width: 200px;">
        <p>CI/CD</p>
      </div>
      <div>
        <img src="https://media.giphy.com/media/l4KhQYor1yFP0v0gM/giphy.gif" alt="Docker GIF" style="width: 200px;">
        <p>Docker</p>
      </div>
      <div>
        <img src="https://media.giphy.com/media/3o7TKwWoCBj20ZoPy0/giphy.gif" alt="Kubernetes GIF" style="width: 200px;">
        <p>Kubernetes</p>
      </div>
      <div>
        <img src="https://media.giphy.com/media/1dd0hCpNdyiKs/giphy.gif" alt="AWS GIF" style="width: 200px;">
        <p>AWS</p>
      </div>
      <div>
        <img src="https://media.giphy.com/media/3o7TKwWoCBj20ZoPy0/giphy.gif" alt="Terraform GIF" style="width: 200px;">
        <p>Terraform</p>
      </div>
      <div>
        <img src="https://media.giphy.com/media/26gs9nI4DBq0SO4z2/giphy.gif" alt="Linux GIF" style="width: 200px;">
        <p>Linux</p>
      </div>
    </div>
  </section>

  <footer>
    <p>Email: <a href="mailto:faizakhter47@gmail.com" style="color: #61dafb;">faizakhter47@gmail.com</a></p>
  </footer>

</body>
</html>
