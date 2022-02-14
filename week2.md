## ТЕМА
	• Типы данных
	• Блок схемы алгоритмов

## ТЕОРИЯ
1) CS50. Вводные лекции 3-4
Источник <https://habr.com/ru/company/vertdider/blog/403823/> 

**Лекция 3**
- 00:00 Вступление
  - Машина Mark1 и первые баги
  - Что будем изучать на этой неделе
~~- 04:50 Объявления (объявления, связанные с учебным процессом).~~
- 06:43 Знакомство с Си
  - Первая программа на Си: hello.c
  - Сравнение структур Си и Scratch
- 13:38 CS50 IDE.
- 17:15 Написание кода.

**Лекция 4**
- 00:00 Вступление. Немного об устройстве памяти компьютера. На прошлой неделе в impression.c мы увидели что 1.0/10.0, вопреки здравому смыслу, вовсе не равно 0.1. На самом деле, разумеется, равно, но не для компьютера с его конечной памятью.
- 12:12 Объявления.
  - Объявления, связанные с учебным процессом.
- 12:34 Разбираем hello.c.
  - Сравнение структур Си и Scratch
- 21:11 Типы данных Си.
- 26:56 Условия (ветвления).
- 28:16 Циклы.
- 32:57 Вопрос переполнения.
- 40:59 И снова циклы.
- 41:40 Переменные.
- 42:12 Функции и аргументы.
- 49:33 Задачи первой недели.
 
2) Еще раз закрепить глазами:
https://habr.com/ru/sandbox/147980/
https://javarush.ru/quests/lectures/questharvardcs50.level01.lecture04

3) https://github.com/nialterexova/self-education

Зарегистрироваться на гитхабе https://github.com/ (+ рекомендую скачать  https://desktop.github.com/). 
Попробовать поиграть с проектом: клонировать локально, запушить изменение из локал в удаленный, изменить удаленный и стянуть пул себе локально и тд.

Зарегистрироваться в онлайн IDE https://replit.com/
+ подключиться к гиту, попробовать создать проект на си

## ЗАДАНИЕ

1) Решение квадратного уравнения. Если ответ получается целым, то дополнительно вывести сообщение о четности числа.  + Блок схема алгоритма

ПРИГОДИТСЯ: Команда для терминала для компиляции с использованием библиотеки math: gcc main.c -lm -o main

2 и 3) 

https://javarush.ru/quests/lectures/questharvardcs50.level01.lecture18

https://javarush.ru/quests/lectures/questharvardcs50.level01.lecture19

ПРИГОДИТСЯ: вместо библиотеки cs50 можно подключить мою функцию (ставить ДО исполняемого main, но учитывайте, что она не зацикленная) или попробовать написать свою

int get_int(void)
{
 int response = 0;
 int x = 0;
 response = scanf("%i", &x);
 if (response == 1) return x; else {
   printf("Введите целое число и перезапустите программу\n");
   exit(1);
   }
}

4*) (Python)

Задания на алгоритмы - B

https://contest.yandex.ru/contest/28730/problems/B/