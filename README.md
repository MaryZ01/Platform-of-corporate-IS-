# Platform-of-corporate-IS

Варіант 4.

Визначити інтерфейс IReadable з методом Read() та клас для представлення валюти Currency, який містить поля CurrencyName та Amount. Цей клас повинен наслідувати інтерфейс IReadable і реалізувати метод Read() для зчитування з файлу певних сум. У текстовому файлі задані дані у вигляді: 123 грн, 34 $, 23 Є, 459 грн і т.д. Зчитати дані з файлу у колекцію List з допомогою методу Read().
З колекції List вибрати лише гривневі суми і видрукувати результат на консоль, використавши метод ToString(). Для цього в класі Currency перевизначити метод ToString для форматного виведення.
Сформувати контейнер пар: назва валюти-загальна сума і вивести результат у файл
Здійснити конвертацію всіх сум у вказану з консолі валюту, результат записати в контейнер і вивести у файл.
Перехоплення винятків. При зчитуванні даних передбачити виняткові ситуації через неправильні вхідні дані та їх перехоплення у відповідних місцях
Використання Linq
Весь код повинен бути покритий юніт тестами
