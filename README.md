# game_v2
Игра угадай число
=======
# Проект 0. Угадай число

## Оглавление  
[1. Описание проекта](https://github.com/zchipirov/game/tree/main/README.md#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/zchipirov/game/tree/main/README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/zchipirov/game/tree/main/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/zchipirov/game/tree/main/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/zchipirov/game/tree/main/README.md#Результат)    
[6. Выводы](https://github.com/zchipirov/game/tree/main/README.md#Выводы) 

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up:[к оглавлению](https://github.com/zchipirov/game/blob/main/README.md#Оглавление)


### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток

**Условия соревнования:**  
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.
- Используем алгоритм бинарного поиск для минимизации количества попыток нахождения загаданного числа.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**     
Учимся писать хороший код на python


### Краткая информация о данных
На вход функции поиск поступает загаданное число компьютером, для проверки эффективности алгоритма запускается функция вычисления среднего количества итераций, требуемых алгоритму для поиска загаданного компьютером числа 
:arrow_up:[к оглавлению](https://github.com/zchipirov/game/blob/main/README.md#Оглавление)


### Этапы работы над проектом  
На первом этапе работы определили алгоритм для поиска - бинарный поиск, далее модифицировали функцию нахождения загаданного числа согласно алгоритму, в заключительном этапе протестировали код на точность вычислений 

:arrow_up:[к оглавлению](https://github.com/zchipirov/game/blob/main/README.md#Оглавление)


### Результаты:  
Алгоритм угадывает число в среднем за:5 попыток

:arrow_up:[к оглавлению](https://github.com/zchipirov/game/blob/main/README.md#Оглавление)


### Выводы:  
Алгоритм бинарного поиска показал свою высокую эффективность в задачах поиска в упорядоченных последовательностях. Стоит отметить, что выбранный алгоритм находит верное совпадение за log2n шагов, из чего следует, что максимальное количество шагов для нахождения загаданного числа равно 7.

:arrow_up:[к оглавлению](https://github.com/zchipirov/game/blob/main/README.md#Оглавление)


Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами