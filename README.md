## Məsələlər  
©Codera academy
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
4)Verilmiş tərəfli üçbucağın sahəsini tapan kod yazın. 
```
a = int(input())
b = int(input())
c = int(input())
s = (a + b + c) / 2
area = (s*(s-a)*(s-b)*(s-c)) ** 0.5
print("The area of the triangle is:", area)
```
5) Ardı var
	

		
