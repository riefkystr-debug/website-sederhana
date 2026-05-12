# website-sederhana
web
[nyoba.html](https://github.com/user-attachments/files/27626987/nyoba.html)
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brosur Es Teler Segar & Dingin</title>
    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600;700&family=Outfit:wght@400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="nyoba.css">
<body>
    <header class="hero-banner">
        <h1>🍹 Segarnya RASA Nusantara!</h1>
        <p>Nikmati Es Teler & Es Campur premium dengan buah-buahan segar pilihan.</p>
        <div class="promo-tag">PROMO SPESIAL HARI INI!</div>
    </header>

    <main class="menu-section">
        <h2>Pilihan Menu Dingin Kami</h2>[nyoba.css](https://github.com/user-attachments/files/27626988/nyoba.css)

        
        <div class="menu-grid">

            <div class="menu-card">
                <div class="item-image">
                    🌴 [Gambar Es Teler: Alpukat, Nangka, Kelapa Muda]
                </div>
                <div class="item-info">
                    <h3>Es Teler Alpukat Premium</h3>
                    <p>Perpaduan sempurna alpukat mentega, nangka manis, dan kelapa muda.</p>
                    <div class="price">Rp 18.000</div>
                    <a href="#" class="order-button">Pesan Sekarang</a>
                </div>
            </div>

            <div class="menu-card">
                <div class="item-image">
                    🍎 [Gambar Es Campur: Cincau, Kolang-kaling, Sirup Merah]
                </div>
                <div class="item-info">
                    <h3>Es Campur Spesial</h3>
                    <p>Aneka isian favorit: cincau hitam, kolang-kaling, tape, dan susu kental manis.</p>
                    <div class="price">Rp 15.000</div>
                    <a href="#" class="order-button">Pesan Sekarang</a>
                </div>
            </div>

            <div class="menu-card">
                <div class="item-image">
                    🍓 [Gambar Es Doger: Es Merah Muda, Pacar Cina]
                </div>
                <div class="item-info">
                    <h3>Es Doger Cokelat</h3>
                    <p>Es santan dingin rasa kelapa dengan sentuhan cokelat dan isian klasik.</p>
                    <div class="price">Rp 16.500</div>
                    <a href="#" class="order-button">Pesan Sekarang</a>
                </div>
            </div>
            
            <div class="menu-card">
                <div class="item-image">
                    🥥 [Gambar Alpukat Keruk: Alpukat, Es Krim Vanila]
                </div>
                <div class="item-info">
                    <h3>Alpukat Keruk Gula Merah</h3>
                    <p>Alpukat kerok murni, es batu, dan siraman gula merah aren otentik.</p>
                    <div class="price">Rp 20.000</div>
                    <a href="#" class="order-button">Pesan Sekarang</a>
                </div>
            </div>

        </div>
    </main>

    <footer class="contact-footer">
        <h3>Hubungi Kami</h3>
        <p>Jl. sumatra utara .desa air teluk kiri</p>
        <p>Telepon/WA: <a href="tel:082165554821">082-165-554-891</a></p>
        <p>Instagram: <a href="#">@es_teler_toko_riefky</a></p>
    </footer>
        
</body>
</html>
  :root {
            --primary-color: #f3eff8; /* Hijau Segar (Warna utama) */
            --secondary-color: #00ff22; /* Orange Ceria (Aksen) */
            --background-light: #ffffff; /* Latar belakang krem muda */
            --text-dark: #333333;
            --text-light: #3313e9;
            --price-color: #ebebeb; /* Merah Muda untuk Harga */
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Outfit', sans-serif;
            line-height: 1.6;
            background-color: var(--background-light);
            color: var(--text-dark);
        }

        .hero-banner {
            background: linear-gradient(135deg, var(--primary-color) 0%, #8BC34A 100%);
            color: var(--text-light);
            padding: 4rem 2rem;
            text-align: center;
            border-bottom-left-radius: 50% 15%; /* Bentuk melengkung yang unik */
            border-bottom-right-radius: 50% 15%;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
        }

        .hero-banner h1 {
            font-family: 'Fredoka', sans-serif;
            font-size: 3.5rem;
            font-weight: 700;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
            margin-bottom: 0.5rem;
        }

        .hero-banner p {
            font-size: 1.25rem;
            margin-bottom: 1.5rem;
            font-weight: 400;
        }
        
        .promo-tag {
            display: inline-block;
            background-color: var(--secondary-color);
            padding: 0.5rem 1.5rem;
            border-radius: 30px;
            font-weight: 700;
            letter-spacing: 1px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .menu-section {
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .menu-section h2 {
            font-family: 'Fredoka', sans-serif;
            text-align: center;
            font-size: 2.5rem;
            color: var(--text-dark);
            margin-bottom: 3rem;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .menu-card {
            background-color: var(--text-light);
            border-radius: 15px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
            border: 3px solid transparent;
        }

        .menu-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.2);
            border-color: var(--secondary-color);
        }

        .item-image {
            width: 100%;
            height: 220px;
            background-color: #F8F4E8; /* Placeholder */
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            color: var(--secondary-color);
            object-fit: cover;
            border-bottom: 4px solid var(--primary-color);
        }

        .item-info {
            padding: 1.5rem;
            text-align: center;
        }

        .item-info h3 {
            font-family: 'Fredoka', sans-serif;
            font-size: 1.8rem;
            color: var(--primary-color);
            margin-bottom: 0.5rem;
        }

        .item-info p {
            color: var(--text-dark);
            font-size: 0.95rem;
            margin-bottom: 1rem;
        }

        .price {
            font-size: 2rem;
            font-weight: 700;
            color: var(--price-color);
            letter-spacing: -1px;
            margin-bottom: 1rem;
        }
        
        .order-button {
            display: inline-block;
            background-color: var(--secondary-color);
            color: var(--text-light);
            padding: 0.75rem 1.5rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            transition: background-color 0.3s;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .order-button:hover {
            background-color: #E68900;
        }

        .contact-footer {
            background-color: #f7e7d2; /* Warna coklat muda */
            padding: 3rem 2rem;
            text-align: center;
            border-top: 5px dashed var(--primary-color);
        }
        
        .contact-footer h3 {
             font-family: 'Fredoka', sans-serif;
             color: var(--primary-color);
             margin-bottom: 1rem;
        }

        .contact-footer p {
            margin-bottom: 0.5rem;
        }

        .contact-footer a {
            color: var(--secondary-color);
            text-decoration: none;
            font-weight: 600;
        }
