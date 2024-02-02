# h3 Hello Web Server

## x) Lue ja tiivistä

### IP-pohjainen virtual host:
-	Jokaisella verkkosivustolla tulee olla oma IP-osoite

### Nimipohjainen virtuaali host:
-	Kätevämpi verrattuna IP-pohjaiseen
-	Useat verkkosivut voivat jakaa saman IP-osoitteen, näin ollen IP-osoitteita säästyy
-	Jokaiselle verkkosivulle määritellään oma verkkotunnus (esim. www.esimerkki1.com, www.esimerkki2.com), jonka jälkeen DNS-palvelin konfiguroidaan niin että kyseiset verkkotunnukset liitetään samaan ip-osoitteeseen
-	Apache http serverissä käytetään VirtualHost-komentoa määrittelemään eri asetukset kullekkin sivustolle

### Lähteet: 
https://httpd.apache.org/docs/2.4/vhosts/name-based.html 
Karvinen, Tero. Name Based Virtual Hosts on Apache – Multiple Websites to Single IP Address. Luettu 02.02.2004. Luettavissa: https://terokarvinen.com/2018/04/10/name-based-virtual-hosts-on-apache-multiple-websites-to-single-ip-address/ 

### A) 
Ensiksi asensin Apache-weppipalvelimen "sudo apt install apache2" komennolla komentorivillä. Seuraavaksi testasin, että weppipalvelimeni vastaa localhost-osoitteesta:



