# antiDDoS
Free simple anti DDoS script in PHP for your site

Бесплатный простой анти DDoS скрипт на PHP для вашего сайта

# How to install
1. Скачать архив
2. Распаковать. В главную дирректорию загрузить файлы: antiddos.php, data.php, .htaccess и папку logs.
3. В каждую внутреннюю директорию закинуть 2 файла из папки folder, а именно .htaccess и main.php
4. В файле data.php заполнить данный MySQL, а так же установить следующие лимиты:<br> 
  4.1. $limit - ограничение по количеству запросов в заданное время, после которого ip уйдет в бан (записываться в .htaccess как запрещенный ip адрес)<br> 
  4.2. $second - ограничение по времени, (за какой промежуток времени в секундах будет проверяться кол-во запросов($limit) )
5. Зайти на PHPMyAdmin и выполнить запрос на создание таблицы. Код создания таблицы представлен в файле antiddos.sql

<i>(Позже, как будет время создам полноценный скрипт для автоматической установки)</i>

<i>(Так же в .htaccess прописал запрет на все ip адреса Tor Project, зачастую ддос идёт через них)</i>

# Пожалуйста, скиньте рублей 50 на пиво!))
<b>Донатерная!</b><br>
http://FSystem88.ru/donate
<br>
https://paypal.me/FSystem88
<br>
https://qiwi.com/n/FSYSTEM88
<br>
https://money.yandex.ru/to/410015440700904
<br>
<br>