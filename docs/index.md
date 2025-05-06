# Homepage

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Code Annotation Exapmles

### Codeblocks

Some `code` goes here.

### Plain codeblock

A plain codeblock:

```
Some code here
    def myfunction() // some comment
```

#### Code for a specific language

Some more code with the `py` at the start:

``` py
def my_function(fname):
  print(fname + " Refsnes") # some python comment 
  
my_function("Emil")
my_function("Tobias")
my_function("Linus")
```

#### With a title 
```python title="bubble_sort.py"
def bubble_sort(arr):  
    for n in range(len(arr) - 1, 0, -1):
        swapped = False  
        for i in range(n):
            if arr[i] > arr[i + 1]:
                arr[i], arr[i + 1] = arr[i + 1], arr[i]
                swapped = True
        if not swapped:
            break
```

#### With line numbers
```python linenums="1"
def bubble_sort(arr):  
    for n in range(len(arr) - 1, 0, -1):
        swapped = False  
        for i in range(n):
            if arr[i] > arr[i + 1]:
                arr[i], arr[i + 1] = arr[i + 1], arr[i]
                swapped = True
        if not swapped:
            break
```

#### Highliting lines
```python linenums="1", hl_lines="2 4"
def bubble_sort(arr):  
    for n in range(len(arr) - 1, 0, -1):
        swapped = False  
        for i in range(n):
            if arr[i] > arr[i + 1]:
                arr[i], arr[i + 1] = arr[i + 1], arr[i]
                swapped = True
        if not swapped:
            break
```

## Icons and Emojs

:smile:
:fontawesome-regular-face-laugh-wink:
:fontawesome-brands-twitter:{ .twitter }
:octicons-heart-fill-24:{ .heart }