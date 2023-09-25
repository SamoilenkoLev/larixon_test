# Тестовое задание

Необходимо написать небольшое приложение на django и django_rest_framework


Модели:

Category - категории объявлений, поля: name<br />
City - город объявления, поля: name<br />
Advert - объявление, поля: created (дата создания), title, description, city, category, views


Вью:

/api/advert-list/ - json список объявлений со всеми полями + название города + название категории
/api/advert/<advert-pk>/ - json detail view одного объявления со всеми полями, просмотр данного вью увеличивает счётчик просмотров в объявлении


Завернуть проект в докер (в конфигурации для локальной разработки). БД - любая. Добавление данных через админку. 


Стоит уделить внимание производительности вашего решения. Кэширование использовать не нужно, достаточно оптимизации работы с базой данных.


