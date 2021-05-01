## Динамический WEB.

Развернуть веб приложения:
- nginx + php-fpm (laravel/wordpress) + python (flask/django) + js(react/angular) nginx + java (tomcat/jetty/netty) + go + ruby можно свои комбинации

Реализации на выбор:
- на хостовой системе через конфиги в /etc
- деплой через docker-compose


### Реализация.
Для развертывания веб приложения подготовим сервер с сайтами:

- Wordpress (nginx + php-fpm)
- Django (nginx + python)
- nginx + python (flask/django)

Поднимаем стенд `vagrant up`.

Wordpress
---------

В браузере открыть [http://192.168.11.10:81/](http://192.168.11.10:81/)

![](wordpress.jpeg)


Django
------

В браузере открыть [http://192.168.11.10:82/](http://192.168.11.10:82/)

![](django.jpeg)


Проверка сайта Wordpress
------------------------

В браузере открыть [http://192.168.11.10:8082/](http://192.168.11.10:8082/)

![](wordpress.jpeg)
