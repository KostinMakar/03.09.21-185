# 03.09.21-185
Скачать OpenCV по ссылке https://opencv.org/releases/
Создать пустой проект C++ в Visual Studio.
Подключить OpenCV:
1. Находим C/C++ -> Общие и включаем дополнительный каталог: C:\Users\Администратор\Downloads\opencv\build\include
2. Находим Компоновщик -> Общие и включаем дополнительные каталоги библиотек: C:\Users\Администратор\Downloads\opencv\build\x64\vc15\lib
3. Компоновщик -> Ввод и включаем дополнительную зависимость: opencv_world453d.lib и opencv_world453.lib
Отправить файл-DLL в Debug
Пишем код 
Вся проделанная работа должны стоять на x64
Копируем opencv_world453.lib и opencv_world453d.lib в папку C:\source\repos(Project1)\Debug
Переписываем исходный код кроме "namedWindow("Hello world", 0);
Включаем и получаем результат.





