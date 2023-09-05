# BrokenPhone
# cook your dish her
t = int(input())
for i in range(t):
    x,y = map(int, input().split())
    if(x>y):
        print('NEW PHONE')
    elif(x==y):
        print('ANY')
    else:
        print('REPAIR')
