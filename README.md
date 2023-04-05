# Demo1
Fact

def func(x):
    if x ==1:
        return 1
    else:
        return (x*func(x-1))
    
n=int(input())
print("The function of",n,"is",func(n))
