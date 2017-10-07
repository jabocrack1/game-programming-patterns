# Шаблоны снижения связности \(Decoupling Patterns\)

Как только вы начинаете разбираться в языке программирования, написание кода, который вам нужен становится достаточно простым. Гораздо сложнее писать код, который будет легко _изменять_ в будущем. Очень редко бывает так что мы можем предполагать что произойдет в будущем, когда запускаем наш редактор.

У нас есть мощный инструмент, упрощения изменений - _снижение связности (decoupling)_. Когда мы говорим два участка кода "слабо связаны (decoupled)", мы имеем в виду что изменение одного обычно не требует изменения другого. Когда вам нужно добавить новый функционал в игре, чем меньше частей кода вам придется затронуть - тем лучше.

Шаблон [Компонент(Component)](shabloni-snizheniya-svyaznosti-decoupling-patterns/komponent-component.md) снижает связность различных областей вашей игры друг от друга с помощью единой сущности, обладающей всеми их аспектами. [Очередь событий (Event Queue)](shabloni-snizheniya-svyaznosti-decoupling-patterns/ochered-sobitii-event-queue.md) снижает связность двух общающихся друг с другом объектов, как статически так и _во время работы (in time)_. Шаблон [Поиск службы (Service Locator)](shabloni-snizheniya-svyaznosti-decoupling-patterns/poisk-sluzhbi-service-locator.md) позволяет коду обращаться к объекту, не привязываясь к коду, который его предоставляет.

Шаблоны

- [Компонент(Component)](shabloni-snizheniya-svyaznosti-decoupling-patterns/komponent-component.md)

- [Очередь событий (Event Queue)](shabloni-snizheniya-svyaznosti-decoupling-patterns/ochered-sobitii-event-queue.md)

- [Поиск службы (Service Locator)](shabloni-snizheniya-svyaznosti-decoupling-patterns/poisk-sluzhbi-service-locator.md)