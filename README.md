# servergame
Игра шашки, полностью написанный на typescript прототип. Содержит в себе сервер HTTP для выдачи статики, и WebSocket для поддержания соединения с игроками.
## Правила игры
Игроки ходят по диагонали, белые ходят первыми. Игрок может съесть фигуру. Если фигура доходит до конца поля противника, то дошедшая фигура становится дамкой. Побеждает игрок, который съел все фигуры противника.
## Запуск игры
Устанавливаем зависимости:
```
npm i
```
Запускаем сборку:
```
npm run build
```
Запускаем сборку:

```
npm start
```
## Подключение игроков
В браузере открываем http://localhost:8000/
Игра запускается на двух игроков. Сервер последовательно соединяет двух подключившихся клиентов в игру.
