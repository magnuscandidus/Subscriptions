# Subscriptions
# cook your dish here
for i in range (int(input())):
    x,y = map(int,input().split())
    if(x%6==0):
        print((x//6)*y)
    else:
        print(((x//6)+1)*y)
