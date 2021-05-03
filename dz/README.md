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
- React (nginx + php-fpm + js)

Поднимаем стенд `vagrant up`.

Wordpress
---------

В браузере открыть [http://192.168.11.10:8080/](http://192.168.11.10:8080/)

![](wordpress.jpeg)


Django
------

В браузере открыть [http://192.168.11.10:8085/](http://192.168.11.10:8085/)

![](django.jpeg)


React
------------------------

В браузере открыть [http://192.168.11.10:8090/](http://192.168.11.10:8090/)

![](react.jpeg)
