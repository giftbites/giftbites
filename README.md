# Gifted Bites 🎁

> Mengubah Snack Sederhana Menjadi Hadiah Estetik

Gifted Bites adalah penyedia mini gift berkualitas dengan harga terjangkau untuk mahasiswa dan pelajar. Kami menyediakan berbagai pilihan kemasan aesthetic seperti pouch makanan berhias, buket snack mini, dan snack box kustom.

## 🌟 Fitur Utama

- **Visual Clean & Aesthetic** - Desain pengemas yang rapi dan premium
- **Harga Ramah Kantong** - Produk berkualitas dengan harga terjangkau
- **Mudah Dipersonalisasi** - Kustomisasi penuh sesuai kebutuhan Anda
- **Layanan B2B & B2C** - Melayani pesanan ritel dan bulk order
- **Responsive Design** - Akses dari desktop, tablet, atau smartphone

## 📁 Struktur File

```
giftbites/
├── index.html          # Halaman utama
├── order.html          # Halaman katalog dan pemesanan
├── style.css           # Stylesheet utama
├── manifest.json       # PWA manifest
├── robots.txt          # SEO robots configuration
├── .gitignore          # Git ignore rules
└── README.md           # File dokumentasi ini
```

## 🚀 Memulai

### Prasyarat
- Browser modern yang mendukung HTML5, CSS3, dan JavaScript ES6+
- Koneksi internet (untuk CDN Tailwind CSS)

### Cara Akses

1. **Local Development**
   ```bash
   # Clone repository
   git clone https://github.com/giftbites/giftbites.git
   cd giftbites
   
   # Buka dengan live server atau server lokal
   # Contoh: gunakan Python http.server
   python -m http.server 8000
   # Kunjungi http://localhost:8000
   ```

2. **Online Deployment**
   - Deploy ke GitHub Pages (gratis)
   - Deploy ke Vercel atau Netlify
   - Deploy ke hosting provider pilihan Anda

## 📱 Teknologi yang Digunakan

- **HTML5** - Struktur semantic
- **CSS3** - Styling dan animasi modern
- **Tailwind CSS** - Framework CSS utility-first
- **Vanilla JavaScript** - Interaksi dan validasi form
- **WhatsApp Integration** - Integrasi untuk order via WhatsApp

## 🎨 Desain & Branding

### Warna Utama
- Primary Orange: `#F97316`
- Dark Blue: `#1E293B`
- Light Gray: `#F9FAFB`
- Text Gray: `#1F2937`

### Font
- **Sans Serif**: Inter (Google Fonts)
- **Serif**: Playfair Display (Google Fonts)

## 📝 Halaman Utama

### index.html
- Hero section dengan call-to-action
- Tentang kami (visi & misi)
- Core values (3 nilai utama)
- Strategi & pengembangan bisnis
- Footer dengan link penting

### order.html
- Katalog produk (3 pilihan)
- Form pemesanan interaktif
- Integrasi WhatsApp untuk submit order
- Product selection dengan visual feedback

## 🔗 Integrasi WhatsApp

Form pemesanan otomatis mengarahkan pelanggan ke WhatsApp dengan pesan yang telah diisi sesuai data form. Pastikan untuk mengganti nomor WhatsApp di kode:

```javascript
const phoneNumber = '6281234567890'; // Ganti dengan nomor bisnis Anda
```

## ♿ Aksesibilitas

- ARIA labels untuk form inputs
- Keyboard navigation support
- Focus management yang baik
- Color contrast yang memenuhi WCAG standar
- Reduced motion support untuk pengguna yang sensitif

## 📊 SEO Optimization

- Meta descriptions di setiap halaman
- Semantic HTML struktur
- Mobile-first responsive design
- Fast loading time
- robots.txt untuk search engine

## 🔒 Security

- No sensitive data stored client-side
- WhatsApp integration via API yang aman
- Input validation pada form
- HTTPS recommended untuk production

## 📈 Performance

- Lightweight CSS dengan Tailwind CDN
- Optimized image loading
- Smooth animations dan transitions
- Fast form submission

## 🌐 Deployment

### GitHub Pages (Gratis)
1. Push ke repository
2. Aktifkan GitHub Pages di settings
3. Pilih branch `main`
4. Website akan live di `https://username.github.io/giftbites`

### Vercel (Recommended)
1. Connect GitHub repository
2. Import project di Vercel
3. Deploy otomatis dengan setiap push
4. Custom domain support

### Netlify
1. Connect GitHub repository
2. Pilih build settings
3. Deploy otomatis
4. Form integration tersedia

## 📞 Kontak & Support

- **WhatsApp**: Hubungi kami melalui form order
- **Instagram**: @giftedbites (setup soon)
- **Email**: Isi di form kontak

## 📄 Lisensi

Proyek ini dibuat untuk keperluan bisnis Gifted Bites. Semua aset dan kode dilindungi copyright © 2026 Gifted Bites.

## 🎯 Roadmap Pengembangan

- [ ] Admin dashboard untuk order management
- [ ] E-commerce integration (Shopify/WooCommerce)
- [ ] Instagram feed integration
- [ ] Customer reviews & testimonials
- [ ] Payment gateway integration
- [ ] Email notification system
- [ ] Analytics tracking
- [ ] Multi-language support

## 💡 Tips Optimalisasi

1. **Perbarui nomor WhatsApp** di order.html
2. **Optimalkan gambar produk** dengan ukuran yang lebih kecil
3. **Tambahkan Google Analytics** untuk tracking
4. **Setup domain custom** untuk branding profesional
5. **Buat social media linked** untuk cross-promotion

---

**Dibuat dengan ❤️ untuk Gifted Bites | 2026**
