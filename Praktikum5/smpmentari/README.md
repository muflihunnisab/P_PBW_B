# Praktikum 5 : Web SMP Mentari

## Langkah - Langkah
1. Git clone folder SMPMentari dari Github 
```bash
   git clone https://github.com/adiwp/smpmentari.git
```
2. Masuk ke foldernya 
```bash 
   cd laragon/www/smpmentari
```
3. Install Dependencies
```bash
   # Install PHP Dependencies
   composer install

   # Install Node Dependencies
   npm install
```
4. Setup Environment
```bash
   # Copy file .env
   cp .env.example .env
   
   # Generate Application Key
   php artisan key:generate
```
5. Setup Database 
```bash
   # Jalankan Migrasi
   php artisan migrate
```
6. Build Asset
```bash
   # Development
   npm run dev

   # Production
   npm run build
```
7. Jalankan Aplikasi
```bash 
   # Menggunakan Built-in Server
   php artisan serve
```
atau Jalankan melalui laragon 
![Laragon](image.png)

## View
1. Tampilan Awal
![Tampilan Awal](image-1.png)
2. Page Register 
![Register](image-2.png)
3. Page Dashboard
![Dashboard](image-3.png)
4. Page Kegiatan -> Tambah Kegiatan
![Tambah Kegiatan](image-4.png)
5. Kegiatan Berhasil di Tambahkan
![Kegiatan Added](image-5.png)
