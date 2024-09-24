# CodeDroneDiy

## Deskripsi
Proyek ini bertujuan untuk membuat pengendali penerbangan quadcopter yang sederhana menggunakan Arduino dan sensor inersia (IMU). Terdapat dua mode penerbangan utama:
- **Mode Akrobatik (Manual)**: Mode ini memerlukan keterampilan penerbangan dan tidak memiliki kemampuan auto-leveling.
- **Mode Sudut (Automatic Leveling)**: Mode ini lebih kompleks, tetapi lebih mudah dikendalikan karena dapat otomatis kembali ke posisi horizontal.

## Daftar Komponen
Berikut adalah komponen yang dibutuhkan:
- **Microcontroller**: Arduino Nano atau Uno
- **ESC (Electronic Speed Control)**: Afro 20A-Simonk
- **Motor**: Multistar 2216-800Kv
- **Propeller**: 10x4.5 SF Props
- **Baterai**: Zippy Flightmax 3000mAh 4S
- **IMU (Inertial Measurement Unit)**: MPU6050 (GY-86)
- **Receiver**: OrangeRx R617XL


## Mode Penerbangan
### Mode Akrobatik
- Menggunakan algoritma sederhana untuk stabilisasi. Kita perlu memiliki skill untuk mengendalikan pesawat.

### Mode Sudut
- Menggunakan sensor untuk mengukur sudut dan kecepatan sudut. Dapat menggabungkan data dari gyroskop dan akselerometer untuk stabilisasi otomatis.


## Kesimpulan
Proyek CodeDroneDIY berhasil mengembangkan pengendali penerbangan quadcopter sederhana dan memberikan platform untuk eksplorasi serta kustomisasi lebih lanjut dalam pengembangan UAV.


## Pengertian
- **ESC**: Kontrol Kecepatan Elektronik
- **IMU**: Unit Pengukuran Inersia
- **PID**: Kontrol Proporsional Integral Derivatif


## Source
https://github.com/liourej/CodeDroneDIY

