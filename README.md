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
3) ardı var
		

		
