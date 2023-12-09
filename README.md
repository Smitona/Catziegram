# Catziegram
Площадка, чтобы поделиться фото ваших или соседских котиков 😾

### Зарегстрировавшись, вы получаете возможность поделить фото пушистого питомца и рассказать о его достижениях или проказах:
* В одну публикацию можно добавить только одно фото кота.
* Есть строка для указания года рождения котика.
* Также палитра для указания расцветки.
* Вы можете выбрать достижение котика из списка или добавить своё.


### Как запустить проект:

1. Клонировать репозиторий и перейти в него в командной строке
```
git clone git@github.com:Smitona/Catziegram.git
cd Catziegram/backend/
```

2. Создать и активировать вирутальное окружение
```
python3 -m venv venv

source venv/Scripts/activate   # for Windows
source venv/bin/activate       # for Linux
```

3. Установить необходимы зависимости из файла requirements.txt:
```
cd ..
pip install -r requirements.txt
```

4. Выполнить миграции:
```
cd backend/
python manage.py migrate
```

---

Стек Django, Python, SQLite, Gunicorn, WGSI.
