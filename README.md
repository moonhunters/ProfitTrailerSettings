# MoonHunter.net


## A. Instruction to setup VERSION 2 (PT v2.x and PTFeeder v1.5.x)

#### 1. ProfitTrailer v2.x
* activate ProfitTrailer license at https://wiki.profittrailer.com/doku.php?id=pt_assistant
* download ProfitTrailer at https://github.com/taniman/profit-trailer/releases (get v2.x, the latest one)
* install instruction at https://wiki.profittrailer.com/doku.php?id=windows_guide
* update application.properties at https://wiki.profittrailer.com/doku.php?id=application.properties
* read PT 2.x wiki at https://wiki.profittrailer.com/doku.php


#### 2. PTFeeder v1.5.x
* download PTFeeder at https://github.com/mehtadone/PTFeeder/releases (get v1.5.x, the latest one)
* install instruction at https://wiki.ptfeeder.co/installation.html
* update hostsetting.json at https://wiki.ptfeeder.co/configuration.html#hostsettings-json
* read PTFeeder 1.5.x wiki at https://wiki.ptfeeder.co


#### 3. PTFeeder settings for version 2
* https://github.com/moonhunters/ProfitTrailerSettings/tree/master/Version%202/PTFeeder


#### 4.  Tips to reduce Binance trading fee & tighten security before running the bots
* use BNB as trading fee, always maintain a small amount of BNB in Binance
* make sure Binance API keys are not allowed for withdrawal, and limited to run from only 1 IP address
* in Binance, enable 2FA, setup anti-phishing code, enable whitelist for withdrawal
* always use clean browser (no add-ons) to access Binance


## B. Instruction to setup VERSION 1 (PT v1.2.6.25 and PTFeeder v1.4.0)

#### 1. ProfitTrailer v1.2.6.25
* activate ProfitTrailer license at https://wiki.profittrailer.com/doku.php?id=pt_assistant
* download ProfitTrailer at https://github.com/taniman/profit-trailer/releases (get v1.2.6.25, not the latest one)
* install instruction at https://wiki.profittrailer.com/doku.php?id=windows_guide
* update application.properties at https://wiki.profittrailer.com/doku.php?id=application.properties1
* read PT 1.x wiki at https://wiki.profittrailer.com/doku.php?id=version_1.x


#### 2. PTFeeder v1.4.0
* download PTFeeder at https://github.com/mehtadone/PTFeeder/releases (get v1.4.0.459, not the latest one)
* install instruction at https://github.com/mehtadone/PTFeeder/wiki/Install-PT-Feeder-on-Windows
* update hostsetting.json at https://github.com/mehtadone/PTFeeder/wiki/hostsettings.json
* read PTFeeder 1.4 wiki at https://github.com/mehtadone/PTFeeder/wiki


#### 3. PTFeeder settings for version 1
* https://github.com/moonhunters/ProfitTrailerSettings/tree/master/Version%201/PTFeeder


## C. Instruction to setup Telegram bot
#### 1. create bot token: 
* in Telegram, add @BotFather and talk to him. Choose /newbot to create new bot, and follow its instruction.
* bot token should look like this : 999999999:AAAAAAAAAAAAAAAAAAAAAAAAAAAA

#### 2. get your Telegram chat id: 
* get your Telegram chat id: in Telegram, add @MyTelegramID_bot to get your Telegram chat id.
* your Telegram chat id should look like this: 888888888

#### 3. add them to application.properties (for ProfitTrailer v1.2.6.25)
* telegram.botToken = your bot token
* telegram.chatId = your Telegram chat id

#### 4. add them to application.properties (for ProfitTrailer v2.x)
* telegram.bot_token_1 = your bot token
* telegram.chat_1 = your Telegram chat id

#### 5. add them to hostsettings.json (for PTFeeder)
* "TelegramBotId": "your bot token",
* "TelegramChatId": "your Telegram chat id",


## D. Useful links

#### 1. ProfitTrailer: https://profittrailer.com/pt/buy/

#### 2. ProfitTrailer Feeder: https://cryptoprofitbot.com/?ref=moonhunter

#### 3. ProfitTrailer Settings: https://github.com/moonhunters/ProfitTrailerSettings

#### 4. Recommended VPS: Vultr
* Vultr: https://www.vultr.com/?ref=7323069
* VirMach: https://billing.virmach.com/aff.php?aff=3684
* Vodien: http://billing.vodien.com/aff.php?aff=809
* Dreamhost: https://www.dreamhost.com/r.cgi?183658
	
	
#### 5. Exchange
* Binance: https://www.binance.com/?ref=20665680
* Coinbase: https://www.coinbase.com/join/5979f8c5b3abca026cfe437b
* Coincheck: https://coincheck.com/?c=YJ_lld-WnhI
* Cryptopia: https://www.cryptopia.co.nz/Register?referrer=minhducle


#### 6. Hardware Wallet
* Ledger Nano: https://www.ledgerwallet.com/r/9daa


#### 7. Manage Profit
* Cointracking: https://cointracking.info?ref=L239596


## E. Thank you for your contribution

* We work everyday to improve bot settings for ourselves and friends. We aim to support our friends until they gain back the investment and are able to run the bot themselves. 
* We do not charge any fee for support. But if you want to send us any token of appreciation, let us know :) 

* Bitcoin (BTC) : 1NsESu8MJn5JdsQvucDgsPg3NWeDAJLcC
* Ether (ETH) : 0x557327633D28a6371a78d0DBA162B3AD2712e557
* Bitcoin Cash (BCC) : qrd9tj3298dl3fy34wtl4lqvleumsygqxuzrss3l4v



