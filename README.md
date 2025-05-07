# PatiPet<!DOCTYPE html><html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PatiPet Evcil Hayvan Oteli</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; margin: 0; padding: 0; background: #fff8f0; color: #333; }
        header { background: linear-gradient(90deg, #f7971e, #ffd200); padding: 30px; text-align: center; color: #fff; }
        header h1 { margin: 0; font-size: 2.5em; }
        nav { background: #444; color: white; text-align: center; padding: 15px; }
        nav a { color: white; margin: 0 20px; text-decoration: none; font-weight: bold; }
        nav a:hover { text-decoration: underline; }
        section { padding: 40px 20px; max-width: 1000px; margin: auto; }
        h2 { color: #f7971e; }
        .services, .gallery, .reviews { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .card { background: white; padding: 20px; border-radius: 12px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
        footer { background: #444; color: white; text-align: center; padding: 15px; margin-top: 40px; }
        form { display: grid; gap: 15px; background: #fff; padding: 20px; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
        input, textarea, select { padding: 10px; border: 1px solid #ccc; border-radius: 5px; font-size: 1em; }
        button { background: #f7971e; color: white; border: none; padding: 10px; font-size: 1em; border-radius: 5px; cursor: pointer; }
        button:hover { background: #e3870e; }
        img { max-width: 100%; border-radius: 10px; }
    </style>
</head>
<body>
    <header>
        <h1>PatiPet Evcil Hayvan Oteli</h1>
        <p>Sevgi ve güvenle patili dostlarınıza konfor sunuyoruz</p>
    </header>
    <nav>
        <a href="#hakkimizda">Hakkımızda</a>
        <a href="#hizmetler">Hizmetler</a>
        <a href="#galeri">Galeri</a>
        <a href="#yorumlar">Yorumlar</a>
        <a href="#rezervasyon">Rezervasyon</a>
        <a href="#iletisim">İletişim</a>
    </nav><section id="hakkimizda">
    <h2>Hakkımızda</h2>
    <p>PatiPet, evcil dostlarınızı kendi evinizdeymiş gibi ağırlayan modern ve güvenli bir hayvan otelidir. Uzman kadromuzla 7/24 gözetim, sağlıklı beslenme ve eğlenceli vakit geçirmeleri için her şeyi sunuyoruz.</p>
</section>

<section id="hizmetler">
    <h2>Hizmetlerimiz</h2>
    <div class="services">
        <div class="card">
            <h3>Konforlu Konaklama</h3>
            <p>Kedi ve köpekler için klimalı, ferah ve hijyenik odalar.</p>
        </div>
        <div class="card">
            <h3>Veteriner Desteği</h3>
            <p>İhtiyaç duyulan her an uzman veteriner desteği.</p>
        </div>
        <div class="card">
            <h3>Egzersiz ve Oyun</h3>
            <p>Geniş oyun alanları ve yürüyüş seansları.</p>
        </div>
        <div class="card">
            <h3>Kişiye Özel Beslenme</h3>
            <p>Evcil dostunuzun diyetine uygun günlük mama servisi.</p>
        </div>
    </div>
</section>

<section id="galeri">
    <h2>Galeri</h2>
    <div class="gallery">
        <img src="https://placekitten.com/300/200" alt="Kedi Odası">
        <img src="https://placedog.net/300/200?id=1" alt="Köpek Parkı">
        <img src="https://placekitten.com/301/200" alt="Oyun Alanı">
        <img src="https://placedog.net/301/200?id=2" alt="Uyuyan Patiler">
    </div>
</section>

<section id="yorumlar">
    <h2>Müşteri Yorumları</h2>
    <div class="reviews">
        <div class="card">
            <p><strong>Ayşe T.</strong>: Kedim Mavi için harika bir deneyim oldu. Temiz ve güvenliydi.</p>
        </div>
        <div class="card">
            <p><strong>Mehmet K.</strong>: Köpeğim Leo çok eğlenmiş, eve mutlu döndü. Teşekkürler!</p>
        </div>
        <div class="card">
            <p><strong>Selin B.</strong>: Güler yüzlü ekip, tertemiz alanlar. Şiddetle tavsiye ederim.</p>
        </div>
    </div>
</section>

<section id="rezervasyon">
    <h2>Rezervasyon Yapın</h2>
    <form>
        <input type="text" placeholder="Adınız Soyadınız" required>
        <input type="tel" placeholder="Telefon Numaranız" required>
        <input type="email" placeholder="E-posta Adresiniz">
        <input type="text" placeholder="Evcil Hayvanınızın Adı" required>
        <select required>
            <option disabled selected>Evcil Hayvan Türü</option>
            <option>Kedi</option>
            <option>Köpek</option>
            <option>Diğer</option>
        </select>
        <textarea rows="4" placeholder="Özel Notlar (varsa)"></textarea>
        <button type="submit">Gönder</button>
    </form>
</section>

<section id="iletisim">
    <h2>İletişim</h2>
    <p>Telefon: 0555 123 45 67<br>Email: info@patipet.com<br>Adres: İstanbul, Türkiye</p>
</section>

<footer>
    <p>&copy; 2025 PatiPet Evcil Hayvan Oteli. Tüm hakları saklıdır.</p>
</footer>

</body>
</html>
