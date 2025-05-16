# JokesApp (Варіант 3)

**Проєкт виконано мовою Kotlin у середовищі Android Studio.**

## Функціонал:
- Виведення списку категорій жартів
- Перехід на окремий екран з жартом по обраній категорії
- (Опціонально) Підключення до API для отримання жартів онлайн
- Офлайн-режим із вбудованими жартами, якщо API не використовується

## Список категорій:
- Favourite Jokes
- Family, Blonde, Animal, Clean, Yo_Mama, Relationship, Office
- Insult, Holiday, Food, Dark, Jokes, Doctor, Engineer

---

## Як додати API-ключ (RapidAPI, для викладача):

1. Зайти на [https://rapidapi.com/sohailFiza/api/jokes-always](https://rapidapi.com/sohailFiza/api/jokes-always)
2. Натиснути "Subscribe to test" (за потреби зареєструватись)
3. Скопіювати значення `X-RapidAPI-Key`
4. У файлі `JokeActivity.kt` знайти рядок:
   ```kotlin
   private val apiKey = "YOUR_RAPIDAPI_KEY"
   ```
   і замінити на:
   ```kotlin
   private val apiKey = "ваш_ключ"
   ```

---

## Як запустити додаток:

1. Відкрити проєкт у Android Studio (`File > Open`)
2. Дочекатись завершення Gradle Sync
3. Натиснути кнопку **Run** (зелена стрілка)

---

## Як запустити тести:
> У цьому проєкті автоматичних unit-тестів не передбачено.  
> Протестувати можна вручну: запуск → вибір категорії → перевірка виводу жарту.

---

Автор:Чичерська Марія
Заліковий проєкт, Варіант 3  

