Ruby on Rails 101
===========

Eğitmen
-------

* Tayfun Öziş ERİKAN - <tayfun.ozis.erikan@lab2023.com>
* Twitter: [@toziserikan](https://twitter.com/toziserikan)
* GitHub: [tayfunoziserikan](https://github.com/tayfunoziserikan)

Asistan Eğitmen
---------------

* Ahmet Sezgin DURAN - <ahmet.sezgin.duran@lab2023.com>
* Twitter: [@marjinal1st](https://twitter.com/marjinal1st)
* GitHub: [marjinal1st](https://github.com/marjinal1st)

Başvuru Şartları
----------------

* Temel ruby bilgisine sahip olmak
* HTTP, Web Server, Request/Response, REST gibi konulara en azından wikipedia'dan göz gezdirmiş olmak
* OOP: Object-oriented programming - Nesne yönelimli programlama bilgisine sahip olmak
* Başka bir dilde MVC, ORM tasarım şablonlarını kullanan frameworkler kullanmış olmak
* Herhangi bir VCS kullanmış olmak ve tercihen Git biliyor olmak
* Bir GitHub hesabına sahip olmak


Katılmadan Önce Yapılması Gerekenker
-------------
* 30-40 dk sürecek [http://tryruby.org](http://tryruby.org) serisini bitirmek
* 15-20 dk sürecek [http://try.github.io](http://try.github.io) serisini bitirmek 
* Geliştirme ortamlarının ayarlanması. Bu işlem için aşağıdaki adımları takip edebilirsiniz
	* Ubuntu 12 veya 13 Linux dağıtımlarından birisini bilgisayarınıza kurmak
	* Performans problemleri yaşamamak için işletim sistemini, sanal makine yerine, bilgisayarınızın herhangi bir bölümüne kurmanız önerilir
	* Linux için kurulum scripti için daha sonra [https://github.com/kebab-project/builder](https://github.com/kebab-project/builder) adresinden ilgili bash script paylaşılacaktır
* Temel linux bilgisine sahip olmak en azından chmod, tail ve nano veya vim'i basit düzeyde kullanabiliyor olmak

Kurs İçeriği
-------------

### Başlangıç

* Çevik programlama araçları
	* Git, GitHub
	* GitFlow 
		* [http://danielkummer.github.io/git-flow-cheatsheet/index.tr_TR.html](http://danielkummer.github.io/git-flow-cheatsheet/index.tr_TR.html)
		* [http://nvie.com/posts/a-successful-git-branching-model/](http://nvie.com/posts/a-successful-git-branching-model/)
	* Semver - [https://github.com/lab2023/semver/blob/master/semver_tr.md](https://github.com/lab2023/semver/blob/master/semver_tr.md)
	* Huboard Kanban - [https://github.com/lab2023/playbook/blob/master/development/cevik_proje_yonetimi.md#huboard](https://github.com/lab2023/playbook/blob/master/development/cevik_proje_yonetimi.md#huboard)

* Temel ruby bilgileri
	* Ruby tanıtımı ve genel özellikleri
	* Irb konsol ile ruby kullanımı
	* RubyGems - Ruby Paket Yöneticisi
	* Bundler
	* Alternatif konsol: Pry
	* Ruby & Rails kaynaklarının paylaşılması

* Geliştirme ortamlarınında problem yaşayan öğrencilerin kurulumlarının tamamlanması

### Rails İle Isınma Turları

* Rails İçin Gereken Temel Bilgiler
	* MVC
	* REST ve RESTful
	* DAO ve ORM
	* Rack Middleware (Basit bir web uygulaması hazırlanacaktır)

* Rails'e Hızlı Başlangıç
	* Rails Guides tanıtımı ve kullanımı
	* Rails nedir?
	* Rails'i kurmak
	* Yeni bir rails projesi oluşturmak
	* Bir blog uygulaması oluşturmak
		* İlk rails uygulamanıza "Merhaba!" demek
		* Uygulamayı geliştirmek ve detaylandırmak
		* Uygulamaya ikinci bir model oluşturmak
		* Kodunuzu iyileştirmek ve sadeleştirmek (Code refactoring)
		* Yorum eklemek ve yorumları silmek
		* Blog uygulaması için güvenlik ayarları
	* Scaffolding

### Temel Rails Bileşenleri

* Models (Model Katmanı)
	* Active Record temelleri
	* Rails Database Migrations
	* Active Record Validations
	* Active Record Callbacks
	* Active Record Assocations
	* Active Record Query Interface

* Views (View Katmanı)
	* Action View genel bakış
	* Layouts & Rendering in Rails
	* Action View Form Helpers

* Controllers (Controller Katmanı)
	* Action Controller genel bakış
	* Routing ve router kullanımı

### Derinlemesine Rails

* Active Support temel bileşenleri (Hızlı bakış)
* Uluslararasılaşma (I18n) API
* Action Mailer temelleri
* Güvenlik (Security) (Hızlı bakış)
* Hata ayıklama (Debuging) (Hızlı bakış)
* Konfigurasyon (Configuring) (Hızlı bakış)
* Komut satırı araçları ve rake görevleri (CLI Tools & Rake Tasks)
* Önbellekleme (Caching) (Hızlı bakış)
* Varlık yönetimi (Asset Pipeline)
* Rails'de JavaScript ile çalışmak (JavaScript in Rails)
* Rails için rack (Hızlı bakış)

### Araçlar ve Alet Çantası

* Kullandığımız bazı GEM'lerin tanıtımı
	* Haml ve haml-rails
	* Compass ve compass-rails
	* Sass ve sass-rails
	* Devise
	* Simple Form
	* Twitter Bootstrap ve Bootstrap-sass
	* Responder
	* Whenever
	* Capistrano
	* Daha fazlası için bkz: [https://github.com/lab2023/playbook/blob/master/development/ruby.md#ruby-gems](https://github.com/lab2023/playbook/blob/master/development/ruby.md#ruby-gems)
* [Kebab Project](https://github.com/kebab-project) ekosisteminin ve GEM'lerinin tantımlası
	* Cybele
	* Katip
	* Hierapolis ve hierapolis-rails
	* Blankable
	* Kangal
	* Kebab Remote API & Client

### Uygulamanızın Yayınlanması (Deployment)

Bu bölümde Rails uygulamanızın Heroku'ya ve standart bir VPS'e gönderilmesi anlatılacaktır. 
Deploy öncesi uygulamanız local ortamda Production'a çekilecek ve test edilecektir.

#### Heroku
* Heroku Toolbelt / Heroku GEM kurulumu 
* Heroku hesabı açılması
* Heroku yönetim konsolunun tanıtılması
* Heroku'ya deploy

#### VPS
Standart bir VPS'e deploy için [https://github.com/lab2023/playbook/blob/master/development/server.md](https://github.com/lab2023/playbook/blob/master/development/server.md)
kaynağından bahsedilecektir.

### Topluluk (Community)
* Açık Kaynak felsefesi
* Rails'in gelişimi ve topluluğun katkısı
* Rails'e nasıl katkı sağlarsınız?
* Birlikte neler geliştirebilirsiniz ve açık kaynaklı projelere nasıl katkı sağlarsınız?

### Soru & Cevap

Bu bölümde katılımcıların kurs hakkındaki genel soruları cevaplandırılacaktır.