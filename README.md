L=[1,2,"two",3,4,"four",5]
s=0
for x in L:
    if type(x)==int:
        s=s+x
print("the sum of integers is:",s)
 
Output:
the sum of integers is: 15

Pgm 22:
lst1=eval(input("enter List1:"))
lst2=eval(input("enter List2:"))
lst3=lst1+lst2
print("given List are:",lst1,"and",lst2)
print("The sum of list are :",lst3)
