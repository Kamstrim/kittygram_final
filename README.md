## Описание

Kittygram - это социальная сеть для обмена фотографиями любимых питомцев.

## Функционал

- Регистрация и авторизация;
- Добавление и редактирование Питомца;
- Просмотр записи других пользователей;

## Стек

[![Python](https://img.shields.io/badge/-Python-464641?style=flat-square&logo=Python)](https://www.python.org/)
[![Django](https://img.shields.io/badge/-Django-464646?style=flat-square&logo=Django)](https://www.djangoproject.com/)

## Как запустить проект:

1. Клонировать репозиторий:

   ```python
   git clone https://github.com/kamstrim/kittygram_final.git
   ```

2. Перейти в папку с проектом:

   ```python
   cd kittygram_final/
   ```

3. Установить виртуальное окружение для проекта:

   ```python
   python -m venv venv
   ```

4. Активировать виртуальное окружение для проекта:

   ```python
   # для OS Lunix и MacOS
   source venv/bin/activate

   # для OS Windows
   source venv/Scripts/activate
   ```

5. Установить зависимости:

   ```python
   cd backend
   python3 -m pip install --upgrade pip
   pip install -r requirements.txt
   ```

6. Выполнить миграции на уровне проекта:

   ```python
   python3 manage.py makemigrations
   python3 manage.py migrate
   ```

7. Запустить проект локально:

   ```python
   python3 manage.py runserver

   # адрес запущенного проекта
   http://127.0.0.1:8000
   ```
