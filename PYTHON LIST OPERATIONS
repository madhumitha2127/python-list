def adding(lst):  # To add another list
    elements = input("Enter the elements to be added (should be separated by commas): ")
    new_elements = elements.split(',')
    lst.extend(new_elements)
    print("Updated list:", lst)

def clearing(lst):  # To clear the list
    lst.clear()
    print("List has been cleared:", lst)

def deleting(lst):  # To delete the entire list
    lst.clear()
    print("List has been deleted:", lst)
def viewing(lst):
    #displays the task
    if not lst:
        print("No tasks to repeat")     
    else:
        for i,task in enumerate(lst,start=1):
            print(f"{i}.{task}")
# Initial list
lst = [input("Enter the elements of lst:")for i in range(1,6)]
print("Original list:", lst)
print("""
1 . Add elements
2 . Clear list
3 . Delete list
4 . view list
""")
choice = int(input("Enter your choice: "))
if choice == 1:
    adding(lst)
elif choice == 2:
    clearing(lst)
elif choice == 3:
    deleting(lst_1)
elif choice ==4:
    viewing(lst)    
else:
    print("The choice is invalid")
