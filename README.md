# PT-Feeder
￼
ProfitTrailer - это умный бот по торговле крипто-валютными парами. Он позволяет вам автоматически торговать на нескольких биржах, делая это быстро, стабильно и просто, в режиме 24/7 круглый год.
Этот инструмент не предназначен для новичков. Если вам интересно, сколько вы заработаете дополнительной прибыли с помощью бота Profit Trailer, то, вероятно, вы еще не готовы к собственному трейдинг боту. Покупая бота вы не получите автоматическую систему заработка денег, вы получите профит только при оптимальных торговых настройках и использования правильной торговой стратегии, что требует глубокого понимания конфигурации Profit Trailer и стратегий покупки и продажи. Сначала прочитайте wiki Profit Trailer

PT Feeder - это плагин для Profit Trailer, который в реальном времени обновляет настройки торговых пар на основе анализа множества переменных, которые необходимо учитывать при построении стратегии для использования в прибыльном трейлере. Некоторые из параметров, такие как цена BTC, тенденция монеты, объем монеты и т. д., Постоянно меняются. «Сигнализация» покупки монеты в этих условиях может привести к «сумке» или плохой покупке. На основании этих и многих других значений создаются определенные парные переопределения для всех пар на основе их атрибутов в тот момент времени и критериев, которые вы установили.

Связка ProfitTrailer и PT Feeder обеспечивает более стабильную работу бота в условиях изменений на рынке криптовалют и уменьшает необходимость тратить ваше время на подобные настройки.

Что нужно чтобы запустить своего бота:

1. Зарегистрироваться на бирже Bittrex, Binance или Poloneix.

2. Купить лицензию для бота Profit Trailer - https://profittrailer.ru 
    Одна лицензия распространяется на одну биржу.  
3. Купить лицензию для плагина PT Feeder - https://cryptoprofitbot.com/?ref=Timur
    B Плагин обеспечивает постоянное обновление настроек Profit Trailer, подстраивает их под настроение рынка и обеспечивает автоматизацию процесса настроек вашего бота к текущим реалиям и курсам монет. Одна лицензия распространяется на три биржи. 

4. В аккаунте биржы нужно создать новый ключ API Key и Secret Key и скопировать их себе, с помощью этих ключей бот будет подключаться к бирже и осуществлять торговлю, в разрешениях ключа API нужно поставить галочки напротив всех действий, кроме вывода денег с биржи (Withdraw).

Также API Key привязывается к вашей лицензии Profit Trailer
 В настройках бота вы задаете ключ API Key и Secret Key, с помощью которых бот будет торговать на бирже.
Одна лицензия Profit Trailer может быть привязана к одной из бирж Bittrex, Binance или Poloneix. 

Стоимость:
Бот Profit Trailer - 1 лицензия: 0.03 ฿ - Купить у разработчика https://profittrailer.ru
Плагин PT Feeder- 1 лицензия: 0.02 ฿ - Купить у разработчика https://cryptoprofitbot.com/?ref=TimurB Услуга установки PT и PTF на сервер VDS: 0.01 ฿ - Telegram https://t.me/cryptodesign_life
Хороший VDS сервер VULTR 4Gb / SSD-60Gb: $20 / месяц -  https://www.vultr.com/?ref=7313176

Полезные ссылки:
Канал Crypto Design в Telegram - https://t.me/crypto_design
YouTube канал Crypto Design - https://www.youtube.com/channel/UCStysobnjunUYrIfC1027Ag
Поддержите канал Crypto Design ฿: 17rXmVEFRGgxV4MX4GQCKmsECi4ENsWoYX
 Офф сайт бота Profit Trailer - https://profittrailer.ru Скачать последнюю актуальную версию Profit Trailer - https://github.com/taniman/profit-trailer/releases
Почитать документацию Profit Trailer тут - https://wiki.profittrailer.io/doku.php/start?id=ru:start
Русскоязычный чат Profit Trailer в Telegram - https://t.me/joinchat/DreUUw-n-aGoi2LunoJTFA

Офф сайт плагина Profit Trailer Feeder - https://cryptoprofitbot.com/?ref=TimurB
Почитать документацию PT Feeder тут - https://github.com/mehtadone/PTFeeder/wiki
Скачать последнюю актуальную версию PT Feeder - https://github.com/mehtadone/PTFeeder/releases

Биржа Binance - https://www.binance.com/?ref=20781679
Биржа Bittrex - https://bittrex.com
Биржа Poloniex - https://poloniex.com/

