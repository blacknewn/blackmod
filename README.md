# [V_1 Admin](https://telegram.me/MahDiRoO)

**An advanced and powerful administration bot based on NEW TG-CLI


* * *

## Commands

| Use help |
|:--------|:------------|
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/mahdiroo/MaTaDoT_TG.git
cd MaTaDoT_TG
chmod +x beyond.sh
./beyond.sh install
./beyond.sh 
# Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/BeyondTeam/MaTaDoT_TG.git && cd MaTaDoT_TG && chmod +x beyond.sh && ./beyond.sh install && ./beyond.sh
```

* * *

### Sudo

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    377450049,
    0,
    YourID
  }
