# Код TG бота, который генерирует QR коды на ссылки
  
Это мой первый работающий код. Я учу Python и для практики собрал себе работающий инструмент - генератор QR-кодов в телеграм боте
  
### Как он работает?
Все очень просто - отправляешь сообщение с одной или несколькими ссылками — в ответ бот присылает QR-код на каждую их них

### .env
В директории, где хранится **BotFirstRun.py** нужно создать .env файл и сохранить в нем две переменные — токен из BotFather и путь сохранения QR-кодов

```python
TOKEN = ''
QR_PATH = ''
```


### Какие библиотеки используются

asyncio — что-то для асинхронного программирования (в этом пока не разобрался)<br/>
logging — чтобы логгировать ошибки и события<br/>
python-dotenv — чтобы хранить и считывать токен бота из .env<br/>
aiogram — библиотека для создания бота в tg<br/>
os — для управления файлами на ОС<br/>
qrcode — библиотека для работы с QR-кодами

> P.S.
Я  учился все писать по урокам с ютуба. Буду рад комментариям и отзывам