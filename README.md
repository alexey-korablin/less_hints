# less_hints
1. Скачать less, например отсюда http://lesscss.org/
2. Подключить файл со стилями: <link rel="stylesheet/less" href="less/styleless.less" type="text/css">
3. Подключить скрипт less: <script type="text/javascript" src="lib/less/less.min.js"></script>
4. Для chrome щелкнуть пкм по ярлыку, вкладка "Общие">"Объекты". В строке "объекты" через пробел дописать -allow-file-access-from-files
5. Перезапустить chrome
6. Опционально можно включить режим watch. Для этого нужно добавить в адресной строке #!watch и перезагрузить страницу.

ПЛАГИНЫ:
Color Highlighter - сканирует css, less, stilys, sass и подсвечивает цвета. Например белый цвет: #fff
Настройка плагина: 
1) Preferences → Package Settings → Color Highlighter → Settings – User 
2) в открывшемся окне пишем 
{
"ha_style": "filled"
}
Всего есть несолько вариантов: 
filled (заливка),
outlined (обводка),
none,
underlined (подчёркивание),
colored text (цвет текста).

*****

LESS - подсветка интаксиса LESS
Установка:
ctrl+shift+P -> Install Package -> LESS
Работает без перезапуска