# EcoScan AI — Pemilahan Sampah dengan AI

Website prototype untuk mendeteksi dan mengklasifikasikan sampah menggunakan kamera dan model AI Google Teachable Machine.

## Kategori
- Organik
- Plastik
- Kaca
- Kertas

## Teknologi
HTML, CSS, JavaScript, TensorFlow.js, Teachable Machine Image.

## Model AI
https://teachablemachine.withgoogle.com/models/CDYnNx0_A/

## Cara Pakai
1. Klik **Muat Model**.
2. Klik **Mulai Kamera** dan izinkan akses kamera.
3. Arahkan kamera ke sampah.
4. Klik **Scan Sekarang**.
5. Lihat klasifikasi, confidence score, dan rekomendasi tempat pemilahan.

## GitHub Pages
Upload seluruh isi ZIP ke repository. Pastikan `index.html` berada di root repository. Lalu buka **Settings → Pages → Deploy from a branch → main → / (root)**.

URL website akan berbentuk `https://USERNAME.github.io/NAMA-REPOSITORY/`.

## Catatan
Internet diperlukan karena TensorFlow.js, library Teachable Machine, dan model AI dimuat secara online. GitHub Pages menggunakan HTTPS sehingga akses kamera dapat digunakan oleh browser yang mendukungnya.
