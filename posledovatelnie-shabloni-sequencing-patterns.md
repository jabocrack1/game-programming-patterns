# Последовательные шаблоны \(Sequencing Patterns\)

Видеоигры прекрасны по большей мере потому, что позволяют нам побывать где-то еще. На несколько минут (а если быть более честным гораздо на дольше) мы становимся обитателями виртуального мира. Создание такого мира - это самое прекрасное, что есть в игровом программировании.

Один из аспектов создания таких игровых миров - это _время_: искусственный мир живет и дышит в своем собственном ритме. Как строители миров мы должны самостоятельно изобретать время и шестеренки, управляющие работой часов игры.

В данном разделе собраны шаблоны, которые могут нам в этом помочь. [Игровой цикл(Game Loop)](posledovatelnie-shabloni-sequencing-patterns/igrovoi-tsikl-game-loop.md) - это центральная ось, на которую опирается игровое время. Объекты слышат его тиканье через [Методы обновления (Update Methods)](posledovatelnie-shabloni-sequencing-patterns/metodi-obnovleniya-update-methods.md). Мы можем спрятать последовательную сущность компьютера за фасадом снимков отдельных моментов времени с помощью [Двойной буферизации (Double Buffering)](posledovatelnie-shabloni-sequencing-patterns/dvoinaya-buferizatsiya-double-buffering.md) и в результате обновление игрового мира будет казаться плавным.

## Шаблоны

- [Двойная буферизация (Double Buffering)](posledovatelnie-shabloni-sequencing-patterns/dvoinaya-buferizatsiya-double-buffering.md)

- [Игровой цикл(Game Loop)](posledovatelnie-shabloni-sequencing-patterns/igrovoi-tsikl-game-loop.md)

- [Методы обновления (Update Methods)](posledovatelnie-shabloni-sequencing-patterns/metodi-obnovleniya-update-methods.md)