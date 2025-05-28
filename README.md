<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kelenteng Hai Kim Thua</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC&family=Roboto+Slab:wght@700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      background: linear-gradient(135deg, #600000, #b30000, #800000);
      font-family: 'Noto Serif SC', serif;
      color: #ffd700;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 2rem;
    }
    header h1 {
      font-family: 'Roboto Slab', serif;
      font-size: 3rem;
      color: #ffd700;
      text-shadow: 2px 2px 6px #000;
      margin: 0;
    }
    header h2, header h3 {
      margin: 0.5rem 0;
      color: #fff;
      text-shadow: 1px 1px 4px #000;
    }
    nav {
      text-align: center;
      margin: 1rem;
    }
    nav a {
      color: #ffd700;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .section {
      max-width: 800px;
      margin: 2rem auto;
      padding: 1rem;
      background: rgba(0,0,0,0.6);
      border-radius: 10px;
      box-shadow: 0 0 10px gold;
    }
    .section h2 {
      text-align: center;
      font-family: 'Roboto Slab', serif;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
      justify-items: center;
      align-items: start;
    }
    .gallery img {
      width: 100%;
      max-width: 180px;
      border-radius: 8px;
      border: 2px solid #ffd700;
    }
    .gallery p {
      margin-top: 6px;
      font-size: 0.9rem;
      color: #fff;
      text-shadow: 1px 1px 2px #000;
    }
    .contact-info {
      text-align: center;
      font-size: 1.1rem;
    }
    footer {
      text-align: center;
      margin-top: 2rem;
      padding: 1rem;
      background: rgba(0,0,0,0.7);
      color: #ccc;
    }
    .lantern-rain {
      position: fixed;
      top: -50px;
      width: 20px;
      height: 30px;
      background: red;
      border-radius: 50%;
      opacity: 0.8;
      animation: fall 6s linear infinite;
    }
    @keyframes fall {
      0% { transform: translateY(-50px) rotate(0deg); }
      100% { transform: translateY(100vh) rotate(360deg); }
    }
  </style>
</head>
<body>
  <header>
    <h1>海金壇</h1>
    <h2>Kelenteng Hai Kim Thua</h2>
    <h3>陳府元帥</h3>
  </header>

  <nav>
    <a href="#tentang">Tentang Kami</a>
    <a href="#layanan">Layanan</a>
    <a href="#daftar">Pendaftaran</a>
    <a href="#galeri">Galeri</a>
    <a href="#kontak">Kontak</a>
  </nav>

  <div class="section" id="tentang">
    <h2>Tentang Kami</h2>
    <p>🌸 Kelenteng Hai Kim Thua (海金壇)
Artinya: "Kelenteng Samudra Emas" atau "Tempat Pemuliaan Samudra Emas"

Didirikan pada tahun 2022, Kelenteng Hai Kim Thua merupakan tempat suci yang lahir dari niat tulus untuk menjaga warisan budaya leluhur dan mempererat ikatan spiritual di tengah masyarakat Tionghoa. Nama Hai Kim Thua sendiri mengandung makna mendalam: "Samudra" melambangkan keluasan hati dan kebijaksanaan yang tak berbatas, sementara "Emas" melambangkan kemurnian, kemakmuran, dan nilai kebajikan yang tinggi.

🌸 Dewa Utama yang Disembah:
陳府元帥 (Chen Fu Yuan Shuai)
Dikenal sebagai Jenderal Agung Chen, beliau adalah tokoh spiritual dalam kepercayaan Tao yang dipuja karena keberaniannya melawan kekuatan jahat dan perlindungannya terhadap umat manusia. Sebagai dewa penjaga (zhen shen), beliau sering diasosiasikan dengan nilai-nilai seperti kesetiaan, keberanian, dan pengabdian — prinsip-prinsip luhur dalam ajaran Konfusianisme dan Taoisme.

Dalam tradisi Tionghoa, keberadaan kelenteng bukan sekadar tempat sembahyang, tetapi juga pusat nilai-nilai moral dan sosial. Kelenteng menjadi pengingat bahwa hidup harus dijalani dengan seimbang — antara langit (tian), bumi (di), dan manusia (ren). Oleh karena itu, Kelenteng Hai Kim Thua dibangun tidak hanya untuk menghormati para dewa, tetapi juga untuk menghidupkan kembali semangat gotong royong, penghormatan kepada leluhur, dan pelestarian kebajikan dalam kehidupan sehari-hari.

Dihiasi dengan ornamen klasik dan simbol-simbol keberuntungan, Kelenteng ini menjadi pelabuhan batin bagi mereka yang mencari kedamaian, bimbingan, dan kekuatan dalam menghadapi gelombang kehidupan.


