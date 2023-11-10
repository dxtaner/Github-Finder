
GitHub Kullanıcı Bilgi Uygulaması
=================================

Bu basit Flask uygulaması, kullanıcıdan aldığı GitHub kullanıcı adını kullanarak GitHub API'ye istek yapar ve kullanıcının profil bilgilerini ile repolarını getirir. Eğer kullanıcı bulunamazsa, uygun bir hata mesajı gösterir.

Kurulum
-------

1.  İlk olarak, Python'un yüklü olduğundan emin olun. [Python'u indirin](https://www.python.org/downloads/).
2.  Proje dosyalarını bilgisayarınıza indirin veya klonlayın.

    git clone [https://github.com/yourusername/github-user-info-app.git](https://github.com/dxtaner/Github-Finder/blob/main/Github%20Finder/github.py)

4.  Proje dizinine gidin.

    cd Github-Finder

6.  Sanal bir ortam oluşturun ve etkinleştirin.

    python -m venv venv

    source venv/bin/activate  

11.  Uygulamayı çalıştırın.

    python github.py

13.  Tarayıcınızdan [http://127.0.0.1:5000/](http://127.0.0.1:5000/) adresine gidin.

Kullanım
--------

1.  Ana sayfada GitHub kullanıcı adınızı girin ve "Ara" butonuna tıklayın.
2.  Kullanıcının profil bilgileri ve repoları görüntülenecektir.

Lisans
------

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.
