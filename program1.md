```python
import numpy as np
list=[1,2,3]
a=np.array(list)
print(type(a))
print(a)
```

    <class 'numpy.ndarray'>
    [1 2 3]
    


```python
a="vandana"
a[0]
```




    'v'




```python
a[-1]
```




    'a'




```python
a[0:2]
```




    'va'




```python
a[0:2]="ba"
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-5-bf88a1807ca7> in <module>
    ----> 1 a[0:2]="ba"
    

    TypeError: 'str' object does not support item assignment



```python
a[0:2:]
```




    'va'




```python
a[0:5:2]
```




    'vna'




```python
a[-1:-3]
```




    ''




```python
a[0:-1]
```




    'vandan'




```python
a[-3:-1]
```




    'an'




```python
print(a)
```

    vandana
    


```python
b=[1,2,3,4,5]
print(type(b))
print(b)
```

    <class 'list'>
    [1, 2, 3, 4, 5]
    


```python
c=["ujjwal","sonu",1,2,3]
print(type(c))
print(c)
c[0:3]
```

    <class 'list'>
    ['ujjwal', 'sonu', 1, 2, 3]
    




    ['ujjwal', 'sonu', 1]




```python
d=["ujjwal","sonu",1,2,3,['b']]
print(d)
```

    ['ujjwal', 'sonu', 1, 2, 3, ['b']]
    


```python
d(3)
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-15-291104d645c2> in <module>
    ----> 1 d(3)
    

    TypeError: 'list' object is not callable



```python
d[3]
```




    2




```python
d=["ujjwal","sonu",1,2,3,['b','c','d','e']]
d[5]
d[5][0:2]
d[3]=0.1
print(d)
d[5][2]
d[0]=2
print(d)
```

    ['ujjwal', 'sonu', 1, 0.1, 3, ['b', 'c', 'd', 'e']]
    [2, 'sonu', 1, 0.1, 3, ['b', 'c', 'd', 'e']]
    


```python
d=["ujjwal","sonu",1,2,3,['b','c','d','e']]
d.append(12)
print(d)
```

    ['ujjwal', 'sonu', 1, 2, 3, ['b', 'c', 'd', 'e'], 12]
    


```python
t=(1,2,3,'a',['c','d'])
print(t)
```

    (1, 2, 3, 'a', ['c', 'd'])
    


```python
s={1,2,3,1}
s
```




    {1, 2, 3}




```python
s.update({4,5,6,10})
s
```




    {1, 2, 3, 4, 5, 6, 10}




```python
s={1, 2, 3, 4, 5, 6, 10}

s.remove(4)
s
```




    {1, 2, 3, 5, 6, 10}




```python
dict={1:3,"yellow":"ball","orange":"fruit"}
dict.keys()
```




    dict_keys([1, 'yellow', 'orange'])




```python
a="vandana"
len(a)
```




    7




```python
len(s)
```




    6




```python
for l in s:
    print(l)
```

    1
    2
    3
    5
    6
    10
    


```python
import numpy as np
list=[1,2,3]
a=np.array(list)
print(type(a))
print(a)
a.shape
```

    <class 'numpy.ndarray'>
    [1 2 3]
    




    (3,)




```python
import numpy as np
b=([[1,2 ,3],[4,5,6]])
b=np.array(b)
b.shape
```




    (2, 3)




```python
c=[[1,2,3],[4,5]]
c=np.array(c)
c
c.shape
```

    <ipython-input-28-e08c5c2e0d59>:2: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
      c=np.array(c)
    




    (2,)




```python
print(c)
```

    [list([1, 2, 3]) list([4, 5])]
    


```python

```
