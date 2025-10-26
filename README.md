# DisiplinTrack - Sistem Monitoring Disiplin Siswa 🎨✨

Aplikasi web modern, colorful, dan profesional untuk monitoring dan pencatatan pelanggaran disiplin siswa di sekolah.

## 🌈 Tampilan Baru yang Lebih Menarik!

Aplikasi ini kini hadir dengan desain yang lebih **colorful**, **modern**, dan **eye-catching** namun tetap **profesional**:

- 🎨 **Gradient Colorful**: Background dan elemen dengan gradient warna-warni yang indah
- ✨ **Animasi Smooth**: Transisi dan efek hover yang halus dan menarik
- 💎 **Glassmorphism Effect**: Efek kaca modern pada modal dan cards
- 🌟 **Shine Effects**: Efek kilau pada icon dan elemen interaktif
- 🎯 **Responsive Design**: Tampil sempurna di semua device

## 🚀 Fitur Utama

### Multi-Role Login System
- **Admin Sekolah**: Akses penuh ke semua fitur
- **Guru**: Mencatat pelanggaran dan pembinaan
- **Wali Kelas**: Monitoring siswa di kelasnya
- **Siswa**: Melihat riwayat pelanggaran sendiri

### Manajemen Data
- ✅ CRUD Data Siswa (NIS, Nama, Kelas, dll)
- ✅ CRUD Data Guru dan Wali Kelas
- ✅ CRUD Data Kelas dan Jurusan
- ✅ CRUD Jenis Pelanggaran (Ringan, Sedang, Berat)

### Pencatatan Pelanggaran
- 📝 Form input pelanggaran lengkap
- 🔢 Sistem poin otomatis
- 📊 Status pelanggaran (Tercatat, Diproses, Selesai)
- 🔍 Filter dan pencarian data

### Dashboard & Monitoring
- 📈 Grafik pelanggaran per bulan
- 🥧 Chart jenis pelanggaran
- 📊 Statistik real-time
- 🏆 Peringkat siswa paling disiplin
- ⚠️ Peringkat siswa paling sering melanggar

### Pembinaan & Tindakan
- 📋 Catatan pembinaan siswa
- 👨‍🏫 Tracking tindak lanjut guru
- ✅ Status penyelesaian pembinaan

### Laporan & Export
- 📄 Generate laporan PDF
- 📊 Export ke Excel
- 🗓️ Filter berdasarkan periode
- 👤 Laporan per siswa atau per kelas

### Pengaturan
- 🌙 Dark Mode
- 🔔 Notifikasi
- 🔐 Ubah password
- ⚙️ Konfigurasi batas poin peringatan

## 📦 Struktur File

```
Monitoring Disiplin Siswa/
├── index.html              # File HTML utama
├── styles.css              # Styling lengkap
├── README.md              # Dokumentasi
└── js/
    ├── app.js             # Entry point aplikasi
    ├── data.js            # Data storage & management
    ├── auth.js            # Authentication & login
    ├── navigation.js      # Navigation & routing
    ├── dashboard.js       # Dashboard & charts
    ├── siswa.js           # CRUD Data Siswa
    ├── guru.js            # CRUD Data Guru
    ├── kelas.js           # CRUD Data Kelas
    ├── pelanggaran.js     # Jenis & Input Pelanggaran
    ├── monitoring.js      # Monitoring & Statistik
    ├── pembinaan.js       # Pembinaan & Tindakan
    ├── laporan.js         # Laporan & Export
    └── pengaturan.js      # Settings & Preferences
```

## 🎯 Cara Menggunakan

### 1. Buka Aplikasi
Buka file `index.html` di browser modern (Chrome, Firefox, Edge, dll)

### 2. Login
Gunakan kredensial demo berikut:

| Role | Username | Password |
|------|----------|----------|
| Admin Sekolah | admin | admin123 |
| Guru | guru | guru123 |
| Wali Kelas | wali | wali123 |
| Siswa | siswa | siswa123 |

