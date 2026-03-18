# Pyi-For-All
This are the PYTHON code which i shortly called as Pyi (Python) which any beginner can use for learning basic of python . I made easy to understand problem and syntax which will help beginner to learn python .If you learn this code this will help in understanding basic concept  of python language .

[1]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Print Hello World.

CODE NO :- 1

    print("Hello World")

OUTPUT :-
Hello World

[2]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Add two numbers.

CODE NO :- 2

a = 5
b = 10
print(a + b)

OUTPUT :-
15

[3]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Check even or odd.

CODE NO :- 3

n = 7
if n % 2 == 0:
print("Even")
else:
print("Odd")

OUTPUT :-
Odd

[4]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Swap two numbers.

CODE NO :- 4

a = 5
b = 10
a, b = b, a
print(a, b)

OUTPUT :-
10 5

[5]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Find largest of two numbers.

CODE NO :- 5

a = 10
b = 20
print(max(a, b))

OUTPUT :-
20

[6]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Find largest of three numbers.

CODE NO :- 6

a, b, c = 10, 25, 15
print(max(a, b, c))

OUTPUT :-
25

[7]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Check positive, negative or zero.

CODE NO :- 7

n = -5
if n > 0:
print("Positive")
elif n == 0:
print("Zero")
else:
print("Negative")

OUTPUT :-
Negative

[8]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Sum of first n numbers.

CODE NO :- 8

n = 5
print(sum(range(1, n+1)))

OUTPUT :-
15

[9]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Multiplication table.

CODE NO :- 9

n = 5
for i in range(1, 11):
print(n * i)

OUTPUT :-
5
10
15
20
25
30
35
40
45
50

[10]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Find factorial.

CODE NO :- 10

n = 5
fact = 1
for i in range(1, n+1):
fact *= i
print(fact)

OUTPUT :-
120

[11]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Reverse a number.

CODE NO :- 11

n = 123
rev = 0
while n > 0:
rev = rev * 10 + n % 10
n //= 10
print(rev)

OUTPUT :-
321

[12]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Check palindrome number.

CODE NO :- 12

n = 121
print(str(n) == str(n)[::-1])

OUTPUT :-
True

[13]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Count digits.

CODE NO :- 13

n = 12345
print(len(str(n)))

OUTPUT :-
5

[14]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Sum of digits.

CODE NO :- 14

n = 123
s = 0
while n:
s += n % 10
n //= 10
print(s)

OUTPUT :-
6

[15]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Armstrong number.

CODE NO :- 15

n = 153
temp = n
s = 0
while temp:
d = temp % 10
s += d**3
temp //= 10
print(s == n)

OUTPUT :-
True

[16]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Fibonacci series.

CODE NO :- 16

a, b = 0, 1
for _ in range(5):
print(a)
a, b = b, a + b

OUTPUT :-
0
1
1
2
3

[17]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Check prime number.

CODE NO :- 17

n = 7
for i in range(2, n):
if n % i == 0:
print("Not Prime")
break
else:
print("Prime")

OUTPUT :-
Prime

[18]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Print prime numbers in range.

CODE NO :- 18

for n in range(2, 20):
for i in range(2, n):
if n % i == 0:
break
else:
print(n)

OUTPUT :-
2
3
5
7
11
13
17
19

[19]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Find GCD.

CODE NO :- 19

import math
print(math.gcd(12, 18))

OUTPUT :-
6

[20]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Find LCM.

CODE NO :- 20

