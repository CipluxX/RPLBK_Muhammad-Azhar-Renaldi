# RPLBK_Muhammad-Azhar-Renaldi

Codingan yang saya buat menerapkan Single Responsibility Principle (SRP) dengan membagi 
tugas menjadi tiga kelas: 

- Kelas `User` => Hanya bertanggung jawab mengelola data pengguna (`username` dan `email`). 
- Kelas `UserRepository` => Hanya bertanggung jawab untuk menyimpan dan menghapus data pengguna dari database. 
- Kelas `EmailService` => Hanya bertanggung jawab untuk mengirim email kepada pengguna. 

Dengan SRP, setiap kelas hanya punya satu tanggung jawab, sehingga perubahan pada satu 
aspek tidak memengaruhi kelas lainnya. 
