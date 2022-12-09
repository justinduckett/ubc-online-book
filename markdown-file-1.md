# Markdown File 1

## example cross referencing

Here is a [reference to the markdown file 2](markdown-file-2.md). 

Here is a reference to [](section-label-1).

Here is a reference to [](section-label-2).

Here is a reference to the Pythagorean theorem {eq}`math_1`.

Here is a reference to Auston Matthews {numref}`auston-matthews`.

(section-label-1)=
## example code cell 1

```
print(2 + 2)
```

(section-label-2)=
## example code cell 2

```
print('This is a string')
```

## example math equation 1

```{math}
:label: math_1
x^2 + y^2 = z^2
```


## example math equation 2

```{math}
:label: math_2
E=mc^2
```


## example admonition 1

```{note}
I'm a note!
```

## example admonition 2

```{warning}
I'm a warning!
```

## example image 1

 ```{figure} https://upload.wikimedia.org/wikipedia/commons/c/cd/Auston_Matthews_9.jpg
 ---
 height: 300px
 name: auston-matthews
 ---
 Auston Matthews
 ```


## example image 2

 ```{figure} https://upload.wikimedia.org/wikipedia/commons/0/0d/2016_NHL_All-Star_Game_%2824660206292%29.jpg
 ---
 height: 300px
 name: leafs-banner
 ---
 Toronto Maple Leafs banner
 ```


## example margin content


```{margin} Example margin content
The Toronto Maple Leafs (officially the Toronto Maple Leaf Hockey Club and often referred to as the Leafs) are a professional ice hockey team based in Toronto. 
```

