# Post-Test-PBO-1

Nama: Azhaar Athahiroh
NIM: 2409116057

## Deskripsi:
Program ini dibuat dengan Java untuk mengatur daftar outfit harian. Program ini punya fitur sederhana: bisa nambah, lihat, ubah, dan hapus data outfit. Data outfit disimpan di dalam ArrayList dan semua program dijalankan di dalam method main.

## Alur Program
1. Inisialisasi Data
   - Program membuat ArrayList<String> outfits untuk menyimpan daftar outfit.
   - Tiga outfit default langsung ditambahkan ke dalam list.
     
2. Menu Utama (Looping do...while)
   - Program menampilkan menu:
     1. Tambah Outfit
     2. Lihat Outfit
     3. Ubah Outfit
     4. Hapus Outfit
     5. Keluar
  - User diminta memilih dengan mengetik angka 1–5.
  - <img width="236" height="125" alt="image" src="https://github.com/user-attachments/assets/fa6c6de5-3c6c-4f3b-a2f4-e7d6e48183b4" />



3. Pilihan Menu
   - **Case 1** = Tambah Outfit
     
     User mengetik outfit baru.
     
     Jika outfit sudah ada = ditolak.
     
     <img width="443" height="58" alt="image" src="https://github.com/user-attachments/assets/dbd29cb0-8f3a-470d-a047-d465f15c580e" />

     Jika belum ada = ditanya yakin/tidak:
     
     ya = outfit disimpan ke list.
     
     tidak = dibatalkan, kembali ke menu.
     
     <img width="281" height="395" alt="image" src="https://github.com/user-attachments/assets/459de45a-669c-449f-95d6-02f32de13694" />

     selain itu = dianggap input tidak valid, kembali ke menu.
     
     <img width="309" height="194" alt="image" src="https://github.com/user-attachments/assets/3f2b447b-e217-4bc9-bc07-5839d0cef37f" />

   - **Case 2** = Lihat Outfit
     
     Jika list kosong = tampil pesan “Belum ada outfit”.
     
     <img width="229" height="174" alt="image" src="https://github.com/user-attachments/assets/6e263992-2c15-469a-93a8-f45046c188a9" />

     Jika tidak kosong = tampil semua outfit dengan nomor urut.
     
     <img width="335" height="78" alt="image" src="https://github.com/user-attachments/assets/300beea4-d6aa-4f65-82ac-6e4265cd5e60" />

   - **Case 3** = Ubah Outfit
     
     Jika list kosong = tampil pesan "Belum ada outfit untuk diubah".
     
     <img width="233" height="139" alt="image" src="https://github.com/user-attachments/assets/b82c90cc-b7f9-4236-93ed-3261a54ae7d6" />

     Jika ada = user pilih nomor outfit:
     
     Jika 0 = batal ubah.
     
     <img width="333" height="225" alt="image" src="https://github.com/user-attachments/assets/4dcd54f2-ec28-4033-9d52-743f8156e3ac" />

     Jika nomor yang dimasukin valid = ditanya yakin atau tidak untuk ubah:
     
     ya = user memasukkan outfit baru, menggantikan outfit lama.
     
     tidak = dibatalkan dan balik ke menu.
     
     <img width="369" height="541" alt="image" src="https://github.com/user-attachments/assets/684dc86a-498d-422a-b636-b4255a4d0558" />

     selain nomor yang ada = nomor tidak valid.
     
     <img width="336" height="110" alt="image" src="https://github.com/user-attachments/assets/831c2872-c7e0-46d7-8495-7dc1646596d8" />

   - **Case 4** = Hapus Outfit
     
     Jika list kosong = tampil pesan belum ada yang bisa dihapus.
     
     <img width="237" height="146" alt="image" src="https://github.com/user-attachments/assets/33fa96d9-879b-4997-bbdf-3b7607c1d586" />

     Jika ada = user pilih nomor outfit:
     
     Jika 0 = batal hapus.
     
     <img width="332" height="223" alt="image" src="https://github.com/user-attachments/assets/affa0db8-5ee1-4b13-90f8-1c2f99fc027d" />

     Jika nomor valid = ditanya yakin atau tidak untuk hapus:
     
     ya = outfit dihapus.
     
     tidak = dibatalkan.
     
     <img width="357" height="485" alt="image" src="https://github.com/user-attachments/assets/4fd9af27-9667-4322-852a-b820f5896fb7" />

     selain itu = input tidak valid.
     
     <img width="337" height="205" alt="image" src="https://github.com/user-attachments/assets/1906204b-2fcf-4a22-b9f7-99897e1fe709" />

     
   - **Case 5** = Keluar Program
     
     Ditanya: yakin mau keluar atau tidak.
     
     ya = keluar dari program.
     
     <img width="270" height="160" alt="image" src="https://github.com/user-attachments/assets/4fc481f9-576e-42e9-8f71-12556e46901e" />

     tidak = batal keluar, kembali ke menu.
     
     <img width="302" height="164" alt="image" src="https://github.com/user-attachments/assets/1f11e4be-5ae1-4cb9-ab3e-a7ea3ac6cbfe" />

     selain itu = input tidak valid, kembali ke menu.
     
     <img width="329" height="53" alt="image" src="https://github.com/user-attachments/assets/fb2324d7-6efd-4f30-9487-22701b4fbd94" />

    - **Default**

      Jika user mengetik angka selain 1–5 = tampil pesan “Pilihan tidak valid. Coba lagi.” lalu kembali ke menu.

      <img width="260" height="147" alt="image" src="https://github.com/user-attachments/assets/97bf3201-f43f-4b26-804e-da81d8bf1419" />

   - **Perulangan**
     
      Setelah setiap selesai dari satu menu, program akan menampilkan menu lagi.

     Perulangan berhenti hanya jika user memilih 5 (Keluar) dan mengonfirmasi dengan ya.

4. Akhir Program
   
   - Scanner ditutup, program selesai.
