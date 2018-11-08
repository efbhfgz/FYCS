# FYCS
Foss 
def evnum(list):
    list1=[]
    for i in list:
        if i%2==0:
            list1.append(i)
    return list1


l=[1,2,3,4,5,6]
print(evnum(l))

S = [x**2 for x in range(10)]
V = [2**i for i in range(13)]
M = [x for x in S if x % 2 == 0]
print(S);print(V); print(M)


            



