# Практика Kotlin fundamentals. День 1

## Практика 2

№1 добавьте две неизменяемые локальные переменные в которых укажите ваши имя и фамилию
выведете их на экран с использованием string interpolation ($)
`fun valName() {}`

№2 создайте изменяемые переменные с именем и фамилией.
Переприсвойте значение переменной имени на первый символ имени + символ точки
пример Иван Иванов -> И. Иванов
выведете их на экран с использованием string interpolation ($)
`fun varShortName() {}`

№3 пропишите логику функции, которая переводит сантиметры в дюймы
1cm = 2.54 inch

``` kotlin
fun cmToInch(cm: Int): Double {
    val inch = 0.0

    return inch
}
```

№4 пропишите логику функции которая складывает 2 числа и возвращает ответ типа Float
для сложения воспользуйтесь функцией plus, а не оператором

```kotlin
fun addTwoDigit(a: Number, b:Number):Float {
    val ans = 0f

    return ans
}
```

№5 сравнить числа передаваемые в параметрах функции

```kotlin
fun numbersComparing(a:Float, b:Double) {
    println()
}
```

№6 определить входит ли переданный символ в список гласных

```kotlin
fun isVowel(c:Char): Boolean {
    val vowels = listOf('a', 'e', 'i', 'o', 'u')

    return false
}
```
