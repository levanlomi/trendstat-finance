# TrendStat Finance — публичный дашборд

Аналитика финрынка России на основе открытых данных (Wordstat, ЦБ, НБКИ).

## Файлы

- `index.html` — интерфейс дашборда
- `data.json` — данные (обновляются автоматически из private backend repo)

## GitHub Pages

Settings → Pages → branch `main`, folder **`/frontend`**.

## Обновление данных

Ручное редактирование `data.json` не требуется: CI в private репозитории пушит свежий файл после ежемесячной сборки.
