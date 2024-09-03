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
