# Frontend часть тестового задания

Простой фронтенд, основанный на CRA. Как и в бэк части, тут нет части кода. 

Тут идет взаимодействие с бэком. URQL в качестве клиента. Должно работать отображение заказов, с открытием корректной страницы списка при перезагрузке (через параметры или роутер, не важно), а так же просмотр конкретного заказа.

Yarn, CRA, MobX, Stylus, CSS Modules. 

P.S. Типы стилей генерируются при сборке автоматически из styl файлов

## Привет другой разработчик, которому досталось проверять мой код
В общем смотри, дизайн страниц хромает ибо у меня было не особо много свободного времени, чтобы придумать что-то хорошее, однако оно и не сильно вырвиглазное. С товарами там такой трабл, что в RetailCRM возвращает мне лишь названия этих товаров и внутренний ID, а также при клике в общем списке заказов не по всем заказам отображается детальная информация, ибо у RetailCRM какие-то траблы с эндпоинтом GET /orders/:id, он не знает часть заказов, которые знает GET /orders/. Как пофиксить это я знаю, просто получать сразу все заказы на бекенде и отдавать лишь нужный, но это ведь звучит не очень на фоне присутствия отдельного эндпоинта для этого и я так и не определился как лучше сделать `¯\_(ツ)_/¯`. А так задание в принципе сделано.
