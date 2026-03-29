<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ankush Chaudhary | Portfolio</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&family=Open+Sans&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background: #F1F5F9;
    }

    h1, h2, h3 {
      font-family: 'Poppins', sans-serif;
      color: #1E3A8A;
    }

    section {
      padding: 80px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .hero {
      text-align: center;
      background: linear-gradient(135deg, #1E3A8A, #2563EB);
      color: white;
      padding: 120px 20px;
    }

    .hero h1 {
      font-size: 3rem;
      color: white;
    }

    .btn {
      padding: 10px 20px;
      margin: 10px;
      background: white;
      color: #1E3A8A;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.05);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #1E3A8A;
      color: white;
    }
  </style>
</head>

<body>

  <!-- HERO -->
  <section class="hero">
    <h1>Ankush Chaudhary</h1>
    <h3>Assistant Professor of Mathematics</h3>
    <p>Empowering minds through mathematics</p>
    <a href="#contact" class="btn">Contact Me</a>
  </section>

  <!-- ABOUT -->
  <section>
    <h2>About Me</h2>
    <p>
      I am Ankush Chaudhary, Assistant Professor of Mathematics at GITM.
      I focus on building strong conceptual understanding and problem-solving skills among students.
    </p>
  </section>

  <!-- COURSES -->
  <section>
    <h2>Courses</h2>
    <div class="grid">
      <div class="card">Engineering Mathematics</div>
      <div class="card">Linear Algebra</div>
      <div class="card">Calculus</div>
      <div class="card">Differential Equations</div>
    </div>
  </section>

  <!-- SKILLS -->
  <section>
    <h2>Skills</h2>
    <div class="grid">
      <div class="card">Mathematical Modeling</div>
      <div class="card">Problem Solving</div>
      <div class="card">Analytical Thinking</div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: ankush@email.com</p>
    <p>Location: India</p>
  </section>

  <footer>
    <p>© 2026 Ankush Chaudhary</p>
  </footer>

</body>
</html>
