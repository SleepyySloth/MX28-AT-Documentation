# 👽MX28-AT-Documentation👽
## **Repositori ini berisi kode-kode terkait servo dynamixel MX28-AT.**

### Berikut adalah deskripsi masing-masing folder yang tersedia:
+ id
  - Kode untuk mengganti ID servo seperti yang kita inginkan.
+ libraries/Dynamixel2Arduino
  - Library yang wajib untuk diletakkan dalam 1 file source code.
  - Tersedia juga (dapat di-download langsung) di library manager arduino IDE.
+ led
  - Kode untuk menyala-matikan lampu servo setiap 1 detik sekali.
+ ping
  - Kode untuk memberikan "ping" ke servo, untuk memastikan komunikasi antara board dan servo sudah sesuai.
+ position_mode
  - Kode untuk menggerakan servo sekaligus mengetahui posisinya dalam derajat setiap 1 detik sekali.
+ scan_dynamixel
  - Kode untuk scanning id servo, baudrate yang bekerja pada servo, protocol version, dan model number pada servo.
  - Fungsinya mirip dengan dynamixel wizard.

>[!NOTE]
> - Board dan pin yang digunakan disesuaikan di bagian #define
> - Perhatikan voltage yang digunakan untuk menggerakan servo. Servo bekerja di 12V, sedangkan komunikasi datanya di 5V.
> - Board yang eligible: openCM 9.04, OpenCR, OpenRB-150, dan beberapa jenis arduino. Selain dari itu harus menggunakan dynamixel shield.
> - Servo dynamixel milik KRSTI: protocol version = 1.0
> - baudrate biasanya disetel ke 1 Mbps (1000000 bps)

>[!WARNING]
> - Jangan sampai kebalik atau salah dalam menyambungkan VCC dengan pin apapun! karena dapat mengakibatkan short.
> - Selalu cek sambungan dan kualitas jumper.

>[!IMPORTANT]
> - IDE yang direkomendasikan adalah Arduino IDE.
> - Jangan lupa download OpenCM 9.04 di Board Manager dan Library <Dynamixel2Arduino> di Library Manager

## **Sekian, _Happy Coding!_** 😀🌻 
