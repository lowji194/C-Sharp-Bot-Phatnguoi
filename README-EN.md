[![🇻🇳 Tiếng Việt](https://img.shields.io/badge/Language-Ti%E1%BA%BFng%20Vi%E1%BB%87t-1e293b?style=flat-square)](README.md)

# C-Sharp-Bot-Phatnguoi

A C# (`.NET 6.0`) Telegram bot for checking Vietnamese traffic violations (*phạt nguội*), matching the workflow of [Bot-telegram-Tracuuphatnguoi](https://github.com/lowji194/Bot-telegram-Tracuuphatnguoi).

## Prerequisites

- [.NET 6.0 SDK / Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)

## Configuration (`config/`)

- `config/api_bot.txt`: Telegram bot token
- `config/lienhe.txt`: Contact message displayed by the bot
- `config/apicaptcha.txt`: Captcha solver API keys (`ocr.space` or `Autocaptcha`, one key per line)

## Running

Execute `Bot_Phatnguoi.exe` after placing your configuration files in `config/`.

## License

Released under the [MIT License](LICENSE).
