# sbl_traefik2.0
Simple example conf for reverse proxy

Для генерации учеток для middleware auth, можно использовать:
htpasswd -c /path/to/.htpasswd username

Если нужно дабавить пользователя, то ключ -c не нужен

Если htpasswd нет на сервере, то можно например поставить так:
sudo apt-get install apache2-utils
