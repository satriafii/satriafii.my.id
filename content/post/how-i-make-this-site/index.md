---
title: "[ID] Bagaimana Cara Membuat Website Seperti ini Bermodal Kemampuan Noob dan Cocoklogi"
date: 2024-12-28T13:05:37+07:00
summary: "Kemampuan yang dibutuhkan adalah bisa membaca, menulis, dan mengetik. Sudah itu saja. Bahasa yang dibutuhkan adalah bahasa Inggris kalau bisa lebih bagus, tapi bahasa Indonesia juga bisa jalan lancar saja."
tags: ["website", "web-dev", "reflection", "self-intro", "Hugo", "indie-web"]
---

Selamat pagi. Kali ini menyapa para pembaca dengan tampilan baru. Meskipun ini saya pede sekali menyebut bakalan ada yang baca tulisanku.

Seenggak adanya pembaca tulisan ini, aku yakin aku bakalan baca lagi entah kapan. Setidaknya ada dua orang yang akan membaca tulisan ini: diriku yang saat ini dan diriku dimasa depan. Kalau beneran ada orang lain selain dua orang itu, HAI! I LOVE YOU HAHAHA

Oke, udah mulai keganggu fokusnya. Tapi mari ditata kembali fokusnya. 

## Pertama-tama, siap-siap

Baru kali ini aku membuat sketsa rancangan desain website(?) yah intinya bayangan bentuk website yang aku inginkan tu bisa dilihat oleh orang lain juga itu.

