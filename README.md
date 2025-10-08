### 🧩 Клонирование проекта

```powershell
git clone https://github.com/hush0k/orderUser.git
cd orderUser
```
### 🐳 Запуск проекта через Docker
**Запусти Docker Desktop**

**Выполни команду:**

```powershell
docker-compose up --build
```
**При первом запуске Docker:**

- скачает нужные образы
- создаст контейнеры
- применит миграции

**⏳ Жди сообщение:**
```bash
Watching for file changes with StatReloader
```

### 📡 API Endpoints
**👤 User (Пользователи)**
Действие	Метод	Эндпоинт
- Создать пользователя	POST	[http://localhost:8000/api/user/create/](http://localhost:8000/api/order/delete/)
- Список всех пользователей	GET	[http://localhost:8000/api/user/](http://localhost:8000/api/user/)
- Посмотреть пользователя по ID	GET	[http://localhost:8000/api/user/<id>/](http://localhost:8000/api/user/<id>/)
- Изменить пользователя по ID	PUT / PATCH	[http://localhost:8000/api/user/update/<id>/](http://localhost:8000/api/user/update/<id>/)
- Удалить пользователя по ID	DELETE	[http://localhost:8000/api/user/delete/<id>/](http://localhost:8000/api/user/delete/<id>/)

**📦 Order (Заказы)**
Действие	Метод	Эндпоинт
- Создать заказ	POST	[http://localhost:8000/api/order/create/](http://localhost:8000/api/order/create/)
- Список всех заказов	GET	[http://localhost:8000/api/order/](http://localhost:8000/api/order/)
- Посмотреть заказ по ID	GET	[http://localhost:8000/api/order/<id>/](http://localhost:8000/api/order/<id>/)
- Изменить заказ по ID	PUT / PATCH	[http://localhost:8000/api/order/<id>/update/](http://localhost:8000/api/order/<id>/update/)
- Удалить заказ по ID	DELETE	[http://localhost:8000/api/order/<id>/delete/](http://localhost:8000/api/order/<id>/delete/)

### 🛑 Остановка проекта
```bash
docker-compose down
```
