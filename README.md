**Клонируй проект**
git clone https://github.com/hush0k/orderUser.git
cd orderUser
**Запусти Docker Desktop**
**Запусти проект**
docker-compose up --build
При первом запуске Docker скачает нужные образы, создаст контейнеры и применит миграции.
Жди сообщение: Watching for file changes with StatReloader
**API Endpoints
User (Пользователи)**

Создать пользователя: POST http://localhost:8000/api/user/create/
Список всех пользователей: GET http://localhost:8000/api/user/
Посмотреть пользователя по ID: GET http://localhost:8000/api/user/<id>/
Изменить пользователя по ID: PUT/PATCH http://localhost:8000/api/user/update/<id>/
Удалить пользователя по ID: DELETE http://localhost:8000/api/user/delete/<id>/

**Order (Заказы)**

Создать заказ: POST http://localhost:8000/api/order/create/
Список всех заказов: GET http://localhost:8000/api/order/
Посмотреть заказ по ID: GET http://localhost:8000/api/order/<id>/
Изменить заказ по ID: PUT/PATCH http://localhost:8000/api/order/<id>/update/
Удалить заказ по ID: DELETE http://localhost:8000/api/order/<id>/delete/

**Остановка проекта**
docker-compose down

