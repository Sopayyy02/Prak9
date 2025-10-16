# 🤓 Pertemuan Kesembilan
Proyek ini bertujuan untuk mempelajari dan menerapkan pembuatan laporan dinamis menggunakan iReport dan JasperReports dalam lingkungan Java (NetBeans) dengan JDK 20 ke atas.

# 📖 Deskripsi Tugas
**Tugas proyek ini mencakup:**
-	Instalasi iReport: Mengunduh dan menginstal iReport versi terbaru, serta menyesuaikan dengan lingkungan JDK 20 ke atas.
-	Integrasi dengan NetBeans: Menyambungkan iReport dengan proyek Java di NetBeans agar laporan dapat dibuat dan dijalankan langsung dari IDE.
-	Pembuatan Laporan: Mendesain laporan dengan menggunakan iReport, termasuk penggunaan Rectangle untuk struktur tabel, Field dan Parameter untuk menampilkan data dinamis.
-	Koneksi Database: Menghubungkan laporan dengan database PostgreSQL untuk menampilkan data secara real-time.
-	Pengujian Laporan: Menjalankan laporan yang dihasilkan untuk memastikan data tampil sesuai dengan desain dan parameter yang diinput

  
**Tujuan Proyek:**
-	Memahami langkah-langkah instalasi iReport dan konfigurasi agar kompatibel dengan JDK 20 ke atas.
-	Mampu mengintegrasikan iReport dengan NetBeans untuk proyek Java.
-	Melatih pembuatan laporan yang dinamis dan interaktif menggunakan iReport, termasuk penggunaan parameter dan subreport.
-	Memahami cara menghubungkan laporan dengan database PostgreSQL secara langsung.
-	Mengembangkan keterampilan dalam menyajikan data dalam format laporan profesional melalui Java dan iReport.


# 🤔 Apa itu iReport dan JasperReports??
- iReport: Merupakan visual report designer berbasis Java yang digunakan untuk membuat laporan dalam format PDF, HTML, Excel, dan format lainnya. iReport adalah frontend untuk JasperReports, memungkinkan pengguna mendesain laporan secara visual.

- JasperReports: Merupakan library Java yang menangani proses generate laporan dari file JRXML (template laporan) dan data database. JasperReports memproses laporan menjadi output siap cetak atau format digital lainnya.

# 📚 Library Pendukung
Beberapa library penting yang digunakan dalam proyek ini:
1. commons-logging-1.2.jar → Digunakan untuk logging dan debugging dalam JasperReports.
2. commons-digester-2.1.jar → Digunakan untuk parsing XML, termasuk membaca file JRXML.
3. AbsoluteLayout.jar → Menyediakan AbsoluteLayout untuk desain GUI atau laporan.
4. groovy-all-2.4.5.jar → Mendukung script Groovy dalam laporan, misalnya untuk logika custom di laporan.
5. itextpdf-5.5.4.jar → Digunakan untuk generate output PDF dari laporan.
6. jasperreports-6.21.5.jar → Library utama JasperReports untuk generate laporan dari JRXML ke berbagai format.
7. commons-collections4-4.4.jar → Mendukung struktur data tambahan yang digunakan JasperReports.


