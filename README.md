**Whitelist Account Auto-Register Tool for ******** **

Quick Setup FAQ:
1. Pop open your terminal and run: pip install selenium
2. Grab the Chrome driver (needed for Selenium to do its thing). Best bet—get it straight from the official site
3. Toss that driver into your PATH. On Mac, just run: sudo mv chromedriver /usr/local/bin/
4. Download VS Code (seriously, just do it) from here
5. Fire up main.py. But first—drop your info into data.csv like this: twitter,wallet,email,discord
6. In the code:
7. Line 9 → plug in the path to your Chrome driver
8. Line 102 → set the path to your data.csv file
9. Hit run. Once it wraps up, you’ll see: "Регистрация завершена для всех записей." (aka “All accounts registered, you’re good to go!”)


====================================================================================


**Софт для регистрации аккаунтов для ****** вайтлиста**

FAQ:
1. В командну строку/терминал ввести команду «pip install selenium»
2. Установить драйвер для работы с библиотекой selenium, рекомендую установку с официального сайта: https://developer.chrome.com/docs/chromedriver?hl=ru
3. Поместите драйвер в PATH: с помощью командной строки на мак « sudo mv chromedriver /usr/local/bin/ »
4. Установите VScode!!!! с официального сайта: https://visualstudio.microsoft.com/ru/downloads/
5. Запустите программу main.py , предварительно введите свои данные в базу data.csv в формате twitter,wallet,email,discord
6. Непосредственно в коде в 9 строке пропишите путь до Chrome Driver, а так же в 102 строке пропишите путь до data.csv файла
7. Запустите программу, при завершении в консоли пропишется сообщение "Регистрация завершена для всех записей."
