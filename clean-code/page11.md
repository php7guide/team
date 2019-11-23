11. Именование переменных
==============

### Контрольный список

#### Общие принципы именования переменных 

+ Описывает ли имя представляемую переменной сущность полно и точно? 
+ Характеризует ли имя проблему реального мира, а не ее решение на языке программирования? 
+ Имеет  ли  имя  длину,  достаточную  для  того,  чтобы  над  ним  не  нужно  было ломать  голову?
+ Спецификаторы  вычисляемых  значений  находятся  в  конце  имен?
+ Используются  ли  в  именах  спецификаторы  Count  или  Index  вместо  Num?

#### Именование  конкретных  видов  данных

+ Выразительные  ли  имена  присвоены  индексам  циклов  (более  ясные,  чем  i,j и k, если цикл содержит более одной-двух строк или является вложенным)?
+ Всем  ли  «временным»  переменным  присвоены  выразительные  имена?
+ Можно  ли  по  именам  булевых  переменных  понять,  какой  смысл  имеют  значения  «истина»  и  «ложь»?
+ Включают  ли  имена  элементов  перечислений  префикс  или  суффикс,  определяющий принадлежность элемента к перечислению — например, префикс Color_  в  случае  элементов  Color_Red, Color_Green, Color_Blue  и  т.  д.?
+ Именованные  константы  названы  в  соответствии  с  представляемыми  абстрактными  сущностями,  а  не  конкретными  числами?

#### Конвенции  именования

+ Проводит  ли  конвенция  различие  между  локальными  данными,  данными класса  и  глобальными  данными?
+ Проводит  ли  конвенция  различие  между  именами  типов,  именованных  констант,  перечислений  и  переменных?
+ Идентифицировали ли вы исключительно входные параметры методов, если язык  не  навязывает  их  идентификацию?
+ Постарались  ли  вы  сделать  конвенцию  как  можно  более  совместимой  со стандартными  конвенциями  конкретного  языка?
+ Способствует  ли  форматирование  имен  удобству  их  чтения?

#### Короткие  имена

+ Стараетесь  ли  вы  не  сокращать  имена  без  необходимости?
+ Избегаете  ли  вы  сокращения  имен  только  на  одну  букву?
+ Все  ли  слова  вы  сокращаете  согласованно?
+ Легко  ли  произнести  выбранные  имена?
+ Избегаете ли вы имен, допускающих неверное прочтение или произношение?
+ Документируете ли вы короткие имена при помощи таблиц преобразования?

#### Распространенные  проблемы  именования.  Избежали  ли  вы... 

+ ...имен,  которые  вводят  в  заблуждение?
+ ...имен  с  похожими  значениями?
+ ...имен,  различающихся  только  одним  или  двумя  символами?
+ ...имен,  имеющих  похожее  звучание?
+ ...имен,  включающих  цифры?
+ ...имен,  намеренно  написанных  с  ошибками  с  целью  сокращения?
+ ...имен,  при  написании  которых  люди  часто  допускают  ошибки?
+ ...имен,  конфликтующих  с  именами  методов  из  стандартных  библиотек  или предопределенными  именами  переменных?
+ ...совершенно  произвольных  имен?
+ ...символов,  которые  можно  спутать  с  другими  символами?

### Ключевые моменты

+ Выбор  хороших  имен  переменных  —  одно  из  главных  условий  понятности программы. С отдельными типами переменных — например, с индексами циклов  и  переменными  статуса  —  связаны  свои  принципы  именования.
+ Имена  должны  быть  максимально  конкретны.  Имена,  которые  из-за  невыразительности или обобщенности можно использовать более чем с одной целью, обычно  являются  плохими.
+ Конвенции именования позволяют провести различие между локальными данными,  данными  класса  и  глобальными  данными,  а  также  между  именами  типов,  именованных  констант,  перечислений  и  переменных.
+ Над каким бы проектом вы ни работали, вам следует принять конвенцию именования  переменных.  При  выборе  типа  конвенции  следует  учитывать  размер программы  и  число  работающих  над  ней  программистов.
+ Современные  языки  программирования  позволяют  отказаться  от  сокращения имен. Если вы все#таки сокращаете имена, регистрируйте аббревиатуры в словаре  проекта  или  используйте  стандартизированные  префиксы.
+ За  чтением  кода  программисты  проводят  гораздо  больше  времени,  чем  за  его написанием. Выбирайте имена так, чтобы они облегчали чтение кода, пусть даже за  счет  удобства  его  написания.