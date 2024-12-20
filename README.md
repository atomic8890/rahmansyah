
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal Berita Indonesia</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #e74c3c;
            color: #fff;
            padding: 15px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #c0392b;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 15px 20px;
            display: block;
            font-size: 1.1em;
        }
        nav a:hover {
            background-color: #a93226;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        .news {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .news-item {
            flex: 1 1 calc(33.333% - 20px);
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            overflow: hidden;
            background-color: #fff;
        }
        .news-item img {
            width: 100%;
            height: auto;
        }
        .news-item h2 {
            font-size: 20px;
            margin: 10px;
            color: #e74c3c;
        }
        .news-item p {
            font-size: 14px;
            margin: 0 10px 10px;
        }
        footer {
            text-align: center;
            padding: 15px;
            background-color: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Portal Berita Indonesia</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Nasional</a>
        <a href="#">Internasional</a>
        <a href="#">Olahraga</a>
        <a href="#">Hiburan</a>
    </nav>
    <div class="container">
        <div class="news">
            <div class="news-item">
                <img src="https://via.placeholder.com/300x200" alt="Berita Gempa">
                <h2>Gempa Bumi Mengguncang Indonesia</h2>
                <p>Gempa berkekuatan 6,5 SR melanda wilayah Indonesia bagian Timur. Banyak warga yang mengungsi ke tempat aman.</p>
            </div>
            <div class="news-item">
                <img src="https://via.placeholder.com/300x200" alt="Berita Sepakbola">
                <h2>Timnas Indonesia Menang Dramatis</h2>
                <p>Dalam laga sengit, Timnas Indonesia berhasil mengalahkan rival beratnya dengan skor 3-2.</p>
            </div>
            <div class="news-item">
                <img src="https://via.placeholder.com/300x200" alt="Berita Hiburan">
                <h2>Film Indonesia Raih Penghargaan Internasional</h2>
                <p>Film lokal sukses membawa pulang penghargaan bergengsi di festival film dunia.</p>
            </div>
            <div class="news-item">
                <img src="https://via.placeholder.com/300x200" alt="Berita Teknologi">
                <h2>Startup Indonesia Mendunia</h2>
                <p>Perusahaan rintisan asal Indonesia berhasil menarik perhatian investor asing.</p>
            </div>
            <div class="news-item">
                <img src="https://via.placeholder.com/300x200" alt="Berita Pariwisata">
                <h2>Destinasi Wisata Baru yang Viral</h2>
                <p>Keindahan alam Indonesia kembali mencuri perhatian dengan destinasi baru yang eksotis.</p>
            </div>
            <div class="news-item">
                <img src="https://via.placeholder.com/300x200" alt="Berita Musik">
                <h2>Band Indonesia Tampil di Panggung Dunia</h2>
                <p>Band lokal sukses tampil di festival musik internasional dengan sambutan meriah.</p>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Portal Berita Indonesia. All rights reserved.</p>
    </footer>
</body>
</html>
