# Сборка gulp 
## Состав
    pug, stylus, server, watcher и др.
## Описание начала работы
Для начала работы с этой сборкой необходимо убедится, что у вас установлен ```npm```. 
Для этого в консоли в корне сборки пишем команду ```npm -v```
Если получили ответ вроде этого ```6.2.0``` можно сразу вводить команду ```npm i``` 
после чего произойдёт установка node_modules необходимых для работы данной сборки.
Всё готово, можно начинать работать! Вводим команду ```gulp```. Теперь у нас есть препроцессор HTML Pug,
препроцессор CSS Stylus, мы можем задавать спрайты и всё сразу видеть на экране браузера (localhost:3000)


## Всё просто!

1. ```git clone``` Клонируем репозиторий с github https://github.com/kolelan/gulp4start.git
2. ```npm i``` для запуска процесса инсталяции модулей 
3. ```gulp``` для запуска в режиме разработки, ```gulp build``` для запуска в режиме сборки

## Не получилось запустить gulp build?
Для запуска в режиме сборки (```gulp build ```) Нужено в файле ```/gulp/task/img.js``` в строке с надписью
```.pipe($.gp.tinypng(YOUR_API_KEY))``` ввести API ключь от tinypng.com. или закомментировать эту строку