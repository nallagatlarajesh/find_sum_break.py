#find positive numbers sum till we eneterd negative number

entry=0
sum1=0
print("enetr numberws to find their sum ,negative numbet ends loop:")
list=[]                                   #optional (6,12,13) lines
while True:
    entry=int(input())
    if entry<0:
        break
    sum1+=entry
    list.append(entry)                    #optional (6,12,13 ) lines
print(list)                               #optinal(6,12,13) lines
print("sum=",sum1)
