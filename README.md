# LAMP

參考資訊
LAMP Web Server 網頁伺服器快速建置入門 :
https://www.peterdavehello.org/2016/03/lamp-linux-apache-mysql-php-web-server-fast-setup-essential/

PHP 安裝 mbstring 模組:
https://www.phpini.com/php/install-php-mbstring


安裝 apacha2 , php , mysql in ubuntu 16.04 :

sudo apt-get install apache2 libapache2-mod-php php php-mysql php-json php-mbstring mysql-server

------------------------------------------------------------
安裝完了，接下來開始驗收/驗證

1. 確認 apache 運作
curl -I 127.0.0.1  

HTTP/1.1 200 OK
Date: Thu, 25 Feb 2016 17:11:41 GMT
Server: Apache/2.4.7 (Ubuntu)
Last-Modified: Thu, 25 Feb 2016 15:33:31 GMT
ETag: "2cf6-52c99e79eb044"
Accept-Ranges: bytes
Content-Length: 11510
Vary: Accept-Encoding
Content-Type: text/html

同時我們也可以透過瀏覽器開啟對應的網頁畫面，如果是在本機上架設可以開啟 http://localhost/ 、http://127.0.0.1/


用 apache, nginx, PHP架網站要注意的安全事項 :

https://www.peterdavehello.org/2014/05/apache-php-web-server-notes/


