Запустить сервер:
1) Скачать файлы с репозитория (git clone https://github.com/daftgrey/skillfactory-D7.git);
2) Установить Виртуальное окружение, в котором необходимо установить нужные зависимости - в файле requirements.txt (pip install -r requirements.txt);
3) Запустить сервер командой python manage.py runserver .

Рабочие ссылки:
1. http://127.0.0.1:8000/ - Авторизация через Github
2. http://127.0.0.1:8000/admin/ - Админка (login: admin; pass: 123).
3. http://127.0.0.1:8000/friends/ - Список друзей.
4. http://127.0.0.1:8000/publishers/ - Список издательств.
5. http://127.0.0.1:8000/friend/create/ - Форма для добавления друзей.
6. http://127.0.0.1:8000/borrowed_books/ - Список одолженных книг, отсортированных по должникам.


Upd:
1) Добавлена авторизация через Github
