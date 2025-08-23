# Panduan Kontribusi

Terima kasih banyak atas minat Anda untuk berkontribusi pada proyek skin AIMP bertema anime ini! Kontribusi Anda sangat berarti.

Sebelum memulai, pastikan Anda memahami alur kerja dan aturan yang ada. Hal ini untuk memastikan proses kolaborasi berjalan lancar.

---

### Jenis Kontribusi yang Diterima

Saat ini, kami menerima kontribusi untuk hal-hal berikut:

1.  **Pencarian Desain (Image Hunting):** Membantu mencari gambar atau wallpaper berkualitas tinggi yang cocok untuk desain skin.
2.  **Bantuan Desain Grafis:** Mengedit file PSD (Photoshop) yang sudah kami sediakan untuk membuat bagian-bagian skin (seperti tombol, background, dll.) berdasarkan desain yang sudah disetujui.

---

### Aturan Kontribusi

Untuk menjaga konsistensi dan kualitas, mohon ikuti aturan berikut:

* **Penting:** Selalu mulai dengan membuat [**Issue**](https://github.com/smiotaku/saeskin-gi/issues) terlebih dahulu.
* **Hak Cipta:** Hanya gunakan gambar yang bebas hak cipta atau gambar yang jelas untuk penggunaan non-komersial. Jika Anda ragu, berikan sumber gambarnya.
* **Konsistensi PSD:** **Jangan** mengubah struktur layer atau nama layer pada file PSD yang kami sediakan.
* **Kualitas Gambar:** Gambar yang digunakan harus memiliki resolusi tinggi dan tidak buram.

---

### Alur Kerja Kontribusi

Ikuti langkah-langkah berikut untuk mengirimkan kontribusi Anda:

1.  **Fork Repositori:** Buka halaman utama repositori ini dan klik tombol **"Fork"** di pojok kanan atas.
2.  **Buat Branch Baru:** Setelah Anda memiliki salinan repositori, **clone** ke komputer lokal Anda dan buat branch baru:  
    `git clone https://github.com/smiotaku/saeskin-gi.git`  
    `git checkout -b saeskin-gi`  
3.  **Kerjakan Kontribusi Anda:**
    * **Desain Grafis:** Unduh file PSD, edit, lalu simpan kembali dalam folder yang sama.
    * **Pencarian Gambar:** Buat folder baru untuk skin yang Anda kerjakan, lalu unggah gambar-gambar ke sana.
4.  **Commit dan Push Perubahan:** Setelah semua pekerjaan selesai, tambahkan perubahan, *commit*, dan *push* ke repositori Anda:  
    `git add .`  
    `git commit -m "feat: tambahkan desain untuk skin Anya Forger"`  
    `git push origin saeskin-gi`  
5.  **Buat Pull Request (PR):** Buka repositori Anda di GitHub, klik tombol **"Pull Request"**, isi deskripsi dengan jelas dan tautkan ke *issue* yang terkait, lalu kirim PR Anda.
