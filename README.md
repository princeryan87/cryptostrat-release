# Cryptostrat

**Crypto Analyzer untuk Binance Spot & Futures** — analisis on-demand berbasis 9 strategi teknikal (5 Spot + 4 Futures), dilengkapi analisis AI (Gemini) dengan grounding berita real-time.

![Platform](https://img.shields.io/badge/platform-Android-3DDC84?logo=android&logoColor=white)
![Status](https://img.shields.io/badge/status-development-yellow)
![License](https://img.shields.io/badge/license-Personal%20Use-lightgrey)

---

## Download

Unduh APK terbaru di halaman **[Releases](../../releases/latest)**.

| Versi | Tanggal | Catatan |
|---|---|---|
| v1.0.0 | - | Rilis awal |

> Setelah download, kamu mungkin perlu mengizinkan **"Install from unknown sources"** di pengaturan Android, karena app ini didistribusikan di luar Google Play Store.

## Apa itu Cryptostrat?

Cryptostrat membantu kamu menganalisis pair crypto tertentu di Binance (Spot maupun Futures) berdasarkan kombinasi indikator teknikal yang sudah ditentukan parameternya secara matang — bukan screening massal yang memakan waktu lama, tapi analisis cepat untuk pair yang sudah kamu tentukan sendiri.

### Cara pakai
1. Buka app, masukkan pair yang ingin dianalisis (contoh: base `BTC`, quote `USDT`)
2. Pilih mode: **Analyze Spot** atau **Analyze Futures**
3. Lihat hasil dari strategi yang relevan, lengkap dengan alasan teknikal di tiap sinyal
4. (Opsional) Masukkan API key Gemini sendiri di Settings untuk mendapat analisis AI tambahan dengan referensi berita terbaru

### Strategi yang tersedia

**Spot (5 strategi)**
- Momentum Breakout
- Whale Watch (order book imbalance)
- Low Cap Hunter
- Volume Surge
- Accumulation Zone

**Futures (4 strategi)**
- Trend Confirm (Open Interest + Price)
- Long/Short Squeeze Radar (Funding Rate ekstrem)
- Low Cap Momentum
- Divergence Hunter

## Catatan Penting

- **Bukan nasihat finansial.** Semua sinyal dan analisis AI di app ini adalah hasil perhitungan otomatis, bukan rekomendasi investasi. Selalu lakukan riset sendiri (DYOR) sebelum mengambil keputusan trading.
- **Mode Futures menggunakan leverage** — risiko kerugian bisa melebihi modal awal. App akan selalu menampilkan disclaimer ini di dalam halaman analisis Futures.
- App ini **read-only** — tidak ada integrasi API key Binance, tidak ada akses ke akun atau dana kamu. Data diambil murni dari Binance Public API.
- API key Gemini (jika kamu masukkan) disimpan **hanya di HP kamu sendiri**, tidak pernah dikirim ke server pihak ketiga selain langsung ke Google.

## Sumber Data

Seluruh data harga, volume, funding rate, dan open interest diambil langsung dari [Binance Public API](https://binance-docs.github.io/apidocs/) secara real-time saat analisis dijalankan.

## Lisensi & Kontribusi

Project personal, dikembangkan untuk penggunaan pribadi dan komunitas. Saran dan laporan bug bisa disampaikan lewat tab **Issues**.

---

**Created by:** Muslimin Juni
**Powered by:** Claude (Anthropic)
