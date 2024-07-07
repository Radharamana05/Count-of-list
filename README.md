# Count-of-list
# python programming using count of numbers in list.
list=[1,2,3,4,5,6,5,4,3,2,1]
search=int(input("enter the number:"))
i=0
c=0
while (i<len(list)):
    if search==list[i]:
        print(search,"element is found at",i,"location")
        c+=1
    i+=1
print(c)

# output
enter the number:3
3 element is found at 2 location
3 element is found at 8 location
2
