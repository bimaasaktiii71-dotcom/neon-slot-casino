# 🎰 Neon Slot Casino

Neon Slot Casino adalah permainan slot machine dengan desain neon yang menarik. Dibangun dengan HTML, CSS, JavaScript, Node.js, Express, dan Socket.IO.

## 🎮 Fitur

- 🎨 **Desain Neon** - Interface yang modern dan menarik
- 🎯 **Gameplay Sederhana** - Klik SPIN dan mainkan
- 💰 **Sistem Saldo** - Mulai dengan 1000 chip
- 🏆 **Tracking Kemenangan** - Pantau jumlah kemenangan Anda
- 🔊 **Sound Effects** - Efek suara untuk setiap aksi
- 📱 **Responsive** - Berfungsi di desktop dan mobile
- 🌐 **Real-time** - Socket.IO untuk update real-time

## 🎮 Cara Bermain

1. **Tentukan Taruhan** - Ubah nilai taruhan (minimum 10)
2. **Klik SPIN** - Putar slot machine
3. **Tunggu Hasil** - Lihat simbol yang keluar
4. **Menang atau Kalah**:
   - 3 simbol sama = JACKPOT (×5 taruhan)
   - 2 simbol sama = MENANG (×2 taruhan)
   - Tidak ada = KALAH

## 📦 Instalasi

### Prasyarat
- Node.js (versi 14 atau lebih)
- npm atau yarn

### Langkah-langkah

1. **Clone repository**
```bash
git clone https://github.com/bimaasaktiii71-dotcom/neon-slot-casino.git
cd neon-slot-casino
```

2. **Install dependencies**
```bash
npm install
```

3. **Jalankan server**
```bash
npm start
```

4. **Buka browser**
```
http://localhost:3000
```

## 🛠️ Development

Untuk mode development dengan auto-reload:
```bash
npm run dev
```

## 📁 Struktur File

```
neon-slot-casino/
├── index.html          # Halaman utama game
├── server.js          # Backend Express & Socket.IO
├── package.json       # Dependencies
└── README.md          # Dokumentasi
```

## 🎯 Teknologi

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: Node.js, Express.js
- **Real-time**: Socket.IO
- **CORS**: Express CORS middleware

## 📊 API Endpoints

- `GET /` - Halaman utama
- `GET /api/health` - Status server
- `Socket.IO /spin` - Event spin permainan
- `Socket.IO /spinResult` - Hasil spin
- `Socket.IO /gameUpdate` - Update game

## 🎨 Kustomisasi

### Ubah Warna Neon
Edit di `index.html` section `<style>`:
```css
border: 2px solid #00ffe5;  /* Ubah kode warna */
```

### Ubah Simbol
Edit array di `<script>`:
```javascript
const symbols = ["🍒","🍋","🍉","⭐","💎","7️⃣"];
```

### Ubah Reward
Edit function `checkWin`:
```javascript
const reward = bet * 5;  // Jackpot multiplier
const reward = bet * 2;  // Win multiplier
```

## 📝 Lisensi

MIT License - Bebas digunakan untuk keperluan personal maupun komersial

## 👤 Author

**Bima Asaktiii**
- GitHub: [@bimaasaktiii71-dotcom](https://github.com/bimaasaktiii71-dotcom)

## 🤝 Kontribusi

Kontribusi sangat diterima! Silakan:
1. Fork repository
2. Buat branch fitur (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buka Pull Request

## ⚠️ Disclaimer

Permainan ini adalah **simulasi untuk hiburan** dan **TIDAK menggunakan uang asli**. Ini hanya permainan demo dengan chip virtual. Jangan gunakan untuk perjudian nyata.

## 📞 Support

Jika ada pertanyaan atau masalah, buka [GitHub Issues](https://github.com/bimaasaktiii71-dotcom/neon-slot-casino/issues)

---

**Selamat bermain! 🎰✨**