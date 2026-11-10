ALIEN FACE — mobile MVP 0.1

CARA MENJALANKAN
1. Upload folder ini ke hosting statis yang menyediakan HTTPS (misalnya GitHub Pages, Netlify, atau Cloudflare Pages).
2. Buka URL HTTPS tersebut dari Chrome Android.
3. Tekan menu Chrome > Tambahkan ke layar utama / Install app.
4. Masukkan gambar karakter PNG/JPG.
5. Aktifkan kamera dan izinkan akses kamera.
6. Kalibrasi wajah netral, lalu atur ukuran/posisi/sensitivitas.

CATATAN
- Kamera membutuhkan HTTPS atau localhost.
- Face tracking memakai MediaPipe dari CDN dan model diunduh saat pertama kali dipakai; koneksi internet diperlukan.
- Prototipe ini menggerakkan gambar utuh mengikuti posisi, skala, dan rotasi kepala. Deteksi kedip dan mulut ditampilkan sebagai status, belum mengubah bagian wajah pada gambar.
- Belum menyediakan virtual camera Android / output langsung ke TikTok Live. Tombol selfie menyimpan frame canvas.
- Kamera diproses di browser; aplikasi tidak mengirim gambar avatar atau video kamera ke server milik pembuat aplikasi.