### 3. Navigasi
- Gunakan sidebar untuk berpindah halaman
- Menu yang tersedia disesuaikan dengan role pengguna
- Klik hamburger menu (☰) untuk toggle sidebar di mobile

### 4. Mengelola Data

#### Tambah Data Siswa
1. Klik menu "Data Siswa"
2. Klik tombol "Tambah Siswa"
3. Isi form lengkap
4. Klik "Simpan"

#### Catat Pelanggaran
1. Klik menu "Input Pelanggaran"
2. Klik tombol "Catat Pelanggaran"
3. Pilih siswa dan jenis pelanggaran
4. Poin akan otomatis ditambahkan
5. Klik "Simpan"

#### Generate Laporan
1. Klik menu "Laporan"
2. Pilih jenis laporan (Per Siswa/Kelas/Periode)
3. Tentukan rentang tanggal
4. Pilih format (PDF/Excel)
5. Klik "Generate Laporan"

## 🎨 Color Scheme & Design

### Gradient Palette
- **Primary**: Purple-Blue Gradient (#667eea → #764ba2)
- **Danger**: Pink-Red Gradient (#f093fb → #f5576c)
- **Success**: Cyan-Pink Gradient (#a8edea → #fed6e3)
- **Warning**: Peach Gradient (#ffecd2 → #fcb69f)

### Design Features
- ✨ **Animated Gradient Background**: Background login dengan animasi gradient 5 warna
- 💎 **Glassmorphism**: Efek kaca dengan backdrop-filter blur
- 🌟 **Shine Effect**: Animasi kilau pada stat icons
- 🎯 **Hover Effects**: Transformasi dan shadow yang smooth
- 🎨 **Gradient Sidebar**: Sidebar dengan gradient purple-blue
- 📊 **Colorful Charts**: Visualisasi data dengan warna-warni menarik

## 🛠️ Teknologi

- **HTML5**: Struktur aplikasi
- **CSS3**: Styling modern dengan gradient & animasi
- **JavaScript (Vanilla)**: Logika aplikasi
- **Chart.js**: Visualisasi data grafik
- **jsPDF**: Export PDF
- **SheetJS (xlsx)**: Export Excel
- **Font Awesome**: Icon library
- **LocalStorage**: Penyimpanan data lokal

## 📱 Responsive Design

Aplikasi fully responsive dan dapat diakses dari:
- 💻 Desktop
- 📱 Tablet
- 📱 Mobile Phone

## 🔒 Keamanan

- Login multi-role dengan validasi
- Data tersimpan di localStorage browser
- Session management
- Password protection

## 💾 Penyimpanan Data

Data disimpan di **localStorage** browser, sehingga:
- ✅ Tidak perlu server/database
- ✅ Data persisten di browser yang sama
- ⚠️ Data akan hilang jika localStorage dibersihkan
- ⚠️ Data tidak tersinkronisasi antar device

## 🎓 Demo Data

Aplikasi sudah dilengkapi dengan data demo:
- 8 Siswa dari berbagai kelas
- 5 Guru dengan berbagai jabatan
- 5 Kelas (IPA & IPS)
- 8 Jenis Pelanggaran
- Beberapa data pelanggaran dan pembinaan

## 🔧 Kustomisasi

### Mengubah Warna Tema
Edit file `styles.css` bagian `:root`:
```css
:root {
    --primary: #4F46E5;  /* Warna utama */
    --secondary: #10B981; /* Warna sekunder */
    /* ... */
}
```

### Menambah Jenis Pelanggaran
Login sebagai Admin → Menu "Jenis Pelanggaran" → Tambah

### Mengubah Batas Poin Peringatan
Menu "Pengaturan" → Batas Poin Peringatan

## 📞 Support

Untuk pertanyaan atau bantuan, silakan hubungi administrator sekolah.

## 📝 Lisensi

Aplikasi ini dibuat untuk keperluan monitoring disiplin siswa di sekolah.

---

**DisiplinTrack** - Membangun Karakter Siswa yang Lebih Baik 🎓
