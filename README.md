# welcome

Статический сайт для публикации через GitHub Pages.

Адрес после включения Pages:
`https://dinkens.github.io/welcome/`

Как опубликовать:

1. Закоммитьте и отправьте репозиторий в `main`.
2. Откройте GitHub: `Settings` -> `Pages`.
3. В `Build and deployment` выберите `Deploy from a branch`.
4. В `Branch` выберите `main` и папку `/ (root)`.
5. Нажмите `Save`.

После публикации GitHub обычно выдает ссылку в течение 1-5 минут.

Что важно:

- Главная страница берется из `index.html`.
- Основной контент загружается из `welcome.html`.
- Форма RSVP отправляет данные во внешний Google Apps Script, поэтому после публикации стоит отдельно проверить отправку с домена `github.io`.
