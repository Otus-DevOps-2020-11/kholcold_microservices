# kholcold_microservices
kholcold microservices repository

HW 12 - docker-2

Выполнена основная работа, директория с файлами [docker-monolith](docker-monolith)

HW 13 - docker-3

Выполнена основная работа, директория с файлами [src](src)

HW 14 - docker-4

Выполнена основная работа:
- Файл [docker-compose.yml](src/docker-compose.yml)
- Файл [.env.example](src/.env.example)
- Изменить базовое имя проекта можно через переменную [COMPOSE_PROJECT_NAME](https://docs.docker.com/compose/reference/envvars/#compose_project_name) или при запуске проекта через командную строку ```docker-compose -p, --project-name NAME```

HW 15 Выполнена основная работа:
- Файл [docker-compose.yml](gitlab-ci/docker-compose.yml) для развертывания gitlab.
- Пайплаин [.gitlab-ci.yml](.gitlab-ci.yml)

HW 16 Выполнена основная работа:
- Файл [docker-compose.yml](docker/docker-compose.yml) для развертывания мониторинга.
Ссыдки на образы:
- [kholcold/ui](https://hub.docker.com/r/kholcold/ui)
- [kholcold/comment](https://hub.docker.com/r/kholcold/comment)
- [kholcold/post](https://hub.docker.com/r/kholcold/post)
- [kholcold/prometheus](https://hub.docker.com/r/kholcold/prometheus)

HW 17 Выполнена основная работа:
- Добавили в мониторинг grafana и alertmanager [monitoring](monitoring)