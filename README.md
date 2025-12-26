# WinNMP

## Windows Nginx MySql PHP 5.2-8.5 stack

[The project](https://web.archive.org/web/20240518072335/https://sourceforge.net/projects/wtnmp/) was dropped 
and now you cannot install it.
So I created [ISO-image](https://drive.google.com/file/d/1o8EU-P74rOIAgFU4ghgVcz2jrOMkJAvv/view?usp=sharing) with already installed stack
(last available version 21.10).   

### Inside
* nginx version: nginx/1.29.4, 
  built by cl 19.44.35211 for x86,
  built with OpenSSL 3.5.4 30 Sep 2025,
  TLS SNI support enabled
* OpenSSL 1.1.1d-dev  xx XXX xxxx
* mysql  Ver 15.1 Distrib 10.4.21-MariaDB, for Win64 (AMD64), source revision 4902b0fdc91cc6dc169dd2322daf966a2eeafdd8
* MongoDB shell version v4.2.23
* Redis v5.0.10
 

* PHP-5.2.17-x86
* PHP-5.3.29-x86
* PHP-5.4.45-x64
* PHP-5.4.45-x86
* PHP-5.5.38-x64
* PHP-5.6.40-x64
* PHP-7.0.33-x64
* PHP-7.1.33-x64
* PHP-7.2.34-x64
* PHP-7.3.33-x64
* PHP-7.4.33-x64
* PHP-8.0.30-x64
* PHP-8.1.32-x64
* PHP-8.2.29-x64
* PHP-8.3.25-x64
* PHP-8.4.12-x64
* PHP-8.5.01-x64

PHP-8.0 - PHP-8.5 with Xdebug v3.5.0


### Installation
* Unpack zip archive containing ISO-image;
* Mount ISO-image;
* Copy &laquo;WinNMP&raquo; folder to appropriate place;
* Add &laquo;bin&raquo;folder to environment variable 
&laquo;Path&raquo;;
* Set &laquo;WINNMP_WWW_UNIX&raquo; environment variable i.e.
&laquo;D:/WWW&raquo;
* Run &laquo;bin/winnmp_setup.bat&raquo;

You are ready to run &laquo;WinNMP.exe&raquo;. 
