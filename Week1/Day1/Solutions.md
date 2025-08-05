
--------------------------------------------------------------------------------------
#PROBLEM 1

```
PSEUDOCODE:-

function fun(a=40, b=4):
y = 0
if ((b%a == 0) OR (a%b == 0))
y = y + 1
else
y = y + 10
print(y)
print(fun(40, 4))

APPROACH:-
a%b will results in 0 so if statement is executed y=y+1

ANS:-
1
```
--------------------------------------------------------------------------------------

#PROBLEM  2

```
PSEUDOCODE:-
Integer a;
a = 1;
while (a < 5) {
    a = a + 2;
}
Print a;


APPROACH:-
loop will execute 2 times as i is now 5 

ANS:-
2
```

--------------------------------------------------------------------------------------

#PROBLEM 3

```
PSEUDOCODE:-

Integer fun(Integer a, Integer b) {
    if ((a & b) && ((a + b) > 0)) {
        return a + fun(a - 2, b - 2) + b;
    } else {
        return a ^ b;
    }
}

res = fun(8, 8);
print(res);

APPROACH:-
8+8+fun(a-2,b-2)
6+6+fun(a-2,b-2)
4+4+fun(a-2,b-2)
2+2+fun(a-2,b-2)

ANS:-
40

```
--------------------------------------------------------------------------------------
