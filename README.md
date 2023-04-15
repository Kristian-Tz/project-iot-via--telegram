# Kode program IoT via bot telegram

## project ini menggunakan module relay dan nodemcu wifi
## Install from Termux/terminal

Install module git clone
```bash
  apt install git
```

Clone the project
```bash
  git clone https://github.com/Kristian-Tz/project-iot-via-telegram
```

Go to the project directory
```bash
  cd project-iot-via-telegram
```

Install dependencies
```bash
  npm install
```

## Installation

Install my-project with npm
```bash
  npm install https://github.com/Kristian-Tz/project-iot-via-telegram
  cd project-iot-via-telegram
```
    
## ubahlah ssid dan password wifi kalian on file main.py

```javascript
sta_if.connect(wifi_config['ssid'], wifi_config['password'])
```
## ubahlah apikey dan token bot telegram kalian on file utelegram.py
cara mendapatkan apikey dan token bot telegram:  [Click ini](https://langsungviral.com/2019/12/04/cara-mendapatkan-api-key-atau-token-bot-telegram-dan-chat-id-telegram/)

```javascript
 def __init__(self, token):
  self.url = 'https://api.telegram.org/bot' + token
```


## Authors

- [@Kristian-Tz](https://www.github.com/Kristian-Tz)


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Badges



[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
