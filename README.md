# MoonHunter.net

## Instruction to setup PT v1.2.6.25 and PTFeeder v1.4.0

#### 1. ProfitTrailer v1.2.6.25
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


## Instruction to setup Telegram bot
* create bot token: in Telegram, add @BotFather and talk to him. Choose /newbot to create new bot, and follow its instruction.
bot token looks like this : 999999999:AAAAAAAAAAAAAAAAAAAAAAAAAAAA

* get your Telegram chat id: in Telegram, add @MyTelegramID_bot to get your Telegram chat id
your Telegram chat id looks like this: 888888888

* for ProfitTrailer v1.2.6.25, edit application.properties
telegram.botToken = your bot token
telegram.chatId = your Telegram chat id

* for ProfitTrailer v2.x, edit application.properties
telegram.bot_token_1 = your bot token
telegram.chat_1 = your Telegram chat id

* for PTFeeder, edit hostsettings.json
"TelegramBotId": "your bot token",
"TelegramChatId": "your Telegram chat id",
	


## Useful links

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