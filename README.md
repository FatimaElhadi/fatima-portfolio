# fatima-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
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
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .project {
      background: #f5f5f5;
      padding: 15px;
      border-radius: 10px;
