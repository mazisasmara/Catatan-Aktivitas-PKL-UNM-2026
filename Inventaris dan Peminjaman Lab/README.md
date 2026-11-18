# Teknologi yang digunakan 

| Laravel 13      | Framework utama aplikasi                                    |
| --------------- | ----------------------------------------------------------- |
| Livewire 4      | Interaksi dinamis tanpa harus refresh halaman secara manual |
| Blade           | Template tampilan frontend                                  |
| MariaDB         | Database dengan driver MySQL Laravel                        |
| Laravel fortify | Sistem autentikasi login, registrasi, dan lupa password.    |
| Git + Github    | Version control dan storage repo                            |
| Tailwind CSS    | Styling antarmuka                                           |
Catatan mengenai auth:
> Tidak menggunakan Laravel Breeze, cukup menggunakan Laravel Official Livewire Starter Kit.
> Alasannya karena sudah menyediakan login dan registrasi, menggunakan Laravel Fortify untuk autentikasi, sudah terintegrasi Livewire 4, Menggunakan Blade, dan tersedia fitur forgot password dan pengaturan autentikasi.

# Struktur template final

| layouts/app.blade.php                  | Pembungkus utama halaman         |
| -------------------------------------- | -------------------------------- |
| layouts/app/sidebar.blade.php          | Sidebar, navigasi, header mobile |
| layouts/app/header.blade.php           | Header halaman jika diperlukan   |
| components/app-logo.blade.php          | identitas dan nama aplikasi      |
| components/desktop-user-menu.blade.php | Profil dan menu akun             |
| dashboard.blade.php                    | konten dashboard                 |

---

### Task 8 November 2026
- [x] Pengambilan bahan
- [x] Pengembalian bahan
- [x] Riwayat transaksi semua role 
- [x] Katalog alat, bahan, dan laboratorium 
- [x] Detail barang dan tombol peminjaman
- [ ] Upload gambar opsional 
- [x] Dashboard admin dan Superadmin dgn Chart.js lokal
- [x] dashboard mahasiswa dan dosen
- [x] homepage publik
- [x] testing, audit, dan deployment 
