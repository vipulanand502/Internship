```python
#Name- Vipul Anand
#Batch- DS2312
```

    enter a number5
    120
    


```python
#11. Write a python program to find the factorial of a number

n= int(input('enter a number'))
fact=1
for i in range(n,0,-1):
    fact=fact*i
print(fact)
```

    enter a number5
    120
    


```python
# using recursion
def factorial(n):
    if n==1 or n==0:
        return 1
    else:
        return n*factorial(n-1)
print(factorial(5))
```

    120
    


```python
#12. Write a python program to find whether a number is prime or composite
a=int(input('enter a  number'))
b=False
if a==1:
    print('the number is prime')
elif a<=0:
    print('enter a number greater than 0')
else:
    for i in range(2,a):
        if a%i==0:
            b=True

if a>1:
    if b:
        print('the number is composite')
    else:
        print('the number is prime')

        
```

    enter a  number8
    the number is composite
    


```python
#13. Write a python program to check whether a given string is palindrome or not
a= input('enter a string')
if a==a[::-1]:
    print('it is a palindrome')
else:
    print('no it is not')

```

    enter a stringnaman
    it is a palindrome
    


```python
#14. Write a Python program to get the third side of right-angled triangle from two given sides
#when we have to find the hypothenis
a= int(input('enter the first side of the triangle'))
b=int(input('enter the second side of the triangle'))
print('the third side(hypothenis of the triangle is)', np.sqrt([(a*a)+(b*b)]))

#when we have to find the sides other than hypothenis

c= int(input('enter the hypothenis'))
d=int(input('enter the one side'))

print('the 3rd side is', np.sqrt([(c*c)-(d*d)]))
```

    enter the first side of the triangle4
    enter the second side of the triangle4
    the third side(hypothenis of the triangle is) [5.65685425]
    enter the hypothenis6
    enter the one side4
    the 3rd side is [4.47213595]
    


```python
#15. Write a python program to print the frequency of each of the characters present in a given string
a= input('enter a string')
b={}
for i in a:
    b[i]= a.count(i)
print('the frequency of each character is the given string is', b)
```

    enter a stringfliprobotechnology
    the frequency of each character is the given string is {'f': 1, 'l': 2, 'i': 1, 'p': 1, 'r': 1, 'o': 4, 'b': 1, 't': 1, 'e': 1, 'c': 1, 'h': 1, 'n': 1, 'g': 1, 'y': 1}
    


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```
