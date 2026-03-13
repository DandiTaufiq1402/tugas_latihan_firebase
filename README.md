Firebase Auth - Week 4
1. Mengatur Environment di Postman
Langkah pertama adalah menambahkan Environment Variable di Postman untuk menyimpan konfigurasi seperti Firebase API Key.

Langkah-langkah
1. Buka Postman.
2. Masuk ke menu Environment.
3. Tambahkan variable baru, misalnya:
   FIREBASE_API_KEY
4. Isi nilai variable dengan API Key dari Firebase Project.

Contoh tampilan
<img width="1918" height="1078" alt="1" src="https://github.com/user-attachments/assets/4d88d0e9-35bc-4f2c-8ae9-1de886c601df" />

2. Melakukan Request POST ke Firebase Auth API
Setelah environment berhasil dibuat, selanjutnya melakukan request POST ke endpoint Firebase Authentication menggunakan API Key yang sudah disimpan.
demo
<img width="1918" height="1078" alt="2" src="https://github.com/user-attachments/assets/cd50748f-dac8-40a3-92e8-8174a1bbc7e2" />

3. Membuat Auto-save Token
Membuat script auto save token untuk menyimpan IdToken secara otomatis
demo
<img width="1918" height="621" alt="image" src="https://github.com/user-attachments/assets/d47885f2-4ba2-4b8d-b466-d986d55aea73" />

4. Verifikasi gmail menggunakan postman
Verifikasi gmail yang telah dibuat
demo
<img width="1918" height="1078" alt="4" src="https://github.com/user-attachments/assets/69463630-308d-447d-9735-6b0cb0c33dad" />

5. Membuka pesan konfirmasi verifikasi di gmail yang dituju
Konfirmasi verifikasi user gmail
demo
<img width="1427" height="867" alt="5" src="https://github.com/user-attachments/assets/2e5f8d77-14cf-47c0-a4b9-d13a2af84a7e" />

6. Berhasi konfirmasi
Pesan verifikasi sukses diterima
demo
<img width="1917" height="1030" alt="6" src="https://github.com/user-attachments/assets/0ed1d6c9-db45-4a84-b28b-367fc50a097d" />

7. Gmail yang terverifikasi masuk ke authentication firebase
gmail berhasil terautentikasi
Demo
<img width="1386" height="606" alt="7" src="https://github.com/user-attachments/assets/2241f4ba-05bf-4ffd-bf20-36b2e2e530d6" />

8. Melakukan Sign In menggunakan gmail yang tadi terverifikasi
Test sign in
Demo
<img width="1918" height="1078" alt="8" src="https://github.com/user-attachments/assets/3992deaa-677c-46f1-be56-f30a89031121" />

9. Melakukan pengecekan di JWT menggunakan Firebase ID Tokn
Cek lewat JWT
Demo
<img width="1657" height="967" alt="9" src="https://github.com/user-attachments/assets/5fb6ab70-73bd-4622-a011-618dd28446fd" />







