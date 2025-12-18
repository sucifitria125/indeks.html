<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VisionPay | Alat Pendeteksi Uang untuk Tunanetra</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body { margin:0; font-family:'Poppins', sans-serif; background:#f4f6f8; color:#333; }
    header { background:#0a3d62; color:#fff; padding:60px 20px; text-align:center; }
    header h1 { font-size:42px; margin-bottom:10px; }
    header p { font-size:18px; }
    nav { background:#082f49; padding:10px; text-align:center; }
    nav a { color:#fff; margin:0 15px; text-decoration:none; font-weight:500; }
    section { padding:60px 10%; }
    .card { background:#fff; padding:30px; border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.08); margin-bottom:30px; }
    h2 { color:#0a3d62; }
    ul li { margin-bottom:8px; }
    footer { background:#082f49; color:#fff; text-align:center; padding:20px; }
    .btn { display:inline-block; background:#0a3d62; color:#fff; padding:12px 20px; border-radius:8px; text-decoration:none; }
  </style>
</head>
<body>

<header>
  <h1>VisionPay</h1>
  <p>Alat Pendeteksi Nominal Uang Otomatis untuk Tunanetra Berbasis ESP32-CAM</p>
</header>

<nav>
  <a href="#tentang">Tentang</a>
  <a href="#fitur">Fitur</a>
  <a href="#teknologi">Teknologi</a>
  <a href="#hasil">Hasil</a>
  <a href="#kontak">Kontak</a>
</nav>

<section id="tentang">
  <div class="card">
    <h2>Tentang VisionPay</h2>
    <p>VisionPay adalah perangkat assistive technology yang dirancang untuk membantu penyandang tunanetra mengenali nominal uang kertas Rupiah secara mandiri. Sistem ini menggunakan kamera ESP32-CAM dan algoritma kecerdasan buatan berbasis Convolutional Neural Network (CNN) dengan output suara.</p>
  </div>
</section>

<section id="fitur">
  <div class="card">
    <h2>Fitur Utama</h2>
    <ul>
      <li>Deteksi otomatis nominal uang Rupiah</li>
      <li>Output suara real-time</li>
      <li>Berjalan secara offline (tanpa internet)</li>
      <li>Desain portabel dan hemat daya</li>
      <li>Mudah digunakan oleh tunanetra</li>
    </ul>
  </div>
</section>

<section id="teknologi">
  <div class="card">
    <h2>Teknologi yang Digunakan</h2>
    <ul>
      <li>ESP32-CAM + Kamera OV2640</li>
      <li>Machine Learning (CNN & TensorFlow Lite)</li>
      <li>Amplifier Audio PAM8403 & Speaker Mini</li>
      <li>Baterai Li-Po & Modul Charger TP4056</li>
    </ul>
  </div>
</section>

<section id="hasil">
  <div class="card">
    <h2>Hasil Pengujian</h2>
    <p>VisionPay mampu mengenali nominal uang Rupiah dengan akurasi rata-rata ±87–93% pada berbagai kondisi pencahayaan, dengan waktu respon sekitar 2–3 detik dan durasi penggunaan hingga 4–6 jam.</p>
  </div>
</section>

<section id="kontak">
  <div class="card">
    <h2>Kontak & Repository</h2>
    <p>Proyek Capstone Design Teknik Biomedis – Institut Teknologi Sumatera</p>
    <a class="btn" href="https://github.com/username/visionpay" target="_blank">GitHub Repository</a>
  </div>
</section>

<footer>
  <p>© 2025 VisionPay | Teknik Biomedis ITERA</p>
</footer>

</body>
</html>
