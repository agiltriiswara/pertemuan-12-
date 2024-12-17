# pertemuan-12- lab 8

nama : agil tri iswara
kelas : IE.23.c12

PROGRAM PHYTON

class DaftarNilaiMahasiswa:
    def __init__(self):
        # Inisialisasi daftar nilai mahasiswa
        self.daftar_mahasiswa = []

    def tambah(self, nama, nilai):
        """Menambah data mahasiswa dan nilainya"""
        mahasiswa = {'nama': nama, 'nilai': nilai}
        self.daftar_mahasiswa.append(mahasiswa)
        print(f"Data mahasiswa {nama} dengan nilai {nilai} berhasil ditambahkan.")

    def tampilkan(self):
        """Menampilkan seluruh data mahasiswa"""
        if not self.daftar_mahasiswa:
            print("Tidak ada data mahasiswa.")
        else:
            print("Daftar Nilai Mahasiswa:")
            for mahasiswa in self.daftar_mahasiswa:
                print(f"Nama: {mahasiswa['nama']}, Nilai: {mahasiswa['nilai']}")

    def hapus(self, nama):
        """Menghapus data mahasiswa berdasarkan nama"""
        for mahasiswa in self.daftar_mahasiswa:
            if mahasiswa['nama'] == nama:
                self.daftar_mahasiswa.remove(mahasiswa)
                print(f"Data mahasiswa {nama} berhasil dihapus.")
                return
        print(f"Mahasiswa dengan nama {nama} tidak ditemukan.")

    def ubah(self, nama, nilai_baru):
        """Mengubah data nilai mahasiswa berdasarkan nama"""
        for mahasiswa in self.daftar_mahasiswa:
            if mahasiswa['nama'] == nama:
                mahasiswa['nilai'] = nilai_baru
                print(f"Data nilai mahasiswa {nama} berhasil diubah menjadi {nilai_baru}.")
                return
        print(f"Mahasiswa dengan nama {nama} tidak ditemukan.")

# Contoh penggunaan kelas DaftarNilaiMahasiswa
daftar_nilai = DaftarNilaiMahasiswa()

# Menambah data
daftar_nilai.tambah('agil', 85)
daftar_nilai.tambah('amad', 90)
daftar_nilai.tambah('regi', 78)

# Menampilkan data
daftar_nilai.tampilkan()

# Mengubah data
daftar_nilai.ubah('agil', 95)

# Menghapus data
daftar_nilai.hapus('amad')

# Menampilkan data setelah perubahan
daftar_nilai.tampilkan()


### SS PROGRAM PHYTON ###












<img width="571" alt="image" src="https://github.com/user-attachments/assets/2d3482e8-2d38-4c86-ab7f-127bcb20a26b" />



<img width="502" alt="image" src="https://github.com/user-attachments/assets/3a313d98-d6dc-46ef-84f9-2dbb23e8e841" />




<img width="560" alt="image" src="https://github.com/user-attachments/assets/7ad8e333-825b-4dea-ad0c-1720a499e096" />




<img width="265" alt="image" src="https://github.com/user-attachments/assets/b88942a9-5dbf-497c-a104-21a7a6bb8b39" />




<img width="624" alt="image" src="https://github.com/user-attachments/assets/8b406f9e-1860-4f81-9319-a931b618bdac" />




<img width="629" alt="image" src="https://github.com/user-attachments/assets/00eae63c-8691-42ae-88ce-7d37ebe5f30b" />




<img width="710" alt="image" src="https://github.com/user-attachments/assets/b578986e-2712-4312-897c-26211d1b40a6" />




<img width="723" alt="image" src="https://github.com/user-attachments/assets/1d2ed6bc-d0ab-4575-9a0f-dfa9195bb289" />




<img width="339" alt="image" src="https://github.com/user-attachments/assets/da753496-67cc-4ab5-8ea9-f46a09fa3d8e" />




<img width="328" alt="image" src="https://github.com/user-attachments/assets/9810b5c9-e99c-43f3-b971-706d000ffaf3" />




###FLOW CHART ###
![FLOW CHAR PERTEMUAN 12 LAB 8_page-0001](https://github.com/user-attachments/assets/a05c33cd-9109-4cad-97b7-f02978d19535)




###DIAGRAM CLASS###




![DIAGRAM CLASS PERTEMUAN 12 LAB 8_page-0001](https://github.com/user-attachments/assets/d70e45ed-9a50-486a-bdf9-c1408d6b4bbd)




**Penjelasan Flowchart:**
0.Mulai: Program dimulai.
1.Pilih Opsi: Pengguna memilih opsi untuk menambah data, menampilkan data, menghapus data, atau mengubah data.
2.Tambah: Jika memilih opsi untuk menambah data, data akan ditambahkan ke dalam list.
3.Tampil: Jika memilih opsi untuk menampilkan data, seluruh data mahasiswa akan ditampilkan.
4.Hapus: Jika memilih opsi untuk menghapus data, data mahasiswa berdasarkan nama yang diberikan akan dihapus.
5.Ubah: Jika memilih opsi untuk mengubah data, nilai mahasiswa yang sesuai dengan nama yang diberikan akan diubah.
6.Selesai: Program selesai.






















