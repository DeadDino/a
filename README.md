# Отчет по ИДЗ №1

## 4 балла

#Были написаны комментарии

### Команда, с помощью которой был получен код на ассемблереа

gcc -O0 -Wall -S -masm=intel -fno-asynchronous-unwind-tables idz1.c

### Тест
idz1.s - ассемблер
idz1.c - код на си

| Входные данные   | idz1.s          | idz1.c          |
|------------------|:---------------:|:---------------:|
| [1 2 3 4]        | [4 3 2 1]       | [4 3 2 1]       |
| [-2 ]            | [-2]            | [-2]            |
| [100 300 200]|   | [300 200 100 ]  | [300 200 100]   |
| [ 5 4 1 7 8]     | [ 8 7 5 4 1]    | [ 8 7 5 4 1]    |
| [ 50 47 12 1 2]  | [50 47 12 2 1]  | [50 47 12 2 1]  |

##5 баллов
### Были заменены глобальные переменные массивов на локальные, программа и в 4 была разделена на функции.
### Были дописаны комментарии

