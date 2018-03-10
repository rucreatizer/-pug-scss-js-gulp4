h1 Сборка gulp на стеке pug+scss+js
=====================

h2 Установка: выполнить npm i
-----------------------------------
h2 Таски:
-----------------------------------

h2 Структура директорий:
-----------------------------------
build
- fonts
- images
- scripts
-- index.js
- styles
-- style.css

src
- fonts
- images
- pug
-- ...
- scripts
-- ...
- styles
-- ...



- **clean:** очистка папки build (куда всё сваливается)
- **styles:** автопрефиксер, scss, sourcemap
- **stylesReady:** автопрефиксер, scss, минификация
- **pug:** сборка html из pug (pretty=true)
- **pug:** сборка html из pug, минификация
- **images:** копирование и уменьшение картинок
- **fonts:** копирование шрифтов
- **scripts:** babel, sourcemap js, объединение
- **scriptsready** babel, минификация js, объединение 
- **server:** запуск browsersync
- **watch:** слежение за изменениями всего
- **default:** styles+images+pug+fonts+scripts+server+watch
- **ready:** stylesReady+images+pugReady+fonts+scriptsReady (сборка на продакшн)

