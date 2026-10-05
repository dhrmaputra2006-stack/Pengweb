<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pastie Bestie - Toko Pastry Vintage</title>
  <!-- Favicon -->
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Ccircle cx='32' cy='32' r='30' fill='%23c8963e'/%3E%3Ctext x='32' y='43' font-size='30' text-anchor='middle' fill='%23fff8e8' font-family='Georgia' font-style='italic'%3EPB%3C/text%3E%3C/svg%3E">
  <link rel="stylesheet" href="baru.css">
</head>
<body>

<!-- ================= HEADER ================= -->
<div class="header" id="home">
  <table class="lebar-penuh">
    <tr>
      <td class="header-logo">
        <!-- Logo berbentuk teks -->
        <a href="#home" class="logo"><i>Pastie</i> Bestie</a>
      </td>
      <td class="header-menu">
        <ul class="menu">
          <li><a href="#home">Home</a></li>
          <li><a href="#product">Product</a></li>
          <li><a href="#outlet">Outlet</a></li>
          <li><a href="#tentang">Tentang</a></li>
        </ul>
      </td>
      <td class="header-cta">
        <!-- Call to Action unik -->
        <a href="#pesan" class="tombol-cta">Gigit Dulu, Mikir Belakangan!</a>
      </td>
    </tr>
  </table>

  <div class="hero">
    <p class="kecil-atas">&mdash; Est. 2024 &mdash; Pastry &amp; Teman Ngopi &mdash;</p>
    <h1>Manisnya Pas,<br>Rasanya Berkelas</h1>
    <p class="teks-hero">Pastry hangat yang dipanggang setiap pagi dengan mentega asli dan resep klasik, untuk menemani ceritamu hari ini.</p>
  </div>
</div>

<!-- ================= BODY ================= -->
<div class="isi">

  <!-- ===== Best Seller ===== -->
  <div class="bagian" id="product">
    <p class="label">Pilihan Favorit</p>
    <h2>Best Seller</h2>
    <hr class="garis">

    <table class="lebar-penuh tabel-best">
      <tr>
        <td class="sel-best">
          <div class="kartu">
            <img src="images/croissant.jpeg" alt="Butter Croissant" class="gambar">
            <h3>Butter Croissant</h3>
          </div>
        </td>
        <td class="sel-best">
          <div class="kartu">
            <img src="images/cinnamonroll.jpeg" alt="Cinnamon Roll" class="gambar">
            <h3>Cinnamon Roll</h3>
          </div>
        </td>
        <td class="sel-best">
          <div class="kartu">
            <img src="images/cromboloni.jpeg" alt="Cromboloni" class="gambar">
            <h3>Cromboloni</h3>
          </div>
        </td>
        <td class="sel-best">
          <div class="kartu">
            <img src="images/puffpastry.jpeg" alt="Puff Pastry" class="gambar">
            <h3>Puff Pastry</h3>
          </div>
        </td>
      </tr>
    </table>
  </div>

  <!-- ===== Menu Pastie Bestie ===== -->
  <div class="bagian bagian-krem" id="menu">
    <p class="label">Daftar Hidangan</p>
    <h2>Menu Pastie Bestie</h2>
    <hr class="garis">

    <blockquote>
      &ldquo;Hidup itu singkat, makan pastry dulu.&rdquo;
    </blockquote>

    <table class="tabel-menu">
      <caption>Daftar menu &amp; harga per item</caption>
      <thead>
        <tr>
          <th class="kolom-no">No</th>
          <th>Daftar Menu</th>
          <th class="kolom-harga">Harga</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>1</td><td>Butter Croissant</td><td>Rp 25.000</td></tr>
        <tr><td>2</td><td>Pain au Chocolat</td><td>Rp 28.000</td></tr>
        <tr><td>3</td><td>Almond Danish</td><td>Rp 30.000</td></tr>
        <tr><td>4</td><td>Cinnamon Roll</td><td>Rp 32.000</td></tr>
        <tr><td>5</td><td>Apple Turnover</td><td>Rp 35.000</td></tr>
        <tr><td>6</td><td>Strawberry Tart</td><td>Rp 40.000</td></tr>
        <tr><td>7</td><td>Lemon Tart</td><td>Rp 42.000</td></tr>
        <tr><td>8</td><td>Eclair Vanilla</td><td>Rp 45.000</td></tr>
        <tr><td>9</td><td>Mille-Feuille</td><td>Rp 55.000</td></tr>
        <tr><td>10</td><td>Paris-Brest</td><td>Rp 60.000</td></tr>
      </tbody>
    </table>
  </div>

  <!-- ===== Form Pemesanan ===== -->
  <div class="bagian" id="pesan">
    <p class="label">Pesan Sekarang</p>
    <h2>Form Pemesanan</h2>
    <hr class="garis">

    <form class="form" action="#" method="post">

      <label for="nama">Nama</label>
      <input type="text" id="nama" name="nama" placeholder="Nama lengkap kamu">

      <label for="wa">Nomor WhatsApp</label>
      <input type="tel" id="wa" name="wa" placeholder="08xxxxxxxxxx">

      <label for="menu-pilihan">Pilih Menu</label>
      <select id="menu-pilihan" name="menu">
        <option value="">-- Pilih menu --</option>
        <option>Butter Croissant - Rp 25.000</option>
        <option>Pain au Chocolat - Rp 28.000</option>
        <option>Almond Danish - Rp 30.000</option>
        <option>Cinnamon Roll - Rp 32.000</option>
        <option>Apple Turnover - Rp 35.000</option>
        <option>Strawberry Tart - Rp 40.000</option>
        <option>Lemon Tart - Rp 42.000</option>
        <option>Eclair Vanilla - Rp 45.000</option>
        <option>Mille-Feuille - Rp 55.000</option>
        <option>Paris-Brest - Rp 60.000</option>
      </select>

      <label for="jumlah">Jumlah</label>
      <input type="number" id="jumlah" name="jumlah" min="1" value="1">

      <label for="alamat">Alamat Pengiriman</label>
      <textarea id="alamat" name="alamat" rows="3" placeholder="Tulis alamat lengkap"></textarea>

      <label for="tanggal">Tanggal Pengambilan</label>
      <input type="date" id="tanggal" name="tanggal">

      <p class="judul-radio">Metode Pembayaran</p>
      <input type="radio" id="cash" name="bayar" value="cash" checked>
      <label for="cash" class="radio">Cash</label>
      <input type="radio" id="qris" name="bayar" value="qris">
      <label for="qris" class="radio">QRIS</label>
      <input type="radio" id="transfer" name="bayar" value="transfer">
      <label for="transfer" class="radio">Transfer Bank</label>

      <label for="catatan">Catatan</label>
      <textarea id="catatan" name="catatan" rows="3" placeholder="Contoh: tanpa kacang, tolong dikemas rapi"></textarea>

      <input type="submit" value="Kirim Pesanan" class="kirim">
    </form>
  </div>

