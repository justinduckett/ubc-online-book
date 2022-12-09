# Markdown File 1

## example cross referencing

Here is a [reference to the intro](intro.md). 

Here is a reference to [](section-label-1).

Here is a reference to [](section-label-2).

Here is a reference to the Pythagorean theorem {eq}`math_1`.

Here is a reference to Auston Matthews {numref}`auston-matthews`.

(section-label-1)=
## example code cell 1

```{code-cell}
print(2 + 2)
```

(section-label-2)=
## example code cell 2

```{code-cell}
print('This is a string')
```

## example math equation 1

```{math}
:label: math_1
\(x^2 + y^2 = z^2\)
```


## example math equation 2

```{math}
:label: math_2
\[E=mc^2\]
```


## example admonition 1

```{note}
I'm a note!
```

## example admonition 2

```{warning}
I'm a warning!
```

```{tip}
I'm a tip!
```

```{danger}
I'm danger!
```

## example image 1

 ```{figure} https://en.wikipedia.org/wiki/Toronto_Maple_Leafs#/media/File:Auston_Matthews_9.jpg
 ---
 height: 300px
 name: auston-matthews
 ---
 Auston Matthews
 ```


## example image 2

 ```{figure} https://en.wikipedia.org/wiki/Toronto_Maple_Leafs#/media/File:Toronto_Maple_Leafs_2016_logo.svg
 ---
 height: 300px
 name: leafs-logo
 ---
 Toronto Maple Leafs logo
 ```


## example margin content


```{margin} Example margin content
The Toronto Maple Leafs (officially the Toronto Maple Leaf Hockey Club and often referred to as the Leafs) are a professional ice hockey team based in Toronto. 
```

