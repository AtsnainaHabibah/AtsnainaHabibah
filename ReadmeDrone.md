
# Proyek Drone

Proyek **Drone** ini adalah bertujuan untuk mengembangkan dan menerapkan sistem drone yang sepenuhnya fungsional. Proyek ini mencakup komponen perangkat keras dan perangkat lunak, yang memungkinkan modularitas, skalabilitas, dan kemudahan penggunaan. Proyek ini cocok untuk hobiis, peneliti, dan pengembang yang ingin membuat drone yang dapat disesuaikan untuk berbagai aplikasi seperti fotografi udara, pemetaan, pemantauan, dan navigasi otonom.

## Fitur Utama

### 1. **Desain Modular**
   - Drone ini dibangun dengan pendekatan modular, sehingga mudah untuk mengganti atau memperbarui bagian tanpa perlu melakukan perombakan besar.
   - Pengontrol penerbangan yang dapat dikustomisasi dengan dukungan untuk berbagai sensor dan kamera.

### 2. **Navigasi Otonom**
   - Kemampuan terbang otonom menggunakan GPS dan sensor IMU.
   - Jalur penerbangan yang sudah diprogram untuk misi tertentu.
   - Deteksi dan penghindaran rintangan secara real-time menggunakan sensor ultrasonik atau LiDAR.

### 3. **Fotografi dan Video Udara**
   - Integrasi kamera beresolusi tinggi untuk fotografi udara.
   - Streaming video real-time dengan latensi rendah untuk penerbangan FPV (First-Person View).
   - Dukungan stabilisasi gimbal untuk pengambilan video yang lebih halus.

### 4. **Ground Control Station (GCS)**
   - Mengontrol drone dari ground control station menggunakan aplikasi yang dibuat khusus atau perangkat lunak GCS open-source seperti Mission Planner atau QGroundControl.
   - Pengiriman data telemetri untuk pemantauan penerbangan secara real-time, termasuk ketinggian, kecepatan, posisi GPS, dan status baterai.

### 5. **Mekanisme Failsafe**
   - Fitur otomatis kembali ke rumah (*Return-to-Home*, RTH) ketika baterai rendah atau koneksi terputus.
   - Protokol pendaratan darurat jika terjadi kegagalan sistem.
   - Geofencing untuk mencegah drone terbang ke area terlarang.

### 6. **Firmware Kustom**
   - Dukungan untuk firmware kustom menggunakan sistem kontrol penerbangan open-source seperti ArduPilot atau PX4.
   - Kemampuan untuk menulis algoritma penerbangan kustom untuk kasus penggunaan tertentu.

### 7. **Perencanaan Misi**
   - Perencanaan misi berbasis waypoint melalui GCS.
   - Pembaruan misi real-time dan penyesuaian rute selama penerbangan.

## Kebutuhan Perangkat Keras

- **Flight Controller:** Pengontrol penerbangan yang kompatibel dengan ArduPilot atau PX4 (misalnya Pixhawk, APM).
- **Motor:** Motor DC brushless (4x atau 6x tergantung pada desain drone).
- **Propeller:** Ukuran propeller tergantung pada motor; biasanya 10" hingga 15".
- **ESC (Electronic Speed Controller):** Sesuaikan dengan spesifikasi motor.
- **Baterai:** Baterai LiPo, 4S atau 6S tergantung pada kebutuhan daya.
- **Frame:** Rangka serat karbon atau aluminium ringan.
- **GPS Module:** Untuk navigasi dan penerbangan otonom.
- **Sensor IMU:** Gyroscope, akselerometer, magnetometer.
- **Sensor Ultrasonik/LiDAR:** Untuk deteksi rintangan (opsional).
- **Kamera:** Untuk pengambilan foto atau video udara (opsional).
- **Modul Telemetri:** Untuk transmisi data real-time ke ground control station.

## Komponen Perangkat Lunak

### 1. **Firmware**
   - **ArduPilot atau PX4:** Perangkat lunak kontrol penerbangan open-source untuk drone. Ini mendukung misi otonom, penghindaran rintangan, dan berbagai jenis kendaraan.

### 2. **Perangkat Lunak Ground Control**
   - **Mission Planner:** Perangkat lunak GCS berbasis Windows untuk perencanaan misi, kontrol penerbangan, dan pemantauan telemetri.
   - **QGroundControl:** GCS lintas platform untuk kontrol penerbangan dan perencanaan misi.

### 3. **Komunikasi Real-Time**
   - **Protokol MAVLink:** Digunakan untuk komunikasi antara drone dan GCS, mendukung telemetri dan eksekusi perintah real-time.

### 4. **Visi Komputer (Opsional)**
   - Integrasi dengan pustaka visi komputer open-source seperti **OpenCV** untuk deteksi dan pelacakan objek.

## Instalasi

### 1. **Perakitan Perangkat Keras**
   - Rakit rangka drone, pasang motor, ESC, dan flight controller. Instal GPS, modul telemetri, dan sensor atau muatan lainnya.

### 2. **Instalasi Firmware**
   - Flash pengontrol penerbangan dengan firmware yang sesuai (misalnya ArduPilot atau PX4) menggunakan Mission Planner atau QGroundControl.

### 3. **Konfigurasi Ground Control Station**
   - Konfigurasikan aplikasi GCS sesuai dengan perangkat keras dan firmware drone Anda.

### 4. **Pengujian dan Kalibrasi**
   - Sebelum penerbangan, pastikan untuk melakukan kalibrasi komponen seperti GPS, IMU, dan pengontrol penerbangan untuk memastikan drone bekerja dengan benar.

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan lakukan fork pada repositori ini, buat fitur baru di branch terpisah, dan kirimkan pull request.

