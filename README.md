# neeraj-saini
k=5
if n > 0:              
    for i in range(n):
        for s in range (n - i) :    
            print(" ", end="")
        for j in range((i * 2) - 1):
            print(k-(i-1), end="")
        print()
    for i in range(n, 0, -1):
        for s in range (n - i) :
            print(" ", end="")
        for j in range((i * 2) - 1):
            print(k-(i-1), end="")
        print()