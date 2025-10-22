# UTS Penambangan Data - Kelompok 12
---

## Anggota Kelompok 8
| No | Nama Lengkap | NIM |
|----|---------------|-----|
| 1. | Harisya Miranti | 122140049 |
| 2. | Shafa Aulia | 122140062 |
| 3. | Elma Nurul Fatika | 122140069 |

## Deskripsi Singkat
Dalam proses **penambangan data (data mining)**, kualitas dan struktur dataset memegang peranan penting terhadap keberhasilan analisis serta akurasi model prediktif.  
Pada dataset **transaksi pembelian obat di Apotek XYZ**, ditemukan dua permasalahan utama yang menjadi fokus analisis, yaitu **ketidakseimbangan kelas (imbalanced data)** dan **redundansi data (data redundancy)**.

Dataset ini berisi informasi transaksi pembelian obat dengan atribut seperti:
- `kode`  
- `nama product`  
- `unit`  
- `tgl transaksi`  
- `kode transaksi`  
- `kategori`  
- `qty` (jumlah pembelian)  
- `nilai` (nilai transaksi)

---

## Permasalahan Utama
1. **Ketidakseimbangan kelas (Imbalanced Data)**  
   Sebagian besar transaksi (±95%) termasuk kategori *Obat Bebas*, sedangkan hanya 5% merupakan *Obat Resep Dokter*.  
   Ketimpangan ini berpotensi membuat model pembelajaran mesin menjadi **bias terhadap kelas mayoritas**.

2. **Redundansi Data (Data Redundancy)**  
   Ditemukan **duplikasi entri pada kolom `kode transaksi`**, terutama antar cabang yang berbeda.  
   Hal ini dapat menyebabkan **distorsi statistik dan bias analisis**, jika tidak dibersihkan terlebih dahulu.

---

## Tujuan Analisis
Analisis ini bertujuan untuk:
- Meningkatkan **kualitas, konsistensi, dan efisiensi dataset pembelian obat**.  
- Menangani **duplikasi dan redundansi data** agar data menjadi lebih akurat.  
- Mengatasi **ketidakseimbangan kelas** agar model prediksi stok obat tidak bias.  
- Melakukan **analisis dependensi fungsional (functional dependency)** untuk memastikan hubungan logis antar atribut (`kode → nama produk → unit`).

---

>  **Mata Kuliah:** Penambangan Data   
>  **Tahun:** 2025
