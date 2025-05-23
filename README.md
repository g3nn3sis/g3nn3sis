<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Gennesis</title>
  <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Rubik', sans-serif;
      background: linear-gradient(145deg, #0f2027, #203a43, #2c5364);
      color: #f0f0f0;
      line-height: 1.6;
    }
    header {
      background: rgba(15, 32, 39, 0.75);
      backdrop-filter: blur(8px);
      padding: 3rem 1rem;
      text-align: center;
      color: #66fcf1;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 10px rgba(0,0,0,0.6);
    }
    header h1 {
      font-size: 3rem;
      animation: fadeInDown 1s ease-out forwards;
      text-shadow: 0 0 10px #66fcf1;
    }
    nav {
      margin-top: 1rem;
      animation: fadeInUp 1s ease-out forwards;
    }
    nav a {
      margin: 0 1rem;
      color: #66fcf1;
      text-decoration: none;
      transition: color 0.3s, transform 0.3s, text-shadow 0.3s;
      display: inline-block;
    }
    nav a:hover {
      color: #ffffff;
      transform: scale(1.15);
      text-shadow: 0 0 15px #66fcf1;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #66fcf1;
      border-bottom: 2px solid #66fcf1;
      display: inline-block;
      padding-bottom: 0.3rem;
    }
    .project-card {
      background: #1f2833;
      padding: 2rem;
      border-left: 5px solid #66fcf1;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.4);
      border-radius: 10px;
      transition: transform 0.4s ease, box-shadow 0.4s ease;
      margin-bottom: 2rem;
    }
    .project-card:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 25px rgba(102, 252, 241, 0.3);
    }
    .languages {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      margin-top: 2rem;
    }
    .lang {
      background-color: #0b0c10;
      border: 1px solid #66fcf1;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      font-weight: bold;
      color: #66fcf1;
      box-shadow: 0 2px 5px rgba(0,0,0,0.3);
      user-select: none;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #0b0c10;
      font-size: 0.9rem;
    }
    a {
      color: #66fcf1;
    }
    a:hover {
      text-decoration: underline;
    }
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>@gennesis</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello, I'm Gennesis and I like making stuff. I work with C# and Python, and I enjoy building games and exploring new tech!</p>
    <div class="languages">
      <div class="lang">C#</div>
      <div class="lang">Python</div>
      <div class="lang">HTML</div>
      <div class="lang">CSS</div>
      <div class="lang">JavaScript</div>
      <div class="lang">Unity</div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project-card">
      <h3>Genne-Taggers</h3>
      <p>A Gorilla Tag-inspired game. Check it out on <a href="https://discord.gg/AmsncKFPn3" target="_blank" rel="noopener noreferrer">Discord</a>.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Reach out to me on Discord: <a href="https://discord.com/users/1244639564396757115">@g3nn3sis</a></p>
  </section>

  <footer>
    <p>&copy; 2025 @g3nn3sis — Built with code &amp; curiosity</p>
  </footer>
</body>
</html>
