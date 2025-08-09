<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Site Vitrine Parfait</title>
  <link rel="stylesheet" href="style 2.css">
</head>
<body>
  <header>
    <nav>
      <h1>MonSite</h1>
      <ul>
        <li><a href="#accueil">Accueil</a></li>
        <li><a href="apropos.html"> A propos</a></li>
        <li><a href="Mes tutos.html">Mes Tutos</a></li>
        <li><a href="Galerie-1.html">Galerie</a></li>
       
      </ul>
    </nav>
  </header>

  <section id="accueil" class="hero">
    <h2>Bienvenue sur le site de GUEDJO 😊😊</h2>
    <p>Un site moderne, rapide et responsive.</p>
    <a href="#services" class="btn">Découvrir</a>
  </section>

  <section id="services">
    <h2>Nos Services</h2>
    <div class="cards">
      <div class="card">
        <h3>Développement Web</h3>
        <p>Sites modernes et performants.</p>
      </div>
      <div class="card">
        <h3>Design UI/UX</h3>
        <p>Expérience utilisateur optimisée.</p>
      </div>
      <div class="card">
        <h3>Formation</h3>
        <p>Apprenez à coder avec nous.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contactez-nous</h2>
    <form>
      <input type="text" placeholder="Votre nom" required>
      <input type="email" placeholder="Votre email" required>
      <textarea placeholder="Votre message" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
  </section>

  <footer>
    <p>&copy;2025 GUEDJO | L'ère de la technologie 🤖🤖🤖.</p>
  </footer>
</body>
</html>
/* style.css */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body {
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

header {
  background-color: #2c3e50;
  padding: 20px;
  color: white;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav h1 {
  font-size: 24px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  background: linear-gradient(to right, #3498db, #2ecc71);
  color: white;
  text-align: center;
  padding: 80px 20px;
}

.hero .btn {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  background-color: white;
  color: #2c3e50;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
}

section {
  padding: 60px 20px;
  text-align: center;
}

.cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin-top: 30px;
}

.card {
  background-color: white;
  padding: 20px;
  width: 250px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

form {
  display: flex;
  flex-direction: column;
  gap: 15px;
  max-width: 400px;
  margin: auto;
}

input, textarea {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  padding: 10px;
  background-color: #2c3e50;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

footer {
  background-color: #2c3e50;
  color: white;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}
