## Overview
Project ini merupakan implementasi Penerapan Kendali GPIO pada Traffic Light 4 Arah dengan Arduino Uno. Sistem ini mensimulasikan lampu lalu lintas pada persimpangan empat arah menggunakan LED sebagai indikator.

Tujuan dari project ini adalah untuk memahami:
- Konsep Physical Computing
- Penggunaan GPIO (General Purpose Input Output)
- Struktur dasar program Arduino
- Manipulasi output menggunakan mikrokontroler

## Komponen yang Digunakan
- Arduino Uno
- 12 LED (Merah, Kuning, Hijau)
- 12 Resistor (220Ω)
- Breadboard
- Kabel jumper

## Mapping pin
Utara   : 2 (Merah), 3 (Kuning), 4 (Hijau)
Timur   : 5 (Merah), 6 (Kuning), 7 (Hijau)
Selatan : 8 (Merah), 9 (Kuning), 10 (Hijau)
Barat   : 11 (Merah), 12 (Kuning), 13 (Hijau)

<img width="936" height="708" alt="Screenshot 2026-03-26 160859" src="https://github.com/user-attachments/assets/14c9b97f-90a5-45d1-81f3-b893aabbfcce" />

## Cara Kerja Sistem

Sistem bekerja secara otomatis dengan urutan:
- Semua lampu dalam kondisi merah (default)
- Lampu hijau menyala selama 5 detik pada satu arah
- Lampu kuning berkedip sebagai transisi
- Kembali ke merah
- Berpindah ke arah berikutnya (searah jarum jam)
- Sistem berjalan terus menerus (looping)
