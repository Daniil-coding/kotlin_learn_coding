# Описание
_lambda_ - безымянная фцнкция<br>
```{``` <сисок параметров> ```->``` <возвращаемый результат в виде выражения> ```}```<br>
```{ x: Int, y: Double -> y / x.toDouble() }```<br>
Присвоить одной _lambda_ функции другую можно только в том случае, если их формальные параметры совпадают.
# Использование
```Kotlin
val f = {x: Double -> x * x - 2 * x + 10}
var sum = { x: Int, y: Int -> x + y}
var selected_func = {x: Double -> x * x * x}
selected_func = f
```
