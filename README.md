#exercise 1

merged list of tuples
fruits=["Apple","Banana","Strawberry","Grapes","Orange"]
colors=["Red","Yellow","Redish","Purple","Orange"]
zip_list=list(zip(fruits,colors))
print(zip_list)


#Exercise 2

lst1=["Energy", "Agriculture", "Industry", "Technology", "Finance", "Forestry", "Transport"]
rng1=list(range(1,8))
lst=zip(lst1, rng1)
print(lst)


#Exercise 3

list1=[12,3,45,6,78,9,4,13]
print(sorted(list1))


#Exercise 4

list4=[1,4,6,8,9,7,6,5,43]
odds=list(filter(lambda n: n%2!=0 , list4))
print(odds)
