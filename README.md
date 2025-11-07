/index.html
/about.html
/contact.html
/services.html
/gallery.html
/style.css
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Главная — Наш сайт</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Добро пожаловать!</h1>
    <nav>
      <a href="index.html">Главная</a>
      <a href="about.html">О нас</a>
      <a href="services.html">Услуги</a>
      <a href="gallery.html">Галерея</a>
      <a href="contact.html">Контакты</a>
    </nav>
  </header>
  <main>
    <h2>Это главная страница нашего сайта</h2>
    <p>Добро пожаловать на наш проект!</p>
  </main>
  <footer>
    <p>© 2025 Наш проект</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f4f4f4;
}

header {
  background: #333;
  color: white;
  padding: 10px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

main {
  padding: 20px;
  background: white;
  margin: 10px;
  border-radius: 8px;
}

footer {
  text-align: center;
  padding: 10px;
  background: #333;
  color: white;
}

