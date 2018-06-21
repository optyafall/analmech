# analmech
Лекции по Аналитической механике М.А. Муницыной в МФТИ за 2017-2018 год

### Содержание

#### Осенний семестр
Все, кроме нескольких рисунков

#### Весенний семестр
- [x] Лекция 1
- [x] Лекция 2
- [x] Лекция 3
- [x] Лекция 4
- [x] Лекция 5
- [x] Лекция 6
- [x] Лекция 7
- [ ] Лекция 8
- [x] Лекция 9
- [x] Лекция 10
- [x] Лекция 11
- [x] Лекция 12

### Ошибки
Об ошиках пишите в issues или в вк: https://vk.com/valentiay

### Если вы вдруг решили сделать пулл-реквест
#### Команды
*До середины осеннего семестра для этих целей могли использоваться другие команды.*

* `\v` - Черта над аргументом. Обозначение для векторов и подобных им вещей.

* `\dv` - Точка с чертой над аргументом. Обозначение для производной вектора.

* `\norm` - Двойные вертикальные черты по бокам от аргумента. Обозначение нормы.

* `\abs` - Одинарные вертикальные черты по бокам от аргумена. Обозначение модуля.

* `\R` - "Красивое" R. Обозначение действительных чисел.

* `\pd` - Дробь, перед числителем (1 аргумент) и знаменателем (2 аргумент) которой стоит знак `\partial`. Частная 
производная.

* `\pdd` - Дробь перед 1 аргументом, в числителе которой стоит знак `\partial`, а в знаменателе `\partial` и 
2 аргумент. Большая частная производная.

* `\lline` - Граница между лекциями.

Другие определенные мной команды "не канон", почти не используются и оставлены для обратной совместимости.

#### Выравнивание формул

Формулы в определениях, теоремах и замечаниях выравниваются по центру с помощью `\[``\]`. 
Формулы в выводах выравниваются по левой стороне с помощью окружения `flalign*`, 
где каждая строка стоит между символами `&` и `&\\`.

#### Изображения

Изображения складываются в папку `/img` вместе с исходниками о подключаются так:
```
\begin{figure}[H]
\centering
\includegraphics[height=4cm]{image.png}
\end{figure}
```
