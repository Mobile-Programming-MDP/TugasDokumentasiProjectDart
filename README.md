# Dokumentasi Project Dart: Menghitung Luas Lingkaran dan Volume Kubus
## Deskripsi Singkat
Program ini memiliki fungsi untuk mengetahui hasil dari luas lingkaran dan volume kubus berdasarkan input dari pengguna.
## Struktur Folder Project
* main.dart: berisi fungsi yang berguna untuk menghitung luas lingkaran dan volume kubus.
* README.md: berisi dokumentasi dari project dart.
## Cara Instalasi
1. Install Dart jika belum terdapat Dart di komputer anda.
2. Jalankan perintah ```dart main.dart``` untuk menjalankan project.
## Cara Penggunaan
* Untuk menghitung luas lingkaran, gunakan fungsi ```luasLingkaran()```. Contoh:
```
double luasLingkaran(double jariJari) {
    double luas = 3.14*jariJari*jariJari;
    return luas;
}
print(luasLingkaran(14)); // Output: 615.44
```
* Untuk menghitung volume kubus, gunakan fungsi ```volumeKubus()```. Contoh:
```
double volumeKubus(double sisi) {
    double volume = sisi*sisi*sisi;
    return volume;
}
print(volumeKubus(6)); // Output: 216
```
## Penjelasan Kode
Fungsi ```luasLingkaran(double jariJari)``` akan menghitung luas dari lingkaran dengan menggunakan rumus π*r^2 (π = 3.14, r = Jari-jari)
<br>
Fungsi ```volumeKubus(double sisi)``` akan menghitung volume dari kubus dengan menggunakan rumus s^3 (s = Sisi)