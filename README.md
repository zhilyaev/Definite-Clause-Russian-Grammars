# Definite-Clause-Russian-Grammars
Синтаксический разбор предложений русского языка. С помощью Prolog.

## Цель работы 
Средствами [DCG](http://www.pathwayslms.com/swipltuts/dcg/) в среде SWI-Prolog разработайте программу, выполняющую синтаксический разбор предложений русского языка. Результат работы программы должен быть представлен перечнем членов предложения с указанием для каждого слова предложения, какой частью речи оно является. 

## Пример
```
?-  s([ты, пишешь, ',', но, я, пишу, '.'], []). 
Начало Разбора 
[Местоимение = подлежащее, Глагол = сказуемое, Местоимение = подлежащее, Глагол = сказуемое,] 
Конец Разбора 
true . 
```


## Run
0. Install swpl
1. swipl main.pl
2. sentence(X,[]).
