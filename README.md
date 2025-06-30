# Pondok Pesantren Darul Amien

Website sederhana untuk Pondok Pesantren Darul Amien menggunakan HTML & CSS.

## Fitur

- Profil pondok
- Jadwal kegiatan
- Kontak WhatsApp dan Email
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pondok Pesantren Darul Amien</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Pondok Pesantren Darul Amien</h1>
    <p>Menuntut Ilmu, Membentuk Akhlak Mulia</p>
  </header>

  <main>
    <section>
      <h2>Tentang Kami</h2>
      <p>Pondok Pesantren Darul Amien adalah lembaga pendidikan Islam modern yang membina generasi Qur’ani, cerdas, dan berakhlak mulia.</p>
    </section>

    <section>
      <h2>Jadwal Kegiatan</h2>
      <ul>
        <li>04:00 - Qiyamul Lail & Subuh</li>
        <li>07:00 - Belajar Pagi</li>
        <li>12:00 - Dzuhur & Istirahat</li>
        <li>14:00 - Belajar Sore</li>
        <li>18:00 - Maghrib & Mengaji</li>
        <li>20:00 - Isya & Istirahat</li>
      </ul>
    </section>

    <section>
      <h2>Hubungi Kami</h2>
      <p>📍 Alamat: Jl. Pesantren No. 123, Kabupaten Asri</p>
      <p>📞 WhatsApp: <a href="https://wa.me/6281234567890" target="_blank">0812-3456-7890</a></p>
      <p>✉️ Email: info@darulamien.sch.id</p>
    </section>
  </main>

  <footer>
    &copy; 2025 Pondok Pesantren Darul Amien
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f3f3f3;
  color: #333;
}

header {
  background-color: #2e7d32;
  color: white;
  padding: 30px;
  text-align: center;
}

main {
  padding: 20px;
  max-width: 800px;
  margin: auto;
}

section {
  margin-bottom: 40px;
}

footer {
  background-color: #1b1b1b;
  color: white;
  text-align: center;
  padding: 10px;
}
a {
  color: #2e7d32;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
