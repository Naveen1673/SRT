# Remote Access Tool #
***

**DISCLAIMER**☠☠ 
|This Tool {Remote Access Tool} is **only** For the Educational purpose try only on **your** PC. Do not be evil!!! 

**

<p align="center">
    <img src="preview.gif" width="320", height="614"> </br>
    *Remote Access preview*
</p>



## Features ##
 Remote Access Tool can:
- Browse files and send selected to chat.
- Turn Off and Lock Down PC.
- Get Info about PC.
- Take ScreenShoots.
- Process viewing and killing.
- more to come...

## Usage ##

Once you've set everything up correctly, you can interact with the bot by typing `/start` or `/help`. This will display a set of buttons that allow you to control your PC remotely.

Button Explanations

- Files: Browse and access files on your PC directly from Telegram. Simply click on the file you need, and it will be sent to you.
- Process Control: View and manage running processes on your PC. This submenu allows you to get information about processes and        terminate them if needed.
- Power Control: Control your PC's power settings remotely. This submenu enables you to lock your PC or shut it down completely.
- PC Info: Get detailed information about your PC, including screenshots and live streaming capabilities. This submenu provides a range of options for monitoring and managing your PC remotely.


## Installation and Init Configuration ##
### Installation ###
This project has to be hosted on **PC, that you want to have remote access to**. </br>
To begin this project, you'll need to install the necessary Python packages on your system. You can find the installation packages for different operating systems on the official Python website.

Next, you’ll need to download the repository. While I recommend using Git, you are free to use any method you prefer. If you choose Git, you can use the following commands:
```
git clone : 
cd telegram-remote-bot/python
```
After downloading you have to install dependencies:
```
pip3 install -r requirements.txt
```
### Init Configuration ###
Configuration

Before the first run, you have to change configuration file config.ini:
```
[TelegramBot]
token = bot_token

[Admin]
id = admin_id 
```
All the following steps are required for the bot to function properly:

The Telegram Remote Access Tool utilizes Telegram Bots, so the first step is to create a bot via {BotFather}(https://t.me/BotFather). Follow the instructions provided by BotFather to set up your bot. Once created, BotFather will give you a token to access the HTTP API. Make sure to copy this token and paste it into the 'token' field in the configuration file.

For security reasons, only the approved administrator will have access to the PC. To set this up, you'll need to find your Telegram ID. You can do this by using a bot like UserInfoBot. Once you have your ID, paste it into the 'id' field in the configuration file.



## Thanks ##

- [PyTelegramBotApi](https://github.com/eternnoir/pyTelegramBotAPI)
- [Keyboa](https://github.com/torrua/keyboa)
