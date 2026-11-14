NEXORA MOVE - APLIKASI PWA SIAP DEPLOY

Ini adalah aplikasi web progresif yang bisa dipasang di Android seperti aplikasi.
Cara tercepat:
1. Upload seluruh isi folder ini ke repository GitHub.
2. Buka Cloudflare Pages > Create project > Connect to Git.
3. Pilih repository ini. Build command kosong, output directory: / (root).
4. Deploy dan buka URL HTTPS hasil deploy di Chrome Android.
5. Menu Chrome (⋮) > Install app / Tambahkan ke layar utama.

Untuk uji tampilan lokal: buka index.html melalui Acode preview.
Catatan sensor:
- GPS jarak memakai geolocation saat sesi aktif dan izin diberikan.
- Langkah memakai deteksi gerakan browser (perkiraan), tidak setara sensor pedometer native.
- Pelacakan tidak dijamin tetap berjalan ketika layar mati atau browser ditutup.
- Data disimpan lokal pada perangkat melalui localStorage.
- Ini PWA, BUKAN APK Android native yang sudah dikompilasi. Untuk APK native perlu proses build Android terpisah.
