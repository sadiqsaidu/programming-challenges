### Chapter 2 - Making Decisions

[Canadian Calorie Count](https://dmoj.ca/problem/ccc06j1/)

Solution:
```python
burger = int(input())
side = int(input())
drink = int(input())
dessert = int(input())

# for burger
if burger == 1:
    burger = 461
elif burger == 2:
    burger = 431
elif burger == 3:
    burger = 420
else:
    burger = 0

# for side 
if side == 1:
    side = 100
elif side == 2:
    side = 57
elif side == 3:
    side = 70
else:
    side = 0

# for drink
if drink == 1:
    drink = 130
elif drink == 2:
    drink = 160
elif drink == 3:
    drink = 118
else:
    drink = 0

# for dessert
if dessert == 1:
    dessert = 167
elif dessert == 2:
    dessert = 266
elif dessert == 3:
    dessert = 75
else:
    dessert = 0

total = burger + side + drink + dessert 

print(f'Your total Calorie count is {total}.')
```

[Special Day](https://dmoj.ca/problem/ccc15j1/)
```python
month = int(input())
day = int(input())

if (month <= 2) and (day < 18):
    print('Before')
elif (month >=2) and (day > 18):
    print('After')
else:
    print('Special')
```

[C.C. and Cheese-kun](https://dmoj.ca/problem/dmopc16c1p0/)
```python
w = int(input())
c = int(input())

m = ''

if (w == 3) and (c >= 95):
    m = 'absolutely'  
elif (w == 1) and (c <= 50):
    m = 'fairly'
else:
    m = 'very'

print(f'C.C. is {m} satisfied with her pizza.')
```

[Who is in the Middle?](https://dmoj.ca/problem/ccc07j1/)
```python
```