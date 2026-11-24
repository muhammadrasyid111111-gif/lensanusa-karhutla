# LensaNusa

Website klasifikasi tingkat ketebalan asap kebakaran hutan dan lahan (Karhutla) di Jalan Trans Kalimantan menggunakan Convolutional Neural Network (CNN).

## Menjalankan lokal

```powershell
powershell -ExecutionPolicy Bypass -File .\server.ps1
```

Buka `http://localhost:5500/index.html` di browser.

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub.
2. Upload seluruh isi folder ini ke repository tersebut.
3. Masuk ke **Settings → Pages**.
4. Pada **Build and deployment**, pilih **GitHub Actions**.
5. Push atau upload ulang perubahan. Workflow akan menerbitkan website secara otomatis.

Login demo: `peneliti` / `karhutla2024`.

> Login ini hanya proteksi antarmuka untuk demo. Untuk aplikasi produksi, autentikasi harus dipindahkan ke backend.
