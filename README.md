# Yatube API
Yatube API - это программный интерфейс для работы с социальной платформой Yatube. Через него реализованы функции публикации постов, комментирования и управления подписками на авторов контента."
# Запуск проекта
1. Клонирование репозитория
```
git clone {SSH key}
```
2. Создание и активирование виртуального окружения
```
cd api_final_yatube/
python -m venv venv
source venv\Scripts\activate
```
3. Устновка и миграция
```
pip install -r requirements.txt
python manage.py migrate
```
4. Заппуск сервера
```
python manage.py runserver
```