# -informasi-gathering


Nama  : M Diaz Alfarizi
Nim   : 09030582225035
Prodi : Teknik Komputer

1. pertama kita harus melakukan coman sudo apt-get update terlebih dahulu, seletah itu jalankan perintah sudo apt-get install python3 python3-pip
   
    ![1](https://github.com/user-attachments/assets/52d2b4ef-b722-4194-8402-fc794b9abd2c)

2. selanjutnya yaitu lakukan perintah sudo pip3 install sublist3r, setelah terintal kita dapat mencari domain dengan gmail.com yaitu dengan melakukan perintah sublist3r -d   gmail.com. Setelah Sublist3r menyelesaikan pencarian, kita bisa lihat hasil yang berisi daftar subdomain yang terkait dengan gmail.com

   ![dua](https://github.com/user-attachments/assets/0e190d1e-950c-48b9-a104-4e47aa66f57a)

3. Dari contoh command di atas bisa di kombinasikan dengan opsi lain, misalnya -t untuk melihat threads. contohnya seperti ini sublist3r -d youtube.com -t 5 dengan menggunakan -t 5 berfungsi untuk melihat

   ![1](https://github.com/user-attachments/assets/30d8df24-eca9-4526-809d-d04bebeae3fb)

4. Opsi yang bisa dicoba selanjutnya yaitu -p befungsi untuk melihat port yang aktif, contohnya sublist3r -d youtube.com -p 443,80 disini kita ingin mengecek port 443 , dan 80

   ![2](https://github.com/user-attachments/assets/cc0ab89a-9bde-4608-9820-ff2580c0ebf1)





