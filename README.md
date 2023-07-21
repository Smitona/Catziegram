# Kittygram
Площадка, чтобы поделиться фото ваших или соседских котиков :3


*Сайт доступен по ссылке [catziegram.mooo.com](https://catziegram.mooo.com)*


### Зарегстрировавшись, вы получаете возможность поделить фото пушистого питомца и рассказать о его достижениях или проказах:
* В одну публикацию можно добавить только одно фото кота.
* Есть строка для указания года рождения котика.
* Также палитра для указания расцветки.
* Вы можете выбрать достижение котика из списка или добавить своё.


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:Smitona/infra_sprint1.git
```
```
cd infra_sprint1/
```

Создать и активировать вирутальное окружение версией python:
```
python3 -m venv venv
```

```
source venv/Scripts/activate   #for Windows
source venc/bin/activate       #for Linux
```

Установить необходимы зависимости из файла requirements.txt:
```
pip install -r requirements.txt
```

Выполнить миграции:
```
python manage.py migrate
```

_____________________________________________________________________________________________________________________________________________

Проект работает на основе Django REST Framework. Он установлен на WSGI-сервере и имеет SSL-сертификаты. Вы можете не волноватсья за безопасность своих данных.
