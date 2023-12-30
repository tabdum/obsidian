> Все сочетания описаны для VS Code на Windows  
> ↓ / ↑ / ← / → — стрелки вниз, вниз и т.д.  
> ЛКМ / ПКМ / СКМ — левая, правая, средняя кнопки мышки соответственно.

1. **Shift + Tab** — сместить табуляцию на один шаг влево. Если вы пишете на Python, то табуляция или четыре пробела — ваш неизменный спутник. Но мало кто знает, что достаточно поставить курсор в любое место строки, нажать Shift + Tab и вуаля, вся строка смещается влево на «один таб».
    
    ![Shift + Tab](https://habrastorage.org/getpro/habr/upload_files/ff7/159/b4e/ff7159b4e42e3e0077ae4dce96a46180.gif "Shift + Tab")
    
    Shift + Tab
    
2. **Ctrl + /** — закомментировать или раскомментировать строку. VS Code сам разберется, какой язык программирования вы используете, и в начале строки установит или удалит необходимый символ для комментария. Место, где находится курсор на строке неважно.  
    
    ![Ctrl + /](https://habrastorage.org/getpro/habr/upload_files/378/2b8/b19/3782b8b19839beb9b839c52c02324047.gif "Ctrl + /")
    
    Ctrl + /
    
3. **Shift + Del** — удалить строку целиком. Теперь не нужно выделять мышкой всю строку и потом нажимать Backspace. Не нужно выделять всю строку. Правда!  
    
    ![Shift + Del](https://habrastorage.org/getpro/habr/upload_files/79b/348/98c/79b34898c8baf5e0495e5ec88970c5e5.gif "Shift + Del")
    
    Shift + Del
    
4. **Alt + ↑ / ↓** — перемещение строки с курсором вверх или вниз. Просто попробуйте и ощутите, насколько это удобно. Знаете шутку «стоит всего один раз зимой надеть подштанники, и ты уже не можешь остановиться»? Так вот стоит только один раз переместить так строку, и вы уже не сможете по-другому!
    
    ![Alt + ↑ / ↓](https://habrastorage.org/getpro/habr/upload_files/4de/bd6/b4e/4debd6b4ec2c01524edbdc4cf83744c0.gif "Alt + ↑ / ↓")
    
    Alt + ↑ / ↓
    
5. **Shift + Alt + ↓ / ↑** — дублирование строки с курсором вниз. В зависимости от ↓ или ↑ курсор останется на текущей или новой строке. Теперь можно обойтись без Ctrl + C, хотя нет, нельзя =)
    
    ![Alt + ↑ / ↓](https://habrastorage.org/getpro/habr/upload_files/d37/6df/40f/d376df40f2b7d799267c2fd32a75c10e.gif "Alt + ↑ / ↓")
    
    Alt + ↑ / ↓
    
6. **F2** — переименовать переменную. Прошу заметить, что переименовываются все переменные с таким названием только внутри блока, не внутри всего открытого файла. Часто нужно переименовать переменную, которая уже используется в нескольких местах функции, и тут либо вручную расставлять курсор в нужное место, либо поставить курсор на переменную и нажать F2.
    
    ![F2](https://habrastorage.org/getpro/habr/upload_files/a49/9b1/737/a499b1737bbbbbb870857077e151dec9.gif "F2")
    
    F2
    
7. **F12** или **Alt + ЛКМ** на переменной — перейти к переменной или родительскому классу. Часто рассказывают про PyCharm, будто только он умеет проваливаться в родительские классы, чтобы посмотреть, какие его атрибуты мы можем переопределять, наследуясь от него; но так умеет и VS Code.
    
    ![F12 или Alt + ЛКМ](https://habrastorage.org/getpro/habr/upload_files/c44/625/9d5/c446259d57475d8b3ad832045007e7a8.gif "F12 или Alt + ЛКМ")
    
    F12 или Alt + ЛКМ
    
8. **Ctrl + D** — выделяет слово, на котором находится курсор. Следующее нажатие на D (удерживая Ctrl) выделить следующее по порядку вниз идентичное значение. Вот пишете вы функцию, и вам нужно выделить ближайшие значения ‘name’. Легко! Выделить все вхождения слова можно вот так — Ctrl + F2. Радует то, что курсор оказывается в конце каждого выделенного значения и сразу можно редактировать!
    
    ![Ctrl + D](https://habrastorage.org/getpro/habr/upload_files/75a/074/56d/75a07456def328e86361306438c0af05.gif "Ctrl + D")
    
    Ctrl + D
    
9. **Ctrl + L** — выделяет всю строку. Целиком. Теперь копипастить еще проще, не правда ли? =)
    
    ![Ctrl + L](https://habrastorage.org/getpro/habr/upload_files/4df/3e3/99f/4df3e399fbb96aa3f47a9218268f5c8c.gif "Ctrl + L")
    
    Ctrl + L
    
10. **Ctrl + Alt + →** — разделить рабочую область и переместить актуальную вкладку вправо. **Ctrl + Alt + ←** возвращает вкладку назад. Вы не поверите, насколько удобно видеть, например, [_models.py_](http://models.py/) и [_views.py_](http://views.py/) рядом.
    
    ![Ctrl + Alt + →](https://habrastorage.org/getpro/habr/upload_files/231/545/4a7/2315454a7de74313a687a5b8da47a746.gif "Ctrl + Alt + →")
    
    Ctrl + Alt + →
    

А теперь неочевидные, но потрясающие возможности. Меню → Файл → Настройки → Сочетания клавиш (Ctrl + K + Ctrl + S), в строке поиска вводим необходимый параметр и кликаем по результату мышкой, после нажимаем нужные клавиши для установки пользовательской настройки и наслаждаемся. Команды, которые точно стоит попробовать:

`editor.action.jumpToBracket` — переход к парной скобке, у меня установлено на Ctrl + Q. Сначала переход к ближайшей скобке, а следующее нажатие перемещает вас к парной скобке и так далее. Часто нам нужно оказаться либо в начале скобок, либо в конце. А кликать мышкой или стрелками не всегда удобно. Теперь достаточно одного нажатия и вы у нужной скобки.

![Ctrl + Alt + →](https://habrastorage.org/getpro/habr/upload_files/dda/839/8c2/dda8398c28730ecdc15dbd98c06128f2.gif "Ctrl + Alt + →")

Ctrl + Alt + →

`editor.action.selectToBracket` — выделить все внутри ближайших скобок и сами скобки, у меня это Ctrl + Shift + Q. Сколько кликов мышкой, сколько ошибок, выделяя внутри скобок мышкой или Shift + стрелки. А теперь можно просто одним нажатием выделить все точно и быстро.

![editor.action.selectToBracket](https://habrastorage.org/getpro/habr/upload_files/cd3/ebc/05a/cd3ebc05a81487127c47e0ac7de0fcbe.gif "editor.action.selectToBracket")








Во всех сочетаниях используется английская раскладка.

## Открыть настройки пользователя: Ctrl + ,

> ![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-1.gif)

Время от времени заходить в настройки всё же приходится. Этот хоткей ускоряет процесс.

## Показать список горячих клавиш: Ctrl + K   Ctrl + S

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-2.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-2.gif)

## Переключиться между средами разработки: Ctrl + R

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-3.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-3.gif)

Этот хоткей открывает список ваших недавних рабочих пространств. Это быстрый способ переключаться между папками и проектами. Обратите внимание, что при переходе сессия терминала закроется (если она была активна).

## Глобальный перенос по словам: Alt + Z

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-4.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-4.gif)

Простой и удобный способ сразу увидеть все длинные строки без горизонтальной прокрутки.

## Перейти на строку: Ctrl + G

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-5.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-5.gif)

Иногда нужно быстро и часто перескакивать на разные строки в объёмных файлах, а скроллить весь документ неудобно. Этот хоткей как раз для таких целей.

## Перейти к файлу: Ctrl + P

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-6.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-6.gif)

Самый быстрый способ переключения между файлами (особенно если они ещё не открыты).

## Перейти к следующей ошибке или предупреждению: F8

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-7.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-7.gif)

Отладка одной клавишей во плоти. Ещё можно переходить на предыдущую ошибку или предупреждение, используя Shift + F8.

## Переключиться между вкладками: Ctrl + Tab

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-8.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-8.gif)

Быстрый способ переключения между уже открытыми файлами.

## Поместить курсор в конец каждой выделенной строки: Shift + Alt + I

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-9.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-9.gif)

Эта возможность удобна для тех случаев, когда нужно выполнить идентичные операции в последовательных строках.

## Выделить текущую строку: Ctrl + L

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-10.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-10.gif)

Хоткей используется для быстрого выделения всей строки, на которой установлен курсор.

## Выделить все вхождения текущего выделения: Ctrl + Shift + L

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-11.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-11.gif)

Хоткей сэкономит время, потому что теперь не нужно использовать Ctrl + D во всём файле.

## Выделить все вхождения текущего слова: Ctrl + F2

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-12.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-12.gif)

Теперь вам не нужно даже выделять конкретное слово — просто поместите на него курсор, нажмите хоткей и одновременно правьте все его вхождения.

## Подсказки по параметрам: Ctrl + Shift + Space

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-13.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-13.gif)

Если вы вдруг забыли порядок параметров, а прерываться на документацию нет желания.

## Форматировать документ: Shift + Alt + F

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-14.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-14.gif)

Специально для тех, кому лень постоянно придерживаться правил форматирования.

## Форматировать выделенную область: Ctrl + K   Ctrl + F

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-15.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-15.gif)

Такой же, как и предыдущий хоткей, но форматируется не весь документ, а только выделенная область.

## Перейти к определению: F12

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-16.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-16.gif)

Быстрый способ перейти к определению функции или переменной.

## Показать определение: Alt + F12

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-17.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-17.gif)

Сочетание клавиш похоже на прошлое, но в этом случае курсор никуда не перемещается.

## Переименовать переменную: F2

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-18.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-18.gif)

Незаменимый хоткей для рефакторинга кода.

## Обрезать пробелы в конце: Ctrl + K   Ctrl + X

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-19.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-19.gif)

Чтобы вручную не удалять лишние пробелы в конце строки. Работает при выделении нескольких строк.

## Отобразить открытый файл в проводнике: Ctrl + K   R

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-20.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-20.gif)

Если вам нужно что-либо сделать с открытым файлом, поиск которого может занять много времени.

## Замена в файлах: Ctrl + Shift + H

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-21.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-21.gif)

Если одного файла вам не достаточно.

## Превью Markdown-файла: Ctrl + K   V

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-22.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-22.gif)

Открыть предпросмотр Markdown-файла.

## Включить Zen Mode: Ctrl + K   Z

> [![](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-23.gif)](https://media.tproger.ru/uploads/2020/01/VS-Hotkey-23.gif)