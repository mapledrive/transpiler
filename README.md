## Инструкция по этапам разработки:
1. Переходим в корень диска c:  cd..  cd..
2. Клонируем проект: git clone https://github.com/mapledrive/transpiler.git
3. Переходим в папку transpiler :   cd transpiler
4. Устанавливаем все пакеты npm install
5. Запускаем транспилятор для файла script.js содержащего JSX: npm run react
6. В корневой папке автоматически появляется файл с реакт кодом на чистом js

Этот проект позволяет брать React код, написанный на JSX и транспилировать его в чистый яваскрипт код, который понимает любой браузер.
Исходный код нужно держать в script.js, а результат транспиляции будет в script-compiled.js
Проект был создан для того, чтобы можно было проанализировать во что превращается React-компонент.