Aku buatnya di [canva](https://www.canva.com/) saja karena nggak punya aplikasi powerpoint. 

Berikut kalau mau ngintip bagaimana aku bikinnya:
{{< img sizes="(min-width: 35em) 800px, 100vw" src="canva.png" alt="sketsa desain website yang kubuat di canva, banyak komentar yang aku tulis untuk diriku sendiri supaya tidak lupa bagaimana jalan pikiranku saat memutuskan untuk menempatkan sesuatu." >}}

Sejatinya lebih nyaman bikin di aplikasi powerpoint karena tujuanku punya website adalah untuk membagikan tulisan saja. Maksudnya aku tidak ingin terlalu banyak hal-hal yang kurang perlu seperti kolom komentar atau fitur like, dislike, atau semacamnya. Aku juga merasa tidak terlalu perlu untuk tahu berapa banyak orang yang tahu pembaca tulisanku (setidaknya untuk saat ini dan beberapa waktu kedepan). Sehingga dengan tujuan itu, aku desain websiteku bener-bener simpel saja. 

Sebelum-sebelumnya, aku menulis kode untuk websiteku berdasarkan pengetahuan apa yang aku punya, jadi untuk bentuknya aku tidak punya ekspektasi apapun. Toh menurutku dulu plain HTML udah sangat bagus tampilannya. Tinggal warnanya saja diganti hehehe

Tapi seiring berjalannya waktu, sebagai seorang perempuan yang umurnya sudah kategori dewasa, pikiranku banyak dan dimana-mana. Bahasa singkatnya adalah mirip seorang ADHD yang nggak bisa fokus 😅 Jadi aku perlu sesuatu untuk menata pikiranku. Project adalah salah satunya. Sekarang setiap hal-hal kecil yang aku lakukan kebanyakan kuanggap sebagai project. Website ini salah satunya. Kali ini nama project yang aku buat adalah redesign website project. Project ini dimulai sejak aku punya tujuan yang jelas apa yang ingin aku buat dan berakhir saat website ini bisa diakses di [domainku ini.](https://satriafii.my.id/)

Saat membuat sketsa desain website itu, aku juga tidak terlalu peduli dengan kemampuan nulis kodeku. Background tulis menulis kodeku adalah aku sekadar tertarik saja dengan HTML dan CSS sejak SMP, itu kira-kira 13 tahun yang lalu. Sejak saat itu, aku suka mencari-cari dan ngintip-ngintip kode sebuah website dengan kemampuan ajaibku: `ctrl` + `shift` + `i` wkwkwkwkwk alias mode inspect aja sih. Kan kode HTML nya pasti kelihatan dan CSS nya juga kelihatan kalau mau dilihat. Karena ketertarikanku itu, aku juga iseng belajar koding di [freecodecamp](https://freecodecamp.org/) dan baru sekitar setengah kukerjakan responsive web design courses karena kadang aku absen bisa sampai beberapa bulan wkwkw Baru-baru ini saja aku tahu tentang [The Odin Project](https://www.theodinproject.com/) dan baru baca satu atau dua materinya.

Tapi menurutku hal yang paling penting untuk menulis kode adalah keberanian untuk belum tahu dan kemauan untuk mencari tahu. Awal-awal aku mencoba menulis sendiri kodeku adalah aku mengumpulkan berbagai macam potongan kode yang menurutku menarik serta bisa diaplikasikan olehku; alias aku bisa paham untuk apa kode itu dan bisa memperbaikinya kalau ada yang salah. 

Well, inti dari tulisan ngga jelas bagian pertama ini adalah:
1. Tentukan tujuanmu, mau untuk apa website yang akan kamu buat itu?
2. Bentukannya mau gimana, yok digambar.
3. Dicoba dulu, nyontek dulu gapapa. 

## Kedua-dua, mulai

Ini bagian yang paling tidak bisa dijelaskan. Karena yah, mulai aja. Mulai nulis kode dengan kemampuanmu sendiri. Jujur aja aku yang bahkan nggak hafal element pertama untuk nulis HTML ini pun dengan nekat nulis sendiri kok.

Satu hal yang menurutku sangat meringankan beban per-koding-an ini adalah aku menulis kodenya bener-bener pure pakai HTML dan CSS yang aku kuasai dulu. Meskipun belum terlalu cantik dan kemungkinan repot sekali kalau dijadikan blog, aku tetap tulis dalam bentuk yang masih bisa aku pahami dulu. Sama seperti mengerjakan soal, dari dulu aku baca dulu secara cepat sambil jawab soal-soal yang langsung bisa aku jawab dalam waktu kurang dari satu menit. Soal-soal yang susah atau butuh pemikiran lebih, aku tinggal dulu. Kali ini, menurutku soal paling mudah adalah membentuk tampilan websiteku sesuai dengan yang telah aku rencanakan di gambar.

Aku memutuskan untuk menulis HTML dan CSS di satu file yang sama karena aku ingin meminimalisir CSS yang aku tulis. Selain karena aku ingin websiteku ini se-*plain* mungkin, aku juga merasa pengetahuan CSS ku masih sangat jongkok 😂 Sejongkok itu kalau ditanyain gimana cara ubah warna aja aku masih bingung 😅 Menurutku juga kalau style nya ditempatkan disatu file yang sama dengan HTML, aku jadi lebih leluasa mengubah perintah untuk satu halaman tertentu. 

Hal-hal yang akan selalu sama di setiap halaman yang aku punya adalah navigation dan footer. Selainnya, aku bisa kostumisasi sendiri. Untuk websiteku ini, aku membuat home, creations, consumptions, photos, dan thoughts saja. Halaman post dan halaman artikel sudah otomatis dibuatkan oleh Hugo, meskipun ada beberapa pengaturan yang perlu disesuaikan.

Tapi karena keinginanku juga tidak terlalu muluk-muluk untuk kemampuanku yang super noob ini, nyaris semua elemen yang aku pakai juga tidak terlalu jauh dari elemen dasar saja. Menurutku, yang paling rumit adalah tabel karena aku sama sekali belum pernah bikin tabel di HTML. Itupun saat aku menyesuaikan diri dengan Hugo, bisa langsung ditulis dengan markdown dan Hugo dengan baik hati membuatkan tabel untukku hehehe

Elemen CSS paling menakutkan dan menurutku paling rumit adalah saat membuat bagian [photos](/photos/). Menakutkan karena aku pikir bikin bentuk grid itu susah banget, ternyata sudah ada perintahnya sendiri di CSS. Rumit karena aku pikir membuat grid yang bisa otomatis menyesuaikan diri di semua layar itu perlu banyak baris kode dan pemahaman yang tinggi. Ternyata tidak juga, kode sederhana hasil aku nyari di tutorial orang pun jalan dengan baik dan bahkan lebih dari apa yang aku bayangkan. 

Setelah selesai dengan file-file HTML yang sesuai dengan keinginan dan rencana, aku sempat berpikir berat mau langsung upload murni file itu saja atau perlu bantuan *site generator* seperti [Hugo](https://gohugo.io) atau perlu cari alternatif lainnya yang lebih simpel lagi. Dua kali aku merombak tampilan websiteku selalu aku dahulukan karena aku pakai *static site generator*, jadi aku malah mengedepankan mempelajari bagaimana sistem *site generator* itu dulu dibandingkan fokus dengan tampilan dan fitur yang aku inginkan di websiteku. Kali ini berbeda, aku sejujurnya lupa dengan hal itu 😅 Ketidaksengajaan itu justru bikin aku lebih fokus sih. 

Makanya mumet di belakang. Sekitar 3 harian aku bingung dengan satu hal itu. Pertimbangannya adalah toh aku juga nulis ini di markdown yang bisa dengan mudah diubah ke bentuk HTML. Kalau misalnya harus banget nulis dengan HTML pun aku nggak takut wkwk karena sudah lancar menulis dengan HTML sih, jadi udah pede hehehe Tapi aku sehari-hari juga lebih sering menyentuh markdown karena aku pakai [Logseq](https://logseq.com/) dan [Obsidian](https://obsidian.md/) untuk menulis journal harianku. Menurutku markdown juga super gampang dan ringan karena dibuka dengan notepad biasa pun lancar jaya maju sejahtera. Hanya saja, kalau aku memutuskan untuk menerbitkan websiteku hanya dengan file HTML saja, aku perlu setiap saat menata file HTML ku dengan rapih dan kemungkinan akan jadi file yang sangat besar nantinya karena aku masih ingin menambahkan gambar, banyak tulisan, dan banyak link. Hal yang paling utama adalah aku yakin aku bakalan bingung kalau aku hanya pake HTML saja. 

Kalau pakai *static site generator*, aku perlu menyesuaikan dengan template yang sudah disediakan. Alias aku harus membuat theme sendiri dari awal. Aku juga perlu setting di netlify (sebenernya nggak rumit-rumit amat sih). Saat ada satu huruf saja yang salah ketik bahkan di file markdown seperti ini saja, kadang site nya nggak jalan sama sekali. Kadang itu bikin aku kebingungan sendiri dan malah grogi sendiri lalu bingung bagaimana memperbaikinya. Padahal ya itu, cuma saltik aja. Tapi keuntungannya adalah aku bisa dengan mudah menulis di markdown lalu dah, tinggal sync saja ke github dan udah deh bisa ditinggal ngapa-ngapain lagi. Selain itu, aku juga tidak terlalu perlu berpikir untuk menata file HTML-ku karena sudah ada perintahnya sendiri. Yah, intinya aku nanti tidak akan terlalu repot kalau mau update-update.

Akhirnya aku memutuskan untuk menggunakan [Hugo](https://gohugo.io) untuk websiteku ini. Aku hanya perlu mengubah-ubah bagian folder layouts dan content saja. HTML nya aku copas sambil menyesuaikan perintah  atau templating di Hugo. Tentu saja langkah ini nggak cuma sehari dua hari saja bisa selesai. Karena aku juga punya kehidupan diluar layar laptop, targetku adalah dua jam memindah file HTML ke format yang disukai Hugo (masih HTML tapi dengan templating yang disesuaikan). Hasilnya seperti ini. 

## Ketiga-tiga, mari dipamerkan

Yes. Akhirnya bisa diupload ke github setelah kontennya dilengkapi dan diperbaharui.

Tentu saja kalau masih awal membuat website, proses ini bisa langsung dilakukan. Tapi untuk kasusku kali ini, aku perlu memindahkan beberapa hal sebelum siap untuk dipamerkan. Misalnya, aku perlu menulis tulisan ini karena akan aku pamerkan di bagian footer. Selain itu, aku ingin menambahkan konten-kontenku dulu baru benar-benar aku pamerkan.

## Oke. Tapi dimana aku bisa lihat contekannya?

Hm.... Bagian ini sebenarnya yang selalu aku cari-cari di tutorial membuat website. 

Seringkali aku tidak menemukan contekan sebenarnya. Jadi, aku ingin menuliskannya disini.

Karena seleraku adalah simpel banget dan yah, noob aja, jadikan itu catatan sebelum mengunjungi website-website yang aku sarankan ini.

- [1mb Club](https://1mb.club/) isinya adalah website-website dengan ukuran kecil di internet. Kebanyakan personal website dan blog kecil. Kebanyakan tampilan websitenya sangat sederhana dan aku beneran membuka banyak link dari website ini demi mencontek kodingan simpel yang bisa aku terapkan di websiteku. Beberapa contekan yang masih aku ingat sampai sekarang adalah menulis CSS di head HTML, menulis style di dalam elemen, membuat *night mode* yang proper (meskipun sebenernya menurutku masih aneh, but okay lah ya), dan menengahkan(?) konten supaya enak dibaca di layar lebar.
- [No CSS Club](https://nocss.club/) dead simple. Dulu aku pengen banget bikin begini waktu baru membuka website ini pertama kali di ponsel. Tapi begitu lihat website ini di laptop, keinginanku lenyap begitu saja, karena sangat panjang tulisannya, aku nggak begitu terbiasa dan kurang nyaman buatku. Tapi beberapa website lumayan cakep jadi aku nyontek beberapa bagiannya. Tapi dari website ini aku lupa sih aku ambil apa aja...... hehehe
- [portable thoughts](https://portable.fyi/#_) website ini menurutku sangat keren. Hanya terdiri dari satu file HTML, nyaman dibaca di layar lebar maupun layar sempit, bahkan sampai punya buku yang bisa dibaca dengan sangat menyenangkan di ponsel (ringan, cepat, jelas navigasinya, dan tampilannya sederhana tapi bagus).
- [Eric Murphy](https://ericmurphy.xyz/) keberanianku bikin theme hugo sendiri berawal dari nonton [video dia tentang theme di Hugo](https://youtu.be/wcMqrb3v2SM?si=fIAbAyBjCf3ihnLB). Lalu aku mencobanya dengan membuat [versi ini](/post/perkenalan-tampilan-website-baru) lalu kupikir-pikir lagi, aku bisa membuat yang lebih sesuai dengan keinginanku sendiri, alias versi ini hehehe Tetap saja, menurutku inspiresyen yang aku dapatkan dari video dengan thumbnail ngawur itu ternyata bisa sehebat ini sampai aku merasa bangga dengan diriku sendiri ❤️


Kebanyakan contekan aku dapat dari mereka. Selain itu, aku banyak cari-cari tutorial singkat di google dan youtube. *Special mention* untuk [Stephen's Notebook](https://stephenpieper.net/photos/) yang bener-bener membantuku untuk membuat bagian [photosku](/photos/) bener-bener sesuai dengan apa yang aku inginkan. [Marginalia](https://search.marginalia.nu/explore/random) juga sangat banyak membantu. Marginalia adalah mesin pencari yang lebih fokus ke indie web. Fitur yang paling aku suka adalah random search. Sempat beberapa bulan aku ketagihan scroll dengan fitur itu. Yah, menuruku lebih bagus daripaa scroll X sih. Isinya jauh lebih menarik dan bervariasi disini. Meskipun masih sangat disayangkan bahasa Indonesia sepertinya belum terlalu masuk di database mereka. 

Aku nggak tahu bagaimana cara membuat buntut yang bagus. Tapi yang jelas aku ingin bilang kalau pembaca tulisan ini benar-benar ingin membuat website sendiri, mending kerjakan sekarang. Kalau kalian disini mau mencuri sesuatu dari aku, [silakan dicuri dan dieksekusi saja](/post/silakan-curi-sesuatu-disini).

Terima kasih sudah membaca sampai sini, semoga harimu bahagia ❤️