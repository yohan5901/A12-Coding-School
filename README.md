<!DOCTYPE html>
<html lang="si">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>A12 Coding School</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&family=Noto+Sans+Sinhala&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', 'Noto Sans Sinhala', sans-serif;
      scroll-behavior: smooth;
    }

    body {
      background-color: #1a1a1a;
      color: white;
    }

    nav {
      background: #000;
      position: fixed;
      width: 100%;
      top: 0;
      left: 0;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 15px;
      z-index: 1000;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 18px;
      padding: 10px 15px;
      transition: all 0.3s ease;
    }

    nav a.active {
      background-color: #2aff13;
      color: #000;
      font-size: 22px;
      font-weight: bold;
      border-radius: 5px;
    }

    nav a:hover {
      color: white;
    }

    .section {
      padding: 100px 20px;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
    }

    #home {
      background: url('https://source.unsplash.com/1600x900/?cushion') no-repeat center center/cover;
      color: white;
    }

    #school {
      background: #222;
    }

    #products {
      background: #2a2a2a;
    }

    #contact {
      background: #fff;
      color: black;
    }

    .btn {
      margin: 10px;
      padding: 10px 20px;
      background: #ff3c00;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 18px;
      cursor: pointer;
      transition: all 0.3s ease-in-out;
    }

    .btn:hover {
      background: #ff9900;
      transform: scale(1.1);
    }

    img {
      max-width: 300px;
      border-radius: 10px;
      margin-top: 20px;
      box-shadow: 0 0 10px rgba(255, 60, 0, 0.4);
    }

    iframe {
      width: 90%;
      height: 300px;
      background-color: #fff;
      border: 2px solid #444;
      border-radius: 10px;
      margin-top: 20px;
    }

    textarea {
      width: 90%;
      height: 200px;
      background: #2e2e2e;
      color: white;
      border: 1px solid #555;
      border-radius: 10px;
      padding: 10px;
      font-family: monospace;
      font-size: 16px;
      resize: vertical;
    }

    .hero {
      text-align: center;
      padding: 50px 20px;
    }

    .hero h1 {
      font-size: 40px;
      color: #ff3c00;
    }

    .hero p {
      font-size: 18px;
      color: #ccc;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 20px;
      padding: 30px;
    }

    .card {
      background-color: #2a2a2a;
      border-radius: 12px;
      padding: 20px;
      transition: transform 0.3s ease;
      box-shadow: 0 0 10px rgba(255, 60, 0, 0.3);
      margin-bottom: 20px; /* 🟧 Card එකකට card එකකට in-between gap එක */
    }

    .card .card {
      margin-top: 20px; /*h.. f.. lesson ekayi 2card ekeyi athara gap rka */
      }

    .card:hover {
      transform: scale(1.03);
    }

    .card h2 {
      color: #ff3c00;
      font-size: 22px;
    }

    .card p {
      color: #ccc;
    }

    .practice-section {
      background-color: #111;
      padding: 30px 20px;
      margin-top: 40px;
    }

    .practice-section h2 {
      text-align: center;
      color: #ff9900;
      margin-bottom: 20px;
    }

    footer {
      background: #111;
      color: #888;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

<!-- 🔝 Navigation Bar -->
<nav>
  <a href="#home" class="nav-link active">Home</a>
  <a href="#school" class="nav-link">Lessons</a>
  <a href="#CODE" class="nav-link">Code practice</a>
</nav>

<!--Home Section-->
<section id="home" class="section">
  <center>
  <font color="red"><h1>Welcome to A12 School</h1></font>
  <p><b><i>මෙම Web Site එක තවමත් යාවත්කාලීන වන බව මතක තබා ගන්න.</i></b></p>
  <h1>Learn Programming in Sinhala</h1>
  <p>HTML, CSS, JavaScript, Python සහ තවත් බොහෝ දේ අතිවිශිෂ්ටව ඉගෙනගන්න!</p>
  </center>
</section>

<!-- 🧠 Lessons Section -->
<div id="school" class="section">
  
  <!-- HTML Headings Lesson -->
  <div class="card">
  
    <!-- HTML Fundamentals -->
    <div class="card">
      <h2>HTML Fundamentals</h2>
      <p>වෙබ් පිටු සාදාගන්න හැම අයටම HTML පළමු පියවරයි.</p>
    </div>

    <div class="card">
      <h2>CSS Styling</h2>
      <p>වෙබ් අඩවි ලස්සන කරන්න CSS අත්‍යවශ්‍යයි.</p>
    </div>

    <div class="card">
      <h2>JavaScript Essentials</h2>
      <p>Interactive වෙබ් අඩවි සෑදීමට JavaScript භාවිතා කරන්න.</p>
    </div>

    <div class="card">
      <h2>Python Programming</h2>
      <p>වෙබ්, AI, Game Development වලට Python ඉතා ජනප්‍රියයි.</p>
    </div>

</div>

<div class="card">
  <h2>HTML First Lesson</h2>
  <div class="card">
    <h2>HTML Headings</h2>
    <p>HTML වලින් heading (ශීර්ෂය) ලියන ආකාරය පහතින් බලන්න:</p>
    <ul style="text-align:left;max-width:600px;">
      <li><code>&lt;h1&gt;...</code> - විශාලම ශීර්ෂය</li>
      <li><code>&lt;h2&gt;...</code> - දෙවැනි විශාලතම</li>
      <li><code>&lt;h3&gt;...</code> - සහිත අනෙකුත් headings</li>
      <li><code>&lt;h6&gt;...</code> - කුඩා ම headings
    </ul>
  </div>
</div>




<!--Code Practice Section -->
<section id="CODE" class="section">
  <h2 style="color: #ff9900;">🔥 ඔබේ කේතය මෙතැනින් පරීක්ෂා කරන්න</h2>
  <p>HTML / JavaScript කේතය ලියලා output එක බලන්න.</p>

  
  <textarea id="code" placeholder="මෙහි ඔබේ කේතය ලියන්න..."></textarea>
  <iframe id="output"></iframe>
</section>


<!-- 🧠 JavaScript for Live Preview + Nav Highlight -->
<script>
  const textarea = document.getElementById("code");
  const iframe = document.getElementById("output");

  textarea.addEventListener("input", () => {
    const userCode = textarea.value;
    const doc = iframe.contentWindow.document;
    doc.open();
    doc.write(userCode);
    doc.close();
  });

  const navLinks = document.querySelectorAll('.nav-link');
  window.addEventListener('scroll', () => {
    const fromTop = window.scrollY + 120;

    navLinks.forEach(link => {
      const section = document.querySelector(link.getAttribute('href'));
      if (
        section.offsetTop <= fromTop &&
        section.offsetTop + section.offsetHeight > fromTop
      ) {
        navLinks.forEach(l => l.classList.remove('active'));
        link.classList.add('active');
      }
    });
  });

  navLinks.forEach(link => {
    link.addEventListener('click', function () {
      navLinks.forEach(l => l.classList.remove('active'));
      this.classList.add('active');
    });
  });
</script>

</body>
</html>

