---
order: 9
icon: list-unordered
---

## Penjelasan Work Request
Work Request adalah pesan atau laporan yang dilaporkan mengenai suatu aset, yang harus ditindaklanjuti lebih jauh menjadi Work Order. Work Request dapat dilakukan oleh siapapun.

## Penjelasan Work Order
Work Order adalah perintah yang harus dikerjakan terhadap suatu aset. Work Order dapat berupa pengecekan, pemeliharaan dan perbaikan.

!!!
Work Order pada umumnya dibuat setelah adanya Work Request. Namun, Work Order dapat langsung dibuat tanpa melalui Work Request dan langsung melalui dashboard, ataupun otomatis melalui PM (Preventive maintenance). Untuk WO ini hanya dapat dibuat oleh supervisor.
!!!

## Open Task
Open task adalah semua WR dan WO yang masih terbuka dan belum selesai.

### Work Request
![](../images/wr-open.png)
Pada halaman open task dan menu Work Request, anda dapat melihat semua WR yang aktif. Untuk membuat WR, anda dapat melakukannya lewat dashboard maupun menu Submit Work Request, yang juga terdapat di menu manage work.

Untuk menindaklanjuti WR, anda dapat menekan tombol action yang akan membawa anda ke halaman detail WR tersebut.
![](../images/wr-detail.png)
Ketika problem telah dianalisis, anda dapat menindaklanjuti WR tersebut menjadi 3 output, yaitu:
* Done : Apabila masalah selesai tanpa harus ditindaklanjuti lebih lanjut.
* Canceled : Apabila masalah tidak perlu, namun bukan berarti selesai.
* Create Work Order : Apabila masalah perlu ditindaklanjuti, dan harus dibuat WO.
Anda juga harus menambahkan notes pada WR ini. Kemudian jika semua telah selesai diisi, tekan (Submit Review) untuk menyelesaikan review.

### Work Order
Pada submenu Work Order, anda dapat mengatur WO, baik membuat maupun menindaklanjuti WO.
Untuk membuat WO, anda dapat membuatnya baik secara langsung melalui dashboard ataupun dari tindak lanjut WR. Dalam pembuatan WO, terdapat beberapa data yang harus anda isi, yaitu:

Field | Makna
--- | ---
WO Name* | Nama/Judul dari WO.
Location* | Lokasi tempat masalah berada.
Asset*| Aset yang bersangkutan.
Description | Deskripsi masalah.
Priority | Prioritas masalah.
Attachment | Lampiran, baik berupa dokumen, foto atau lainnya.

!!!
field bertanda bintang (*) adalah field yang harus diisi (required).
!!!

Ketika WO telah dibuat, maka akan tampil di list WO seperti berikut:
![](../images/wo-list.png)

Field | Makna
--- | ---
WO-PM-XXXX | Kode WO
High | Prioritas WO
Monthly Indoor AC | Nama/Judul WO
Planned | Jenis WO, yaitu: 1. Planned : WO yang dibuat dari PM, 2. Unplanned : WO yang dibuat tanpa melalui PM
Response | Status WO

### Menjalankan Work Order (Engineer)
![](../images/wo-eng-button.png)
Untuk menjalankan sebuah WO, anda dapat menekan tombol dengan simbol mata berwarna biru seperti tabel diatas. Pada halaman ini, anda dapat melihat dan mengisi detil-detil yang diperlukan dalam pengerjaan WO, seperti:

![](../images/wo-eng.png)

* **Work Order Detail**, yaitu detail dari WO yang mungkin dibutuhkan selama pekerjaan. Anda juga dapat mengisi data-data seperti status dari WO, tanggal pengerjaan, dan lain-lain.

* **Part**, yaitu halaman yang menampilkan suku cadang yang dibutuhkan dalam WO. Anda juga dapat menambahkan part jika dibutuhkan dengan menekan tombol (Add Part) yang berada pada bagian atas halaman. 

* **Asset Information** menampilkan aset apa yang terkait dengan WO dan detail dari aset tersebut, termasuk lokasi dimana aset tersebut berada.

* **Log History** menampilkan histori perubahan segala hal yang terkait dengan suatu WO, lengkap dengan jam, jenis perubahan, dan siapa yang merubah.

* **Instruction**, keterangan ataupun instruksi tambahan yang diberikan untuk pengerjaan WO. Anda juga dapat menambahkan instruction dan mencetaknya.

* **Job Plan**, berguna untuk menampilkan rencana pekerjaan yang akan dilakukan dalam WO

* **Safety Instruction**, berguna untuk menampilkan instruksi keamanan yang akan dilaksanakan dalam WO. Berbeda dengan instruction, tab ini berguna spesifik untuk masalah keamanan.

### Mengelola Work Order (Supervisor)
![](../images/wo-spv-button.png)
Untuk mengelola dan mengawasi sebuah WO, anda dapat menekan tombol edit seperti tabel diatas. Pada halaman ini, anda dapat melihat dan mengisi detil-detil yang diperlukan dalam review WO, seperti:

![](../images/wo-spv.png)

* **Work Order Detail**, yaitu detail dari WO yang mungkin dibutuhkan selama pekerjaan. Anda juga dapat mengisi data-data seperti status dari WO, tanggal pengerjaan, siapa yang mengerjakan dan lain-lain.

* **Cost Summary**, keseluruhan biaya dan part yang mungkin atau akan dibutuhkan pada WO. Anda juga dapat mencetak daftar part yang dibutuhkan dengan menekan tombol (Request Purchase).

* **Assets/Location**, menampilkan aset apa yang terkait dengan WO dan detail dari aset tersebut, termasuk lokasi dimana aset tersebut berada.

* **Log History**, menampilkan histori perubahan segala hal yang terkait dengan suatu WO, lengkap dengan jam, jenis perubahan, dan siapa yang merubah.

* **Instruction**, keterangan ataupun instruksi tambahan yang diberikan untuk pengerjaan WO. Anda juga dapat menambahkan instruction dan mencetaknya.

Untuk lebih jauh mengenai flow pekerjaan baik WR maupun WO, silahkan baca bagian [Workflow](/workflow/work-order)

Ketika anda telah selesai merubah WO, baik itu merubah detailnya maupun menyelesaikan WO, jangan lupa untuk menekan tombol (Submit Review) yang terdapat pada bagian bawah halaman. Jika anda memerlukan bentuk cetak dari WO, anda juga dapat menekan tombol (Print Work Order).


## Completed Task
Completed task adalah pekerjaan baik itu berupa WR ataupun WO yang sudah diselesaikan.

WR ditandai selesai apabila telah ditindaklanjuti/diasesmen apapun hasilnya (Done, Canceled, Create WO), namun untuk WO, status WO tersebut haruslah **Done**, yang menandakan telah selesai dan telah dievaluasi.


## Submit Work Request
Untuk membuat laporan WR, anda dapat memilih menu ini dan mengisi field-field data yang diperlukan:

Field | Makna
---|---
Title of the WR* | Judul laporan
Tell Us About it* | Keterangan singkat laporan
Where/What’s the problem* | Dimana/Apa masalahnya
Your Name* | Nama pelapor
Phone | Nomor telepon pelapor
Email | Surel pelapor
Attachment | Foto/Dokumen mengenai masalah

!!!warning
Field bertanda bintang (*) adalah field yang harus diisi (required).
!!!

Jika anda sudah mengisi semua data tersebut, anda dapat menekan tombol (Submit work request) dan pembuatan WR selesai.


