# Group Members

## Kenneth Ruto      SCT211-0029/2021
## Lewis Munene      SCT211-0014/2021
## Vincent Mutethia  SCT211-0017/2019 

<br> <br>

# Python Implememntation

```
def f(x) :
    return x**3 -2*x -5
a = 2
b = 3
tolerance = 1e-6
x0 = a 
max_iterations = 100
for  i in range(max_iterations) :
    print(f"Step {i+1} ----> a = {a:.6f} , b={b:.6f} , c={b:.6f} ")
    c = (a+b)/2
    if abs(f(c))<tolerance:
        print(f"\nBisection Root  found at x={c:.6f}")
        break
    elif f(c) * f(a) <0 :
        b= c
    else:
        a = c 
```




