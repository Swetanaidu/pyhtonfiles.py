# pyhtonfiles.py
print('hello world')
print("4+1=", 4+1)
print('4-1=', 4-1)
print('4*1=', 4*1)
print('4/1=', 4/1)
print('4%1=', 4%1)
print('4**1=', 4**1)
grocery_list=['sugar','salt','bread']
print('third item',grocery_list[2])
print(grocery_list[1:3])

other_events=['play','eat','sleep']
to_do_list=[other_events,grocery_list]
print(to_do_list)
del grocery_list[2]
print(to_do_list)

print('what is your name')
print('sweta naidu')
def addNumber(fNum,lNum):
    sumNum = FNum+lNum
    return sumNum
print(addNumber (1,2))
