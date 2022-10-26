# MD tutorial

\# - for level 1 header

\## - for level 2 header

***Semibold + cursive text***

~~Stroked text~~

## How add headers
-------
Add \# or more \# before line

## How add underscore headers
_____
Add --- or ___ 3 or more times


## How add citations
-----



## How add lists
___

Чтобы добавить список, необходимо поставить __*__, __-__ или __+__

```markdown
- одын
- два
- тры
```

* element 
* element
* element

Для добавления нумерованого списка делаем, как в приере:
```markdown
1. first
    1. first
    2. second
2. second
3. third
```

## How add code

Для добавления кода на любом языке надо обрамить код тремя тильдами с обоих сторон. Для подстветски синтаксиса можно указать язык разметки кода, например `python`, `bash` или `markdown`
___
```markdown
```python
a = [1, 2, 3]
print(sum(a) / len(a))```
```


```python
a = [1, 2, 3]
print(sum(a) / len(a))
```
Для размещения кода в тексте можно использовать также тройные амперсаныт или одинарные амперсанты: ```console.log(`mean = ${mean}`)```

___
## images
!Квадратный скобки и круглые для ссылки
----

![Альтернативный текст](https://cdn.spacetelescope.org/archives/images/large/potw2243a.jpg)

Картинка с сылкой делается так:
[![](https://cdn.spacetelescope.org/archives/images/large/potw2243a.jpg)](https://github.com)

___

## HTML and colors
В `markdown` можно использовать `html` теги со стилями.
<p style="background-color: white; color: black;">Текст между <b>html</b> тегами.</p>
