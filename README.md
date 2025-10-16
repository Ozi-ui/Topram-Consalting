<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Topram Consulting</title>
  <link rel="stylesheet" href="style.css" />
  <script defer src="script.js"></script>
</head>
<body>
  <header>
    <h1>Topram Consulting</h1>
    <button class="burger" id="burger">&#9776;</button>
    <nav id="nav-menu">
      <a href="#home">Start</a>
      <a href="#kontakt">Kontakt</a>
      <a href="#karriere">Karriere</a>
    </nav>
  </header>

  <section id="home">
    <h2>Willkommen bei Topram Consulting</h2>
    <p>Strategie. Effizienz. Erfolg.</p>
  </section>

  <section id="kontakt">
    <h2>Kontaktformular</h2>
    <form id="contact-form">
      <label for="name">Name:</label>
      <input type="text" id="name" required />

      <label for="email">E-Mail:</label>
      <input type="email" id="email" required />

      <label for="message">Nachricht:</label>
      <textarea id="message" required></textarea>

      <button type="submit">Absenden</button>
    </form>
    <p id="form-status"></p>
  </section>

  <section id="karriere">
    <h2>Karriere</h2>
    <ul class="job-list">
      <li>
        <h3>Junior Consultant (m/w/d)</h3>
        <p>Beratung im Bereich Prozessoptimierung und Digitalisierung.</p>
      </li>
      <li>
        <h3>HR Manager (m/w/d)</h3>
        <p>Personalgewinnung und Betreuung von Transferprojekten.</p>
      </li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Topram Consulting</p>
  </footer>
</body>
</html>
