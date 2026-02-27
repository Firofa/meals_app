# Meals App

Aplikasi Flutter untuk menjelajahi berbagai resep makanan dengan fitur filter dan sistem favorit.

## Deskripsi

Meals App adalah aplikasi mobile yang memungkinkan pengguna untuk:

- Melihat berbagai kategori makanan
- Menjelajahi resep makanan dari setiap kategori
- Melihat detail resep termasuk ingredients dan langkah-langkah pembuatan
- Memfilter makanan berdasarkan preferensi diet (gluten-free, lactose-free, vegetarian, vegan)
- Menyimpan makanan favorit untuk akses mudah di kemudian hari

## Fitur Utama

- 📋 **Kategori Makanan** - Jelajahi berbagai kategori resep makanan
- 🍽️ **Detail Resep** - Lihat bahan-bahan dan langkah pembuatan untuk setiap resep
- ❤️ **Sistem Favorit** - Simpan makanan favorit Anda
- 🔍 **Filter Lanjutan** - Filter makanan berdasarkan:
  - Gluten-Free
  - Lactose-Free
  - Vegetarian
  - Vegan
- 🎨 **Material Design 3** - Antarmuka modern dengan tema dark mode
- 📱 **Cross Platform** - Berjalan di iOS, Android,Web, Windows, macOS, dan Linux

## Teknologi yang Digunakan

- **Flutter** - Framework UI cross-platform
- **Material 3** - Design system terbaru dari Google
- **Google Fonts** - Typography yang menarik
- **Dart** - Bahasa pemrograman

## Dependensi

```yaml
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.8
  google_fonts: ^8.0.2
  transparent_image: ^2.0.1
```

## Struktur Proyek

```
lib/
├── main.dart              # Entry point aplikasi
├── models/
│   ├── category.dart      # Model kategori makanan
│   └── meal.dart          # Model resep makanan
├── data/
│   └── dummy_data.dart    # Data dummy untuk testing
├── screens/
│   ├── tabs.dart          # Layar utama dengan tab navigation
│   ├── categories.dart    # Layar kategori makanan
│   ├── meals.dart         # Layar daftar makanan
│   ├── meal_details.dart  # Layar detail makanan
│   └── filters.dart       # Layar filter makanan
└── widgets/
    ├── main_drawer.dart           # Navigation drawer
    ├── category_grid_item.dart    # Widget item kategori
    ├── meal_item.dart             # Widget item resep
    └── meal_item_trait.dart       # Widget badge properties resep
```

## Memulai

### Prasyarat

- Flutter SDK (v3.11.0 atau lebih baru)
- Dart SDK
- Android Studio / Xcode / VS Code

### Instalasi

1. Clone repository atau extract project
2. Masuk ke direktori project:
   ```bash
   cd meals_app
   ```
3. Dapatkan dependencies:
   ```bash
   flutter pub get
   ```
4. Jalankan aplikasi:
   ```bash
   flutter run
   ```

## Penggunaan

1. Buka aplikasi
2. Pilih kategori makanan dari layar utama
3. Lihat resep-resep dalam kategori
4. Klik pada resep untuk melihat detail lengkap
5. Gunakan drawer menu untuk:
   - Melihat favorit
   - Mengatur filter makanan sesuai preferensi diet Anda

## Sumber Daya Pembelajaran

- [Dokumentasi Flutter](https://docs.flutter.dev/)
- [Material Design 3](https://m3.material.io/)
- [Dart Programming Language](https://dart.dev/)

## Lisensi

Proyek ini tidak dipublikasikan ke pub.dev dan bersifat private.
