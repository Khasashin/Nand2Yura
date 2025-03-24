# Ревью

## Впечатления
Задумка неплохая но сыровато, просто нужно доделать

## по КОДУ 
- Думаю стоит разделить на 3 метода для каждого типа а не писать все в один https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Display.jack#L55
- Лишнее https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L10C9-L10C14
- три помидора? Много магическич чисел, надо хотя бы комменты добавить https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L46
- Снова магические числа https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L65
- Слишком ответственная функция, надо разбить как минимум на 3 (я предлогаю на 4):
  какой-нибудь init, chooseLevel, run, addPlayer https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L32
- в один if через и. сократите вложенность https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L143
- тоже самое https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L162
- дублирование, вынести во что-то отдельное с переменной +-1 https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L145
- думаю этот уровень и остальные следует вынести в отдельный класс Levels https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L669
- слишком большая функция https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L118
- длинная строка https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L198
- длинная строка https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L255
- слишком большая функция https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L395
- длинная строка https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L312
- В один if https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Movement.jack#L35
- тоже самое https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Movement.jack#L48
- тоже самое https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Movement.jack#L61
- также в этих циклах есть дублирование
- в один if https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Movement.jack#L85
- в один if https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Movement.jack#L104
- дублирование в циклах https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Movement.jack#L108
- аналогично предыдущим 2 функциям: дублирование и лишняя вложенность https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Movement.jack#L124
- удалить https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L120
- удалить https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L177

  Другие замечания
- программа просто заканчивает работу при смерти https://github.com/Khasashin/Nand2Yura/blob/4d0b463bf9bf6a2dd549a5eacd9057c36e61f6f4/Main.jack#L115
- думаю стоит отображать текущее количество жизней
- нигде не прописано что на q игра заканчивается
- пули растворяются в воздухе
+- наверное можно было обойтись и без массивов массивов

## Оценка
Идея 5 / 5
Код - 1 / 5
Рисовка - 5 / 5
Оформление - 2 / 5
Итог 3.25
