<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Gebrüder H&H Transporte</title>
  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", sans-serif;
      background-color: #f5f5f5;
      color: #333;
    }
    header {
      background-color: #1e1e1e;
      color: white;
      padding: 30px 0;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    main {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }
    section {
      margin-bottom: 50px;
    }
    h2 {
      border-bottom: 2px solid #ddd;
      padding-bottom: 5px;
    }
    img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin-top: 20px;
    }
    footer {
      background-color: #1e1e1e;
      color: white;
      text-align: center;
      padding: 20px 0;
      margin-top: 60px;
    }
    .contact, .impressum {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      padding: 10px 20px;
      background: #333;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    iframe {
      width: 100%;
      height: 300px;
      border: none;
      margin-top: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Gebrüder H&H Transporte</h1>
  <nav>
    <a href="#ueberuns">Über uns</a>
    <a href="#kontakt">Kontakt</a>
    <a href="#impressum">Impressum</a>
  </nav>
</header>

<main>

  <section id="ueberuns">
    <h2>Über uns</h2>
    <p>Wir sind ein zuverlässiges Transportunternehmen mit Sitz in Österreich, spezialisiert auf nationale und internationale Transporte. Unsere Flotte ist modern ausgestattet und unser Team arbeitet schnell, sicher und effizient.</p>
    <p>Das Unternehmen wird von zwei erfahrenen Brüdern geführt, die täglich mit vollem Einsatz hinter dem Steuer und in der Planung stehen.</p>
    <img src="https://via.placeholder.com/900x400?text=Teamfoto+der+Geschäftsführer" alt="Teamfoto Geschäftsführer">
  </section>

  <section id="kontakt" class="contact">
    <h2>Kontakt</h2>
    <p><strong>Adresse:</strong> Musterstraße 12, 1234 Beispielstadt</p>
    <p><strong>Telefon:</strong> +43 123 456 789</p>
    <p><strong>E-Mail:</strong> <a href="mailto:info@transportfirma.at">info@transportfirma.at</a></p>

    <form action="#" method="post">
      <input type="text" name="name" placeholder="Ihr Name" required>
      <input type="email" name="email" placeholder="Ihre E-Mail" required>
      <textarea name="nachricht" rows="5" placeholder="Ihre Nachricht" required></textarea>
      <button type="submit">Nachricht senden</button>
    </form>

    <iframe 
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2656.738143133587!2d13.033553315650535!3d47.74928397919252!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47769f6039a443d5%3A0x61d81c1b4a5aa3d1!2sGr%C3%B6dig%2C%20%C3%96sterreich!5e0!3m2!1sde!2sat!4v1712700000000"
      allowfullscreen
      loading="lazy">
    </iframe>
  </section>

  <section id="impressum" class="impressum">
    <h2>Impressum</h2>
    <p><strong>Firma:</strong> Gebrüder H&H Transporte OG</p>
    <p><strong>Geschäftsführer:</strong> Max Mustermann, Maxine Musterfrau</p>
    <p><strong>Firmenbuchnummer:</strong> FN 123456x</p>
    <p><strong>UID:</strong> ATU12345678</p>
    <p><strong>Adresse:</strong> Musterstraße 12, 1234 Beispielstadt</p>
  </section>

</main>

<footer>
  &copy; 2025 Gebrüder H&H Transporte – Alle Rechte vorbehalten
</footer>

</body>
</html>
