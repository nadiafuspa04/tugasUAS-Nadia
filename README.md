# Hello Informatics !

## Menjelaskan dan Menginternalisasi Computational Thinking ⭐⭐⭐⭐⭐⭐⭐
Computational Thinking (Pemikiran Komputasional) adalah suatu kemampuan atau pola pikir yang memungkinkan seseorang untuk memecahkan masalah secara efektif dengan menggunakan konsep dan metode yang umumnya terkait dengan komputasi. Ini melibatkan sejumlah keterampilan kognitif dan konseptual yang dapat diterapkan dalam pemecahan masalah di berbagai konteks. Ada empat elemen kunci dalam computational thinking, yaitu:
Pemecahan Masalah:

Idea Dasar: Pisahkan masalah besar menjadi masalah-masalah kecil.
Contoh Sederhana: Jika masalahnya adalah menyusun puzzle, mulailah dengan memisahkan potongan-potongan puzzle dan fokus pada satu bagian kecil terlebih dahulu.
Algoritma:

Idea Dasar: Rencanakan langkah-langkah langkah demi langkah untuk memecahkan masalah.
Contoh Sederhana: Jika Anda membuat sandwich, langkah-langkahnya mungkin termasuk memotong roti, meletakkan isi di atas roti, dan menutupnya.
Representasi Data:

Idea Dasar: Gambarkan informasi dengan cara yang mudah dimengerti oleh komputer atau orang.
Contoh Sederhana: Jika Anda ingin mencatat berapa banyak kelereng yang dimiliki setiap teman, Anda bisa membuat daftar atau menggambar diagram.
Pemecahan Masalah Secara Abstrak:

Idea Dasar: Sederhanakan masalah dengan fokus pada hal-hal penting.
Contoh Sederhana: Ketika memutuskan apa yang ingin dimakan untuk makan malam, pertimbangkan jenis makanan (misalnya, protein, sayuran) daripada memikirkan merek atau rasa tertentu.
Menginternalisasi Computational Thinking berarti membuat cara berpikir ini menjadi bagian alami dari cara kita memahami dan menyelesaikan masalah sehari-hari. Ini dapat dilakukan dengan:

Memahami ide-ide dasar di atas.
Menggunakan cara berpikir ini ketika menyelesaikan masalah sehari-hari.
Berlatih dengan masalah-masalah kecil dan nyata.
Belajar dari pengalaman dan mencari cara untuk menjadi lebih baik dalam memecahkan masalah.
Dengan melibatkan diri dalam cara berpikir ini, kita dapat menjadi lebih baik dalam menyelesaikan masalah dan membuat keputusan yang lebih baik dalam kehidupan sehari-hari.

## Menjelaskan Jenis-Jenis Mesin Komputasi ⭐⭐⭐
Komputer Buat Sendiri (PC) 

Ini tuh komputer yang buat kita sendiri, bisa desktop, laptop, atau tablet. Biasanya buat main internet, ngetik, atau kerjaan ringan aja.

Komputer Gede Buat Nyimpen Data (Server)

Ini kayak penyimpanan gede buat komputer-komputer lain. Misalnya, kaya gudang besar yang nyimpan barang banyak buat toko.

Komputer Canggih Banget (Superkomputer)

ini komputer yang paling hebat. Dipake buat hitung angka yang banyak banget, misalnya buat ramalan cuaca atau penelitian rumit.

Komputer Bisnis (Mainframe)

Ini komputer buat urusin banyak data bisnis. Kayak bendahara besar yang catat semua transaksi.

Komputer di Alat Listrik (Mikrokontroler)

Ini komputer kecil yang ada di dalam alat-alat elektronik kita. Contohnya di rice cooker atau mobil.

Sistem di Dalam Alat (Embedded Systems)

ini komputer yang diselipin di alat atau mobil buat bantuin kontrol beberapa fungsi khusus.

Komputer yang Canggih Banget dan Aneh (Kuantum Komputer) 

Ini komputer super canggih yang pake fisika aneh buat hitung cepet. Tapi masih di uji coba dan dicari-cari manfaatnya.

Intinya, ada banyak jenis komputer dengan tugas masing-masing, dari yang buat ngetik sampai yang bisa nebak cuaca! Semuanya punya peran penting dalam dunia teknologi.

## Mengktifkan dan Mencoba Google Colab [v] ⭐⭐⭐⭐⭐
https://colab.research.google.com/drive/1bCDKdmElSrEGZLWGpH-IZSx2NsdTxp1d?usp=sharing

## Mencoba Console Sistem Operasi

### Windows CMD [v] ⭐⭐⭐⭐

Berikut adalah beberapa perintah dasar yang sering digunakan di Command Prompt (CMD) pada sistem operasi Windows:

