# Про пользовательские истории

Способ описания требований к разрабатываемой системе. Хорошо подходит для пользовательских и функциональных требований. Формулируется в виде текста на повседневном или деловом языке пользователя.

Не путать с UX User Story! То [другой продукт](/products/dvmn_org/ux-user-story/).

Не путать со сценариями использования! То другой продукт. [Сравнение](./comparison_with_use_case.md).

Пользовательские истории — быстрый способ документировать требования клиента, без необходимости разрабатывать обширные формализованные документы и впоследствии тратить ресурсы на их поддержание.

История помещается буквально в одно предложение, что позволяет легко встроить их в текст любого задания на разработку. Не приходится составлять лишних документов, что удобно.

Рекомендованный шаблон:

```
{Роль действуюшего лица}| {Что случилось?} → Хочу … → {Почему поверю, что сделано}
```

Действующее лицо может быть строго одно -- он заказчик и его "хотелка" руководит всем процессом.

Шаблон выше отличается от общепринятого. Добавлены ещё два раздела с триггерами: какое событие привело к появлению желания и какое событие выступило акцептором действия. Триггеры важны, чтобы убедиться, что действующее лицо достигнет желаемого.

> Я, как водитель, в момент включения лампочки низкого уровня топлива, хочу заправить свою машину на ближайшей заправке.
Действующее лицо может быть строго одно -- он заказчик и его "хотелка" руководит всем процессом.

Минусы пользовательской истории вытекают из её главного плюса — лаконичности. Доведённая до крайности краткость формулировки оставляет широчайший простор для интерпретаций и разного рода ошибок. Требуется глубокое погружение в контест, чтобы суметь воспользоваться историей правильно.

По этой причине пользовательские истории могут быть важной составной частью задания на продукт, но не могут быть самодостаточными. С ними нельзя работать отдельно от остальной документации на продукт.

Пользовательские истории специально адаптированы для встраивания внутрь другой документации в виде списка требований. Такой список легко дополнять, чистить и поддерживать в актуальном состоянии.

*Одна история -- одна строка текста.*

При этом пользовательские истории могут быть разного масштаба. Например, желание действующего лица "пообедать пиццей" при взаимодействии с сайтом рассыпается на несколько более мелких желаний:

- Хочу заказать пиццу на сайте
    - Хочу выбрать вкусную пиццу
    - Хочу узнать срок доставки
    - Хочу оформить заказ
    - …

Пользовательские истории создаются вокруг "связки роль + желание + триггеры", что позволяет так же их объединять в иерархию:

- Клиент | Почувствовал голод → Хочу заказать пиццу на сайте → Сайт сообщил, что заказ доставят через 15 мин.
    - Клиент | Вижу на сайте ассортимент → Хочу выбрать вкусную пиццу → Нашёл знакомое название и список ингредиентов
    - Клиент | Чувство голода напомнило о себе → Хочу узнать срок доставки → Увидел на сайте баннер "доставим за 15 минут"
    - Клиент | Чувство голода напомнило о себе → Хочу оформить заказ → Сайт сообщил, что заказ принят
    - …

При этом список пользовательских историй не является линейным сценарием. В примере выше клиент может начать не с первого пункта, а сразу со второго, затем вернуться к началу либо вообще пропустить шаг, сразу выбрав предложение по акции.

Пользовательская история — это то что связывает фичи продукта в единое целое. При этом истории нарочно обходят стороной детали реализации, чтобы оставить эту задачу за описанием фич.

Когда сеансы использования подходят идеально:

- Документация взаимодействия с сайтом
- Документация взаимодействия с чат-ботом
- Документация взаимодействия с организацией

Для чего пользовательские истории использовать не стоит:

- Нефункциональные требования
    - архитектурные ограничения
    - соглашения по оформлению кода
    - прочие орг.моменты

## Читать далее

- [Сравнение пользовательских историй со сценариями использования](./comparison_with_use_case.md)
- [Про пользовательские истории](https://ru.wikipedia.org/wiki/%D0%9F%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%D1%81%D0%BA%D0%B8%D0%B5_%D0%B8%D1%81%D1%82%D0%BE%D1%80%D0%B8%D0%B8), статья на Википедии
