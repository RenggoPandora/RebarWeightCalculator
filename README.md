# Rebar Weight Calculator

Kalkulator berat besi beton (rebar) yang akurat dan profesional dengan tampilan modern menggunakan HTML dan Tailwind CSS.

## Fitur

- 🎯 **Akurat**: Menggunakan rumus standar industri dengan berat jenis material yang tepat
- ⚡ **Cepat**: Hasil perhitungan instan dengan auto-calculate
- 📱 **Responsif**: Tampilan optimal di semua perangkat
- 🎨 **Modern UI**: Desain yang bersih dan profesional
- 🔢 **12 Jenis Material**: Berbagai pilihan material dengan berat jenis yang berbeda

## Jenis Material yang Tersedia

1. Carbon Steel / Baja Karbon (7850 kg/m³)
2. Mild Steel / Baja Lunak (7800 kg/m³)
3. Stainless Steel 304 (8000 kg/m³)
4. Stainless Steel 316 (7750 kg/m³)
5. Low Carbon Steel (7750 kg/m³)
6. High Tensile Steel (7900 kg/m³)
7. Tool Steel (8000 kg/m³)
8. Galvanized Steel (7700 kg/m³)
9. Deformed Bar / Ulir (7850 kg/m³)
10. Plain Bar / Polos (7850 kg/m³)
11. Spring Steel (7950 kg/m³)
12. Cast Steel (8050 kg/m³)

## Rumus Perhitungan

```
Berat = (D² × 0.006165) × L × Q × (ρ/7850)
```

Dimana:
- D = Diameter (mm)
- L = Panjang (m)
- Q = Quantity (jumlah batang)
- ρ = Massa jenis material (kg/m³)

## Informasi yang Ditampilkan

- Total berat (kg dan ton)
- Berat per batang
- Berat per meter
- Luas penampang
- Berat jenis material
- Total panjang

## Deployment ke Vercel

### Cara 1: Menggunakan Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Cara 2: Menggunakan Git

1. Push project ke GitHub repository
2. Import repository di [vercel.com](https://vercel.com)
3. Deploy otomatis akan berjalan

### Cara 3: Drag & Drop

1. Buka [vercel.com/new](https://vercel.com/new)
2. Drag & drop folder project
3. Deploy!

## Struktur File

```
rebar-weight-calculator/
├── index.html          # File utama aplikasi
├── vercel.json         # Konfigurasi Vercel
└── README.md          # Dokumentasi
```

## Teknologi yang Digunakan

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Inter)

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Lisensi

MIT License - bebas digunakan untuk keperluan pribadi maupun komersial.

---

Dibuat dengan ❤️ menggunakan HTML, Tailwind CSS & JavaScript
