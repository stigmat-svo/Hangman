# Hangman
Интерпритация лингвистической игры "Виселица"

Игроку загадывается слово, визуально дается количество букв загаданного слова. А также нарисованная виселица.
Каждая угаданная буква открывается в визуальном представлении слова, каждая неугаданная попадает в список ошибочных попыток.
Количество таких попыток ограничено. При каждом ошибочном выборе буквы, на графически отображенной виселице, появляется
часть тела человечка. Количество частей тела равно количеству попыток. Если, до момента окончания попыток слово не угадано,
игра считается проигранной.

Автор приложения: Виталий Шелудько.

Игра написана на языке программирования Ruby.
Протестирована на версиях 2.5.5, 2.7.0 и 2.7.1.

Для работы игры у вас должен быть установлен bundler, установщик гемов. Для
его установки, в терминале выполните команду

```gem install bundler```

В игре используется гем "colorize", поэтому перед запуском игры, в терминале, перейдите
в корневую папку игры, и выполните команду

```bundle install```

Для запуска игры, в терминале перейдите в папку с файлом игры ```main.rb```. И выполните команду

```ruby main.rb```

Для добавления своих слов, отредактируйте файл ```word.txt``` в папке ```data```, внутри папки игры.

Пример запуска игры:

<a href="https://asciinema.org/a/JU7QnrcGj7GTYEtdSIYnzMz4C" target="_blank"><img src="https://asciinema.org/a/JU7QnrcGj7GTYEtdSIYnzMz4C.svg" /></a>

Почитать об игре "Виселица" можно на Википедии:

https://ru.wikipedia.org/wiki/Виселица_(игра)
