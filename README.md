# latihan-1
LANGKAH PERTAMA :

cara pertama sebelum menggunakan github yaitu membuat akun github dan ini halaman utama nya.
Setelah terbuat akun-nya, login dengan akun baru(kalau langsung diarahkan ke halaman utama), 
setelah itu pada pojok kanan atas terdapat tombol “+”, klik button tersebut dan pilih “new repository”.

LANGKAH KEDUA :

Membuat Repositori online :
 
Tombol add
Lalu kalian akan diarahkan ke halaman pembuatan repository, pembuatan repositori ini tergantung dari project kalian yang mau kalian upload, jadi saya harapkan kalian sudah punya proyek yang ingin di upload ke repositori.

Form repositori :
Untuk mengisi, ada beberapa hal yang perlu di perhatikan :
•	Repository name : nama repository(isi saja dengan nama proyek), akan lebih rapi kalau misalnya nama repository juga di beri jenis pemogramannya juga contohnya “Android/test” atau “js/test”.
•	Description : deskripsi repository (bisa kisah project dan siapa yang terlibat)
•	Public/Private : kondisi repository mau di public (di buat umum) atau private(di buat pribadi atau tertutup)
•	Intiallize the repository with README : ini adalah isi dokumentasi pada project yang dikerjakan, saya sarankan tidak usah di centang karena mempermudah praktek untuk mengelola git.

Contoh project yang saya gunakan adalah “js/belajar-react”
Setelah di isi sesuai dengan keinginan, klik saja tombol “create repository”, maka pada halaman selanjutnya akan menampilkan repositori yang sudah dibuat, dan tahap selanjutnya adalah upload project ke repository online.

Mengupload folder(repositori lokal)
Sebelum melakukan upload pastikan di PC atau laptop sudah tersedia git, untuk Windows bisa menggunakan cmder yang sempat saya tulis disini untuk memudahkan proses penggunaan git, sedangkan untuk pengguna linux bisa menginstall dengan menggunakan perintah “sudo apt-get install git” jika menggunakan OSX install dengan brew, jika sudah file siap di upload ke repository online.
jika sudah memiliki proyek yang ingin diletakkan di repository online, buka saja folder project tersebut dengan perintah command line, atau jika belum terbiasa di command line (nanti belajar command line) buka saja folder tersebut menggunakan file exploler dan klik kanan “open terminal/cmder here”. Ada beberapa perintah dasar yang akan digunakan, perintah ini sudah tersedia kok saat membuat repo tadi (lihat gambar atas) :

LANGKAH KE TIGA:

buka gitbush anda lalu ketikan code yang di bawah ini.....
- git init (enter)
- git status (enter) " cek status untuk mengecek file yang ingin di upload"
- git add . (enter) " memasukan file"
- git status (enter) " cek status lagi ,sudah tersimpan atau belum ,jika tersimpan text nya berwarna hijau"
git commit -m "first commit" (enter)
git remote add origin https://github.com/dikisetiawan1/latihan1tugas.git (enter)" sesuai url repositori anda di github"
git push -u origin master (enter) "tahap terakhir untuk penyimpanan"

Keterangan perintah diatas seperti ini :
git init
untuk meng-set folder yang digunakan tersebut sebagai repo local git. bisa di bilang ini instalasi git pertama kali
git add “.” atau nama file
untuk menambah file project yang mau di upload sebelum di commit, tanda titik setelah kata “add” pada perintah tersebut adalah keseluruhan file dan folder project tersebut, saat awal upload kalian bisa menggunakan perintah tersebut. Namun saat commit atau upload ke repository selanjutnya bisa menggunakan perintah add dengan “nama file” untuk memberikan status commit. Ini adalah contohnya apabila ingin menggunakan “git add” :
// mengupload keseluruhan file pada repo (hanya digunakan saat upload pertama saja)
git add .
// mengupload file sesuai dengan nama file
git add index.html
// mengupload file pada dalam folder
git add pages/index.html
git commit -m “isi commit”untuk menambah keterangan/status perubahaan saat upload ke repo online, untuk memasukkan keterangan tersebut setelah “git commit -m” ditambah tanda petik lalu komentar(lihat di list perintah untuk contoh).


git remote add origin https://github.com/dikisetiawan1/latihan1tugas.git


git push -u origin master

lalu tunggu proses nya sampai selesai......















Screenshot langkah-langkah proses penyimpanan file di github





