# laravel-app-dockerized
### DOCKER - Install into Linux, Nginx, MySQL, PHP, LARAVEL (LEMP stack)
<div align="center">
  <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="600" height="300"/>
</div>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&pause=1000&center=true&vCenter=true&multiline=true&width=1080&height=160&lines=I+welcome+everyone!+My+name+is+Rinat.+;I+am+engaged+in+web+development+of+back-end+applications+and;websites+and+a+little+front-end." alt="Typing SVG" /></a>

### Инструкция по разворачиванию среды разработки на ваш компьютер:
1. Склонируйте данную сборку на ваш локальный компьютер и выбранную директорию.
2. В консоле-терминале наберите команду:
* docker-compose up -d
3. В консоле-терминале наберите команду:
* docker-compose run composer create-project laravel/laravel .
4. В файле .env введите информацию для соединения с базой данных( с mysql.env), эта информация находится в /var/www/laravel-app-dockerized/env/mysql.env (это вводная инфа исходник который вы можете редактировать)
5. В консоле-терминале наберите команду:
* sudo chmod - R 777 var/www
6. Перейдите в директорию src:
* cd src
7. В консоле-терминале наберите команду:
* docker-compose run artisan migrate
* docker-compose run artisan serve
8. В среде разработки IDE PHP STORM настройте подключение к БД:
* HOST: localhost
* port: 3316
* user: laravel
* database: laravel_db
* password: password
#### Импорт и экспорт даннных легко можете сделать через приложение HeidiSql она бесплатна и доступна к скачиванию в маркете Линукса Убунту.
* Важная инфрормация о том что незабывайте при сборке учитывать совместимости и версии среды разработки программ и версии языка.
* Пример: если вы решите сделать сборку с php 7-7.4 то учитывайте что и версия mysql будет 5-5,7 и фреймворк ларавел будет примерно установлен 5-8,5.
* При сборке своего проекта будте внимательны. Всем желаю кода без бага и успеха в разработке!



