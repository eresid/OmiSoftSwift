# OmiSoftSwift
В даному репозиторії ми будемо вивчати мову програмування Swift

## Базовий синтаксис

Ми швиденько пробіжимося по синтаксу мови Swift після чого повністю
поглибимось у практику.

### Коментарі
 
```swift
// Так позначається у Swift однорядковий коментар

/*
  А ось так позначається багаторядковий коментар.
  Такий же синтаксис мають мови: C, C++, D, Java,
  Kotlin, JavaScriptта багато інших
*/
```

### Привіт світ

Першою програмою на будь якій мові традиційно є "Привіт світ", де
потрібно в консоль вивести звичайний рядок.

У Swift не потрібно огортати інструкції у класи, на відміну від Java,
тому файлик з цим єдиним рядком компілюватиметься і без проблем працюватиме

```swift
// Інструкція print допомагає нам виводити текст у термінал
print("Привіт світ")
```

Щоб виконати дану програму, скопіюйте цей рядок у пустий файл, наприклад
*hello.swift*, збережіть його і потім запустіть у терміналі наступною
командою:

```bash
# swift hello.swift
```

Вітаємо! Ви реалізували першу програму.

### UTF-8

Swift, як і будь-яка сучасна мова, підтримує кодування UTF-8, а це
значить, що ми можемо без проблем працювати з кирилицею. Такою
можливістю не можуть похвалитися мови C та C++, але у D, Java, Kotlin
та JavaScript з цим проблем також не буде.

### Умовні оператори

Для програміста найважливіше - це логіка. По суті, будь-яка програма -
це набір інструкцій, описаних певною логікою. Для цього існують умовні
оператори. Наведемо простий приклад:

```swift
// Оголошуємо змінну *a* та присвоюємо їй значення 5
let a = 5

if (a == 5) {
    print("Умова виконується")
} else if (a > 10) {
    print("Інша умова виконується")
} else {
    print("Нічого не виконується!")
}
```
