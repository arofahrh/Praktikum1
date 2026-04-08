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

### 7. Membuat auto roting
screenshot : 
<img width="960" height="512" alt="Screenshot 2026-04-08 063217" src="https://github.com/user-attachments/assets/f239e8e1-4070-4abf-9ac9-d76a1b21ae43" />

---

### 8. Membuat layout web
screenshot:  
<img width="957" height="506" alt="Screenshot 2026-04-08 064704" src="https://github.com/user-attachments/assets/c3ac3f70-acc5-4695-86a1-a15665207148" />

