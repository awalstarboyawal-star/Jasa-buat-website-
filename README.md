# Jasa-buat-website-
Disini kalian akan di buatkan sebuah website sesuai budget yang kalian kirim 
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Profil Cahyadi</title>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Outfit', sans-serif;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: #fff;
      padding: 2rem;
    }
    header {
      text-align: center;
      margin-bottom: 2rem;
    }
    header h1 {
      font-size: 3rem;
      color: #00ffff;
    }
    header p {
      font-size: 1.2rem;
      color: #ddd;
    }
    .container {
      max-width: 800px;
      margin: auto;
      background: rgba(255, 255, 255, 0.05);
      padding: 2rem;
      border-radius: 15px;
      box-shadow: 0 0 10px rgba(0, 255, 255, 0.2);
    }
    section {
      margin-bottom: 2rem;
    }
    h2 {
      color: #00ffff;
      margin-bottom: 0.5rem;
    }
    ul {
      list-style: none;
      padding-left: 1rem;
    }
    ul li::before {
      content: "🔹";
      margin-right: 0.5rem;
    }
    a {
      color: #00ffff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    input, textarea {
      padding: 10px;
      margin: 8px 0;
      border-radius: 8px;
      border: none;
      outline: none;
      font-size: 1rem;
    }
    button {
      background-color: #00ffff;
      color: #000;
      border: none;
      padding: 10px;
      font-weight: bold;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      background-color: #00dddd;
    }
    .paket {
      background: rgba(0, 255, 255, 0.1);
      padding: 1rem;
      border-radius: 10px;
    }
    .paket ul li {
      margin-bottom: 0.5rem;
      font-size: 1.1rem;
    }
    .harga {
      font-weight: bold;
      color: #00ffcc;
    }
    footer {
      text-align: center;
      margin-top: 2rem;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>Cahyadi</h1>
    <p>Editor ✦ Programmer ✦ Kreator Digital</p>
  </header>

  <div class="container">
    <section>
      <h2>Tentang Saya</h2>
      <p>Halo, saya Cahyadi! Saya seorang kreator digital yang ahli dalam editing (foto & video) dan juga berpengalaman dalam pemrograman website dan aplikasi. Saya suka menciptakan karya visual yang menarik dan membangun solusi digital yang efisien.</p>
    </section>

    <section>
      <h2>Hobi & Keahlian</h2>
      <ul>
        <li>Editing (Foto & Video)</li>
        <li>Web Design & Development</li>
        <li>HTML, CSS, JavaScript</li>
      </ul>
    </section>

    <section>
      <h2>Paket Jasa</h2>
      <div class="paket">
        <ul>
          <li>Paket Hemat - <span class="harga">Rp100.000</span></li>
          <li>Paket Standar - <span class="harga">Rp1.500.000</span></li>
          <li>Paket VIP - <span class="harga">Rp2.000.000</span></li>
        </ul>
      </div>
    </section>

    <section>
      <h2>Sosial Media</h2>
      <p>📺 YouTube: <a href="https://www.youtube.com/@Ceritaawal1" target="_blank">Cerita Awal</a></p>
    </section>

    <section>
      <h2>Kontak Saya</h2>
      <form action="https://wa.me/6287775671827" target="_blank">
        <label for="name">Nama Kamu</label>
        <input type="text" id="name" name="name" placeholder="Nama kamu..." required />

        <label for="message">Pesan</label>
        <textarea id="message" name="message" rows="4" placeholder="Tulis pesanmu..." required></textarea>

        <button type="submit">Kirim ke WhatsApp</button>
      </form>
    </section>
  </div>

  <footer>
    &copy; 2025 Cahyadi | Dibuat dengan semangat
  </footer>
</body>
</html>
