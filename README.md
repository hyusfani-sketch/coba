<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Profil Instansi</title>
<style>
body {
    margin:0;
    font-family: Arial, sans-serif;
}

/* HEADER */
header {
    background:#004080;
    color:white;
    padding:15px;
    text-align:center;
}

/* MENU */
nav {
    background:#0066cc;
    padding:10px;
    text-align:center;
}
nav a {
    color:white;
    margin:0 15px;
    text-decoration:none;
    font-weight:bold;
}

/* BANNER */
.banner {
    background:#e6f2ff;
    padding:50px;
    text-align:center;
}
.banner h1 {
    margin:0;
}

/* SECTION */
.section {
    padding:30px;
}
.section h2 {
    color:#004080;
}

/* BOX LAYANAN */
.box {
    display:flex;
    gap:20px;
    flex-wrap:wrap;
}
.card {
    flex:1;
    min-width:200px;
    background:#f2f2f2;
    padding:20px;
    border-radius:10px;
}

/* FOOTER */
footer {
    background:#004080;
    color:white;
    text-align:center;
    padding:10px;
}
</style>
</head>

<body>

<header>
    <h1>DINAS PERHUBUNGAN</h1>
    <p>Kabupaten Kutai Timur</p>
</header>

<nav>
    <a href="#">Beranda</a>
    <a href="#">Profil</a>
    <a href="#">Layanan</a>
    <a href="#">Kontak</a>
</nav>

<div class="banner">
    <h1>Selamat Datang</h1>
    <p>Website Resmi Dinas Perhubungan</p>
</div>

<div class="section">
    <h2>Profil</h2>
    <p>Dinas Perhubungan bertugas mengelola transportasi dan pelayanan publik di bidang perhubungan.</p>
</div>

<div class="section">
    <h2>Layanan</h2>
    <div class="box">
        <div class="card">Uji Kendaraan</div>
        <div class="card">Perizinan</div>
        <div class="card">Manajemen Lalu Lintas</div>
    </div>
</div>

<div class="section">
    <h2>Kontak</h2>
    <p>Email: dishub@email.com</p>
    <p>Telp: 08xxxxxxx</p>
</div>

<footer>
    <p>© 2026 Dinas Perhubungan</p>
</footer>

</body>
</html>
