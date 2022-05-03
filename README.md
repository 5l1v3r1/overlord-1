# [![wtf](https://i.ibb.co/fXzW8w7/Untitled-Copy-Copy-1.png "overlord")](https://www.youtube.com/watch?v=dQw4w9WgXcQ&list=PLrpgO-fUNO4OKpFbFXb2cQlF72Yj3ppJv) 
# Overlord - marketing software

[![Button](https://badgen.net/badge/ebankoff/ebankoff/red?icon=github&label)](https://github.com/ebankoff) [![Button](https://badgen.net/badge/telegram/telegram/yellow?icon=telegram&label)](https://t.me/The_W_T_F) [![Button](https://badgen.net/badge/icon/qiwi/orange?icon=bitcoin&label)](https://qiwi.com/n/HERAMANT) [![Button](https://badgen.net/badge/fork/fork/purple?icon=github&label)](https://github.com/ebankoff/overlord/fork) [![Button](https://badgen.net/badge/fork/fork/purple?icon=gitlab&label)](https://gitlab.com/ebankoff/overlord/fork) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Get%20over%20170%20free%20design%20blocks%20based%20on%20Bootstrap%204&url=https://www.froala.com/design-blocks&via=froala&hashtags=bootstrap,design,templates,blocks,developers)

# 📌 EN

`Features`
* Account checker
*	DM spammer
*	Server spammer
*	Server joiner
*	Server leaver
*	Parsing server member IDs
*	HypeSquad changer
*	Nicknames changer
*	Avatars changer
*	Proxy grabber
* Record all the actions of the software in the files .txt (located in the folder log)

`Installation`
* git clone https://github.com/ebankoff/overlord

`First setup`
- The program will configure everything on its own. If the automatic configuration fails, you can configure everything manually. A requirements.txt file is supplied with overlord. This file contains external dependencies. To install them, open cmd/terminal and write: **pip install -r requirements.txt.**
- To work correctly the software needs a good proxies and [anticaptcha](https://anti-captcha.com) API key to solve captchas.
- Write Discord accounts in the **accounts.txt** file (located in the files folder) in the format: **mail:password:token.**
- Next, write the [anticaptcha](https://anti-captcha.com) API key into the **api_config.ini** file (located in the files folder). 
- In the **message.txt** file (located in the files folder) write the message to be sent out. 
- In file **targets.txt** (located in files folder) write manually IDs of accounts where message should be delivered or automatically by server member parser.
- In file **blacklist.txt** (located in files folder) write IDs of accounts where it is not necessary to deliver the message. 
- In the folder **avatars** put avatars (at least one), they will be needed if you enable the function to change the avatars. 

**The setup is done!**

`Launch`
* cd overlord
* python3 overlord.py

# 📌 RU

`Преимущества`
* Чекер аккаунтов
*	DM спамер
*	Спам сервера
*	Зайти на сервер
*	Выйти с сервера
*	Парсер ID участников сервера
*	HypeSquad
*	Изменение никнеймов аккаунтов
*	Изменение аватаров аккаунтов
*	Парсер бесплатных прокси
* Запись всех действий софта в файлы .txt (находятся в папке log)

`Установка`
* git clone https://github.com/ebankoff/overlord

`Первая настройка`
- Программа настроит все самостоятельно. Если автоматическая настройка не удалась, Вы можете настроить все вручную. Вместе с overlord идет файл requirements.txt. Этот файл содержит внешние зависимости. Чтобы установить их, нужно открыть cmd/terminal и написать: **pip install -r requirements.txt**
- Для корректной работы софту нужны хорошие прокси и API ключ [anticaptcha](https://anti-captcha.com) для решения капч.
- Запишите в файл **accounts.txt** (находится в папке files) аккаунты Discord в формате: **почта:пароль:токен.**
- Далее запишите в файл **api_config.ini** (находится в папке files) API ключ [anticaptcha](https://anti-captcha.com). 
- В файл **message.txt** (находится в папке files) запишите сообщение для рассылки. 
- В файл **targets.txt** (находится в папке files) вручную запишите ID аккаунтов, куда должно быть доставлено сообщение, либо автоматически, при помощи парсера участников сервера. 
- В файл **blacklist.txt** (находится в папке files) запишите ID аккаунтов, куда **не нужно достовлять сообщение.** 
- В папку **avatars** поместите аватары (не менее одного), они потребуются, если вы включите функцию смены аватаров.

**Настройка завершена!**

`Запуск`
* cd overlord
* python3 overlord.py
