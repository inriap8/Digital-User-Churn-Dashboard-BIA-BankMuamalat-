# Digital User Churn Dashboard PT Sejahtera Bersama (Final Task Bank Muamalat Business Intelligence Analyst Project Based Internship Program)
## Case Study
Sebagai BI analyst PT Sejahtera Bersama, apa yang bisa anda usulkan untuk mempertahankan penjualan ataupun menaikkan penjualan berdasarkan 4 dataset penjualan:
1.	Customer
2.	Products 
3.	Orders 
4.	ProductCategory

## Dataset
- <a href="https://github.com/inriap8/Digital-User-Churn-Dashboard-BIA-BankMuamalat-/blob/main/Customers.xlsx">Dataset Customer</a>
- <a href="https://github.com/inriap8/Digital-User-Churn-Dashboard-BIA-BankMuamalat-/blob/main/Orders.xlsx">Dataset Orders</a>
- <a href="https://github.com/inriap8/Digital-User-Churn-Dashboard-BIA-BankMuamalat-/blob/main/ProductCategory.xlsx">Dataset ProductCategory</a>
- <a href="https://github.com/inriap8/Digital-User-Churn-Dashboard-BIA-BankMuamalat-/blob/main/Products.xlsx">Dataset Product</a>

## Langkah Pengerjaan
1.	Menentukan masing-masing primary key pada 4 dataset penjualan.
2.	Menentukan relationship dari ke-4 table.
3.	Membuat sebuah table master dari ke-4 table (Google BigQuery).
4.	Membuat visualisasi yang menampilkan data penjualan tersebut (Looker Studio).
5.	Memberikan usulkan untuk mempertahankan penjualan ataupun menaikkan penjualan dengan tabel transaksi detail yang sudah ada.

## Query (Google BigQuery)
![Cuplikan layar 2025-01-22 144415](https://github.com/user-attachments/assets/eef14a4e-8231-42bc-b5f0-87c839e8d83a)

## Tebel Hasil Query
![Cuplikan layar 2025-01-22 144626](https://github.com/user-attachments/assets/9e6f3f14-981c-414b-9ba2-bb7cca5fdf63)

## Dashboard (Looker Studio)
![Dashboard](https://github.com/user-attachments/assets/a03244fa-4076-4bb0-8b51-d2ef6e7a6ca7)

## Insight
-	Produk kategori Robot menempati posisi pertama total sales, yaitu sebesar 743.505, sedangkan quantity order terbesar ditempati oleh produk kategori eBooks dengan 3.123 penjualan.
-	Kota dengan total sales dan quantity order tertinggi ditempati oleh Washington dengan 55.381,94 dan 308 penjualan.
-	Bulan Juni 2021 merupakan periode tertinggi penjualan dengan total sales sebesar 95.401,53 dan quantity order 582.
-	MICR-23K dari kategori Robot merupakan produk dengan total sales tertinggi yaitu sebesar 157.325, sedangkan Sleepy Eye dari kategori Blueprints adalah produk dengan quantity order tertinggi dengan 312 penjualan.

## Kesimpulan
	Beberapa usulan yang dapat dipertimbangkan untuk mempertahankan penjualan ataupun menaikkan penjualan:
-	Total sales dan quantity order di akhir tahun (Bulan Desember) selalu mengalami penurunan dibandingkan dengan awal tahun (Bulan Januari). Untuk mengatasi periode penurunan penjualan di akhir tahun seperti ini, tim marketing dapat memberikan diskon akhir tahun agar dapat menarik minat customer untuk berbelanja sehingga dapat meningkatkan penjualan.
-	Robot menempatkan diri sebagai kategori produk dengan total sales tertinggi, tetapi menempati posisi terendah kedua dalam quantity order. Maka diperlukan upaya untuk meningkatkan penjualan produk kategori Robot, misalnya dengan menambahkan jenis robot lainnya pada penjualan yang dipilih berdasarkan minat yang sedang berkembang di masyarakat.
-	Quantity order dari produk kategori eBooks menempati posisi pertama dibandingkan dengan kategori lainnya. Untuk mempertahankan atau bahkan menaikkan penjualan eBooks dapat dengan menambah kategori atau judul eBooks yang dijual, misalnya untuk kategori novel dapat menambahkan judul-judul baru untuk genre buku yang sedang diminati di pasaran.


