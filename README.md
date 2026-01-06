# 🌟 Portfolio Glassmorphism Template

Template portfolio website modern dengan desain glassmorphism, animasi smooth, dan fully responsive.

## ✨ Fitur

- 🎨 **Glassmorphism Design** - Efek kaca yang aesthetic
- 📱 **Fully Responsive** - Tampilan sempurna di semua device
- 🚀 **Loading Screen** - Progress bar animasi
- 🔥 **Animasi Smooth** - Fade in/out, floating shapes, hover effects
- 💚 **WhatsApp Button** - Chat langsung via WhatsApp
- 🌈 **Gradient Background** - Warna campuran yang beautiful
- 📊 **Skill Bars** - Progress bars animasi
- 🎯 **Scroll Animations** - Elements muncul saat scroll

## 📂 Struktur File

```
portfolio-glassmorphism/
├── index.html    (Halaman utama)
├── style.css     (Styling & animasi)
├── script.js     (Interaksi & loading)
└── README.md     (Panduan ini)
```

## 🚀 Cara Menggunakan

### 1. Clone/Download
Download atau clone repository ini ke komputer Anda.

### 2. Buka di Browser
Buka file `index.html` langsung di browser (Chrome, Firefox, Safari, dll).

### 3. Kustomisasi
Edit file `index.html` untuk mengubah konten sesuai kebutuhan Anda.

---

## 📝 Panduan Kustomisasi

### 🔤 Mengganti Nama

Di section **Hero**, cari dan ganti:
```html
<span class="name">Your Name</span>
```
Ganti `Your Name` dengan nama Anda.

---

### 👤 Mengganti Foto Profil

Di section **Hero**, cari:
```html
<div class="profile-placeholder">
    <svg viewBox="0 0 100 100" class="profile-icon">
        <circle cx="50" cy="35" r="15" fill="rgba(255,255,255,0.6)"/>
        <path d="M20 80 Q50 60 80 80 L80 100 L20 100 Z" fill="rgba(255,255,255,0.6)"/>
    </svg>
</div>
```

Ganti dengan gambar Anda:
```html
<img src="path/to/foto-anda.jpg" alt="Foto Profil" class="profile-image">
```

Tambahkan CSS di `style.css`:
```css
.profile-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%;
}
```

---

### 📝 Mengganti Deskripsi About

Di section **About**, cari:
```html
<p>
    Saya seorang web developer passionate yang especializada dalam menciptakan
    website modern dengan teknologi terdepan. Fokus saya adalah pada performa,
    aksesibilitas, dan desain yang menawan.
    Ganti ini dengan deskripsi diri Anda sendiri ya!
</p>
```

Ganti dengan deskripsi diri Anda.

---

### 💪 Mengganti Skill Bars

Di section **Skills**, edit skill dan persentase:
```html
<div class="skill-item">
    <span class="skill-name">HTML/CSS</span>
    <div class="skill-bar">
        <div class="skill-progress" data-progress="95"></div>
    </div>
</div>
```

- `HTML/CSS` → Nama skill Anda
- `data-progress="95"` → Persentase (0-100)

---

### 💼 Mengganti Project Cards

Di section **Projects**, edit project Anda:
```html
<div class="project-card glass-effect">
    <div class="project-image">
        <div class="project-placeholder">
            <!-- Ganti dengan screenshot project Anda -->
        </div>
    </div>
    <div class="project-content">
        <h3>Nama Project Anda</h3>
        <p><strong>Problem:</strong> Deskripsi masalah yang diselesaikan</p>
        <p><strong>Solusi:</strong> Deskripsi solusi yang Anda buat</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="https://link-project-anda.com" class="project-link">Live Demo</a>
            <a href="https://github.com/anda/project" class="project-link">Source Code</a>
        </div>
    </div>
</div>
```

---

### 📧 Mengganti Informasi Kontak

Di section **Contact**, cari dan ganti:

**Email:**
```html
<h4>Email</h4>
<p>your.email@example.com</p>
```
Ganti dengan email Anda.

