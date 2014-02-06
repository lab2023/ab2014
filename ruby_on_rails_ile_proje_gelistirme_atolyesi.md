Ruby on Rails İle Proje Geliştirme Atölyesi
===========

Eğitmen
-------

* Muhammet DİLEK - <muhammetdilek@lab2023.com>
* Twitter: [@dilekmuhammet](https://twitter.com/dilekmuhammet)
* GitHub: [muhammetdilek](https://github.com/dilekmuhammet)
* Blog: [http://www.muhammetdilek.com](http://www.muhammetdilek.com)

Başvuru Şartları
----------------
* Ruby On Rails ile tanışmış olmak.
* Tercihen, daha önce çalışan bir projede yer almak.

Katılmadan Önce Yapılması Gerekenker
-------------
* 15-20 dk sürecek [http://try.github.io](http://try.github.io) serisini bitirmek .
* Geliştirme ortamlarının ayarlanması. Bu işlem için aşağıdaki adımları takip edebilirsiniz.
	* Ubuntu 12 veya 13 Linux dağıtımlarından birisini bilgisayarınıza kurmak.
	* Performans problemleri yaşamamak için işletim sistemini, sanal makine yerine, bilgisayarınızın herhangi bir bölümüne kurmanız önerilir.
	* Linux için kurulum scripti için daha sonra [https://github.com/kebab-project/builder](https://github.com/kebab-project/builder) adresinden ilgili bash script paylaşılacaktır.
* Temel linux bilgisine sahip olmak en azından chmod, tail ve nano veya vim'i basit düzeyde kullanabiliyor olmak.

Kurs İçeriği
-------------
### Proje Tanımı
* **Proje İsmi:** Yakut Project
* **Github Organizasyon:** [https://github.com/yakut-project/](https://github.com/yakut-project/)
* **Tanım:** Proje kurs ve seminerler için eğitmen ve öğrencilerin kolayca yönetimini sağlayarak, başvuruları otomatik hale getirerek, süreçleri hızlandıracaktır.

### Proje Geliştirme Süreci
* Git, Github, GitFlow, Semver, Huboard(Kanban) teknolojilerinin anlatılması.
* Proje modellemesi yapılacaktır.
* Projenin oluşturulması ve github reposu güncellemeleri (Issue, milestones).
* Rails generator' ların projeye göre düzenlenmesi.
* Projenin kodlanması.
* Projenin herokuya deploy edilmesi.
* Projenin güncel bir ubuntu sunucusuna deploy edilmesi.

### Başlangıç

* Çevik programlama araçları
	* Git, GitHub
	* GitFlow 
		* [http://danielkummer.github.io/git-flow-cheatsheet/index.tr_TR.html](http://danielkummer.github.io/git-flow-cheatsheet/index.tr_TR.html)
		* [http://nvie.com/posts/a-successful-git-branching-model/](http://nvie.com/posts/a-successful-git-branching-model/)
	* Semver - [https://github.com/lab2023/semver/blob/master/semver_tr.md](https://github.com/lab2023/semver/blob/master/semver_tr.md)
	* Huboard Kanban - [https://github.com/lab2023/playbook/blob/master/development/cevik_proje_yonetimi.md#huboard](https://github.com/lab2023/playbook/blob/master/development/cevik_proje_yonetimi.md#huboard)


### Projede Anlatılacak Gemler

* cybele
* haml, haml-rails
* bootstrap-sass
* responders
* exception_notification
* simple_form
* show_for
* rails_config
* devise
* will_paginate
* paperclip
* kangal
* ransack
* hierapolis-rails
* breadcrumbs_on_rails
* blankable
* capistrano
* unicorn

### Deploy İşlemleri

#### Heroku

* Heroku Toolbelt / Heroku GEM kurulumu.
* Heroku hesabı açılması.
* Heroku yönetim konsolunun tanıtılması.
* Heroku'ya deploy.

#### VPS

Standart bir VPS'e deploy yapılacaktır.
