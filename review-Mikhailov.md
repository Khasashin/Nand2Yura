# 🎮 Мое ревью

## 🌟 Впечатления
Стартовый интерфейс довольно скудный, стоило расположить его хотя бы в центре
Управление можно было бы описать в главном меню
И то что нужно нажать цифру для выбора уровня тоже стоит отметить
Управление по крайней мере для веб эмулятора требует нажатия заглавных букв, добавьте реакцию и на строчные буквы, также почему именно X для спуска вниз, гораздо привычнее S
После прохождения уровня ничего не происходит, добавьте хоть что то чтобы понять что он закончен
Сама игра довольно интересная, анимация врагов, круто йоу

## 🔍 Разбор кода

- [Здесь](https://github.com/graphento/Nand2Yura-forreview/blob/2b3644c8d5ce1ecf1f07c40ba9c76a6839437131/src/Display.jack#L3C19-L3C32) думаю стоило сделать отрисовку игрока через обращение к памяти экрана
- [То же самое](https://github.com/graphento/Nand2Yura-forreview/blob/2b3644c8d5ce1ecf1f07c40ba9c76a6839437131/src/Display.jack#L55)
- [Здесь](https://github.com/graphento/Nand2Yura-forreview/blob/2b3644c8d5ce1ecf1f07c40ba9c76a6839437131/src/IntArrayOfArrays.jack#L27C13-L27C29) стоит использовать номер ошибки хотя бы больше 20, поскольку коды меньше 20 использует сам язык
- [Здесь](https://github.com/graphento/Nand2Yura-forreview/blob/2b3644c8d5ce1ecf1f07c40ba9c76a6839437131/src/IntArrayOfArrays.jack#L39) стоит использовать другой код ошибки, чтобы избежать путаницы
- [Здесь](https://github.com/graphento/Nand2Yura-forreview/blob/2b3644c8d5ce1ecf1f07c40ba9c76a6839437131/src/Main.jack#L147) лишние скобки
- [Здесь](https://github.com/graphento/Nand2Yura-forreview/blob/2b3644c8d5ce1ecf1f07c40ba9c76a6839437131/src/Main.jack#L129) числа не такие как [здесь](https://github.com/graphento/Nand2Yura-forreview/blob/2b3644c8d5ce1ecf1f07c40ba9c76a6839437131/src/Main.jack#L257) и [здесь](https://github.com/graphento/Nand2Yura-forreview/blob/2b3644c8d5ce1ecf1f07c40ba9c76a6839437131/src/Main.jack#L314) 
- [здесь](https://github.com/graphento/Nand2Yura-forreview/blob/2b3644c8d5ce1ecf1f07c40ba9c76a6839437131/src/Main.jack#L200) можно сделать массив и проверять через (tempInt < 37) & (fireTable[tempInt]) где fireTable - массив boolean-ов
- [здесь](https://github.com/graphento/Nand2Yura-forreview/blob/2b3644c8d5ce1ecf1f07c40ba9c76a6839437131/src/Main.jack#L791) и ниже опять же можно использовать массив с числами
- [Здесь и везде где так же](https://github.com/graphento/Nand2Yura-forreview/blob/2b3644c8d5ce1ecf1f07c40ba9c76a6839437131/src/Movement.jack#L18) - зачем строки когда это константы. Просто используйте разные числа

## 💡 Предложения
- Главное меню хотелось бы посодержательнее
- Хотелось бы надпить типа "КРАСАВА ЖЕСТКО" за победу в уровне

## ⭐ Оценка
- **Качество кода**: 3 / 5
- **Увлекательность**: 4.7 / 5
- **Рисовка**: 5 / 5
- **Сложность**: 4.8 / 5
- **В общем**: 4.4 / 5
