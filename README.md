# 03.09.21-185
1. Скачать OpenCV по ссылке https://opencv.org/releases/
2. Создать пустой проект C++ в Visual Studio.
3. Подключить OpenCV:
4. Находим C/C++ -> Общие и включаем дополнительный каталог: C:\Users\Администратор\Downloads\opencv\build\include
5. Находим Компоновщик -> Общие и включаем дополнительные каталоги библиотек: C:\Users\Администратор\Downloads\opencv\build\x64\vc15\lib
6. Компоновщик -> Ввод и включаем дополнительную зависимость: opencv_world453d.lib и opencv_world453.lib
7. Отправить файл-DLL в Debug
8. Пишем код 
9. Вся проделанная работа должны стоять на x64
10. Копируем opencv_world453.lib и opencv_world453d.lib в папку C:\source\repos(Project1)\Debug
11. Переписываем исходный код кроме "namedWindow("Hello world", 0);
12. Включаем и получаем результат.





