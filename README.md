<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Fatima Elhadi | UI Designer</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #fff;
      color: #333;
      padding: 40px 20px;
    }
    .container {
      max-width: 1000px;
      margin: auto;
    }
    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 40px;
    }
    header img {
      border-radius: 50%;
      width: 120px;
      height: 120px;
      object-fit: cover;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 5px;
    }
    h2 {
      font-size: 1.5rem;
      margin-top: 40px;
      margin-bottom: 15px;
      color: #111;
    }
    .about-me, .skills, .projects {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 20px;
    }
    .about-me p {
      flex: 1;
      min-width: 250px;
    }
    .skills-icons {
      display: flex;
      gap: 20px;
      align-items: center;
      flex-wrap: wrap;
    }
    .skills-icons img {
      width: 40px;
    }
    .project {
      background: #f5f5f5;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
      flex: 1 1 280px;
      max-width: 320px;
    }
    .project img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 10px;
    }
    .projects-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    footer {
      margin-top: 40px;
      text-align: center;
      font-size: 0.9rem;
      color: #777;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div>
        <h1>Fatima Elhadi</h1>
        <p>UI Designer</p>
      </div>
      <img src="https://via.placeholder.com/120" alt="Fatima Elhadi" />
    </header>

    <section class="about-me">
      <p>
        I am a UI designer with 5+ years of experience, working on health, e-commerce,
        and financial applications. Proficient in Figma and Photoshop, I focus on
        crafting engaging and modern user experiences. I have projects featured on
        Behance and currently work as a freelancer.
      </p>
    </section>

    <h2>Skills</h2>
    <div class="skills-icons">
      <div>✔️ UI Design</div>
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/33/Figma-logo.svg" alt="Figma" title="Figma" />
      <img src="https://upload.wikime
