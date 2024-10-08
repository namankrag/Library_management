# Library_management

'''
class Library:
    dic={}

    def __init__(self,no_of_book,book):
        self.no_of_book=no_of_book
        self.book=book
        self.dic.update({self.book:self.no_of_book})
        
    def show_book(self):
        print("List of Books are : ")
        for key in self.dic.keys():
            print(key)
    
    def number(self):
        for key,value in self.dic.items():
            print(f"There are {value} books of {key}.")

t=0
while True:
    print("---------- M E N U -----------")
    print("1. Print all books ")
    print("2. Add a book ")
    print("3. Get number of book ")
    print("4. Exit")
    print("-------------------------------")
    ch=int(input("Enter your choice : "))
    print("-------------------------------")

    if t==0 or ch==2:
        book=input("Enter name of the book : ")
        no_book=int(input("Enter the number of book : "))
        a=Library(no_book,book)
        t=1

    elif ch==1:
        a.show_book()
    
    elif ch==3:
        a.number()
    
    elif ch==4:
        print("Thanks for using.")
        break
    
    else:
        print("Try again!!")
    
    print("-------------------------------")
'''
