String method
=============
````ruby
s = input().split()
for i in range (len(s)):
    print(s[i][0], end = ".")
````
````ruby
s = input().split('.')  
for i in s:
    if int(i) < 0 or int(i) > 255: 
        print('NO')  
        break  
else:
    print('YES')
````
````ruby
s = input().split()  
c = 0  
for i in range(len(s)):
    for j in range(i + 1, len(s)):
        if s[j] == s[i]:  
            c += 1  
print(c)
````
