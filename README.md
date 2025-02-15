## Содержание уроков:
### Работа в облаке
- `ПР 1`. [First Alpine Linux Containers](https://training.play-with-docker.com/ops-s1-hello/).
- `ПР 2`. [Docker for Beginners - Linux](https://training.play-with-docker.com/beginner-linux/).
- `ПР 3`. [Swarm Mode Introduction for IT Pros](https://training.play-with-docker.com/ops-s1-swarm-intro/).
- `ПР 4`. [Swarm mode introduction](https://training.play-with-docker.com/swarm-mode-intro/).
- `ПР 5`. [Application Containerization and Microservice Orchestration](https://training.play-with-docker.com/microservice-orchestration/).

## Работа на локальной ВМ:
### 1. Установка Docker
- Установка Docker в Ubuntu
- Установка Docker в Windows

### 2. Первый контейнер
- Как получить образ?
- Основные команды для контейнеров
- Интерактивный режим (-it)
- Вход в работающий контейнер (exec command)
- Фоновый режим (-d)
- Как одной командой остановить/удалить все контейнеры 
- Как сохранить состояние контейнера (commit)
- Изучаем слои образа (history)

### 3. Создание образа
- Что такое Dockerfile и основной синтаксис
- .dockerignore
- Кастомный образ ubuntu
- CMD и ENTRYPOINT
- ADD и COPY
- Собственные образы на Docker Hub
- Команды для работы с репозиторием

### 4. Работа с файлами
- BIND MOUNT
- VOLUME
- Посмотреть содержимое тома, ресурс диска
- Копируем файлы в работающий контейнер (и их него) - docker cp
- Телеграм-бот в контейнере с BIND MOUNT
- Телеграм-бот в контейнере с VOLUME
- Опасность работы с BIND MOUNT
- Итог: Основные команды для работы с VOLUME

### 5. Переменные окружения, логи и порты
- Переменные окружения: прокидываем секретные данные в контейнер
- Считываем переменную окружения (токен) в телеграм-боте (python)
- Логи: консоль
- Логи: logs.txt
- Логи: библиотека
- Потоки вывода: stdout и stderr
- Управление потоками вывода
- API docker для работы с логами: docker logs
- docker inspect (узнаем все о контейнере/сети/образе)
- Проброс портов
- EXPOSE (Dockerfile)
- Разворачиваем базы данных в контейнере
- yandex/clickhouse-server
- tabix и yandex/clickhouse-server
- PostgreSQL и Superset
- Телеграм-бот с БД PostgreSQL
- Запись/дозапись в stdout и stderr
- Как узнать какой порт слушает приложение в контейнере, если не указан EXPOSE

### 6. Введение в сети
- Виды сетей в Docker
- Кастомные сети
- Немаршрутизируемые ip (0.0.0.0, 127.0.0.1 и т.д.)
- Запуск web-приложения (backend) TODO-листа в контейнерах (Flask, Postgres и Gunicorn)
- Создание кастомной сети и команды для работы с сетями
- Сравнение сетей host, bridge и none на практике
- Сетевое взаимодействие в Docker
- Сетевые интерфейсы и прослушка трафика: eth, docker, veth, lo
- Обращение контейнеров друг к другу по их имени
- Разворачивание Postgres в контейнере
- Проброс данных Postgres в контейнер с приложением
- Как зайти в консоль psql работающего контейнера Postgres
- Работа с Postgres
- Работа с несколькими сетями

### 7. Веб-приложение в контейнерах
- Фронтенд Nginx
- Multi-stage build
- Сборка фронтенда
- Веб-приложение в контейнерах

### 8. YAML и docker-compose
- YAML
- docker-compose
- Разворачиваем Airflow
- Команды

### 9. Веб-приложение в docker-compose
- Инструкции docker-compose
- Веб-приложение в docker-compose
- Расширяем docker-compose файл
- Сокращаем docker-compose файл

### 10. За пределами контейнеров
- Ansible
- CI/CD
- Kubernetes

