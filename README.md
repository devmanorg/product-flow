# Product Flow — фреймворк и каталог заданий на разработку ПО

Внимание! Это ранняя предрелизная версия базы. Многие фрагменты ещё плохо проработаны, изменения вносятся веерным способом и без каких либо предупреждений.

После релиза первой версии 1.0 скорость изменений заметно спадёт, и все правки можно будет отслеживать по CHANGELOG.

Набор заданий на разработку типовых продуктов, из которых можно сложить более крупные, сложные и уникальные продукты. Включает в себя полезные чеклисты:

- для самостоятельной проверки качества
- со стандартными рисками → возможность подготовиться и проработать их заранее
- полезные материалы и инструменты

Работу команды можно рассматривать как последовательность изготавливаемых продуктов, где каждый следующий строится на базе предыдущих. Например:

```
- Комплект пользовательских историй
- Макеты ключевых страниц
- Комплект фич
- Детальные сценарии использования
- …
```

Важно, что перечисленные продукты не одноразовые, а продолжают поддерживаться на протяжении всей жизни проекта, включая его последующую поддержку.

## Основной шаблон

Фреймворк задаёт структуру новых заданий на продукты с помощью шаблона. Используйте его, когда создаёте что-то с нуля: 

- [Шаблон yaml-задания](https://github.com/devmanorg/product-flow/blob/main/framework/product/template.yaml)

## Шаблоны заданий

Часто встречающиеся задания в проектах по разработке сайтов и чат-ботов. Эти шаблоны прошли проверку и рекомендованы к использованию:

- [Графическая схема SQL БД](/products/dvmn_org/sql-db-graphical-scheme/assignment.yaml)
- [Модели данных Django](/products/dvmn_org/django_orm_models/assignment.yaml)
- [Деплой в dev-окружение](/products/dvmn_org/dev-deploy/assignment.yaml)
- [Проектирование чего угодно](/framework/product/assignment.yaml)
- [Документирование пользовательской истории](/framework/agile-user-story/assignment.yaml)

## Задания из старых проектов

Примеры заданий, уже встречавшихся ранее на прежних проектах. Используйте их для вдохновения и заимствования хороших идей, но
делайте это на свой страх и риск. Качество может сильно скакать от задания к заданию.

### Сайт менторов

- 🔒 [Сайт для менторов](https://github.com/devmanorg/mentors/blob/main/product_docs/assignment.yaml)
- [Графическая схема БД](https://gist.github.com/savilard/c1bf33d7b5116b7b74ede01ce535493c)
- [Импорт данных из gist-документов](https://gist.github.com/multipassport/06df9f08a78c463086045b80dcaf0ede)
- [Схема API endpoints](https://gist.github.com/mukhametdinovigor/320cc8f221d054b44bf3e9cbe27e1169)
- [Деплой в dev-окружение](https://gist.github.com/multipassport/9755fe9f2c5c3470b89a0f0f5a184e4e)
- [Прототип системы аутентификации и авторизации](https://gist.github.com/mukhametdinovigor/b86aaadd2c358b8410f6483d230a0400)

### Сайт Девмана

- [Перевести уведомления GA о поступлении платежа с фронтенда на server-to-server](https://gist.github.com/pelid/eb532bebec35a3164f149480beee340d)
- [Трекинг в Google Analytics пробной недели](https://gist.github.com/Fiskless/64faae4d3ce1d6b29f166bd3c0e05a89)

### Энциклопедия Девмана

- [Код отслеживания просмотров и кликов по баннеру](https://gist.github.com/pelid/feea98cff321713b0c15dd05f00cf1f1)

### Чат-бот для доставки воды

- [Задание на чат-бот](https://gist.github.com/pelid/1e359675def9e816f2f0a468a537fb25)
- Система подтверждения пользовательского ввода (задание в разработке)
- [Схема состояний бота на Node-RED](https://gist.github.com/pelid/55cef07f7aef4de7e250afcf7194a2e9)

### Бот «МФВЦ» для автоматической записи на сайте

Технологии: Django, Selenium, asyncio, aiogram, Telethon, Docker, Kubernetes

- [Задание на бота](https://gitlab.levelupdev.ru/traineeship/mfvc-bot/-/blob/master/assignment.yaml)

### Марафон-бот

Технологии: Django, DRF, asyncio, aiogram, Docker, Kubernetes

- [Задание на чат-бота](https://gitlab.levelupdev.ru/traineeship/marathon-bot/-/blob/master/assignment.yaml)

## Читать далее

- [Задание на каталог](./assignment.yaml)
- [Описание фреймворка](/framework/README.md)
