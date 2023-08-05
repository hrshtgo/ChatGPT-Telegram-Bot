# ChatGPT-Telegram-Bot
A voice chatbot that has the computational powers of ChatGPT and is easily accessible via Telegram on your smartphone.  

## Requirements
Create your openai API key: [https://gptforwork.com/help/gpt-for-docs/setup/create-openai-api-key].

Follow the following steps in telegram to generate your API token:
* Search for BotFather in telegram.
* Type "/start" to start the chat with BotFather.
* Type "/newbot" to create a new bot.
* Give the name of your bot followed by the username.
* This will create the telegram api token which is used in the application.

You will need to install some python packages via the following commands in your terminal:
```
pip install openai
pip install python-telegram-bot
pip install gtts
pip install moviepy
```

## Usage
* Run the python file [run.py] in your terminal or alternatively you can also freely host it online like on [https://pythonanywhere.com] if you want it to run 24/7.
* Go to the bot that you created via BotFather and press "Start".
* You can input using your voice or alternatively via text.
* The ouput is received via a voice message or a text message.
