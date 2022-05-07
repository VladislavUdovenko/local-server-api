# local-server-api
По пути "local-server-api/TodoApi/Controllers/TodoItemsController.cs" изменить путь до папки с фото.

Демо версия API документации
Работа с сервером:
1) *url*/start: отправляет список названий мебели
2) *url*/catalog: при входе в каталог отправляет запрос на фото всех моделей раздела (пол, стена, потолок)
3) *url*/catalog/*name*: отправляет фото префаба по имени, если не указать имя отправит фото всех объектов
4) *url*/asset/*name*: при выборе нужной модели отправляет архив с моделькой и текстурой, имя ассета указывается обязательно 
     // 4) еще не готово

Приложение:
1) При запуске приложения автоматически отправляется старт на сервер
2) При выборе нужной модельки отправляется запрос на ассет
3) При входе в меню отправляются запросы на фото нужных моделек или всех, если нет конкретного списка
Все запросы выполняются методом POST
