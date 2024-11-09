
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Pernikahan Bakti & Sinta</title>
    <style>
        /* CSS Dasar */
        body {
            font-family: 'Playfair Display', serif;
            color: #333;
            background-color: #faf3e0;
            margin: 0;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }
        .section {
            padding: 60px 20px;
            text-align: center;
        }
        .intro {
            background: url('background.jpg') no-repeat center center/cover; /* Ganti 'background.jpg' dengan foto latar belakang */
            color: #fff;
            padding: 100px 20px;
        }
        .greeting {
            font-size: 1.5em;
            margin-bottom: 20px;
            font-weight: bold;
        }
        .names {
            font-size: 2.5em;
            color: #8c5a3e;
        }
        .event-details {
            font-size: 1.2em;
            color: #666;
            margin-top: 20px;
        }
        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #8c5a3e;
            color: white;
            border-radius: 5px;
            text-decoration: none;
        }
        /* Profil Pengantin */
        .couple {
            display: flex;
            justify-content: space-around;
            padding: 40px 0;
            background: url('backround 1.jpeg') no-repeat center center/cover; /* Ganti 'background.jpg' dengan foto latar belakang */

            color: #fff;
            padding: 100px 20px;
        }
        .couple div {
            text-align: center;
        }
        .couple img {
            width: 150px;
            border-radius: 50%;
            margin-bottom: 15px;
        }
        /* Hitung Mundur */
        .countdown {
            font-size: 1.5em;
            margin: 20px 0;
            display: flex;
            justify-content: center;
            gap: 10px;
        }
        .countdown div {
            background-color: #8c5a3e;
            color: white;
            padding: 10px;
            border-radius: 5px;
        }
        /* Galeri Foto */
        .gallery {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        .gallery img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }
        .video-section {
        background-color: #f9f5ef;
        padding: 40px 20px;
        text-align: center;
        }
        .video-section h2 {
        color: #8c5a3e;
        margin-bottom: 20px;
        }
        .video-section video {
        max-width: 20%;
        height: auto;
        border: 2px solid #8c5a3e;
        border-radius: 10px;
        }
        /* Kolom Ucapan dan Doa */
        .comments {
            background-color: #f9f5ef;
            padding: 20px;
            border-radius: 10px;
            max-width: 600px;
            margin: auto;
        }
        /* Berikan Hadiah */
        .gift-info {
            background-color: #f1e8d6;
            padding: 20px;
            border-radius: 10px;
            margin: auto;
            max-width: 600px;
            text-align: left;
        }
    </style>
</head>
<body>

    <!-- Halaman Pembuka -->
    <section class="section intro">
        <div class="greeting">
            Kepada Yth, <span id="guest-name">[Nama yang Diundang]</span>
        </div>
        <div class="names">
            The Wedding of <br> Bakti & Sinta
        </div>
        <p class="event-details">
            8 Juni 2025 <br> Cijeler Girang Cikancana, Kec. Gekbrong, Kabupaten Cianjur, Jawa Barat
        </p>
        <a href="#details" class="button">Lihat Selengkapnya</a>
    </section>

    <!-- Profil Pengantin -->
    <section class="section couple" id="details">
        <div>
            <img src="groom.jpg" alt="Pengantin Pria"> <!-- Ganti 'groom.jpg' dengan foto pengantin pria -->
            <h2>Bakti</h2>
            <p>Putra dari Keluarga Bapak A dan Ibu B</p>
        </div>
        <div>
            <img src="bride.jpg" alt="Pengantin Wanita"> <!-- Ganti 'bride.jpg' dengan foto pengantin wanita -->
            <h2>Sinta</h2>
            <p>Putri dari Keluarga Bapak C dan Ibu D</p>
        </div>
    </section>

    <!-- Hitung Mundur -->
    <section class="section countdown">
        <div id="days">00 Hari</div>
        <div id="hours">00 Jam</div>
        <div id="minutes">00 Menit</div>
        <div id="seconds">00 Detik</div>
    </section>

    <!-- Hadist Pernikahan -->
    <section class="section">
        <blockquote>
            “Dan di antara tanda-tanda kekuasaan-Nya ialah Dia menciptakan untukmu isteri-isteri dari jenismu sendiri,<br> 
            supaya kamu cenderung dan merasa tenteram kepadanya, dan dijadikan-Nya di antaramu rasa kasih dan sayang.” 
            <br> (QS. Ar-Rum : 21)
        </blockquote>
    </section>

    <!-- Informasi Acara -->
    <section class="section">
        <h2>Akad & Resepsi</h2>
        <p>Akad Nikah: 8 Juni 2025, Pukul 09.00 WIB</p>
        <p>Resepsi: 8 Juni 2025, Pukul 11.00 - 14.00 WIB</p>
        <p>Lokasi: Grand Ballroom, Jakarta</p>
    </section>

    <!-- Google Maps -->
    <section class="section">
        <h2>Lokasi Pernikahan</h2>
        <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3909.4816385654353!2d107.08756472611195!3d-6.883666332607838!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e684f99b79b382d%3A0xbaa2ecb502a097a0!2sCijeler%20Girangg!5e1!3m2!1sen!2sus!4v1731084750303!5m2!1sen!2sus" <!-- Ganti URL ini dengan URL embed Google Maps Anda -->
            width="600"
            height="450"
            style="border:0;"
            allowfullscreen=""
            loading="lazy">
        </iframe>
    </section>

    <!-- Galeri Foto -->
    <section class="section gallery">
        <img src="photo1.jpg" alt="Foto 1"> <!-- Ganti 'photo1.jpg' dengan foto pilihan -->
        <img src="photo2.jpg" alt="Foto 2"> <!-- Ganti 'photo2.jpg' dengan foto pilihan -->
        <img src="photo3.jpg" alt="Foto 3"> <!-- Ganti 'photo3.jpg' dengan foto pilihan -->
        <img src="photo4.jpg" alt="Foto 4"> <!-- Ganti 'photo3.jpg' dengan foto pilihan -->
        <img src="photo5.jpg" alt="Foto 5"> <!-- Ganti 'photo3.jpg' dengan foto pilihan -->
        <img src="photo6.jpg" alt="Foto 6"> <!-- Ganti 'photo3.jpg' dengan foto pilihan -->
    </section>

    <!-- Halaman Video -->
<section class="section video-section">
    <h2>Video Singkat Kami</h2>
    <video controls width="80%" style="border-radius: 15px;">
        <source src="video.mp4" type="video/mp4"> <!-- Ganti 'video.mp4' dengan path video yang Anda miliki -->
        Browser Anda tidak mendukung video HTML5.
    </video>
    <p>Terima kasih telah meluangkan waktu untuk menyaksikan momen bahagia kami.</p>
</section>


    <!-- Kolom Ucapan dan Doa -->
     
    <section class="section">
        <h2>Ucapan & Doa</h2>

        <form id="guest-form">
            <input type="text" id="nama" placeholder="Nama" required><br>
            <textarea id="komentar" placeholder="Komentar" required></textarea><br>
            <button type="submit">Kirim Komentar</button>
        </form>
        <p id="status"></p>
    </section>


    <!-- Berikan Hadiah -->
    <section class="section gift-info">
        <h2>Berikan Hadiah</h2>
        <p>Bagi yang ingin memberikan hadiah, berikut adalah informasi rekening:</p>
        <ul>
            <li>Bank ABC - No. Rek: 1234567890 - a.n. Bakti</li>
            <li>Bank XYZ - No. Rek: 0987654321 - a.n. Sinta</li>
        </ul>
        <p>Alamat Pengiriman Kado:</p>
        <p>Jl. Mawar No. 12, Jakarta</p>
    </section>

    <!-- JavaScript untuk Nama Tamu dan Hitung Mundur -->
    <script>
    document.getElementById('guest-form').addEventListener('submit', async function(event) {
    event.preventDefault();

    const nama = document.getElementById('nama').value;
    const komentar = document.getElementById('komentar').value;

    try {
        const response = await fetch('https://script.google.com/macros/s/AKfycbwXJ-uLlMpcnlw3rGFRUiZ5SCWYpxNS8KzJkkrwCSVKmoZzhy0TUEWq80D8tR5itowZ/exec', {
            method: 'POST',
            headers: {
                'Content-Type': 'application/json'
            },
            body: JSON.stringify({ nama, komentar })
        });

        const result = await response.json();
        
        if (result.status === 'success') {
            document.getElementById('status').textContent = 'Komentar berhasil dikirim!';
            document.getElementById('guest-form').reset();
        } else {
            document.getElementById('status').textContent = 'Gagal mengirim komentar: ' + result.message;
        }
    } catch (error) {
        console.error('Error:', error);
        document.getElementById('status').textContent = 'Terjadi kesalahan. Coba lagi nanti.';
    }
});

        // Fungsi Hitung Mundur
const countdownDate = new Date("June 8, 2025 08:00:00").getTime();
const countdownFunction = setInterval(() => {
    const now = new Date().getTime();
    const distance = countdownDate - now;

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);

    document.getElementById('days').textContent = `${days} Hari`;
    document.getElementById('hours').textContent = `${hours} Jam`;
    document.getElementById('minutes').textContent = `${minutes} Menit`;
    document.getElementById('seconds').textContent = `${seconds} Detik`;

    if (distance < 0) {
        clearInterval(countdownFunction);
        document.querySelector('.countdown').textContent = "Acara telah dimulai!";
    }
}, 1000);
    
</script>
</body> </html> ```
