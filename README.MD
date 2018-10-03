# **Docker Test Task**

Для запуска приложения необходимо:

## Окружение:
  - Docker 
  - Docker Compose
  
## Доступ к проекту:
 - В файле **docker-compose.yml** для переменных **GIT_USD**, **GIT_PWD** указать
 свой логин и пароль для доступа в GitLab.
 
## Предустановки

 - Необходимо установить **Docker** и **Docker Compose**.
 
 P.S. В случае проблем с **Docker For Windows** рекомендуется использовать 
 виртуальную машину с **Ubuntu Desktop**.
 - [Установка Docker на Linux](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
 - [Установка Docker на Windows](https://docs.docker.com/docker-for-windows/install/#install-docker-for-windows-desktop-app)
 - [Установка Docker Compose](https://docs.docker.com/compose/install/)
 
 
## Запуск
 Выполнить из корня проекта команду:
 - _docker-compose up -d_

Приложение будет доступно по адресу:
- _localhost:8080/web_ - веб часть.
- _localhost:8080/api_ - API.

Где _localhost_ - адрес машины, на которой установлен Docker.