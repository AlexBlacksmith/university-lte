## Тестовое задание.

Backend project "Университет"
- Разработать на Laravel или Yii2
- Написать миграции
- Интегрировать с AdminLTE
- Удобный интерфейс
- Если успеете, подключить RBAC

**Главное задание:**

Разработать расписание уроков. Добавить возможность фильтрации, чтобы при выборе времени и кабинета, можно было увидеть кто преподает какой группе.

### Развертывание приложения:

- composer install
- npm install

Создаем файл .env по примеру .env.example (При использовании функции "сброс пароля", необходимо прописать настройки почты).

Создаем базу данных MySQL под названием university-lte

- php artisan storage:link
- php artisan migrate
- php artisan db:seed
- php artisan key:generate