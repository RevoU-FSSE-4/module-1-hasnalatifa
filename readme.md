<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ReviewMe - Beranda</title>
    <link rel="stylesheet" href="stylereviewme.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Protest+Riot&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <nav class="navbar">
            <div class="container">
                <a href="index.html" class="logo">ReviewMe</a>
                <ul class="nav-links">
                    <li><a href="index.html">Beranda</a></li>
                    <li><a href="about.html">Tentang Kami</a></li>
                    <li><a href="reviews.html">Review Produk</a></li>
                    <li><a href="tips.html">Tips & Trik</a></li>
                    <li><a href="contact.html">Kontak</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="hero">
            <div class="container">
                <h1>Selamat Datang di ReviewMe</h1>
                <p>Temukan review jujur tentang produk skincare dan makeup favoritmu!</p>
            </div>
        </section>
<!-- Contoh Review Terbaru -->
<section class="latest-reviews">
    <div class="container">
        <h2>Review Terbaru</h2>
        <div class="review-items">
            <!-- Skintific 5X Ceramide -->
            <div class="review-item">
                <img src="https://th.bing.com/th/id/OIP.QYknIuTsl7sBF5amGJfdQgHaHa?rs=1&pid=ImgDetMain" alt="skintific 5x ceramide moisturizer">
                <h3>Skintific 5X Ceramide Barrier Repair Moisture Gel</h3>
                <p>Moisturizer yang ringan dengan 5 jenis ceramide untuk memperkuat barrier kulit.</p>
                <a href="reviews.html">Baca selengkapnya</a>
            </div>
            <!-- Npure Cica Clear Pad -->
            <div class="review-item">
                <img src="https://cdn.shopify.com/s/files/1/0550/8205/7898/products/8b26d077-0bc3-43aa-a7e1-b79a75a2a902_1024x.jpg?v=1623812485" alt="npure cica clear pad">
                <h3>Npure Cica Clear Pad</h3>
                <p>Pad toner dengan ekstrak cica untuk menenangkan dan membersihkan kulit.</p>
                <a href="reviews.html">Baca selengkapnya</a>
            </div>
            <!-- Pixy Make It Glow Primer -->
            <div class="review-item">
                <img src="https://khyrastore.com/wp-content/uploads/2020/02/pixy-skin-primer.jpg" alt="Pixy Make It Glow Primer">
                <h3>Pixy Make It Glow Primer</h3>
                <p>Primer yang memberikan efek glowing alami dan menyiapkan kulit untuk makeup.</p>
                <a href="reviews.html">Baca selengkapnya</a>
            </div>
        </div>
    </div>
</section>

<section class="request-review">
    <div class="container">
        <h2>Minta Review Produk</h2>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="Nama" required>
            <input type="text" name="product" placeholder="Produk yang ingin direview" required>
            <button type="submit">Kirim</button>
        </form>
    </div>
</section>
    <footer>
        <div class="container">
            <p>&copy; 2024 ReviewMe. Semua Hak Cipta.</p>
        </div>
    </footer>
</body>
</html>