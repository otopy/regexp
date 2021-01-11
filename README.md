# REGEXP шпаргалка

##### Содержание  
[Позиция](#position)  
[Символы](#simbol)  
[Квантификаторы](#kvant)  
[Особые символы](#links)

<a name="position"><h2>Позиция</h2></a>

| Выражение       |  Значение |
| ------------- | -----:|
| ^    | начало строки |
| $     | конец строки |

```console
 ^ 
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/001.png)

```console
 $ 
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/002.png)

<a name="simbol"><h2>Символы</h2></a>

| Выражение       |  Значение |
| ------------- | -----:|
| .    | любой сомвол |
| [a]     | любой одиночный символ |
| [a-d]    | любой одиноный символ в интервале |
| [^a]    | не указанный символ |
| [^a-d]     | не указанный символ из интервала |
| \n    | перенос строки |
| \d     | любая единичная цифра |
| \D   | все что угодно кроме цифр |
| \s     | пробел |
| \S   | все кроме пробела |
| \w     | любая буква |
| \W     | все кроме букв |
| \b   | граница слова |
| \B     | все кроме границ слова |
| ()   | группировка символов для послеующей обработки |
| \|     | или, или 1 или 2 |
| \t     | табуляция |

```console
 . 
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/003.png)

```console
 [a] 
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/004.png)

```console
 [a-d] 
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/005.png)

```console
 [^a] 
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/006.png)

```console
 [^a-d] 
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/007.png)

```console
 \n
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/008.png)

```console
 \d
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/009.png)

```console
 \D
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/010.png)

```console
 \s
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/011.png)

```console
 \S
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/012.png)

```console
 \w
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/013.png)

```console
 \W
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/014.png)

```console
 \b
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/015.png)

```console
 \B
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/016.png)

```console
 (a|t)
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/017.png)

```console
 \t
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/018.png)

<a name="kvant"><h2>Квантификаторы</h2></a>

| Выражение       |  Значение |
| ------------- | -----:|
| *    | ноль или более |
| +     | один или более |
| ?    | ноль или один |
| {n}    | n раз |
| {n,m}     | от n до m раз |

```console
 \w*
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/020.png)

```console
 \w+
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/021.png)

```console
 \w?
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/022.png)

```console
 o{2}
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/023.png)

```console
 o{1,5}
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/024.png)

<a name="links"><h2>Особые символы</h2></a>

| Выражение       |  Значение |
| ------------- | -----:|
| \\   | экранирование |

```console
 \(
```
![alt-текст](https://github.com/otopy/regexp/blob/main/img/025.png)


