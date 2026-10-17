# Buat Pacar Ku ❤️

Website romantis interaktif dengan tampilan modern, estetik, dan penuh animasi manis untuk pasangan tersayang.

## ✨ Fitur-Fitur:
- 🌸 **Floating Hearts & Sparkles Canvas Background**: Efek partikel hati dan kilau lembut melayang di layar.
- 💌 **Surat Interaktif (Typewriter Effect)**: Amplop interaktif yang saat dibuka memunculkan surat dengan animasi ketik halus.
- ⏳ **Days Counter (Penghitung Hari Kebersamaan)**: Menghitung durasi hari, jam, menit, dan detik secara real-time.
- 📸 **Polaroid Memories**: Galeri foto polaroid dengan rotasi estetik dan efek interaktif.
- 💖 **Carousel 'Alasan Aku Sayang Kamu'**: Kartu kutipan manis yang bisa digeser.
- 🏃 **Tombol Usil 'Do You Love Me?'**: Tombol 'Nggak' otomatis kabur saat didekati kursor atau disentuh di HP.
- 🎉 **Confetti Effect**: Efek taburan konfeti saat surat atau tombol interaktif ditekan.
- 🎵 **BGM Player**: Tombol memutar musik romantis santai di pojok kanan atas.

## 🛠️ Cara Kustomisasi:
1. **Ganti Tanggal Jadian / Spesial**:
   Buka file `index.html` dan cari baris:
   ```javascript
   const startDate = new Date(2024, 0, 1, 0, 0, 0);
   // Format: new Date(Tahun, Bulan - 1, Tanggal)
   ```
2. **Ganti Isi Surat Cinta**:
   Cari variabel `letterText` di `index.html` dan ketikkan pesan manis sesuai keinginanmu.
3. **Ganti Lagu / Musik**:
   Cari elemen `<audio id="bgMusic">` dan ubah `src` file audionya ke file lagu favorit kalian.
4. **Ganti Foto Polaroid**:
   Cari elemen `.polaroid-img` dan ganti dengan tag `<img>` yang mengarah ke foto kalian.
