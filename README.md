# Builder's guild

## Подготовка окружения

1. Необходимо убедиться что на ПК установлен Docker: для проверки выполняем в терминале команду `docker -v` в итоге должен отобразиться номер версии, если этого нет тогда надо выполнить [установку](https://docs.docker.com/engine/install/ubuntu/)
2. Также должен быть установлен NodeJs локально: для проверки выполняем в терминале команду `node -v` в итоге должен отобразиться номер версии, если этого нет тогда надо выполнить [установку](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04)

## Установка проекта

1. Открываем терминал в папке этого проекта, и запускаем команду `docker compose build`, после успешного билда выполняем `docker compose up -d`
2. Далее выполняем **ЕДИНОРАЗОВО ПРИ ПЕРВОЙ НАСТРОЙКЕ ПРОЕКТА** команду `docker exec guild-app sh docker/first_start.sh`
3. Далее выполняем команду `npm i` и `npm run dev`
4. В итоге мы можем попасть на страницу проекта по этому адресу [http://localhost:8181/](http://localhost:8181/)


## Полезная информация

- Авторизоваться на сайте можно под двумя аккаунтами:
1. Админ: <br> - телефон `777` <br> - пароль `111`
2. Юзер: <br> - телефон `888` <br> - пароль `111`



