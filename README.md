Задания для выполнения


  Используя apt-get установить Apache2 на виртуальную машину
  С браузера хост-машины по IP-адресу виртуальной машины увидеть приветствие
  В настройках сервера изменить  порт на :8080
  Снова выполнить п 2, но с указанием порта
  Изменить порт обратно и проверить как работает заглушка
  Запустить сервер Apache на портах 80 и 8080 одновременно и проверить работу
  В hosts хост-машины создать три домена: a1.com, b2.com, c3.com и связываем с IP виртуальной машины с Apache
  Для каждого домена проверить всё ли правильно, с помощью ping
  Зайти на все три домена, написав их вместо IP виртуальной машины
  Создать директории /var/www/a1.com, /var/www/b2.com, /var/www/c3.com
  В каждой из них создать пустой index.html
  В каждом из них написать различное содержимое
  Сделать так, чтобы из браузеров хост-машины открывались сайты из директории, а не общая заглушка
  Запустить на выполнение скрипт, проверить отображение его в браузере:
