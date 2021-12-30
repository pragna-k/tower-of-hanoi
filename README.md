# tower-of-hanoi
def tower(n,source,des,aux):
    if n==1:
     print('move disk,from'source,'to'des)
else:
    tower(n-1,source,aux,des)
    print("move disk",n,'from'source "to",des)
tower(n-1,aux,des,source)
n=int(input(""))
tower(n,'a','c','b')
