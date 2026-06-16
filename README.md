# moy-proekt-dashboards

Публикуемые дашборды для руководства. Хостится через **Cloudflare Pages** (автодеплой при push),
доступ закрыт через **Cloudflare Access** (вход по e-mail из списка).

Приватный репозиторий. Источник отчётов и runbook - в основном репозитории `moy-proekt`
(`business/reports/`). Сюда кладётся только готовый `index.html` под публикацию.

## Обновление

1. В `moy-proekt` пересобрать отчёт и скопировать в `index.html` здесь.
2. `git add index.html` -> `git commit` -> `git push`.
3. Cloudflare Pages автоматически передеплоит. URL не меняется.
