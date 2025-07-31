<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bobur Portfolio</title>
  <link rel="stylesheet" href="index.css">
</head>
<body>
  <header>
    <h1>Salom, men Bobur</h1>
    <p>Frontend Dasturchiman</p>
  </header>

  <section class="about">
    <h2>Men haqimda</h2>
    <p>Men HTML va CSS yordamida zamonaviy, responsiv saytlar yarat(aman. Sizga shaxsiy yoki biznesingiz uchun chiroyli sayt kerak bo‘lsa — men yordam bera olaman.</p>
  </section>

  <section class="contact">
    <h2>Aloqa</h2>
    <p>Email: boburdev@example.com</p>
  </section>

  <footer>
    <p>&copy; 2025 BoburDev</p>
  </footer>
</body>
</html>


body {
  font-family: sans-serif;
  margin: 0;
  padding: 0;
  background: #f9f9f9;
  color: #333;
}

header {
  background-color: #4CAF50;
  color: white;
  text-align: center;
  padding: 40px 20px;
}

section {
  padding: 20px;
  max-width: 600px;
  margin: auto;
}

.about, .contact {
  background: white;
  margin-top: 20px;
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

footer {
  text-align: center;
  padding: 10px;
  margin-top: 30px;
  color: gray;
}
