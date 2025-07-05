# QurbaninAja - Platform Qurban Online

![QurbaninAja Logo](https://github.com/MYusrilM10/QurbaninAja/blob/main/public/images/logo.png)

## Deskripsi Projek

QurbaninAja adalah platform digital untuk memudahkan pelaksanaan ibadah qurban secara online. Aplikasi ini dibangun dengan:

- **Frontend**: Next.js (React Framework)
- **Backend**: Express.js
- **Database**: MySQL
- **Styling**: Tailwind CSS

## Fitur Utama

✅ Pendaftaran dan autentikasi pengguna  
✅ Pemilihan hewan qurban (sapi, kambing, domba)  
✅ Sistem pembayaran terintegrasi  
✅ Pelacakan status qurban  
✅ Sertifikat qurban digital  
✅ Manajemen admin untuk pengelolaan qurban

## Cara Menjalankan Projek

### Prasyarat

- Node.js (v14 atau lebih baru)
- MySQL database
- NPM atau Yarn

### Instalasi

1. Clone repositori:

```bash
git clone https://github.com/MYusrilM10/QurbaninAja.git
cd QurbaninAja
```

2. Install dependencies:

```bash
npm install
# atau
yarn install
```

3. Setup database:

- Buat database MySQL baru
- Import file SQL yang tersedia di `/database/qurbaninaja.sql`

4. Konfigurasi environment:
   Buat file `.env` berdasarkan template `.env.example` dan isi dengan konfigurasi yang sesuai.

5. Jalankan aplikasi:

```bash
npm run dev
# atau
yarn dev
```

Aplikasi akan berjalan di `http://localhost:3000`

## Struktur Direktori

```
├── public/            - Aset statis (gambar, font, dll)
├── src/
│   ├── components/    - Komponen React
│   ├── pages/         - Halaman Next.js
│   ├── styles/        - File CSS global
│   ├── utils/         - Fungsi utilitas
│   └── server/        - Backend Express.js
├── database/          - Skema dan data SQL
└── ...
```

## Kontribusi

Kontribusi selalu diterima! Ikuti langkah berikut:

1. Fork projek ini
2. Buat branch fitur baru (`git checkout -b fitur-baru`)
3. Commit perubahan Anda (`git commit -am 'Menambahkan fitur baru'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buat Pull Request

## Lisensi

Projek ini dilisensikan di bawah [MIT License](LICENSE).

## Kontak

- **Muhammad Yusril **
- Email: myusril@gmail.com
- LinkedIn: [linkedin.com/in/muhammad-yusril-](https://www.linkedin.com/in/muhammad-yusril-)

---

Dibangun dengan ❤️ untuk memudahkan ibadah qurban di era digital.
