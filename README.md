# debank-badge-minter

Минтер баджей на дебанке

# Features

- **Поддержка прокси**

- **Чекер всех баджей + минт доступных**

- **Возможно устанавливать тайминги работы**

### Settings

Смотри config.py file

~~~python
TIMEOUT = [1, 2] # отвечает за задержкой между запросами
TO_MINT_BADGES = [2, 3, 4, 5, 6] # айдишники баджей, можно посмотреть на странице https://debank.com/badge
RUN_THREAD_TIMEOUT = [5, 10] # отвечает за задержкой между стартом аккаунтов

~~~

Чтобы начать работу:
 - Загрузи приватники в файл secrets.txt
 - Загрузи прокси в формате: login:pass@ip:port в файлик proxies.txt

По поводу прокси. Их в целом можно и не загружать (просто файлик оставить пустым). Но осторожней, дебанк любит рейтлимитать за большое кол-во запросов / плохие прокси

DEV           : https://t.me/lang_crypto

With love for : https://t.me/swiper_tools

Приобрести бота на ZkSync / LayerZero можно тут: https://t.me/swipersoft_bot
