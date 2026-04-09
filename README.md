# Praktikum 1 - PHP Framework (CodeIgniter 4)

## Nama
- Nama: Arofah Raudlatul Hasanah
- NIM: 312410231
- Kelas: I241B
## Langkah-langkah Praktikum

### 1. Instalasi CodeIgniter 4
**Screenshot:**  
<img width="478" height="533" alt="Screenshot 2026-04-08 061645" src="https://github.com/user-attachments/assets/e73c2fd2-c70f-4a98-9614-dc845bce2eae" />

---

### 3. Menjalankan CLI CodeIgniter
Selanjutnya saya masuk ke folder project lewat terminal lalu menjalankan perintah `php spark` untuk memastikan CLI CodeIgniter bisa digunakan. Modul juga meminta pengecekan route lewat CLI. 

**Screenshot:**  
<img width="960" height="539" alt="image" src="https://github.com/user-attachments/assets/f63126e5-bf17-42f6-8dfa-dec42c7d53ae" />


---

### 4. Mengaktifkan Mode Debugging
File `env` diubah menjadi `.env`, lalu nilai `CI_ENVIRONMENT` diganti menjadi `development` supaya error lebih mudah diketahui saat proses coding. :contentReference[oaicite:5]{index=5}

**Screenshot:**  
<img width="310" height="117" alt="image" src="https://github.com/user-attachments/assets/601f0c62-2be3-41e6-8439-8c7fb86f7da1" />


---

### 5. Membuat Routing
Routing ditambahkan di file `app/Config/Routes.php` untuk halaman:
- `/about`
- `/contact`
- `/faqs`

Route ini mengarahkan request ke controller `Page`. :contentReference[oaicite:6]{index=6}

**Screenshot:**  
<img width="457" height="248" alt="image" src="https://github.com/user-attachments/assets/542c03d3-20e2-4264-a25e-fd51f6b2cfee" />


---

### 6. Membuat Controller Page
Saya membuat controller `Page.php` di folder `app/Controllers` yang berisi method:
- `about()`
- `contact()`
- `faqs()`

Method ini digunakan untuk menampilkan halaman sesuai route yang telah dibuat. :contentReference[oaicite:7]{index=7}

**Screenshot:**  
<img width="591" height="214" alt="image" src="https://github.com/user-attachments/assets/0c1c1942-1af9-4582-9eb5-5a917bbc48ce" />
<img width="960" height="510" alt="Screenshot 2026-04-08 062651" src="https://github.com/user-attachments/assets/7a30c2c8-ac30-49e9-80ce-9dd94b0a1927" />

---

### 7. Membuat auto routing
screenshot : 
<img width="960" height="512" alt="Screenshot 2026-04-08 063217" src="https://github.com/user-attachments/assets/f239e8e1-4070-4abf-9ac9-d76a1b21ae43" />

---

### 8. Membuat layout web
screenshot:  
<img width="957" height="506" alt="Screenshot 2026-04-08 064704" src="https://github.com/user-attachments/assets/c3ac3f70-acc5-4695-86a1-a15665207148" />

# Praktikum 2 - Framework Lanjutan (CRUD)  
### 1. Membuat database dan tabel artikel   
screenshot :  
<img width="678" height="247" alt="image" src="https://github.com/user-attachments/assets/6cd794b1-efce-4bef-8f76-5d5b616845e5" />  
---
### 2. Konfigurasi Koneksi Database
Saya mengatur koneksi database pada file `.env` agar project CodeIgniter terhubung ke MySQL. :contentReference[oaicite:3]{index=3}
Screenshot :  
<img width="392" height="138" alt="image" src="https://github.com/user-attachments/assets/af70afcb-72f8-4783-bec8-1d7bb74c6697" />  

---

### Membuat Controller, Model, View dan menambahkan data artikel  
Screenshot :  
<img width="960" height="511" alt="Screenshot 2026-04-09 115900" src="https://github.com/user-attachments/assets/2d5a684e-dfb1-45de-a2ad-858f8bc0d236" />

--- 

### Membuat Tampilan Detail artikel 
Screenshot :  
<img width="960" height="508" alt="image" src="https://github.com/user-attachments/assets/3d7e3515-0b1d-414f-85fb-5f6f15bff61d" />  

--- 

### Membuat Menu Admin
Screenshot :  
<img width="960" height="511" alt="Screenshot 2026-04-09 115942" src="https://github.com/user-attachments/assets/711fec53-375c-43f3-9ca5-167b410b35a3" />  

---

### Membuat From tambah dan edit artikel
Screenshot : 
<img width="960" height="511" alt="Screenshot 2026-04-09 115950" src="https://github.com/user-attachments/assets/e946abf8-7022-4efb-ba6c-25776e38e4d0" />
<img width="960" height="513" alt="Screenshot 2026-04-09 120022" src="https://github.com/user-attachments/assets/1b963060-076d-41c3-a94b-17a82dbd4362" />

--- 









