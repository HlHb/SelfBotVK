# SelfBOT VK-API
###### v1
____
Данный репозиторий поможет создать Self бота в ВК для личной страницы пользователя 
в учебных целях


## Функционал

Реализуемые функции:
 - Исключен сбой программы при возникновении ошибки и перезапуске серверов ВК
 - Функция отправки сообщения
   - Возможность приложить файл
   - Отправка клавиатуры (пользователи не могут их оправлять, только группы, боты)
   - Отправка ответов
 - Функция редактирования сообщения
 - Функция создания ссылки с именем для ВК
 - Пару команд с описанием их работы для примера и обучения

____
## Как запустить проект:

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source env/bin/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```