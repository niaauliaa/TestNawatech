# Nawatech Technical Test
# Project 1 

# Website ini merupakan aplikasi berbasis .NET Core yang digunakan untuk mengelola produk makanan secara digital. Pengguna dapat melakukan login, mengatur profil mereka, serta menambahkan, mengedit, dan menghapus data kategori dan produk.

# Fungsi Web:
- Registrasi & Login: Pengguna bisa mendaftar dan masuk ke akun mereka.
- Manajemen Profil: Edit data diri dan unggah foto profil.
- Kelola Kategori Makanan: Tambah, ubah, dan hapus kategori seperti minuman, camilan, makanan berat, dll.
- Kelola Produk Makanan: Tambah produk makanan lengkap dengan nama, harga, deskripsi, dan gambar.
- Soft Delete: Produk yang dihapus tidak langsung hilang, tapi bisa dipulihkan.
- Autorisasi Pengguna: Beberapa fitur hanya bisa diakses jika sudah login.

## Fitur
- Autentikasi (register, login)
- Manajemen profil (termasuk foto profil)
- CRUD kategori produk dan produk (dengan soft delete)
- Validasi dan konfirmasi email 

# Prasyarat
- Pastikan sudah menginstal:
- C# (biasanya sudah termasuk dalam .NET SDK)
- .NET Core SDK
- SQL Server (atau database lain sesuai kebutuhan)
- Visual Studio 2022 

# Cara Menjalankan Proyek
- Clone repositori di github 
- Atur connection string di appsettings.json
- Jalankan migration “dotnet ef database update"
- Jalankan aplikasi “dotnet run atau dari Visual Studio”
