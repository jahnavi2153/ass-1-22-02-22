# ass-1-22-02-22
n=int(input())
for i in range(n):
    for j in range(n-i-1):
        print(' ',end=' ')
    for k in range(2*i+1):
        print('*',end=' ')
        print('*',end=' ')
    print('\n')
for i in range(n-1):
    for j in range(i+1):
        print(' ',end=' ')
    for k in range(2*(n-i-1)-1):
        print('*',end=' ')
    print('\n')
    
 output:
 3
          *
        * * *
      * * * * *
        * * *
          *
    
