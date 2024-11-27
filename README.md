# Telegram Bot для отправления сообщений в mail

это простое приложение телеграм бота, которое собирает 1) данные о почте откуда отправить 2) сообщение которое отправить на почту
## Установка

1. Clone repo:
   ```bash
   git clone https://github.com/g4kuen/otrpo8.git
   cd otrpo8
   ```

2. Установите необходимые зависимости:
   ```bash
   pip install -r requirements.txt
   ```

3. Создайте a `.env` файл в корневой папке и заполните его необходимыми данными:
   ```env
   SMTP_SERVER=your_smtp_server
   SMTP_PORT=your_smtp_port
   SMTP_USER=your_email@example.com
   SMTP_PASSWORD=your_email_password
   TOKEN=your_telegram_bot_token
   ```

4. Запустите бота:
   ```bash
   python otrpo8_bot.py
   ```

## Использование бота

1. Начните с команды `/start` в телеграм чате с вашим ботом.
2. Напечатайте почту КУДА хотите отправить сообщение.
3. Напишите само СОДЕРЖАНИЕ сообщения, которое хотите отправить.
