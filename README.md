## Məsələlər  

1) Verilmiş natural ədədin ikilik say sistemindəki yazılışındalı birlərin (1) sayını tapın.

 ```
   n=int(input())
   s=0
   while n>0:
         a=n%2
         if a ==1:
             s=s+1
         n=n//2
   print(s)
```
2) Mağazada n sayda gül var. Heç bir gülün artıq qalmaması şərti ilə neçə fərqli buket qurmaq olar. (bir buketdə azı 2 gül olmalıdır) 

1.
 ```
 n = int(input())
 s=0
for i in range(2,n+1):
	if n%i==0:
		s = s + 1
print(s)
```

2.
 ```
n = int(input())
k = 0
i = 2
while i <=n//2:
		if n%i==0:
			k = k + 1
		i = i + 1
k= k + 1
print(k)
```
3)Verilmiş ədədin bütün rəqəmlərinin eyni olub olmadığını müəyyən edin.
1.
```
 n = int(input())
a =0
b = 0
s = n%10
while n>0:
	k = n %10
	n =n //10
	b = b + 1
	if s == k:
		a = a + 1
if a == b:
		print("yes")
else:
		print("no")
```
2.
```
n=int(input()) 
n=str(n) 
İf len(n) == n.count(n[0]):
     print("yes") 
else:
      print("no")
```
4) Verilmiş tərəfli üçbucağın sahəsini tapan kod yazın. 
```
a = int(input())
b = int(input())
c = int(input())
s = (a + b + c) / 2
area = (s*(s-a)*(s-b)*(s-c)) ** 0.5
print(area)
```
5) Ədədin faktorialını tapın. 
 ```
def fact(n):
    if n==1:
        f=1
    else:
        f = n * fact(n-1)
    return f
num = int(input())
s = fact(num)
print(s)
```
6) Ədədin 5'in bölünəni olub olmadığını tapın.
```
n = int(input())
if n%5==0:
    print("T")
else:
    print("F")
```
7) Ədədin həm 5'in həm 7'nin bölünəni olub olmadığını tapın
```
n = int(input())
if n%5==0 and n%7==0:
    print("T" )
else:
    print("F")
```
8) Ədədin rəqəmlərini tərsinə çevirən kodu yazın.
```
n = int(input())
r = 0
while n!=0:
    k = n%10
    r= (r*10)+k
    n = n//10
print(r)
```
9) 100 200 arası rəqəmləri cəmi cüt olan ədədləri tapın.
```
for i in range(100,200):
    n = i
    s = 0
    while n!=0:
        d= n%10
        s = s + d
        n = n//10
    if(s%2==0):
        print(i)
```
10) Verilmiş a = [4, 3, 9, 7, 16] listində tam ədədin kvadratı olan ədədləri tapın. (Dim 2023)
```

a = [4, 3, 9, 7, 16]
for i in a:
	k = i **0.5
	if int(k)== k: 
		print(i, "tam ədədin kvadratıdır")
	else:
		print(i, "deyil")
```
11) Verilmiş cümlədə a hərflərini b'yə, b hərflərini a'ya çevirən kod yazın. (Dim 2023)
```
n = input()
n = list(n)
for i in range(0, len(n)):
		if n[i] == "a":
				n[i] = "b"
		elif n[i] == "b":
			n[i] = "a"
print("".join(n))
```
12) birinci sətirdə bir "a" ikinci sətirdə iki "b" üçüncü sətirdə üç "c" çap edən proqram yazın
```
for i in range(1,4):
	if i ==1:
		print("a"*i)
	elif i == 2:
		print("b"*i)
	else:
		print("c"*i)
```
13)
