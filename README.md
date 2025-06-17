# undangan.github.io
Undangangan Pernikahan 
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Undangan Pernikahan</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #fff0f5;
      color: #333;
      margin: 0;
      padding: 30px;
      text-align: center;
    }
    .card {
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      display: inline-block;
      max-width: 500px;
    }
    img {
      width: 100%;
      border-radius: 15px;
      margin-bottom: 20px;
    }
    h1 {
      color: #d6336c;
    }
    .btn {
      display: inline-block;
      padding: 12px 25px;
      background: #d6336c;
      color: white;
      border: none;
      border-radius: 10px;
      text-decoration: none;
      margin: 10px;
      font-weight: bold;
    }
    .btn:hover {
      background: #b62b5a;
    }
    #notif {
      margin-top: 10px;
      color: green;
    }
  </style>
</head>
<body>

  <div class="card">
    <img src="foto.jpg" alt="Foto Mempelai">
    <h1>Undangan Pernikahan</h1>
    <h2>Memet & Siti</h2>
    <p>Dengan penuh cinta dan kebahagiaan, kami mengundang Anda untuk menghadiri hari istimewa kami.</p>

    <p><strong>Tanggal:</strong> Minggu, 25 Agustus 2025</p>
    <p><strong>Waktu:</strong> 10.00 WIB - selesai</p>
    <p><strong>Lokasi:</strong> Gedung Serbaguna Cinta Abadi, Bekasi</p>

    <a class="btn" href="https://maps.google.com/?q=Gedung Serbaguna Cinta Abadi, Bekasi" target="_blank">Lihat Lokasi</a>
    <br><br>

    <a class="btn" href="https://wa.me/6281234567890" target="_blank">Hubungi Mempelai</a>
    <a class="btn" onclick="salinRekening()">Salin Rekening</a>
    <p id="notif"></p>
  </div>

  <script>
    function salinRekening() {
      const rekening = "1234567890 (BCA a.n. Memet)";
      navigator.clipboard.writeText(rekening).then(function() {
        document.getElementById('notif').innerText = "Nomor rekening disalin ke clipboard!";
      });
    }
  </script>

</body>
</html><!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Undangan Pernikahan</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #fff0f5;
      color: #333;
      margin: 0;
      padding: 30px;
      text-align: center;
    }
    .card {
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      display: inline-block;
      max-width: 500px;
    }
    img {
      width: 100%;
      border-radius: 15px;
      margin-bottom: 20px;
    }
    h1 {
      color: #d6336c;
    }
    .btn {
      display: inline-block;
      padding: 12px 25px;
      background: #d6336c;
      color: white;
      border: none;
      border-radius: 10px;
      text-decoration: none;
      margin: 10px;
      font-weight: bold;
    }
    .btn:hover {
      background: #b62b5a;
    }
    #notif {
      margin-top: 10px;
      color: green;
    }
  </style>
</head>
<body>

  <div class="card">
    <img src="foto.jpg" alt="Foto Mempelai">
    <h1>Undangan Pernikahan</h1>
    <h2>Memet & Siti</h2>
    <p>Dengan penuh cinta dan kebahagiaan, kami mengundang Anda untuk menghadiri hari istimewa kami.</p>

    <p><strong>Tanggal:</strong> Minggu, 25 Agustus 2025</p>
    <p><strong>Waktu:</strong> 10.00 WIB - selesai</p>
    <p><strong>Lokasi:</strong> Gedung Serbaguna Cinta Abadi, Bekasi</p>

    <a class="btn" href="https://maps.google.com/?q=Gedung Serbaguna Cinta Abadi, Bekasi" target="_blank">Lihat Lokasi</a>
    <br><br>

    <a class="btn" href="https://wa.me/6281234567890" target="_blank">Hubungi Mempelai</a>
    <a class="btn" onclick="salinRekening()">Salin Rekening</a>
    <p id="notif"></p>
  </div>

  <script>
    function salinRekening() {
      const rekening = "1234567890 (BCA a.n. Memet)";
      navigator.clipboard.writeText(rekening).then(function() {
        document.getElementById('notif').innerText = "Nomor rekening disalin ke clipboard!";
      });
    }
  </script>

</body>
</html>