</p>
  </div>

  <div class="section" id="layanan">
    <h2>Layanan</h2>
    <ul>
      <li>Doa Keselamatan & Rejeki</li>
      <li>Pengobatan Non-Medis Tradisional</li>
      <li>Perhitungan Shio & Ramalan</li>
      <li>Pemberkatan Usaha dan Rumah</li>
    </ul>
  </div>
    <div class="daftar"><div class="section" id="daftar">
  <div class="form-container" style="max-width: 450px; margin: 2rem auto; padding: 2rem; background: #d40000; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2); font-family: 'Segoe UI', sans-serif; color: #fff;">
  <h2 style="text-align:center; font-weight:bold; margin-bottom: 1.2rem; font-size: 1.6rem;">Form Pendaftaran Pengobatan Non-Medis</h2>

  <form action="https://formspree.io/f/xeogyljz" method="POST">
    <label>Nama:</label>
    <input type="text" name="nama" placeholder="Nama lengkap" required style="width:100%; padding:10px; margin:8px 0; border:1px solid #fff; border-radius:4px; background:#fff; color:#000;">

    <label>Tanggal Lahir:</label>
    <input type="date" name="tanggal_lahir" required style="width:100%; padding:10px; margin:8px 0; border:1px solid #fff; border-radius:4px; background:#fff; color:#000;">

    <label>Shio:</label>
    <select name="shio" required style="width:100%; padding:10px; margin:8px 0; border:1px solid #fff; border-radius:4px; background:#fff; color:#000;">
      <option value="">Pilih Shio</option>
      <option>Tikus</option>
      <option>Kerbau</option>
      <option>Macan</option>
      <option>Kelinci</option>
      <option>Naga</option>
      <option>Ular</option>
      <option>Kuda</option>
      <option>Kambing</option>
      <option>Monyet</option>
      <option>Ayam</option>
      <option>Anjing</option>
      <option>Babi</option>
    </select>

    <label>Keluhan:</label>
    <textarea name="keluhan" rows="3" placeholder="Keluhan atau masalah yang dihadapi" style="width:100%; padding:10px; margin:8px 0; border:1px solid #fff; border-radius:4px; background:#fff; color:#000;"></textarea>

    <label>Email:</label>
    <input type="email" name="email" placeholder="Email aktif" required style="width:100%; padding:10px; margin:8px 0; border:1px solid #fff; border-radius:4px; background:#fff; color:#000;">

    <label>No. Telepon:</label>
    <input type="tel" name="telepon" placeholder="Nomor telepon" required style="width:100%; padding:10px; margin:8px 0; border:1px solid #fff; border-radius:4px; background:#fff; color:#000;">

    <button type="submit" style="width:100%; padding:12px; margin-top:15px; background:#fff; color:#d40000; border:none; border-radius:4px; font-weight:bold; font-size:1rem; cursor:pointer;">Kirim</button>
  </form>
</div>


  <div class="section" id="galeri">
    <h2>Galeri</h2>
    <div class="gallery">
      <div><img src="https://s14.gifyu.com/images/bxxjV.png" /><p style="text-align:center;">2021</p></div>
      <div><img src="https://s14.gifyu.com/images/bxx0b.png" alt="Altar Utama" /><p style="text-align:center;">SHANG THI KONG 2021</p></div>
      <div><img src="https://s14.gifyu.com/images/bxx0T.png" alt="Lilin Persembahan" /><p style="text-align:center;">2023</p></div>
      <div><img src="https://s14.gifyu.com/images/bxx0G.png" alt="Patung Dewa" /><p style="text-align:center;">陳府元帥</p></div>
      <div><img src="https://s14.gifyu.com/images/bxxjh.png" /><p style="text-align:center;">1999/2025</p></div>
      <div><img src="https://s14.gifyu.com/images/bxxCc.png" alt="Ritual Ramalan" /><p style="text-align:center;">SHANG THI KONG 2023</p></div>
      <div><img src="https://s14.gifyu.com/images/bxxC5.png" alt="Umat Bersembahyang" /><p style="text-align:center;">FOTO BERSAMA USAI PERESMIAN KELENTENG HAI KIM THUA 2023</p></div>
      <div><img src="https://s14.gifyu.com/images/bxxUC.png" alt="Pengobatan Non-Medis" /><p style="text-align:center;">2025
      </p></div>
      <div><img src="https://s14.gifyu.com/images/bxxoi.png" alt="Patung Naga" /><p style="text-align:center;">MEMBER AKTIF (OFF)</p></div>
      <div><img src="https://s14.gifyu.com/images/bxx14.png" alt="Kelenteng di Malam Hari" /><p style="text-align:center;">PELANTIKKAN KITONG BARU DI HAI KIM THUA 2025</p></div>
    </div>
  </div>

  <div class="section" id="kontak">
    <h2>Kontak & Lokasi</h2>
    <div class="contact-info">
      <p>Alamat: <a href="https://maps.app.goo.gl/MAHL2CeWAG4ziu3Z6" target="_blank" style="color: #ffd700; text-decoration: underline;">Jl. Titi Pahlawan, Perumahan Bumi Marelan Permai Blok A21 Medan Marelan</a></p>
      <p>Telepon: 0822-7417-0248</p>
      <p>Email: haikimthua@gmail.com</p>
      <p>Instagram: @kelentenghaikimthua</p>
    </div>
  </div>

  <footer>
    &copy; 2025 Kelenteng Hai Kim Thua. Semua hak cipta dilindungi.
  </footer>

  <script>
    for (let i = 0; i < 25; i++) {
      let lampion = document.createElement("div");
      lampion.className = "lantern-rain";
      lampion.style.left = Math.random() * 100 + "vw";
      lampion.style.animationDuration = (3 + Math.random() * 4) + "s";
      lampion.style.opacity = Math.random();
      document.body.appendChild(lampion);
    }
  </script>
</body>
</html>
