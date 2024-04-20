# Free GPT Telegram Bot

Этот проект представляет собой Telegram бота, который предоставляет бесплатный доступ к функциям GPT для пользователей. Он позволяет автоматически общаться с пользователями, используя модель GPT от OpenAI.

## Установка

1. Клонируйте репозиторий:
```bash
git clone https://github.com/<ваш_логин>/<ваш_репозиторий>.git
```

2. Установите зависимости:
```bash
pip install -r requirements.txt
```

3. Укажите токен бота Telegram в файле TOKEN_API_BOT.

## Использование

1. Запустите бота:
```bash
python main.py
```

2. Найдите бота в Telegram и начните общение.

## Как это работает

Этот бот использует библиотеку [gpt4free](https://github.com/xtekky/gpt4free) для парсинга зеркал ChatGPT и получения запросов. Когда пользователь отправляет сообщение, бот передает его в библиотеку gpt4free для обработки. Затем библиотека использует модель GPT для генерации ответа на основе полученного сообщения. Сгенерированный ответ затем отправляется пользователю через Telegram.

Библиотека gpt4free позволяет боту получать доступ к функциям GPT без необходимости в получении API OpenAI, что делает его проще в использовании и более экономичным в ресурсах.

## Лицензия
Этот проект лицензирован в соответствии с условиями [MIT License](https://opensource.org/licenses/MIT).