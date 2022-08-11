# programming-challenges
## Chapter 1 - Getting Started 

Problem #1: [Not a Wall of Text](https://dmoj.ca/problem/dmopc15c7p2)

Solution:
```python
line = input()
total_words = line.count(' ') + 1
print(total_words)
```
Problem #2: [Core Drill](https://dmoj.ca/problem/dmopc14c5p1)

Solution:
```python
PI = 3.141592653589793

radius = int(input())
height = int(input())

volume = (PI * radius ** 2 * height) / 3

print(volume)
```
Problem #3: [A Spooky Season](https://dmoj.ca/problem/wc16c1j1)

Solution:
```python
prompt = int(input())

n = 'o' * prompt

word = 'sp' + n + 'ky'

print(word)
```
Problem #4 [A New Hope](https://dmoj.ca/problem/wc15c2j1/)

Solution:
```python
prompt = int(input())

n = 'far, ' * (prompt - 1)

Phrase = f'A long time ago in a galaxy {n}far away...'

print(Phrase)
```
