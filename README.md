# 💻 Proyek HTML Modern dengan Tailwind CSS

Proyek HTML modern yang menggunakan **Tailwind CSS** untuk membangun aplikasi web responsif dengan pengaturan minimal.

## 🚀 Fitur

- **HTML5** – Struktur HTML modern dengan praktik terbaik
- **Tailwind CSS** – Framework CSS berbasis utilitas untuk pengembangan UI yang cepat
- **Komponen Kustom** – Kelas komponen siap pakai untuk tombol dan container
- **Skrip NPM** – Perintah mudah digunakan untuk pengembangan dan build
- **Desain Responsif** – Pendekatan mobile-first untuk semua ukuran layar

## 📋 Prasyarat

- Node.js (versi 12.x atau lebih tinggi)
- npm atau yarn

## 🛠️ Instalasi

1. Instal dependensi:
   ```bash
   npm install
   # atau
   yarn install


2. Start the development server:
npm run dev
# atau
yarn dev


## 📁 Project Structure

```
hhtml_app/
├── css/
│   ├── tailwind.css       # File sumber Tailwind dengan utilitas kustom
│   └── main.css           # CSS yang telah dikompilasi (tergenerate)
├── pages/                 # Halaman HTML
├── index.html             # Titik masuk utama
├── package.json           # Dependensi proyek dan skrip
└── tailwind.config.js     # Konfigurasi Tailwind CSS

```

## 🎨 Styling

This project uses Tailwind CSS for styling. Custom utility classes include:


## 🧩 Customization

To customize the Tailwind configuration, edit the `tailwind.config.js` file:


## 📦 Build for Production

Build the CSS for production:

```bash
npm run build:css
# or
yarn build:css
```

## 📱 Responsive Design

The app is built with responsive design using Tailwind CSS breakpoints:

- `sm`: 640px and up
- `md`: 768px and up
- `lg`: 1024px and up
- `xl`: 1280px and up
- `2xl`: 1536px and up