</div>

<!-- ================= FOOTER ================= -->
<div class="footer">

  <table class="lebar-penuh tabel-footer">
    <tr>
      <!-- Outlet Kami -->
      <td class="kolom-footer" id="outlet">
        <h3>Outlet Kami</h3>
        <p><a href="https://www.google.com/maps/search/?api=1&amp;query=Ciputat+Tangerang+Selatan" target="_blank">Lihat di Google Maps &rarr;</a></p>
        <p>Jl. Ir. H. Juanda No. 12, Ciputat, Tangerang Selatan, Banten 15412. Letaknya di samping toko buku, bersebelahan dengan taman kecil. Buka setiap hari pukul 08.00 &ndash; 21.00 WIB.</p>
      </td>

      <!-- Dokumentasi Toko Kami -->
      <td class="kolom-footer">
        <h3>Dokumentasi Toko Kami</h3>
        <p><a href="https://www.youtube.com/" target="_blank">Tonton video di YouTube &rarr;</a></p>
        <p>Di toko kami, oven lebih rajin dari kami, croissant lebih berlapis dari rencana hidup, dan aroma mentega selalu sukses bikin dompet dan hati luluh bersamaan.</p>
      </td>

      <!-- Tentang -->
      <td class="kolom-footer" id="tentang">
        <h3>Tentang</h3>
        <p>Pastie Bestie adalah toko pastry bergaya klasik yang percaya bahwa hal-hal sederhana, seperti pastry hangat dan teman yang tepat, bisa membuat hari terasa lebih manis.</p>
        <ul class="kontak">
          <li><b>WhatsApp:</b> 0812-3456-7890</li>
          <li><b>Email:</b> <a href="mailto:halo@pastiebestie.id">halo@pastiebestie.id</a></li>
          <li><b>Instagram:</b> <a href="#">@pastiebestie</a></li>
          <li><b>TikTok:</b> <a href="#">@pastiebestie</a></li>
        </ul>
      </td>
    </tr>
  </table>

  <p class="hak-cipta"><small>&copy; 2026 Pastie Bestie. Seluruh hak cipta dilindungi.</small></p>
</div>

</body>
</html>
