[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/+1fc0or8gCHsyNGFi)      [![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/boinker_bot/boinkapp?startapp=boink1076726282)

# 💩 АВТО ФАРМ ДЛЯ BOINKERS 💩

> [!WARNING]
> Я не несу ответственности за ваш аккаунт. Пожалуйста, учитывайте потенциальные риски перед использованием этого бота.

## Рекомендация перед использованием

# 🔥🔥 Используйте PYTHON версии 3.10 🔥🔥

> 🇪🇳 README in english available [here](README.md)

## Функционал  
|                   Функционал                   | Поддерживается |
|:----------------------------------------------:|:--------------:|
|                Многопоточность                 |       ✅        | 
|            Привязка прокси к сессии            |       ✅        | 
| Авто-регистрация аккаунта по вашей реф. ссылке |       ✅        |
|                   Авто-спины                   |       ✅        |
|             Авто активация бустера             |       ✅        |
|                   Авто таски                   |       ✅        |
|             Авто апгрейд Боинкера              |       ✅        |
|         Авто прокрутка колеса фортуны          |       ✅        |
|            Авто покупка в событиях             |       ✅        |
|                   Авто лифт                    |       ✅        |
|         Проверка изменений на сервере          |       ✅        |
|          Поддержка pyrogram .session           |       ✅        |


## [Настройки](https://github.com/telbip/Boinker/blob/master/.env-example)
|           Настройки           |                                      Описание                                       |
|:-----------------------------:|:-----------------------------------------------------------------------------------:|
|     **API_ID / API_HASH**     | Данные платформы, с которой будет запущена сессия Telegram (по умолчанию - android) |
| **USE_RANDOM_DELAY_IN_RUN**   |                                 Имя говорит за себя                                 |
|    **RANDOM_DELAY_IN_RUN**    |            Рандомная задержка в секундах для ^^^ (по умолчанию - [5, 30]            |
|          **USE_REF**          |  Регистрировать ваши аккаунты по вашей реф. ссылке или нет (по умолчанию - False)   |
|          **REF_ID**           |       Ваш реферальный аргумент (идет после app/startapp? в вашей реф. ссылке)       |
|    **USE_PROXY_FROM_FILE**    |       Использовать ли прокси из файла `bot/config/proxies.txt` (True / False)       |

## Быстрый старт 📚

Для быстрой установки и последующего запуска - запустите файл run.bat на Windows или run.sh на Линукс

## Предварительные условия
Прежде чем начать, убедитесь, что у вас установлено следующее:
- [Python](https://www.python.org/downloads/) **версии 3.10**

## Получение API ключей
1. Перейдите на сайт [my.telegram.org](https://my.telegram.org) и войдите в систему, используя свой номер телефона.
2. Выберите **"API development tools"** и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка
Вы можете скачать [**Репозиторий**](https://github.com/telbip/Boinker) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
git clone https://github.com/telbip/Boinker.git
cd boinkers
```

Затем для автоматической установки введите:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux ручная установка
```shell
sudo sh install.sh
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Здесь вы обязательно должны указать ваши API_ID и API_HASH , остальное берется по умолчанию
python3 main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/boinkers >>> python3 main.py --action (1/2)
# Or
~/boinkers >>> python3 main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```


# Windows ручная установка
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Указываете ваши API_ID и API_HASH, остальное берется по умолчанию
python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/boinkers >>> python main.py --action (1/2)
# Или
~/boinkers >>> python main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```
