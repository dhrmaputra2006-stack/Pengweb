
   Krem #f6ecd9 | Coklat #5b3a29 | Mustard #c8963e
   Rose #c97b7b | Sage #7d8f69

/* ---------- Dasar ---------- */
body {
  margin: 0;
  padding: 0;
  width: 100%;
  background-color: #f6ecd9;
  color: #5b3a29;
  font-family: Georgia, "Times New Roman", serif;
  line-height: 1.7;
  font-size: 17px;
}

a { color: #9c4a55; text-decoration: none; }
a:hover { text-decoration: underline; }
img { display: block; }
table { border-collapse: collapse; }
ul { margin: 0; padding: 0; list-style-type: none; }
h1, h2, h3 { font-weight: normal; margin: 0; }

.lebar-penuh { width: 100%; }

/* ---------- Header ---------- */
.header {
  background-color: #efe0c2;
  border-bottom: 4px double #5b3a29;
}
.header > table { padding: 0 8%; }
.header-logo { width: 30%; padding: 22px 0 22px 8%; }
.header-menu { text-align: center; }
.header-cta { width: 30%; text-align: right; padding-right: 8%; }

.logo {
  font-size: 34px;
  color: #5b3a29;
}
.logo i { color: #c8963e; }

.menu li {
  display: inline-block;
  margin: 0 16px;
}
.menu a {
  color: #5b3a29;
  font-size: 16px;
  letter-spacing: 2px;
  text-transform: uppercase;
  padding-bottom: 3px;
  border-bottom: 1px solid #efe0c2;
}
.menu a:hover { border-bottom: 1px solid #c8963e; text-decoration: none; }

.tombol-cta {
  display: inline-block;
  padding: 10px 22px;
  background-color: #c8963e;
  color: #fff8e8;
  border: 2px solid #5b3a29;
  border-radius: 30px;
  font-size: 15px;
  font-style: italic;
  white-space: nowrap;
  text-align: center;
}
.tombol-cta:hover { background-color: #5b3a29; text-decoration: none; }

/* ---------- Hero ---------- */
.hero {
  height: 340px;
  padding: 60px 8% 0 8%;
  background-color: #e9d5b0;
  background-image: url("images/storefront.jpeg");
  background-size: cover;
  background-position: center;
  border-top: 1px solid #5b3a29;
}
.kecil-atas {
  margin: 0 0 12px 0;
  font-size: 14px;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: #9c4a55;
}
.hero h1 {
  font-size: 64px;
  line-height: 1.1;
  color: #5b3a29;
}
.teks-hero {
  width: 45%;
  margin: 18px 0 0 0;
  font-size: 19px;
}

/* ---------- Bagian umum ---------- */
.isi { width: 100%; }
.bagian {
  padding: 70px 8%;
  text-align: center;
}
.bagian-krem {
  background-color: #efe0c2;
  border-top: 1px solid #5b3a29;
  border-bottom: 1px solid #5b3a29;
}
.label {
  margin: 0;
  font-size: 14px;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: #9c4a55;
}
.bagian h2 {
  margin-top: 6px;
  font-size: 44px;
  color: #5b3a29;
}
.garis {
  width: 120px;
  height: 0;
  margin: 18px auto 36px auto;
  border: 0;
  border-top: 4px double #c8963e;
}

/* ---------- Best Seller ---------- */
.tabel-best { table-layout: fixed; }
.sel-best { width: 25%; padding: 10px; vertical-align: top; }
.kartu {
  padding: 12px 12px 18px 12px;
  background-color: #fff8e8;
  border: 1px solid #5b3a29;
  outline: 1px solid #c8963e;
  outline-offset: -7px;
}
.gambar {
  width: 100%;
  height: 260px;
  border: 1px solid #5b3a29;
}
.kartu h3 {
  margin-top: 14px;
  font-size: 21px;
  font-style: italic;
  color: #5b3a29;
}

/* ---------- Tabel Menu ---------- */
blockquote {
  width: 50%;
  margin: 0 auto 30px auto;
  padding: 6px 20px;
  border-left: 4px solid #c8963e;
  border-right: 4px solid #c8963e;
  font-style: italic;
  font-size: 19px;
  color: #9c4a55;
}
.tabel-menu {
  width: 70%;
  margin: 0 auto;
  background-color: #fff8e8;
  border: 3px double #5b3a29;
}
.tabel-menu caption {
  padding-bottom: 10px;
  font-size: 14px;
  letter-spacing: 3px;
  text-transform: uppercase;
  caption-side: bottom;
  margin-top: 10px;
}
.tabel-menu th {
  padding: 14px;
  background-color: #5b3a29;
  color: #fff8e8;
  font-weight: normal;
  letter-spacing: 3px;
  text-transform: uppercase;
  font-size: 15px;
}
.tabel-menu td {
  padding: 12px 14px;
  border-bottom: 1px dashed #c8963e;
}
.tabel-menu td:nth-child(2) { text-align: left; }
.tabel-menu tbody tr:nth-child(even) { background-color: #f6ecd9; }
.tabel-menu tbody tr:hover { background-color: #efe0c2; }
.kolom-no { width: 70px; }
.kolom-harga { width: 160px; }

/* ---------- Form ---------- */
.form {
  width: 55%;
  margin: 0 auto;
  padding: 36px 40px;
  text-align: left;
  background-color: #fff8e8;
  border: 3px double #5b3a29;
}
.form label {
  display: block;
  margin: 16px 0 6px 0;
  font-size: 15px;
  letter-spacing: 1px;
  text-transform: uppercase;
  color: #5b3a29;
}
.form input[type="text"],
.form input[type="tel"],
.form input[type="number"],
.form input[type="date"],
.form select,
.form textarea {
  width: 100%;
  box-sizing: border-box;
  padding: 11px 14px;
  background-color: #f6ecd9;
  border: 1px solid #5b3a29;
  color: #5b3a29;
  font-family: Georgia, "Times New Roman", serif;
  font-size: 16px;
}
.judul-radio {
  margin: 16px 0 6px 0;
  font-size: 15px;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.form label.radio {
  display: inline-block;
  margin: 0 20px 0 6px;
  text-transform: none;
  font-size: 17px;
  letter-spacing: 0;
}
.form .kirim {
  display: block;
  width: 100%;
  margin-top: 30px;
  padding: 14px;
  background-color: #5b3a29;
  color: #fff8e8;
  border: 2px solid #5b3a29;
  font-family: Georgia, "Times New Roman", serif;
  font-size: 17px;
  letter-spacing: 3px;
  text-transform: uppercase;
}
.form .kirim:hover { background-color: #c8963e; }

/* ---------- Footer ---------- */
.footer {
  padding: 60px 8% 20px 8%;
  background-color: #5b3a29;
  color: #f6ecd9;
  border-top: 6px double #c8963e;
}
.tabel-footer { table-layout: fixed; }
.kolom-footer {
  width: 33%;
  padding: 0 30px 0 0;
  vertical-align: top;
  font-size: 16px;
}
.kolom-footer h3 {
  margin-bottom: 10px;
  padding-bottom: 8px;
  border-bottom: 1px solid #c8963e;
  font-size: 24px;
  font-style: italic;
  color: #e8c27a;
}
.kolom-footer p { margin: 10px 0; }
.footer a { color: #e8c27a; }
.kontak li { margin-bottom: 4px; }
.hak-cipta {
  margin: 40px 0 0 0;
  padding-top: 16px;
  border-top: 1px solid #c8963e;
  text-align: center;
  letter-spacing: 1px;
}

/* ---------- Media (layar kecil / HP) ---------- */
@media (max-width: 899px) {
  .header-logo, .header-menu, .header-cta {
    display: block;
    width: auto;
    padding: 12px 6%;
    text-align: center;
  }
  .menu li { margin: 0 8px; }
  .hero { height: auto; padding: 40px 6% 40px 6%; }
  .hero h1 { font-size: 40px; }
  .teks-hero { width: 100%; }
  .bagian { padding: 50px 6%; }
  .sel-best { display: inline-block; width: 46%; }
  .tabel-best, .tabel-best tbody, .tabel-best tr { display: block; }
  blockquote { width: 90%; }
  .tabel-menu { width: 100%; }
  .form { width: 88%; padding: 24px 20px; }
  .tabel-footer, .tabel-footer tbody, .tabel-footer tr, .kolom-footer {
    display: block;
    width: auto;
  }
  .kolom-footer { padding: 0 0 30px 0; }
}
