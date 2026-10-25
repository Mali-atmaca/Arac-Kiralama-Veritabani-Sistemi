🚗 Araç Kiralama ve Veritabanı Yönetim Sistemi

PHP & MySQL | Database Management System

PHP ve MySQL kullanılarak geliştirilmiş, araç kiralama süreçlerini ve veritabanı işlemlerini yönetmeyi amaçlayan web tabanlı bir uygulamadır.

Bu proje, Veritabanı Yönetim Sistemleri dersi kapsamında ilişkisel veritabanı tasarımı, SQL sorguları, Stored Procedure, Trigger ve PHP–MySQL entegrasyonu konularının uygulamalı olarak öğrenilmesi amacıyla geliştirilmiştir.

🎯 Projenin Amacı

Araç kiralama işletmelerinde araçların, müşterilerin ve kiralama işlemlerinin tek bir sistem üzerinden yönetilmesini sağlamak.

Proje kapsamında:

Araç bilgilerinin yönetilmesi

Müşteri kayıtlarının tutulması

Araç kiralama ve iade süreçlerinin takip edilmesi

Kullanıcı kayıt ve giriş işlemleri

Yönetici paneli üzerinden verilerin yönetilmesi

SQL Stored Procedure ve Trigger yapılarıyla veritabanı işlemlerinin gerçekleştirilmesi

hedeflenmiştir.

🛠️ Kullanılan Teknolojiler

Teknoloji

Kullanım Amacı

PHP

Backend geliştirme

MySQL

İlişkisel veritabanı yönetimi

SQL

Veri sorgulama ve işleme

Stored Procedures

Veritabanı işlemlerinin merkezi olarak yürütülmesi

Triggers

Veritabanı olaylarında otomatik işlemler

PDO

PHP ile parametreli veritabanı sorguları

HTML5

Web sayfalarının yapısı

CSS3

Kullanıcı arayüzü

XAMPP

Yerel PHP ve MySQL geliştirme ortamı

✨ Temel Özellikler

👤 Kullanıcı Yönetimi

Kullanıcı kayıt olma ve giriş yapma

PHP Session ile oturum yönetimi

Yönetici ve kullanıcı yetkilerinin ayrılması

Oturum kapatma işlemleri

🚘 Araç Yönetimi

Araç ekleme ve bilgilerini güncelleme

Araç listeleme

Araç detaylarını görüntüleme

Araçların kiralama durumlarını takip etme

📋 Kiralama Yönetimi

Araç kiralama kayıtlarının oluşturulması

Kiralanan araçların listelenmesi

Müşteri ve araç kayıtlarının ilişkilendirilmesi

Kiralama işlemlerinin veritabanında yönetilmesi

🛡️ Yönetici Paneli

Araç kayıtlarının yönetimi

Kiralama işlemlerinin kontrolü

PHP üzerinden veritabanı işlemlerinin gerçekleştirilmesi

Yönetici yetkisiyle erişim kontrolü

🗄️ Veritabanı Tasarımı

Projenin temelini MySQL üzerinde oluşturulan ilişkisel veritabanı yapısı oluşturmaktadır.

Veritabanı tasarımında tablolar arasındaki ilişkiler, anahtar alanlar ve veri bütünlüğü dikkate alınmıştır.

Stored Procedures: Araç ekleme, güncelleme ve diğer veritabanı işlemlerinin SQL tarafında yönetilmesini sağlar.

Triggers: Belirli veritabanı olayları gerçekleştiğinde otomatik işlemler yürütmek için kullanılır.

PDO Prepared Statements: Kullanıcıdan alınan verilerin parametreli sorgularla işlenmesini sağlar.

Bu yapı sayesinde uygulamanın iş mantığı ile veritabanı işlemleri arasında daha düzenli bir entegrasyon hedeflenmiştir.

📁 Proje Dosya Yapısı

Arac-Kiralama-Veritabani-Sistemi/
│
├── admin.php
├── arac_detay.php
├── arac_kiralama.sql
├── db.php
├── home.php
├── index.php
├── kiralanan_araclar.php
├── login.php
├── logout.php
├── navbar.php
├── register.php
├── style.css
├── .gitignore
├── .gitattributes
├── LICENSE
└── README.md

🚀 Kurulum ve Çalıştırma

1. Gereksinimler

PHP

MySQL

Apache Web Server

XAMPP veya eşdeğer bir yerel sunucu ortamı

2. Projeyi indirin

git clone https://github.com/Mali-atmaca/Arac-Kiralama-Veritabani-Sistemi.git

3. Projeyi XAMPP dizinine yerleştirin

Projeyi aşağıdaki dizine kopyalayın:

C:\xampp\htdocs\Arac-Kiralama-Veritabani-Sistemi

4. Veritabanını oluşturun

XAMPP üzerinden Apache ve MySQL servislerini başlatın.

http://localhost/phpmyadmin adresini açın.

arac_kiralama.sql dosyasını içeri aktarın.

SQL dosyasında tanımlanan veritabanı yapısının oluştuğunu kontrol edin.

5. Veritabanı bağlantısını yapılandırın

db.php dosyasında kullanılan bağlantı ayarlarını kendi MySQL ortamınıza uygun olarak yapılandırın.

Veritabanı kullanıcı adı ve şifreleri GitHub deposuna eklenmemelidir. Gerçek bağlantı bilgileri ortam değişkenleri üzerinden sağlanmalıdır.

6. Uygulamayı başlatın

Tarayıcınızdan şu adresi açın:

http://localhost/Arac-Kiralama-Veritabani-Sistemi/

Not: Paylaşılan SQL dosyası örnek kullanıcı veya müşteri kayıtları içermiyorsa uygulama başlangıçta boş veritabanıyla çalışacaktır.

🔐 Güvenlik ve Sınırlamalar

Veritabanı bağlantı bilgilerinin doğrudan kaynak kodda paylaşılmaması hedeflenmiştir.

Veritabanı şeması paylaşılırken gerçek müşteri ve kullanıcı verileri kaldırılmıştır.

Projede oturum ve rol temelli erişim kontrolleri bulunmaktadır.

Parola saklama ve oturum güvenliği üretim ortamında kullanılmadan önce iyileştirilmelidir.

Proje eğitim amaçlı geliştirilmiştir; üretim ortamında kullanıma hazır olduğu iddia edilmemektedir.

📈 Kazanılan Teknik Yetkinlikler

Bu proje kapsamında aşağıdaki konularda uygulama geliştirme deneyimi kazanılmıştır:

Relational Database Design

SQL Queries

Stored Procedures & Triggers

PHP Backend Development

PDO Database Connectivity

CRUD Operations

Session Management

Database Integration

🔮 Gelecekteki Geliştirmeler

Parolaların password_hash() ve password_verify() ile güvenli şekilde yönetilmesi

Daha kapsamlı kullanıcı yetkilendirme mekanizması

CSRF koruması ve gelişmiş form doğrulama

Araç müsaitlik takvimi

Kiralama süresi ve ücret hesaplamalarının geliştirilmesi

Yönetici paneline raporlama ve istatistik ekranları

Responsive arayüz iyileştirmeleri
