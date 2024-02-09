# Руководство по развёртыванию Moodle с использованием Docker

## Зависимости

### Для развёртывания данного решения потребуется установленный Docker и Docker Compose на вашем хосте.

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Развёртывание

1. **Клонирование репозитория**

   ```bash
   git clone https://github.com/komore1616/moodle
   cd moodle
2. **Запуск контейнера**

   ```bash
   docker compose up -d
3. **Проверка работоспособности**

 Откройте браузер и перейдите по адресу http://localhost:80 для доступа к Moodle.
 Используйте учетные данные пользователя Moodle, указанные в файле .env.
