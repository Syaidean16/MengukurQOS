## NAMA : SYAI DEAN PUTRI
## KLS  : TK4C
## NIM  : 09030282327044

# Mengukur QOS menggunakan wireshark

## 1. Pastikan Komputer/Laptop sudah terhubung ke internet.
   
## 2. Buka aplikasi Wireshark, lalu pilih interface yang terhubung ke internet
![Screenshot 2025-02-18 215421](https://github.com/user-attachments/assets/5bd4dce5-0e03-4fad-815a-20de26d3f81c)

## 3. Jalankan wireshark untuk melakukan capture packet.
![Screenshot 2025-02-19 151635](https://github.com/user-attachments/assets/6972dfb4-4511-4d9b-970e-b06cabe02b09)

## 4. Selanjutnya, lakukanlah beberapa kegiatan di Komputer/Laptop kalian seperti menonton YouTube, Upload, Download dan kegiatan yang berhubungan dengan internet lainnya selama ±5 menit.
![Screenshot 2025-02-19 141221](https://github.com/user-attachments/assets/29573347-b320-4c16-b5ae-617f4e1420ec)


## 5. Jika sudah ±5 menit, selanjutnya stop melakukan capturing packet dengan menekan ikon berbentuk kotak dipojok kiri atas.
![WhatsApp Image 2025-02-19 at 15 19 41_6a4d25c5](https://github.com/user-attachments/assets/8bab0871-3e32-4a15-9be7-a4a91d5eab86)

## 6.Selanjutnya lihat properties dari packet capture yang dilakukan. Dengan menekan Statistics > Caputure File Properties, atau dapat langsung menekan Ctrl+Alt+Shift+C pada keyboard secara bersamaan. 
![Screenshot 2025-02-19 152402](https://github.com/user-attachments/assets/6029e645-f5c0-443b-b194-6f188568e2a9)

## 7. Perhatikan bagian Statistics pada halaman Capture File Properties. Pada halaman ini kita dapat melakukan perhitungan Throughput, Packet Loss, Delay, dan Jitter.
![Screenshot 2025-02-19 142029](https://github.com/user-attachments/assets/e5062c4b-1233-4866-b704-4639f4711391)

![Screenshot 2025-02-19 142154](https://github.com/user-attachments/assets/ea547ab8-116a-4f8b-9685-96f33a733723)


## 8. Hitunglah berapa Throughput, Packet Loss, Delay, dan Jitter yang didapatkan dari Statistics Wireshark yang kalian jalankan di Komputer/Laptop masing-masing. 

## Parameter qos 

## Thoughput :

jumlah bytes : time span = hasil bytes

447543026 : 1921.477 = 232,9161504405205  b x 8 

     = 1863 k



## Packet loss :

[((Paket dikirim - Paket diterima)  : Paket dikirim) x 100]
	
 = (499576  - 499564 ) : 499576  ) x 100

 = (12 : 499576)

   = 0,0


## Delay :

Total Delay 	: 8,521319 s	


Rata-rata Delay :0,00362147 sx 1000 = 3,62147 ms 



## Jitter

Total jitter	 : 0,064633 s


Rata-rata Jitter : 2,75E-05 s x 1000 = 2.750ms


