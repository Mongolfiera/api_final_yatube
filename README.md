# API для Yatube
## API для социальной сети Yatube. 
Позволяет получать, изменять и удалаять публикации, комментарии, подписываться на других авторов.
Создание и мзменение собственного контента доступно только авторизованным пользователям.   

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Mongolfiera/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
### Примеры запросов:

Получить список постов - 
```
api/v1/posts
```
Получить инормацию о группе - 
```
api/v1/groups/2/
```