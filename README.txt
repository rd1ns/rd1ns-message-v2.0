# RD1NS Message Application / RD1NS Mesaj Uygulaması

--------------------------------------------------------------------------------
[ENGLISH VERSION]
--------------------------------------------------------------------------------

## Description
RD1NS Message is a modern, real-time messaging Progressive Web Application (PWA) built with PHP, MySQL, and Vanilla JavaScript. It supports private chats, group conversations, media sharing, and real-time status updates.

## Key Features
- **Real-time Messaging:** Send and receive messages instantly.
- **Group Chats:** Create groups, manage members (Admin/Creator roles), and group avatars.
- **Media Sharing:** Support for sending Images, Audio, and general Files.
- **PWA Support:** Installable on mobile and desktop devices with offline caching and potential for push notifications.
- **User Profiles:** Customizable profile names and pictures.
- **Interactions:** Message reactions, message editing, and message deletion.
- **Story/Status:** Share temporary photos or videos (24-hour visibility).
- **User Status:** Live "Last Seen" and "Typing..." indicators.
- **System Features:** Pinned chats and read receipts (Seen status).

## Requirements
- XAMPP / WAMP / Laragon (PHP 7.4+ or 8.x)
- MySQL / MariaDB
- Web Browser (Chrome, Edge, or Safari recommended for PWA)

## Installation Steps
1. **Prepare Environment:** Ensure you have XAMPP or a similar local server running.
2. **Copy Files:** Place the project folder in your `htdocs` directory (e.g., `C:\xampp\htdocs\rd1ns-message`).
3. **Database Setup:**
   - Open PHPMyAdmin (`http://localhost/phpmyadmin`).
   - Create a new database named `rd1ns_message`.
   - Import the `rd1ns_message.sql` file provided in the root directory.
4. **Configuration:**
   - Open `includes/db.php` in a text editor.
   - Update the database credentials (`$host`, `$dbname`, `$user`, `$pass`) to match your local setup.
5. **Launch:**
   - Open your browser and navigate to `http://localhost/rd1ns-message`.
6. **Register:** Create an account using a username and start messaging!

--------------------------------------------------------------------------------
[TURKCE VERSIYON]
--------------------------------------------------------------------------------

## Aciklama
RD1NS Message; PHP, MySQL ve Vanilla JavaScript ile gelistirilmis modern, gercek zamanli bir mesajlasma Progressive Web Uygulamasidir (PWA). Ozel sohbetleri, grup konusmalarini, medya paylasimini ve gercek zamanli durum guncellemelerini destekler.

## Temel Ozellikler
- **Gercek Zamanli Mesajlasma:** Anlik mesaj gonderimi ve alimi.
- **Grup Sohbetleri:** Grup olusturma, uye yonetimi (Admin/Kurucu rolleri) ve grup resimleri.
- **Medya Paylasimi:** Resim, Ses ve Genel Dosya gonderim destegi.
- **PWA Destegi:** Mobil ve masaustu cihazlara yuklenebilir, cevrimdisi onbelirleme ve bildirim potansiyeli.
- **Kullanici Profilleri:** Ozellestirilebilir profil adlari ve resimleri.
- **Etkilesimler:** Mesaj tepkileri (emoji), mesaj duzenleme ve silme ozellikleri.
- **Durum/Hikaye:** 24 saat sureli fotograf veya video paylasimi.
- **Kullanici Durumu:** Canli "Son Gorulme" ve "Yaziyor..." gostergeleri.
- **Sistem Ozellikleri:** Sabitlenen sohbetler ve okundu bilgisi (Goruldu).

## Gereksinimler
- XAMPP / WAMP / Laragon (PHP 7.4+ veya 8.x)
- MySQL / MariaDB
- Web Tarayici (PWA icin Chrome, Edge veya Safari onerilir)

## Kurulum Adimlari
1. **Ortami Hazirlayin:** XAMPP veya benzeri bir yerel sunucunun calistigindan emin olun.
2. **Dosyalari Kopyalayin:** Proje klasorunu `htdocs` dizinine yerlestirin (orn: `C:\xampp\htdocs\rd1ns-message`).
3. **Veritabani Kurulumu:**
   - PHPMyAdmin'i acin (`http://localhost/phpmyadmin`).
   - `rd1ns_message` adinda yeni bir veritabani olusturun.
   - Kok dizinde bulunan `rd1ns_message.sql` dosyasini ice aktarin (Import).
4. **Yapilandirma:**
   - `includes/db.php` dosyasini bir metin düzenleyici ile acin.
   - Veritabani bilgilerini (`$host`, `$dbname`, `$user`, `$pass`) kendi yerel ayarlariniza gore guncelleyin.
5. **Baslatin:**
   - Tarayicinizi acin ve `http://localhost/rd1ns-message` adresine gidin.
6. **Kayit Olun:** Bir kullanici adi ile hesap olusturun ve mesajlasmaya baslayin!

--------------------------------------------------------------------------------
Designed by RD1NS / RD1NS tarafindan tasarlandi.
