# Product Flow

Product Flow — это методика, фреймворк и набор инструментов для управления разработкой продуктов. Заменяет собой техническое задание, user story mapping, приёмочные тесты и таск-трекер. Product Flow собирает все эти компоненты в единую интегрированную систему.

**Внимание!** Это ранняя предрелизная версия Product Flow. Многие элементы системы ещё плохо проработаны, изменения вносятся веерным способом и без каких либо предупреждений.

После релиза первой версии 1.0 скорость изменений заметно спадёт, и все правки можно будет отслеживать по [CHANGELOG](./CHANGELOG.md).


## Оглавление

- [Кому и чем полезен Product Flow](#motivation)
- [Ключевые концепции](#key-conceptions)
- [Инструменты Product Flow](#product-flow-tools)


<a name="motivation"></a>
### Кому и чем полезен Product Flow

С помощью Product Flow вы сможете быстро планировать разработку продуктов. Подходит для самостоятельного использования или внутри команды, с внутренним или внешним заказчиком.

Product Flow позволяет быстро документировать требования клиента, без необходимости разрабатывать обширные формализованные документы и впоследствии тратить ресурсы на их поддержание в актуальном состоянии.

Product Flow решает проблему потери мотивации в процессе делегирования задачи от заказчика к исполнителю.

TODO


<a name="key-conceptions"></a>
### Ключевые концепции

TODO:

- Про измеримость/фальсифицируемость результата
- Про мотивацию исполнителя
- Про потерях в мотивации на каждом следующем уровне делегирования
- Про ситуацию коллективной безответственности
- Про делегирование
- Про приёмку работы
- Про главный продуктовый риск -- результат работы не востребован
- Про иллюзию альтернативы
- Выгрузка контекста из головы мейнтейнера
- Рабочий процесс рассматривается как изготовление множества продуктов
- Децентрализация изготовления продуктов -- теперь все члены команды становятся продакт-менеджерами
- Про петли обратной связи на ранних этапах проектирования
- Обеспечить качество мышления и орг.процессов через инструменты VS личные скиллы
- Про поток создания ценности (Toyota)
- Про выгорание
- Нет образа результата, есть только критерии готовности
- Волшебное сочетание возможности и необходимости == результат

Методика Product Flow предлагает рассматривать работу команды в виде последовательности изготовления продуктов и инструментов, где каждый следующий строится с использованием предыдущих. Например, разработка веб-сайта может выглядеть так:

```
1. Нарисовать макеты → Макеты ключевых страниц
2. Изготовить вёрстку → Вёрстка
3. Сделать заготовку бэкенда → ПО сайта
4. Написать деплойные скрипты → Инструменты деплоя на сервер
5. Выкатить сайт на сервер → Разработческая версия сайта
- …
```

TODO

<a name="product-flow-tools"></a>
### Инструменты Product Flow

Product Flow включает в себя несколько подсистем:

- [Задания — Product Flow Assignment](assignment)
- [Задачи — Product Flow Tasks](tasks)
- [Каталог заданий и задач](catalog)
