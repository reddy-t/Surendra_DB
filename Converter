c=input('1: B to D\n2: D to B\n')

def btod(n):
    f=reversed(str(n))
    out=0
    count=0
    for j in f:
        out=out+int(j)*2**count
        count+=1
    print(out)
    
def dtob(n):
    x=[]
    while n>=1:
        r=n%2
        x.append(str(r))
        n=n//2
    print(''.join(list(reversed(x))))

if c=='1':
    n=int(input('Enter Number: '))
    btod(n)
elif c=='2':
    n=int(input('Enter Number: '))
    dtob(n)
else:
    print('Wrong Choice')
        