Crypto Gnome - Забугорный YouTube обзорщик, который хорошо успешно использует Profit Trailer и PT Feeder, который выкатывает на GitHub актуальные файлы с настройками для Profit Trailer и PT Feeder.
Настройки для Profit Trailer от Crypto Gnome - https://github.com/CryptoGnome/Profit-Trailer-Settings
Настройки для PT Feeder от Crypto Gnome -  https://github.com/CryptoGnome/Gnome-Feeder


Установка Profit Trailer на VDS сервер VULTR:
1. Купите лицензию https://profittrailer.ru и активируйте API ключ вашей биржи в телеграмм боте ProfitTrailer 
2.  Зарегистрируйтесь на https://www.vultr.com/?ref=7313176 и создать сервер: 1.1) Server Location - Не так важно, выбираем допустим Frankfurt 1.2) Server Type - 64 bit OS / Ubuntu 17.10 x64 1.3) Server Size - Мы рекомендуем 60 GB SSD / 4096MB Memory - $20/месяц        Можете использовать следующие конфигурации для VDS сервера.        - 1 x PT Feeder и/или 1 x Profit Trailer -  40GB SSD / 2048MB Memory - $10/месяц        - 1 x PT Feeder и/или до 3 x Profit Trailer -  60 GB SSD / 4096MB Memory - $20/месяц
3. Создайте SSH ключ, например в терминале mac os с помощью команды ssh-keygen -t rsa (или ищите в Гугл как создать ssh ключ) сохраните ключ и добавьте содержимое фала .pub в админке Vultr > Servers > Add Ssh Key  
4. Подключитесь к серверу с помощью терминала или SSH клиента командой: ssh -i /путь_до_ключа/файл_ключа.pem root@ip_вашего_сервера При запросе пароля, введите пароль из админки Vultr > Servers > Кликните на ваш сервер, на странице с информацией о сервере найдите поле Password: и используйте его 
5. Команды для установки нужных для работы Profit Trailer компонентов на VDS сервер Debian 17: sudo apt-get update  sudo apt-get install default-jdk sudo apt-get install -y build-essential curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash - sudo apt-get install nodejs  npm install pm2@latest -g 
6. С помощью клиента типа FileZilla и вашего SSH ключа подключитесь к вашему серверу по SFTP и залейте  файлы ProfitTrailer в папку /var/opt/pt Введите следующие команды: cd /var/opt/pt sudo chown -R root /var/opt chmod +x ProfitTrailer.jar 
7. Вам необходимо внести все настройки в файлы перед запуском Profit Trailer 
8. Для запуска Profit Trailer подключитесь к вашему серверу по SSH и введите команды cd /var/opt/pt sudo pm2 start pm2-ProfitTrailer.json  
9. Готово - Перейдите по адресу http://ip_вашего_сервера:8081 и наблюдайте за работой вашего Profit Trailer онлайн

Установка дополнения Profit Trailer FEEDER на VDS сервер VULTR - Debian 17:
1. Купите лицензию PT Feeder - https://cryptoprofitbot.com/?ref=TimurB и привяжите к ней ключи API вашей биржи или бирж (один PT Feeder может работать одновременно на три биржи)
2. Подключитесь к серверу с помощью терминала или SSH клиента и введите следующие команды: curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg sudo mv microsoft.gpg /etc/apt/trusted.gpg.d/microsoft.gpg sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/microsoft-ubuntu-artful-prod artful main" > /etc/apt/sources.list.d/dotnetdev.list' sudo apt-get install apt-transport-https sudo apt-get update sudo apt-get install dotnet-sdk-2.1.4

2. С помощью клиента типа FileZilla и вашего SSH ключа подключитесь к вашему серверу по SFTP и залейте  файлы PT Feeder в папку /var/opt/pt /var/opt/ptf 

3. Для запуска Profit Trailer подключитесь к вашему серверу по SSH и введите команды: cd /var/opt/ptf sudo pm2 start pm2-PT-Feeder.json

Полезные SSH команды: pm2 status - показывает текущие запущенные процессы Pm2 и используемую память
cd /var/opt/pt - Переход в нужную папку, в примере в папку /var/opt/pt 
ssh -i /путь/файл.pub root@123.45.67.89 - Подключение c SSH ключём к серверу
sudo chown -R root /var/opt/pt - Назначает права пользователя на папку где root это имя пользователя
sudo chmod -R 755 /var/opt/pt - Назначает права доступа к папке

