Node.js FAQ
==========
**Apa itu Node.js?**
> Node.js adalah *asynchronous* I/O framework berbasis *event* yang menggunakan Google V8 Javascript Engine yang berjalan di sisi server.

**Apa itu Google V8 Javascript Engine?**

> Google V8 Engine adalah open source Javascript engine milik Google yang juga digunakan pada browser Google Chrome.

**Apakah Node.js salah satu produk Google?**

> Bukan, meskipun menggunakan Google V8 Engine, Node.js tidak memiliki afiliasi dengan Google Inc. Pengembangan Node.js sejak awal disponsori oleh Joyent, yang juga sebagai pemilik merek dagang Node.js

**Apakah ada dokumentasi resmi Node.js?**

> Ya, anda dapat membaca dokumentasi resmi Node.js disini: http://nodejs.org/api/


**Apakah Node.js dapat berjalan di browser?**

> Tidak, Node.js hanya dapat berjalan di sisi server. Namun Node.js dapat membuat HTTP/web server yang dapat diakses oleh browser seperti halnya PHP dan Apache.

**Bagaimana saya menginstall Node.js di komputer saya?**

> Anda dapat men-download *package* Node.js dan melihat panduan untuk meng-install Node.js sesuai sistem operasi komputer Anda disini: http://nodejs.org/download/

**Bagaimana saya menginstall module Node.js?**

> Anda, bisa menginstall module Node.js dengan menjalankan perintah ```npm install nama_module``` pada command line, pastikan Anda berada pada direktori project karena ```npm``` akan membuat direktori ```node_modules``` pada direktori dimana Anda melakukan ```npm install```.

**Apa itu** ```npm```**?**

> ```npm``` adalah Node Package Module. Digunakan sebagai distribusi modul-modul Node.js yang dipublish oleh komunitas Node.js.

**Dimana saya dapat mencari module-module Node.js?**

> Anda bisa mencari module Node.js sesuai kebutuhan anda di: http://npmjs.org

**Apakah koneksi internet selalu dibutuhkan untuk menginstall module Node.js?**

> Ya, untuk menginstall module Node.js pastikan komputer Anda terkoneksi dengan internet.

**Bagaimana saya menggunakan module Node.js?**

> Untuk menggunakan module, Anda harus mengimport module tersebut terlebih dahulu dengan fungsi seperti ini: ```var module = require('nama_module')``` lalu variabel ```module``` dapat digunakan pada file dimana anda mengimport file tersebut.

**Apakah saya harus melakukan import/require pada setiap file yang menggunakan module?**

> Ya, namun module tersebut akan ter-cache saat pertama kali module dibaca (require).

**Apakah saya bisa menjalankan Node.js pada platform Windows?**

> Ya, bisa. Selain Windows, Node.js dapat berjalan pada platform *NIX dan MacOSX.

**Apakah saya bisa menjalankan Node.js pada platform MacOSX?**

> Ya, bisa. Selain MacOSX, Node.js dapat berjalan pada platform *NIX dan Windows.

**Apa itu Express.js?**

> Express.js adalah salah satu web application framework yang berjalan di atas Node.js. Anda bisa mempelajarinya disini: http://expressjs.com

**Apakah saya membutuhkan Apache untuk menjalankan Node.js?**

> Tidak, Node.js dapat membuat HTTP/Web servernya sendiri sehingga tidak memerlukan Apache sebagai web server.

**Apakah perbedaan Node.js dan Angular?**

> Angular adalah MVC framework yang berjalan di sisi klien/browser. Sedangkan Node.js adalah platform Javascript yang berjalan di sisi server.

**Apakah saya bisa menggunakan jQuery dengan Node.js**

> Ya, package jQuery untuk Node.js tersedia pada ```npm``` https://www.npmjs.org/package/jquery

**Apakah saya bisa membaca dan menulis file/dokumen pada server menggunakan Node.js?**

> Ya, dengan menggunakan [FileSystem API](http://nodejs.org/docs/latest/api/fs.html) Anda bisa membuat, membaca dan menulis file/dokumen pada server.

**Apakah saya bisa bekerja menggunakan Node.js dan MySQL?**

> Ya, Anda bisa menggunakan https://github.com/felixge/node-mysql sebagai driver MySQL untuk Node.js

**Apakah saya bisa menggunakan MD5 pada Node.js?**

> Ya, dengan menggunakan [Crypto API](http://nodejs.org/api/crypto.html) Anda bisa menggunakan MD5 dan berbagai algoritma hash lainnya.
