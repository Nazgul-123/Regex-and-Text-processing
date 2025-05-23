# Text Processing and Regular Expressions Tool
Регулярные выражения и обработка текста
Этот репозиторий содержит примеры и инструменты для работы с регулярными выражениями и для обработки текста на Python.

## Основные функции
* Замена римских цифр на арабские
* Обработка дат в тексте
* Создание частотного словаря слов
* Токенизация и нормализация текста
* Удаление стоп-слов
* Стемминг и лемматизация
* Вычисление TF-IDF
* Автоматическое реферирование текста

## Используемые библиотеки
re - для работы с регулярными выражениями, 
nltk - для обработки естественного языка, 
pymorphy2 - для морфологического анализа,
scikit-learn - для вычисления TF-IDF,
pandas - для работы с данными.

## Примеры использования
* Замена римских цифр
```
text = "В XIV веке произошло MCCCXLV важных событий"
result = convert_roman_numbers(text)
```

* Создание частотного словаря
```
tokens = preprocess_text(text)
freq_dict = Counter(tokens)
```

* Вычисление TF-IDF
```
tfidf = calculate_tfidf(documents)
```

* Автореферирование  
```
summary = summarize(text, compression_ratio=0.3)
```

## Структура проекта
* Замена римских цифр
* Обработка дат
* Предобработка текста
* Создание частотного словаря
* Автореферирование
 
## Запуск
1. Установите зависимости.
2. Запустите нужный скрипт.
