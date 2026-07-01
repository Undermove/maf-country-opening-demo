# Процесс открытия страны (упрощённо)

1. **Ветка** — создаём `feature/country-<код>` от `main`.
2. **Конфиг страны** — добавляем `countries/<код>.json`
   (поля: `code`, `name`, `currency`, `languages`, `status: "opening"`).
3. **Язык** — при необходимости добавляем язык в `languages/languages.json`.
4. **Pull Request** — открываем PR с изменениями. Ревью и мёрж — за человеком.
