Bu Ansible dosyası ile <strong>Debian ve RedHat</strong> Tabanlı Linux dağıtımlı işletim sistemlerinin; <br>
<ul>
  <li>repo listesinin güncelleme işleminin gerçekleştirilmesi <br> </li>
  <li>sistem üzerinde olan paketlerin güncellenmesi <br> </li>
  <li>inventory.ini dosyasında belirtilen spesifik sunucu gruplarına Apache/HTTP Server kurulumunun gerçekleştirilmesi <br> </li>
  <li>firewalld ve ufw üzerinde var/http_https_port.yaml dosyası içerisinde yer alan http ve https parametrelere karşılık gelen portların allow hale getirilmesi <br> </li>
  <li>firewalld ve ufw üzerinde port allow işlemi tamamlandıktan sonra firewall servislerinin restart/reload edilmesi <br> </li>
  <li>Ansible controller'da bulunan bir index dosyasının kullanılan dağıtıma göre var/apache_RedHat / var/apache_Debian dosyaları içerisinde yer alan değişkenlere karşılık gelen local dizindeki dosyaların <i>(project_dir)</i>i> bir apache sunucusna transfer edilmesi <i>(dest_dir)</i> <br> </li> işlemleri gerçekleştirilebilmektedir.
<ul>

