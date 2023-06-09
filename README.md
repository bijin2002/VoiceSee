## Installation
Clone the repo and install [requirements.txt]()
```
[git clone https://github.com/IS2AI/telegram-bot-chatgpt.git](https://github.com/bijin2002/VoiceSee.git)
cd visionsee
pip install -r requirements.txt
```

## Authentication 
1) Create an account on [OpenAI's ChatGPT](https://chat.openai.com)
2) Update ```config.json``` file with your email and password
3) Other authentication methods can be found [here](https://github.com/acheong08/ChatGPT)

## Create a new Telegram bot with [BotFather](https://telegram.me/botfather)
1) Start a new conversation with the [BotFather](https://telegram.me/botfather)


2) Send ```/newbot``` to create a new Telegram bot.
3) When asked, enter a name for the bot.
4) Give the Telegram bot a unique username. Note that the bot name must end with the word "bot" (case-insensitive).
5) Send ```/token``` to generate authorization token
6) Insert the generated token on ```tele_token = "<YOUR TELEGRAM BOT TOKEN>"``` in ```telegram_chatgpt_en.py``` file.

## Run 
1) Launch the Telegram bot
```
visionsee.py
```
2) Open the bot on Telegram and start a new conversation with ChatGPT via voice messages


## Official ChatGPT API
1. Log/Sign in to [OpenAI platform](https://platform.openai.com/)
2. Go to the profile section (top right) and click on ```View API keys```
3. If you don't have an existing key then create a new one
4. Install the OpanAI package: ```pip install --upgrade openai```
5. Export your key on your working enviroment: ```export OPENAI_API_KEY=<YOUR_OPENAI_API_KEY>```
6. Launch the telegram bot: ```visionsee.py```
8. For more information about the official ChatGPT API: https://platform.openai.com/docs/guides/chat 

## Future Scope 
1) Improvements in OCR to identify currency and notes
2) File management 

## References
1) [revChatGPT](https://github.com/acheong08/ChatGPT)
2) [SpeechRecognition](https://github.com/Uberi/speech_recognition)
3) [gTTS](https://github.com/pndurette/gTTS/tree/6c6300c346747fb42f8daed70eb240c98e27cb88)
