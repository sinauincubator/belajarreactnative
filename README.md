## BELAJAR REACT NATIVE MOBILE HYBRID FRAMEWORK ##

React native merupakan framework untuk membuat aplikasi mobile berbasis HTML5. Framework ini berbasis pada reactjs buatan facebook. Hmmm... sepertinya menarik, so let's get started.

### PERSIAPAN ###

#### Android SDK ####

1. Download & install android SDK & android studio
2. Pasang android SDK ke path environment variable
3. Jalankan perintah `android` dan install API, emulator, dll sesuai kebutuhan dan pastikan telah menginstall SDK tools, platform-tools dan build-tools versi 23.0.1 ke atas - untuk lebih jelasnya [baca link berikut](https://facebook.github.io/react-native/docs/android-setup.html)
4. Jalankan perintah `android avd` untuk membuat emulator baru
5. Download dan install gradle build system
6. Pasang gradle ke path environment variable
7. Konfigurasi gradle supaya dapat berjalan secara [daemon mode](https://docs.gradle.org/2.9/userguide/gradle_daemon.html), yaitu dengan menambahkan baris `org.gradle.daemon=true` pada file gradle.properties (buat file tersebut jika belum ada).

#### React Native Framework ####

1. Install NodeJS, bisa pakai v.4.x keatas
2. Install react native dari npm `npm install -g react-native-cli`
3. Pasang react developer tools extension pada web browser: [chrome](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi), atau firefox

#### Editor ####

Untuk editor JS ini ada banyak sekali pilihannya: visual studio (windows only), sublime, atom, brackets, dll. Silahkan pakai yang membuat kita nyaman.

Atom bisa diunduh dilink berikut: https://atom.io/.
Brackets bisa dicicipi dengan mengunduh dilink berikut: http://brackets.io/.

Sayangnya untuk pengguna linux versi terbaru, ada bugs yang memungkinkan brackets tidak dapat diinstall. Ini dikarenakan dependency dari aplikasi tersebut masih menggunakan library versi lawas yaitu libgcrypt11, sedangkan pada linux versi baru sudah menggunakan libgcrypt20. Sampai saat ini (2-Feb-2016) bugs tersebut masih dalam kondisi open atau [belum terselesaikan oleh developer brackets](https://github.com/adobe/brackets/issues/10255).

Ada yang mencoba mencari alternatif workaround yang lain dan berhasil menjalankan brackets dengan selamat. Untuk yang penasaran dan ingin mencoba, bisa mengunjungi [link berikut](http://www.webupd8.org/2015/04/fix-missing-libgcrypt11-causing-spotify.html).

### NGODING TIME ###

1. Jalankan perintah `react-native init belajarreactnative` untuk membuat project dan kita beri nama project ini belajarreactnative
2. Jalankan emulator android dengan perintah `android avd`, biasanya ketika menjalankan emulator untuk pertama kali membutuhkan waktu yang cukup lama
3. Pindahkan direktori console ke dalam project `cd belajarreactnative` dan jalankan perintah `react-native run-android` untuk menjalankan aplikasi

Referensi:
[React native android setup](https://facebook.github.io/react-native/docs/android-setup.html)
[React native getting started](https://facebook.github.io/react-native/docs/getting-started.html)
[React native tutorial](https://facebook.github.io/react-native/docs/tutorial.html)
[React developer tools chrome extension](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)

Catatan:
Instalasi ini dilakukan secara online dan membutuhkan bandwidth yang sangat besar.
Jangan sekali-sekali mencoba react ios kalau tidak menggunakan MacOS, karena akan menjadi amal perbuatan yang sia-sia.