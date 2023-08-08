# dev_infra

# infra builder

## Репозиторий для сборки инфраструктуры. 
Содержит необходимые репозитории для сборки и настройки инфраструктуры.
Поднимает инфру с помощью kubectl и helm. Работает на образе infra:latest
Создает неймспейсы для работы микросервисов.
Поднимает mongodb, rabbitmq, ingress-controller, prometheus stack. 
Настраивает prometheus и ingress для grafana.
Запускается после ручного подтверждения.