import math
a, b = 12, 18
print((a*b)//math.gcd(a,b))

OUTPUT :-
36

[21]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Reverse string.

CODE NO :- 21

s = "hello"
print(s[::-1])

OUTPUT :-
olleh

[22]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Palindrome string.

CODE NO :- 22

s = "madam"
print(s == s[::-1])

OUTPUT :-
True

[23]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Count vowels.

CODE NO :- 23

s = "hello"
count = sum(1 for i in s if i in "aeiou")
print(count)

OUTPUT :-
2

[24]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Remove spaces.

CODE NO :- 24

s = "hello world"
print(s.replace(" ", ""))

OUTPUT :-
helloworld

[25]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Convert to uppercase.

CODE NO :- 25

print("hello".upper())

OUTPUT :-
HELLO

[26]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Convert to lowercase.

CODE NO :- 26

print("HELLO".lower())

OUTPUT :-
hello

[27]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Find string length.

CODE NO :- 27

print(len("python"))

OUTPUT :-
6

[28]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- First character of string.

CODE NO :- 28

s = "Ved"
print(s[0])

OUTPUT :-
V

[29]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Last character of string.

CODE NO :- 29

s = "Ved"
print(s[-1])

OUTPUT :-
d

[30]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Concatenate strings.

CODE NO :- 30

print("Ved" + " Pillewar")

OUTPUT :-
Ved Pillewar

[31]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Create list.

CODE NO :- 31

l = [1,2,3]
print(l)

OUTPUT :-
[1, 2, 3]

[32]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Sum of list.

CODE NO :- 32

l = [1,2,3]
print(sum(l))

OUTPUT :-
6

[33]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Maximum in list.

CODE NO :- 33

l = [1,5,2]
print(max(l))

OUTPUT :-
5

[34]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Minimum in list.

CODE NO :- 34

l = [1,5,2]
print(min(l))

OUTPUT :-
1

[35]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Sort list.

CODE NO :- 35

l = [3,1,2]
l.sort()
print(l)

OUTPUT :-
[1, 2, 3]

[36]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Reverse list.

CODE NO :- 36

l = [1,2,3]
print(l[::-1])

OUTPUT :-
[3, 2, 1]

[37]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Remove element from list.

CODE NO :- 37

l = [1,2,3]
l.remove(2)
print(l)

OUTPUT :-
[1, 3]

[38]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Append element to list.

CODE NO :- 38

l = [1,2]
l.append(3)
print(l)

OUTPUT :-
[1, 2, 3]

[39]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Count occurrences.

CODE NO :- 39

l = [1,2,2,3]
print(l.count(2))

OUTPUT :-
2

[40]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Remove duplicates.

CODE NO :- 40

l = [1,2,2,3]
print(list(set(l)))

OUTPUT :-
[1, 2, 3]

[41]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Create dictionary.

CODE NO :- 41

d = {"a":1, "b":2}
print(d)

OUTPUT :-
{'a': 1, 'b': 2}

[42]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Access dictionary value.

CODE NO :- 42

print({"a":1}["a"])

OUTPUT :-
1

[43]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Update dictionary.

CODE NO :- 43

d = {"a":1}
d["b"] = 2
print(d)

OUTPUT :-
{'a': 1, 'b': 2}

[44]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Get dictionary keys.

CODE NO :- 44

print({"a":1}.keys())

OUTPUT :-
dict_keys(['a'])

[45]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Get dictionary values.

CODE NO :- 45

print({"a":1}.values())

OUTPUT :-
dict_values([1])

[46]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Create set.

CODE NO :- 46

s = {1,2,3}
print(s)

OUTPUT :-
{1, 2, 3}

[47]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Add element to set.

CODE NO :- 47

s = {1,2}
s.add(3)
print(s)

OUTPUT :-
{1, 2, 3}

[48]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Remove element from set.

CODE NO :- 48

s = {1,2,3}
s.remove(2)
print(s)

OUTPUT :-
{1, 3}

[49]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Create tuple.

CODE NO :- 49

t = (1,2,3)
print(t)

OUTPUT :-
(1, 2, 3)

[50]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Length of tuple.

CODE NO :- 50

print(len((1,2,3)))

OUTPUT :-
3

[51]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Simple interest.

CODE NO :- 51

p, r, t = 1000, 5, 2
print((p*r*t)/100)

OUTPUT :-
100.0

[52]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Area of circle.

CODE NO :- 52

r = 5
print(3.14*r*r)

OUTPUT :-
78.5

[53]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Area of rectangle.

CODE NO :- 53

l, b = 5, 10
print(l*b)

OUTPUT :-
50

[54]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Celsius to Fahrenheit.

CODE NO :- 54

c = 25
print((c*9/5)+32)

OUTPUT :-
77.0

[55]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Fahrenheit to Celsius.

CODE NO :- 55

f = 77
print((f-32)*5/9)

OUTPUT :-
25.0

[56]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Check leap year.

CODE NO :- 56

year = 2024
print(year%4==0 and (year%100!=0 or year%400==0))

OUTPUT :-
True

[57]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Count even numbers in list.

CODE NO :- 57

l = [1,2,3,4]
print(sum(1 for i in l if i%2==0))

OUTPUT :-
2

[58]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Sum list using loop.

CODE NO :- 58

l = [1,2,3]
s = 0
for i in l:
s += i
print(s)

OUTPUT :-
6

[59]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Find element in list.

CODE NO :- 59

l = [1,2,3]
print(2 in l)

OUTPUT :-
True

[60]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Simple calculator.

CODE NO :- 60

a, b = 5, 2
print(a+b, a-b, a*b, a/b)

OUTPUT :-
7 3 10 2.5
