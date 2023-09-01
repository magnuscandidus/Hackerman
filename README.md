# Hackerman
# cook your dish here
prime = [1,2,3,5,7,11]
for i in range (int(input())):
    x,y = map(int,input().split())
    a = x+y
    if(a in prime ):
        print("Alice")
    else:
        print("Bob")
