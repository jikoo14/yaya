# 💌 Amplop Surat Animasi

![Version](https://img.shields.io/badge/versi-1.0.0-blue.svg)
![License](https://img.shields.io/badge/lisensi-MIT-green.svg)
![CSS](https://img.shields.io/badge/CSS-3-1572B6.svg)
![HTML](https://img.shields.io/badge/HTML-5-E34F26.svg)

Proyek animasi CSS yang menampilkan amplop interaktif yang dapat dibuka untuk mengungkapkan surat di dalamnya. Ketika kursor diarahkan ke amplop, tutup amplop akan terbuka secara bertahap dan surat akan muncul dengan animasi yang halus.

## ✨ Fitur Utama

- 🎨 **Animasi CSS Murni** - Tidak memerlukan JavaScript sama sekali
- 🖱️ **Efek Hover Interaktif** - Amplop terbuka saat mouse diarahkan
- 📝 **Pesan Dapat Dikustomisasi** - Mudah mengubah isi pesan surat
- 🌈 **Tema Warna Fleksibel** - Dapat mengubah warna sesuai keinginan
- ⚡ **Performa Optimal** - Menggunakan CSS transform untuk animasi yang smooth
- 📱 **Desain Responsif** - Tampil baik di berbagai ukuran layar

## 🚀 Cara Instalasi

### Persyaratan Sistem
- Browser web modern (Chrome, Firefox, Safari, Edge)
- Editor teks (VS Code, Notepad++, atau editor lainnya)

### Langkah-langkah Instalasi

1. **Unduh atau Clone Proyek:**
   ```bash
   git clone https://github.com/username/amplop-surat-animasi.git
   cd amplop-surat-animasi
   ```

2. **Buka File HTML:**
   - Klik dua kali pada file `index.html`, atau
   - Klik kanan → "Open with" → pilih browser favorit Anda

3. **Menggunakan Live Server (Opsional):**
   ```bash
   # Jika menggunakan VS Code dengan Live Server extension
   # Klik kanan pada index.html → "Open with Live Server"
   
   # Atau gunakan Python untuk server lokal
   python -m http.server 8000
   ```

## 📖 Cara Menggunakan

### 🔤 Mengubah Pesan Surat

Ini adalah bagian terpenting! Berikut cara mengubah pesan yang ditampilkan dalam surat:

#### Langkah 1: Buka File HTML
Buka file `index.html` dengan editor teks favorit Anda.

#### Langkah 2: Temukan Bagian Letter
Cari kode berikut di dalam file:
```html
<div class="letter">
  <p>For R??</p>  <!-- Ini adalah pesan yang akan diubah -->
</div>
```

#### Langkah 3: Ganti Pesan
Ubah teks di antara tag `<p>` dan `</p>`:

**Contoh Pesan Sederhana:**
```html
<div class="letter">
  <p>Aku Sayang Kamu ❤️</p>
</div>
```

**Contoh Pesan dengan Emoji:**
```html
<div class="letter">
  <p>Selamat Ulang Tahun! 🎉🎂</p>
</div>
```

**Contoh Pesan Panjang:**
```html
<div class="letter">
  <p>Terima Kasih</p>
  <p style="font-size: 16px; margin-top: 10px;">Atas semua kebaikanmu</p>
</div>
```

### 📝 Template Pesan Siap Pakai

Berikut beberapa template pesan yang bisa langsung Anda gunakan:

#### 💕 Pesan Romantis
```html
<div class="letter">
  <p>I Love You 💕</p>
</div>

<div class="letter">
  <p>Kamu Istimewa ✨</p>
</div>

<div class="letter">
  <p>Be My Valentine 💝</p>
</div>
```

#### 🎉 Pesan Ucapan
```html
<div class="letter">
  <p>Selamat Ulang Tahun! 🎂</p>
</div>

<div class="letter">
  <p>Selamat Wisuda! 🎓</p>
</div>

<div class="letter">
  <p>Selamat Tahun Baru! 🎊</p>
</div>
```

#### 🙏 Pesan Terima Kasih
```html
<div class="letter">
  <p>Terima Kasih 🙏</p>
</div>

<div class="letter">
  <p>Thank You So Much! 💖</p>
</div>
```

#### 📢 Pesan Undangan
```html
<div class="letter">
  <p>Kamu Diundang! 💌</p>
</div>

<div class="letter">
  <p>Save The Date 📅</p>
</div>
```

### 🎨 Mengubah Gaya Teks

Anda juga bisa mengkustomisasi tampilan teks dengan menambahkan style:

#### Mengubah Ukuran Font
```html
<div class="letter">
  <p style="font-size: 24px;">Pesan Besar</p>
</div>

<div class="letter">
  <p style="font-size: 14px;">Pesan kecil</p>
</div>
```

#### Mengubah Warna Teks
```html
<div class="letter">
  <p style="color: red;">Pesan Merah ❤️</p>
</div>

<div class="letter">
  <p style="color: blue;">Pesan Biru 💙</p>
</div>
```

#### Menambahkan Beberapa Baris
```html
<div class="letter">
  <p>Baris Pertama</p>
  <p style="font-size: 16px; margin-top: 5px;">Baris Kedua</p>
  <p style="font-size: 12px; margin-top: 5px;">Baris Ketiga</p>
</div>
```

## 🎨 Mengubah Warna Amplop

### Mengubah Warna Latar Belakang
Buka file `style.css` dan temukan:
```css
body {
  background-color: #e9abff; /* Ubah kode warna ini */
}
```

### Mengubah Warna Amplop
```css
.wrapper {
  background-color: #fea8fa; /* Warna dasar amplop */
}

.envelope {
  border-right: 150px solid #ff8ef9; /* Sisi kanan amplop */
  border-bottom: 100px solid #f978f3; /* Bagian bawah */
  border-left: 150px solid #fb69f3; /* Sisi kiri amplop */
}
```

### Contoh Tema Warna

#### Tema Biru
```css
body { background-color: #a8d8ff; }
.wrapper { background-color: #8fc8fa; }
.envelope {
  border-right: 150px solid #6bb6ff;
  border-bottom: 100px solid #4da6ff;
  border-left: 150px solid #2e96ff;
}
```

#### Tema Hijau
```css
body { background-color: #a8ffa8; }
.wrapper { background-color: #8ffa8f; }
.envelope {
  border-right: 150px solid #6bff6b;
  border-bottom: 100px solid #4dff4d;
  border-left: 150px solid #2eff2e;
}
```

## 📁 Struktur File Proyek

```
amplop-surat-animasi/
├── index.html          # File HTML utama
├── style.css           # File CSS untuk styling dan animasi
├── README.md           # Dokumentasi proyek (file ini)
└── .gitignore         # File yang diabaikan Git
```

### Penjelasan File

- **`index.html`** - Berisi struktur HTML amplop dan surat
- **`style.css`** - Berisi semua styling, warna, dan animasi
- **`README.md`** - Dokumentasi lengkap cara penggunaan

## ⚙️ Pengaturan Lanjutan

### Mengubah Kecepatan Animasi
```css
.lid {
  transition: transform 0.25s linear; /* Ubah 0.25s untuk kecepatan berbeda */
}

.letter {
  transition: 0.5s; /* Ubah 0.5s untuk kecepatan animasi surat */
}
```

### Mengubah Ukuran Amplop
```css
.wrapper {
  height: 200px;  /* Tinggi amplop */
  width: 300px;   /* Lebar amplop */
}
```

## 💡 Contoh Penggunaan Kreatif

### 1. Kartu Valentine
```html
<div class="letter">
  <p>💕 Jadilah Valentineku 💕</p>
</div>
```

### 2. Undangan Pernikahan
```html
<div class="letter">
  <p>Kamu Diundang! 💒</p>
  <p style="font-size: 14px; margin-top: 10px;">Pernikahan Kami</p>
</div>
```

### 3. Pengumuman Kelulusan
```html
<div class="letter">
  <p>🎓 Aku Lulus!</p>
  <p style="font-size: 16px; margin-top: 10px;">Terima kasih dukunganmu</p>
</div>
```

### 4. Pesan Rahasia
```html
<div class="letter">
  <p>🤫 Pesan Rahasia</p>
  <p style="font-size: 12px; margin-top: 10px;">Hanya untukmu...</p>
</div>
```

## 🔧 Tips dan Trik

### Menambahkan Font Kustom
```css
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;700&display=swap');

.letter p {
  font-family: 'Dancing Script', cursive;
  font-weight: 700;
}
```

### Menambahkan Efek Bayangan
```css
.wrapper {
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
  border-radius: 10px;
}
```

### Animasi Zoom Saat Hover
```css
.wrapper:hover {
  transform: scale(1.05);
  transition: transform 0.3s ease;
}
```

## 🐛 Pemecahan Masalah

### Masalah Umum dan Solusi

**Q: Animasi tidak berjalan dengan lancar**
A: Pastikan browser Anda sudah update ke versi terbaru dan mendukung CSS3 transforms.

**Q: Amplop tidak terbuka saat di-hover**
A: Periksa apakah file CSS sudah ter-load dengan benar. Buka Developer Tools (F12) untuk melihat error.

**Q: Teks tidak terlihat jelas**
A: Sesuaikan warna teks dengan mengubah property `color` di CSS atau menambahkan style inline.

**Q: Pesan terlalu panjang dan terpotong**
A: Perkecil ukuran font atau bagi pesan menjadi beberapa baris menggunakan beberapa tag `<p>`.

## 🤝 Kontribusi

Kami menyambut kontribusi dari siapa saja! Jika Anda ingin berkontribusi:

1. Fork repository ini
2. Buat branch baru untuk fitur Anda
3. Commit perubahan Anda
4. Push ke branch tersebut
5. Buat Pull Request

### Ide Kontribusi
- Template pesan baru
- Tema warna tambahan
- Efek animasi yang lebih menarik
- Peningkatan responsivitas
- Dokumentasi yang lebih baik

## 📄 Lisensi

Proyek ini menggunakan lisensi MIT. Anda bebas menggunakan, memodifikasi, dan mendistribusikan kode ini.

---

**Selamat berkreasi dengan amplop surat animasi Anda! 💌✨**
