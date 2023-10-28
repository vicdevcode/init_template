# ЭТО МОЙ ШАБЛОНЧИК ДЛЯ ОБЫЧНОГО REST API СЕРВЕРА

Простой шаблон, который имеет в себе config, logger, postgres, gorm.

## Интеграция в проект

```bash
go mod init <реп>
```

Скопировать всё кроме `go.mod и go.sum`, но удали `example.config.yaml` и
`example.env`

Добавить свои `.env` и `config.yaml`

Не забыть создать `bin` папку

Заменить все import на свой <реп>
