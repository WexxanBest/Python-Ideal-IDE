# Python-Ideal-IDE
Проект позволяет создавать ПО, используя язык программирования Python для написания графической и логической части.
### Статус разработки
Пока лишь доступен прототип приложения, но приложение постоянно развивается и вскоре должна выйти полноценная первая его версия
### Принцип работы в общих чертах
Основой логической части приложения выступает локальный сервер, написанный на веб-фреймворке Python Flask. За графическую часть приложения отвечает код написанный на Python, который взаимодействует с бразуером Chromium и отправляет запросы локальному сервису для выполнения каких-либо процессов.

Пользователь пишет приложения, используя различные библиотеки Python, которые сам установит, и предостовляемые нами библиотеки для написания интерфейса приложения. Поведения веб-страницы тоже пишется с использованием языка Python, который затем при помощи javascript-библиотеки brython интерпретируется в javascript, понятный браузеру Chromium. 

В конце концов, у пользователя будет возможность скомпилировать код. Для этого используется библиотека PyInstaller, которая компилирует Python код в программу, которая может запускаться на разлиных компьютерных ОС, даже если на них не установлен Python. 