**WhatsApp:**
```html
<h4>WhatsApp</h4>
<p>+62 123 456 789</p>
```
Ganti dengan nomor WhatsApp Anda.

**Location:**
```html
<h4>Location</h4>
<p>Your City, Country</p>
```
Ganti dengan lokasi Anda.

---

### 📱 Mengganti Link WhatsApp

Cari tombol WhatsApp:
```html
<a href="https://wa.me/62123456789" target="_blank" class="whatsapp-btn">
```

Ganti `62123456789` dengan nomor WhatsApp Anda (tanpa +).

Contoh: `628891983723` untuk nomor +628891983723

---

### 🔗 Mengganti Social Media Links

Di section **Contact**, cari:
```html
<div class="social-links">
    <a href="#" class="social-link glass-effect">GH</a>
    <a href="#" class="social-link glass-effect">LI</a>
    <a href="#" class="social-link glass-effect">IG</a>
</div>
```

Ganti `#` dengan link social media Anda:
- `GH` → GitHub
- `LI` → LinkedIn
- `IG` → Instagram
- `DRI` → Dribbble
- `BE` → Behance

---

### ⚙️ Mengganti Pengaturan Lainnya

#### Footer:
```html
<p>&copy; 2026, Your Name. Dibuat dengan ❤️ menggunakan Glassmorphism Design</p>
```

#### Title Browser:
```html
<title>Portfolio - Glassmorphism</title>
```

#### Logo/Navbar:
```html
<span class="logo-text">Portfolio</span>
```

---

## 🎨 Kustomisasi Warna

Di file `style.css`, bagian `:root`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --text-light: #ffffff;
    --text-gray: #e2e8f0;
    --glass-bg: rgba(255, 255, 255, 0.1);
    --glass-border: rgba(255, 255, 255, 0.2);
    /* Gradient variables juga bisa diubah */
}
```

### Mengganti Background Gradient:

Cari di `style.css`:
```css
body {
    background: linear-gradient(135deg, #FF6B6B 0%, #FF8E53 15%, #FFC837 30%, #000000 45%, #4ECDC4 60%, #5B4E9D 75%, #A66DD6 85%, #000000 100%);
}
```

Ganti dengan warna gradient pilihan Anda.

---

## 📱 Responsive Design

Website ini sudah fully responsive dan menyesuaikan dengan:
- 🖥️ Desktop (≥968px)
- 📱 Tablet (576px - 968px)
- 📲 Mobile (<576px)

Tidak perlu edit CSS tambahan untuk responsive!

---

## 🚀 Deploy ke Internet

### Menggunakan GitHub Pages (Gratis):

1. Buat repository di GitHub
2. Upload file-file portfolio ke repository
3. Pergi ke Settings → Pages
4. Pilih branch `main` atau `master`
5. Klik Save
6. Website akan online di `https://username.github.io/repo-name`

### Menggunakan Netlify (Gratis):

1. Login ke [Netlify](https://netlify.com)
2. Drag & drop folder portfolio ke Netlify
3. Website akan online otomatis

### Menggunakan Vercel (Gratis):

1. Login ke [Vercel](https://vercel.com)
2. Install Vercel CLI atau connect ke GitHub
3. Deploy folder portfolio

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur halaman
- **CSS3** - Styling & animasi
- **JavaScript** - Interaksi & loading
- **Google Fonts** - Font Poppins
- **Backdrop Filter** - Efek glassmorphism

---

## 📄 Lisensi

Free to use untuk personal dan commercial project.

---

## 🤝 Kontribusi

Beri star ⭐ jika suka dengan template ini!
Feel free untuk fork dan modifikasi sesuai kebutuhan.

---

## 📧 Kontak

Jika ada pertanyaan, silakan hubungi:
- Email: your.email@example.com
- WhatsApp: +62 123 456 789

---

**Dibuat dengan ❤️ menggunakan Glassmorphism Design**
