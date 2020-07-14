# Praktikum VoIP Lab. CPS
### Apa itu Cloud VoIP?
- Pada sistem Cloud VoIP, *PBX* atau *Call server* di jalankan pada Cloud. Jadi, kita tidak perlu membeli hardware seperti *PBX*/*PC*/*Server* untuk menjalankan dan *me-maintain* VoIP tersebut.

- **miniSIPServer Cloud** merupakan salah satu contoh Cloud VoIP.

### Ilustrasi Cloud VoIP
![3__1](https://user-images.githubusercontent.com/56960819/87371351-57ba5780-c5af-11ea-83f8-1f2b51d3a2ab.jpg)

- Dari gambar diatas, bisa kita simpulkan PC milik Holly dan PC milik GT masing-masing terhubung dengan **Virtual miniSIPServer Cloud** dimana domainnya "7859.s1.minisipserver.com"

- Metode ini bisa kita aplikasikan pada praktikum online kita di modul **SIP / VoIP**

### Step by step instalasi & konfigurasi

1. Pertama kita harus ***Sign up*** & ***Sign in*** sebuah akun pada website https://www.minisipserver.com/index.html

   jika sudah ***Sign in*** maka klik ***Data/Server*** untuk mengetahui domain miniSIPServer Cloud kita. 
   
   - *(setiap akun yang berhasil dibuat, akan diberikan domain gratis. sebaiknya kita memakai 1 akun saja untuk praktikum nanti, agar praktikan tidak bingung.)*
  
  ![](https://www.minisipserver.com/docs/setup-cloud-voip-step-by-step/sys_info.jpg)
  
  Pada ilustrasi diatas, domain server kita berada pada "7859.s1.minisipserver.com"

2. Setelah kita mengetahui domain kita, kita harus membuat akun local untuk praktikan agar mereka bisa saling komunikasi.

  - klik ***Data/Local user***  dan klik ***Add local user*** untuk menambahkan akun local ke Cloud server
  
  ![image](https://user-images.githubusercontent.com/56960819/87373029-15931500-c5b3-11ea-9e90-943da6e0163b.png)

  ![image](https://user-images.githubusercontent.com/56960819/87373199-6f93da80-c5b3-11ea-9238-8a43a627e1fc.png)

  - *(secara default, ada beberapa akun local yang sudah terbuat, seperti 100,101,102)*
  
  Masukkan username & password sesuka kita.
  
  3. Download Aplikasi Softphone disini https://www.myvoipapp.com/download
  
  ![image](https://user-images.githubusercontent.com/56960819/87373737-70793c00-c5b4-11ea-9a27-d7ae6eef5af8.png)
  
  - *(download yang miniSIPPhone V7.3)*
    
   4. Setelah install SIPPhone, klik ***File/ SIP Account***
   
   ![image](https://user-images.githubusercontent.com/56960819/87378767-c5b74c80-c5b8-11ea-88c2-ee9be4d10401.png)
    
   Setelah itu akan muncul menu seperti ini
    
    
   ![image](https://user-images.githubusercontent.com/56960819/87378831-f5feeb00-c5b8-11ea-8ff0-2589eadcf76e.png)
   
   Masukkan data-data sesuai akun yang kita buat tadi.
   
   - *(perhatikan SIP Server adress. isi sesuai domain yang kita dapat tadi. pada ilustrasi diatas domain kita "7859.s1.minisipserver.com" )*
   
   Klik OK untuk menyelesaikan konfigurasi.
   
   
   5. Untuk test apakah sudah berhasil, Buat 2 akun dan login menggunakan PC yang berbeda.
   
   ![image](https://user-images.githubusercontent.com/56960819/87379986-b554a100-c5bb-11ea-9169-1964c0c1ab4a.png)
   
   Sekarang Holly sudah terkoneksi dengan Cloud server yang kita buat. Lakukan hal yang sama untuk GT pada PC yang berbeda 
   
   - *(bisa pake ubuntu untuk GT.)*
   
   ![image](https://user-images.githubusercontent.com/56960819/87380897-a8d14800-c5bd-11ea-83b0-a46a642b0a7a.png)
   
   Jika kedua akun sudah connect, maka gambar nya akan berubah warna menjadi biru spt diatas. untuk menelfon Holly atau GT, kita tinggal masukkan nomornya
   
   - *(pada ilustrasi diatas nomor Holly 100 dan nomor GT 102)*
   
   
   
   
 
