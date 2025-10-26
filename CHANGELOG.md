# Changelog - DisiplinTrack

## [Latest Update] - 26 Oktober 2025

### ✨ Fitur Baru
- **Manajemen Data Jurusan**
  - CRUD lengkap untuk data jurusan (Create, Read, Update, Delete)
  - Form tambah/edit jurusan dengan layout 2 kolom
  - Search/filter jurusan berdasarkan kode, nama, atau deskripsi
  - Auto-count jumlah kelas per jurusan
  - Validasi kode jurusan unik
  - Integrasi dengan data kelas

### 🎨 Perbaikan UI/UX
- **Konsistensi Form Layout**
  - Form tambah/edit kelas menggunakan `form-grid` (layout 2 kolom)
  - Form tambah/edit jurusan menggunakan `form-grid` (layout 2 kolom)
  - Semua form sekarang konsisten dengan form guru
  - Textarea dengan styling yang konsisten
  - Label dan input field yang seragam

- **Tampilan Colorful & Modern**
  - Background login dengan animated gradient 5 warna
  - Sidebar dengan gradient purple-blue
  - Stat cards dengan gradient backgrounds
  - Buttons dengan gradient dan ripple effect
  - Badges dengan gradient pills
  - Table headers dengan gradient
  - Glassmorphism effect pada modal dan cards
  - Shine effect pada stat icons
  - Smooth animations dan transitions

### 🔧 Perubahan Teknis
- Menambahkan `js/jurusan.js` untuk modul manajemen jurusan
- Update `js/data.js` dengan array jurusan dan demo data
- Update `js/kelas.js` untuk integrasi dengan data jurusan dinamis
- Update `js/auth.js` dengan menu "Data Jurusan" di sidebar
- Update `js/navigation.js` dengan routing ke halaman jurusan
- Update `styles.css` dengan styling untuk textarea dan alert

### 📊 Struktur Data
```javascript
// Data Jurusan
{
    id: number,
    kode: string,        // Contoh: "IPA", "IPS", "TKJ"
    nama: string,        // Contoh: "Ilmu Pengetahuan Alam"
    deskripsi: string,   // Deskripsi singkat jurusan
    jumlahKelas: number  // Auto-calculated
}

// Data Kelas (Updated)
{
    id: number,
    nama: string,
    jurusan: string,     // Kode jurusan
    jurusanId: number,   // ID jurusan untuk relasi
    waliKelas: string,
    jumlahSiswa: number
}
```

### 🎯 Fitur Form Grid
Semua form sekarang menggunakan layout 2 kolom yang responsif:
- Desktop: 2 kolom (side by side)
- Tablet/Mobile: 1 kolom (stacked)
- Gap 20px antar field
- Min-width 250px per kolom

### 🌈 Color Palette
- **Primary**: Purple-Blue Gradient (#667eea → #764ba2)
- **Danger**: Pink-Red Gradient (#f093fb → #f5576c)
- **Success**: Cyan-Pink Gradient (#a8edea → #fed6e3)
- **Warning**: Peach Gradient (#ffecd2 → #fcb69f)
- **Login BG**: Rainbow Gradient (5 warna animasi)

### 📱 Responsive Design
- Form grid otomatis menjadi 1 kolom di mobile
- Modal tetap centered dan scrollable
- Sidebar collapsible di mobile
- Touch-friendly button sizes

### 🔒 Validasi & Keamanan
- Kode jurusan harus unik
- Konfirmasi sebelum hapus data
- Warning jika jurusan memiliki kelas terhubung
- Required field validation
- Auto uppercase untuk kode jurusan

---

## Demo Data
Aplikasi dilengkapi dengan demo data:
- 3 Jurusan (IPA, IPS, Bahasa)
- 5 Kelas
- 5 Guru
- 8 Siswa
- 8 Jenis Pelanggaran
- 4 Pelanggaran
- 2 Pembinaan

## Akses Demo
- **Admin**: admin/admin123
- **Guru**: guru/guru123
- **Wali Kelas**: wali/wali123
- **Siswa**: siswa/siswa123
