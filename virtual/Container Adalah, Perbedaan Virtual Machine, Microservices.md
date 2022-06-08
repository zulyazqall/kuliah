[BLOG](https://datacommcloud.co.id/blog/ "Go to BLOG.")[Cloud Service](https://datacommcloud.co.id/category/cloud-service/ "Go to the Cloud Service category archives.")[Microservices](https://datacommcloud.co.id/category/cloud-service/microservices/ "Go to the Microservices category archives.")

Container Adalah, Perbedaan Virtual Machine, Microservices
==========================================================

**Apakah itu container?**

**Keuntungan dan perbedaannya dengan Virtual Machine**

Definisi [Container](/containers/) adalah sejenis software yang mengemas dan mengisolasi applikasi secara virtual untuk mempermudah software deployment. Berbeda dengan traditional Virtual Machine konsep, Container consep tidak membutuhkan dedicated operating system (OS Kernel) tetapi Container Kernel dapat di pergunakan secara bersama-sama.

![](data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==)

![](https://datacommcloud.co.id/wp-content/uploads/2021/06/image.png)

![](data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==)

![](https://datacommcloud.co.id/wp-content/uploads/2021/06/image-1.png)

Adopsi [Cloud Computing](/definisi-cloud-computing/) untuk perusahaan di Indonesia berkembang dengan sangat cepat sekali. Percepatan adopsi ini di dukung sejalan juga dengan perkembangan teknology terkini. Dunia cloud computing diawali dengan memanfaatkan teknology Virtual Machine. Belakangan ini teknology Container berkembang menjadi suatu standard teknologi cloud yang mulai banyak di minati oleh pakar-pakar di industri.

**Apakah Container itu?**

[Container](/containers/) adalah suatu alternative teknologi yang dapat di pergunakan untuk memvirtualisasi komputer system. Dengan mempergunakan Container kita dapat mengemas komputer programing (code) menjadi suatu unit yang standard sehingga semua dependensi dari aplikasi dapat di ikut sertakan dalam kemasan tersebut.

Container memungkinkan aplikasi dapat di pindah-pindahkan dengan cepat dan andal dari satu lingkungan komputasi ke lingkungan komputasi lainnya. Container merupakan paket perangkat lunak yang ringan, mandiri, dan dapat dieksekusi. Paket Container mencakup semua yang diperlukan untuk menjalankan aplikasi: kode, runtime, alat sistem, pustaka sistem, dan pengaturan.

Rangkuman dari perbedaan, manfaat, kelebihan dan kurangan dari Container di banding dengan Virtual Machine bisa di lihat di dibawah ini:

![](data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==)

![](https://datacommcloud.co.id/wp-content/uploads/2021/06/image-2.png)

![](data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==)

![](https://datacommcloud.co.id/wp-content/uploads/2021/06/image-3.png)

![](data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==)

![](https://datacommcloud.co.id/wp-content/uploads/2021/06/image-4.png)

**Bagaimana Container bekerja?**

Container menampung seluruh komponen yang diperlukan untuk aplikasi dapat di jalankan. Komponen ini termasuk file, environment variable, dependency dan library. Host Operating System akan mengatur dan membatasi akses ke pada computer resources seperti CPU, Storage dan Memory sehingga pengunaan resource tidak di kuasai oleh single user.

Container image merupakan adalah suatu aplikasi atau service yang complete, static and executable versions. Salah satu contoh container host yang popular adalah Docker Containter. Image dari Docker container ini terdiri dari beberapa lapisan, yang dimulai dengan image dasar yang menyertakan semua dependensi yang diperlukan untuk mengeksekusi aplikasi dalam sebuah container.

Setiap image memiliki lapisan yang dapat dibaca / ditulis di atas lapisan statis yang tidak berubah. Karena setiap Container memiliki environment yang spesifik untuk dirinya sendiri, maka Image container dapat di simpan dan dipergunakan untuk container-container yang lain.

Image Open Container Initiative (OCI) terdiri dari manifes, file system layers dan configuration. OCI Image memiliki dua spesifikasi yang di butuhkan untuk bisa dioperasikan: runtime dan image specification. Runtime specification meringkas fungsi dari file system bundle termasuk file-file yang berisi semua data yang diperlukan untuk proformance dan runtime. Image specification berisi informasi yang diperlukan untuk meluncurkan aplikasi atau layanan di container OCI.

**Keuntungan mempergunakan Container?**

Container memberikan cara utk mengemas aplikasi secara terstruktur dan logis sehingga aplikasi ini tidak lagi tergantung lagi dengan configurasi komputer operating system tertentu untuk dapat berjalan secara sempurna. Proses Containerization memungkinkan aplikasi untuk dapat di deploy dengan mudah dan konsisten terlepas dari berbagai macam system komputer baik di on-premise, di local atau di cloud bahkan di komputer laptop pribadi atau kumputer server yang besar.

Containerization memungkinkan pemisahan yang jelas antara team IT yang bertanggun jawab dengan komputer infrastruktur operasi (Ops Team) dan team programmer (Dev Team). Programming team dapat memfokuskan pada pengembang logika programming dan ketergantungan aplikasi mereka, sementara tim operasi TI dapat fokus pada penerapan dan manajemen tanpa mengganggu detail aplikasi seperti versi perangkat lunak tertentu dan konfigurasi khusus untuk aplikasi tersebut.

Bagi mereka yang datang dari lingkungan virtual, container sering dibandingkan dengan mesin virtual (VM). Anda mungkin sudah terbiasa dengan VM: sistem operasi tamu seperti Linux atau Windows berjalan di atas sistem operasi host dengan akses virtual ke perangkat keras yang mendasarinya. Seperti mesin virtual, container memungkinkan Anda mengemas aplikasi Anda dengan library dan dependensi lainnya, menyediakan lingkungan yang terisolasi untuk menjalankan layanan software Anda. Namun, seperti yang akan Anda lihat di bawah, kesamaan berakhir di sini karena container menawarkan unit yang jauh lebih ringan bagi developer dan tim IT Ops untuk bekerja sama, membawa banyak sekali manfaat.

Inilah salah satu alasan mengapa adopsi Container sejalan dengan DevOps (Development Operation) metodologi. Sepanjang aplikasi lifecycle dimulai dari pembuatan pemograman aplikasi hingga pengujian dan produksi, file sistem, binaries dan informasi pendukung lainnya bisa tersimpan dalam satu repository container. Version control pada level image dapat di mengantikan configurasi dan management pada system level.

**Bagaimana memanfaatkan Container didalam Microservices Architecture?**

Container adalah software packet yang executable dan individual, di dalamnya sudah termasuk keseluruhan environment dependencies yang dibutuhkan untuk dapat berfungsi secara independent. Container merupakan software yang terpisah dari software pendukung yang terdapat di sekelilingnya. Container software yang sama dapat di jalankan di sebuah environment yang sama. Di dalam Microservices Architecture, setiap layanan dapat di masukan ke dalam container sehingga secara keseluruhan service yang kecil-kecil ini dapat berfungsi melakukan tugas besar secara keseluruhan.

*   [Hands On Kubernetes Workshop](https://datacommcloud.co.id/hands-on-kubernetes-workshop/)
    
    Mengatur dan mengelola container memang bukanlah sebuah hal yang mudah, dibutuhkan skill yang memumpuni, serta management container yang lebih terotomisasi dan policy-driven untuk dapat melakukannya. Maka dari itu K8S hadir …
    
*   [Perbandingan Zerto Site Recovery Manager & Replikasi vSphere](https://datacommcloud.co.id/perbandingan-zerto-vs-site-recovery-manager-srm-dan-replikasi-vsphere/)
    
    Disaster Recovery di Era Virtualisasi Virtualisasi telah membuat Disaster Recovery menjadi sangat tidak rumit bagi perusahaan, besar dan kecil. Faktanya, bukanlah hal yang berlebihan untuk mengatakan bahwa virtualisasi telah membuat …
    
*   [Microservices Adalah dan Perbedaan Monolithic Architecture](https://datacommcloud.co.id/microservices-adalah-perbedaan-monolithic-architecture/)
    
    Memanfaatkan Teknologi Microservice & Container untuk memodernisasi aplikasi menuju Cloud Native Arsitektur di Era Digital. Microservices adalah suatu framework Architecture yang dipakai sebagai model dalam pembuatan aplikasi cloud yang modern. Di …
    
*   [Cara Kerja Kubernetes Adalah, Keuntungan, Arsitekur, Komponen](https://datacommcloud.co.id/kubernetes-adalah/)
    
    Apa yang anda perlu ketahui tentang Kubernetes, keuntungan yang bisa di dapat dan bagaimana dengan arsitektur, komponen dan cara kerjanya. Apa itu Kubernetes (K8S) dan bagaimana cara kerjanya? Kubernetes adalah sebuah open …
    
*   [Monolithic to Cloud Native – Microservices Migration Strategy](https://datacommcloud.co.id/microservices-migration-from-monolithic/)
    
    Langkah yang harus di ambil untuk bisa memigrasikan Monolitik aplikasi ke Cloud Native arsitektur. Sebelum memulai dalam memodernisasi aplikasi Monolithic anda yang lama, sebaiknya anda memulai dulu dari mendalami lebih …
    

Posted in [Microservices](https://datacommcloud.co.id/category/cloud-service/microservices/)
