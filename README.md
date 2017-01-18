
# به ترتیب بزنید
#Installation
### Install dependencies.
### Tested on Ubuntu 14.04.
```
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev
cd $HOME
git clone https://github.com/sajjad-021/TgSelf.git
cd TgSelf
chmod +x launch.sh
./launch.sh install
cd .luarocks/bin
./luarocks-5.2 install luafilesystem
./luarocks-5.2 install lub
./luarocks-5.2 install luaexpat
./luarocks-5.2 install serpent
./luarocks-5.2 install feedparser
./luarocks-5.2 install redis-lua
./luarocks-5.2 install fakeredis
cd ../..
./launch.sh 
 بعد از زدن این دستور از شما شماره و کد تایید میخواد
Then Enter Your Phone And Confirmation Code
```
#بعد از لانچ بات را خاموش کنید و به پوشه دیتا رفته و فایل کانفیگ رو باز کنید در این فایل باید خودتونو سودو کنید
###After you run the bot for first time, send it !id @YourUserName. Get your ID and stop the bot.

###Open ./data/config.lua and add your ID to the "sudo_users" section in the following format:
```
  sudo_users = {
    157059515,
    YourID
  }
```
#بعد از ان دوباره ربات خود رو لانچ کنید.
###Then restart the bot.

#برای ران کردن ربات با اتو لانچ از دستورات زیر استفاده کنید.
###For Launch With AutoLaunch :
```
chmod 777 beyond.sh
screen ./beyond.sh
```

#Developer&Founder : 
#[SoLiD021](https://telegram.me/SoLiD021)

#Developer&Manager : 
#[AliReza](https://telegram.me/CliApi)

* * *

# Special Thx To :
###Seed Team

###And All My Friends :D

#Team Channel :

#[@BeyondTeam](https://telegram.me/BeyondTeam)

###اگر مشکلی داشتید به لینک زیر بیاید و مطرح کنید
###If You Have Any Problem With Source, Join To Link And Ask About Your Problem
#[Group Support](https://telegram.me/joinchat/DH-5lD7jQzz0TsOC3Ar5Tg)

#موفق باشید -_-
#Good Luck -_-
