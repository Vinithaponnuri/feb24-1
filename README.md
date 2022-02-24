PROGRAMME:
x=int(input('enter x: '))
l=[]
for i in range(0,x):
    k=int(input('enter k: '))
    l.append(k)
o=[]
e=[]
for i in l:
    i=int(i)
    if i%2==0:
        e.append(i)
    else:
        if i%2!=0:
           o.append(i)
print(o,' ',e)
OUTPUT:
enter x: 6
enter k: 2
enter k: 3
enter k: 5
enter k: 7
enter k: 8
enter k: 9
[3, 5, 7, 9]   [2, 8]