dir: Menampilkan daftar file dan folder dalam direktori saat ini.
cd: Pindah ke direktori lain.
mkdir: Membuat direktori baru.
copy: Menyalin file dari satu lokasi ke lokasi lain.
del: Menghapus file.
rmdir: Menghapus direktori.
ren: Mengganti nama file atau direktori.
type: Menampilkan isi dari file teks.
echo: Menampilkan teks ke layar atau menulis teks ke file.
cls: Membersihkan layar.
help: Menampilkan bantuan untuk perintah tertentu.

### Linux Terminal Menggunakan Google Colab [v] ⭐⭐⭐⭐

## Membuat Algoritma Dalam Bentuk Flow Chart [v] ⭐⭐⭐⭐⭐

![AlgoritmaMasakMie drawio](https://github.com/nadiafuspa04/tugasUAS-Nadia/assets/148792940/edc4acea-7594-46bf-954f-3fc26508c4b3)


## Mencoba Scratch Bahasa Indonesia [v] ⭐⭐⭐⭐⭐⭐⭐

![image](https://github.com/nadiafuspa04/tugasUAS-Nadia/assets/148792940/0305d482-3b3c-4927-997c-61832920d771)

![Screenshot (21)](https://github.com/nadiafuspa04/tugasUAS-Nadia/assets/148792940/8f102956-2281-4276-8d4d-9e77907dcdff)


## Mencoba Algoritma Bubble Sort Menggunakan Java [v] ⭐⭐⭐
public class BubbleSortExample {

    public static void main(String[] args) {
       
        int[] arr = {64, 34, 25, 12, 22, 11, 90};

        System.out.println("Array sebelum diurutkan:");
        printArray(arr);

        
        bubbleSort(arr);

        System.out.println("Array setelah diurutkan:");
        printArray(arr);
    }

    
    static void bubbleSort(int[] arr) {
        int n = arr.length;

        
        for (int i = 0; i < n - 1; i++) {
           
            for (int j = 0; j < n - i - 1; j++) {
                
                if (arr[j] > arr[j + 1]) {
                  
                    int temp = arr[j];
                    arr[j] = arr[j + 1];
                    arr[j + 1] = temp;
                }
            }
        }
    }

    
    static void printArray(int[] arr) {
        for (int value : arr) {
            System.out.print(value + " ");
        }
        System.out.println();
    }
}


## Mencoba dan Mendemonstrasikan Penggunakan IDE ⭐⭐

Jadi,salah satu produk IDE adalah android studio :
![Screenshot (23)](https://github.com/nadiafuspa04/tugasUAS-Nadia/assets/148792940/fc8249ad-d34b-461b-8bda-ed772afb6b89)


## Mendaftar, Mengeksplorasi, dan Mendemonstrasik!
an Penggunaan HackerRank [v] ⭐⭐⭐⭐⭐

## Mendemonstrasikan Pembuatan Aplikasi / Game Pada Platform : Mobile / Desktop / Web Browser ⭐⭐⭐⭐⭐

## Mencoba Instalasi Database (PostgreSQL / MySQL / dsb.) [v] ⭐⭐⭐

Referensi installer [PostgreSQL](https://www.postgresql.org/download/windows/)
Referensi tambahan [1](https://db-engines.com/en/ranking)

## Mencoba Eksplorasi dan Query Database Menggunakan Database Explorer (Dbeaver / dsb.) [v] ⭐⭐⭐

Referensi installer [Dbeaver](https://dbeaver.io/download/)
Referensi [1](https://www.w3schools.com/postgresql/postgresql_create_table.php)

## Mendemonstrasikan dan Menjelaskan Penggunaan Web Browser untuk Mengakses Halaman Website HTML [v] ⭐⭐⭐⭐
- Dokumen HyperText Markup Language (HTML) ada untuk memudahkan pertukaran informasi berbasis Hypertext.
- Web Browser seperti Firefox, Chrome, Opera, ada untuk membuka dan mempresentasikan dokumen HTML
- Dokumen HTML ini bisa bersumber dari web server yang kita ingin datanya (Tokopedia, Wikipedia, Detik.com, dsb.) atau bisa juga dukumen HTML yang kita buat sendiri

## Mendemonstrasikan dan Menjelaskan Komponen Dari Contoh Uniform Resource Locator (URL) [v] ⭐⭐

Referensi: [1](https://www.startertutorials.com/ajwt/uniform-resource-locator.html)

## Mencoba Pelacakan Informasi Server dari Alamat Domain [v] ⭐

Referensi terkait: [1](https://en.wikipedia.org/wiki/Country_code_top-level_domain) [2](https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains)

## Mencoba Pembuatan Halaman Web Menggunakan HTML, CSS, dan JavaScript [v] ⭐⭐⭐

Referensi tutorial 
- Isi konten halaman web : [HTML](https://www.w3schools.com/html/)
- Styling halaman web : [CSS](https://www.w3schools.com/css/)
- Interaktivitas halaman web : [JavaScript](https://www.w3schools.com/js/)

## Mencoba Penerapan Teknik Search Engine Optimization (SEO) Pada HTML [v] ⭐⭐⭐

Referensi []

## Mencoba Pembuatan File JSON [v] ⭐⭐⭐

## Mencoba Penggunaan Web Hosting Dengan Untuk Halaman HTML [v] ⭐⭐⭐


## Mencoba Penggunaan Web Hosting Dengan Untuk Web Service [v] ⭐⭐⭐

## Mencoba HTTP Request dan Web API dengan Hoppscotch / Postman [v] ⭐⭐

## Mendemonstrasikan Penggunaan Developer Tools Pada Web Browser (Firefox / Chrome) [v] ⭐⭐⭐⭐⭐

## Mengeksplorasi dan Menjelaskan Layanan Cloud Service yang Diminati (GCP / AWS / Azure) [v] ⭐⭐
Saat ini banyak perusahaan berbasis digital seperti Gojek, Tokopedia, Instagram, Telkom memanfaatkan Cloud Service karena memudahkan untuk mulai pembangunan dan analisis menggunakan infrastruktur digital yang dapat berkembang secara dinamis dengan tarif yang sangat teliti.

Referensi cloud service: [Amazon Web Service](https://aws.amazon.com/) [Microsoft Azure](https://azure.microsoft.com) [Google Cloud Platform](https://cloud.google.com) 

## Mencoba Penggunaan Content Management System (Wordpress) [v] ⭐⭐⭐

## Mendemonstrasikan Akses Konten Multimedia (Image, Audio, Video) ⭐⭐⭐

## Mencoba Edit Konten Multimedia (Image, Audio, Video) [v] ⭐⭐

## Mencoba Pembuatan Game dan Simulasi Menggunakan Logo [v] ⭐⭐

## Mencoba Pemrosesan Konten Multimedia (Image, Audio) Menggunakan Google Colab [v] ⭐⭐⭐

## Mencoba Web Tool AI Discriminative (Image Classification) [v] ⭐⭐⭐⭐

## Mencoba Web Tool AI Generative (Text to Image, Text to Text) [v] ⭐⭐⭐⭐

## Mencoba Model Machine Learning Menggunakan Google Colab, TTS, Speechrecognition, dan HuggingFace [v] ⭐⭐⭐

## Mencoba Data Visualization Dengan Tools [v] ⭐⭐

## Mencoba Data Visualization Dengan Code [v] ⭐⭐

## Mendaftar dan Mencoba Eksplorasi HuggingFace [v] ⭐⭐⭐

## Mendaftar dan Mencoba Eksplorasi Kaggle [v] ⭐⭐⭐⭐

## Mencoba Protokol Komunikasi IoT (MQTT) [v] ⭐

## Mencoba Memproses File CSV Menggunakan Google Colab [v] ⭐⭐

## Mencoba Memproses File Big Data ORC Menggunakan Google Colab [v] ⭐⭐

## Menjelaskan Jurnal, Conference, Artikel, Grade Jurnal [v] ⭐⭐⭐⭐⭐

## Eksplorasi Artikel Jurnal / Conference di Repository Terekognisi Internasional (IEEE / Arxiv / Science Direct / ACM /DBLP) [v] ⭐⭐⭐⭐

## Menonton Video Presentasi Tugas Akhir Informatika ⭐⭐⭐⭐⭐

## Mengeksplorasi Seluruh Profesi Terkait Informatika dan Profesi yang Diminati ⭐⭐⭐⭐

## Eksplorasi Tools Untuk Belajar Bahasa Inggris (Duolingo) ⭐⭐⭐

## Eksplorasi Tools Untuk Belajar Berbicara Bahasa Inggris (HelloTalk) ⭐⭐⭐ 

## Eksplorasi Lowongan Pekerjaan IT ⭐⭐⭐

## Eksplorasi Lowongan Freelancer IT (Upwork / Toptal / Freelancer.com) ⭐⭐⭐

## Eksplorasi dan Pilih Topik yang Diminati di Roadmap.sh ⭐⭐⭐

## Eksplorasi Top Github Project yang Diminati ⭐⭐ 

## Membangun Profil Linkedin dan Mengikuti Akun-Akun Inspirasif Bertema Informatika ⭐⭐⭐

## Membangun Profil Github Page ⭐⭐⭐⭐⭐

## Mengikuti Workshop / Event / Course Terkait IT ⭐⭐⭐⭐

## Membaca dan Mengambil Inspirasi Dari Buku Bertema Informatika ⭐⭐⭐⭐⭐




