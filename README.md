# Backend

# не успел разобраться с докером

Инструкция по запуску:
  1)Установить open server panel.
  2)В каталог "domains" копировать нашу папку "Project".
  3)В настройках OSPanel -> Сервер поменять значение "Настройка использования переменной Path" на "Свой Path + userdata".
  4)Создать "path.txt" по пути "ospanel/userdata/config/" и внутри прописать путь до NodeJS.
  5)В настройках OSPanel -> Домены добавить домен приложения.
  6)Запустить сервер.
  7)В консоли перейти в папку проекта и прописать "php artisan migrate --seed".
  8)В консоли прописать "php artisan serve".
  9)готово.
