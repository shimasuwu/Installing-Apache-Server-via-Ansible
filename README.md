Bu Ansible dosyası ile Debian ve RedHat Tabanlı Linux dağıtımlı işletim sistemlerinin;
repo listesini güncelleme,
sistem üzerinde olan paketlerin güncellenmesi,
inventory.ini dosyasında belirtilen spesifik sunucu gruplarına Apache/HTTP Server yüklenmesi,
firewalld ve ufw üzerinde var/http_https_port.yaml dosyası içerisinde her alan http ve https parametrelere karşılık gelen portların allow edilmesi,
firewall ve ufw üzerinde port allow işlemi tamamlandıktan sonra firewall servislerinin restart/reload edilmesi,
Ansible controller'da bulunan bir index dosyasının kullanılan dağıtıma göre var/apache_RedHat / var/apache_Debian dosyaları içerisinde yer alan değişkenlere karşılık gelen local dizindeki dosyaların(project_dir) bir apache sunucusna transfer edilmesi(dest_dir)
işlemlerini gerçekleştirebilirsiniz.
