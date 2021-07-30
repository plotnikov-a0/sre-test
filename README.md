## Решение тестового задания для SRE инженера.
В репозитории находятся два плейбука:

[site.yml](https://github.com/plotnikov-a0/sre-test/blob/main/site.yml) - разворачивает Nginx и PostgreSQL на сервере, скачивает актуальную версию приложения из репозитория и запускает его в контейнере.

[deploy.yml](https://github.com/plotnikov-a0/sre-test/blob/main/deploy.yml) - подтягивает актуальную версию приложения, перезапускает контейнер.
