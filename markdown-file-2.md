# Markdown File 2

## example cross referencing

Here is a [reference to the markdown file 1](markdown-file-1.md). 

Here is a reference to the example math equation {eq}`math_3`.

Here is a reference to a picture of Maple Leaf Gardens {numref}`leaf-gardens`.


## example code cell 1

```
for n in range(5):
    print(n)
```

(section-label-2)=
## example code cell 2

```
for i in 'Justin':
    print(i)
```

## example math equation 1

```{math}
:label: math_3
x + y
```


## example math equation 2

```{math}
:label: math_4
x + y = z
```


## example admonition 1

```{tip}
I'm a tip!
```

## example admonition 2

```{danger}
I'm danger!
```

## example image 1

 ```{figure} https://upload.wikimedia.org/wikipedia/commons/3/36/MapleLeafGardens1934.jpg
 ---
 height: 300px
 name: leaf-gardens
 ---
 Maple Leaf Gardens
 ```


## example image 2

 ```{figure} https://upload.wikimedia.org/wikipedia/commons/a/ac/TimHorton_03.jpg
 ---
 height: 300px
 name: tim-horton
 ---
 Tim Horton
 ```


## example margin content


```{margin} The Toronto Maple Leafs:
They compete in the National Hockey League (NHL) as a member of the Atlantic Division in the Eastern Conference. 
```

