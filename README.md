A=[]
m=int(input('enter no.of rows:'))
n=int(input('enter no.of columns:'))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    A.append(row) 
print(A)    
B=[]
m=int(input('enter no.of rows'))
n=int(input('enter no.of columns:'))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    B.append(row)
print(B)
result=[[0,0],[0,0]]
for i in range(m):
    for j in range(n):
        result[i][j]=A[i][j]-B[i][j]
print('resultant matrix is:')
for i in range(m):
    for j in range(n):
        print(result[i][j],end=' ')
    print()
    
    enter no.of rows:2
    enter no.of columns:2
    0
    6
    1
    0
    [[0,6],[1,0]]
    enter no.of rows2
    enter no.of columns:2
    6
    8
    1
    3
    [[6,8],[1,3]]
    resultant matrix is:
    -6  -2
    0   -3
