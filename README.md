# Start-to-Data-Science

## Реализованы следующие декораторы, находящиеся в папке decorators:
- benchmark, выводящий время, которое заняло выполнение декорируемой функции
- logging, который выводит параметры с которыми была вызвана функция
- counter, считающий и выводящий количество вызовов декорируемой функции
- memo, запоминающий результаты исполнения функции func, чьи аргументы *args должны быть хешируемыми.

## Выполнено сравнение времени выполнения рекурсивной реализации расчета чисел Фибоначчи без декоратора и с ним, и сделан следующий вывод - скорость выполнения функции с декоратором "memo" значительна выше, чем без него.
