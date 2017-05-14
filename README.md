# BasicClass
#A Basic Class

class Hello:
    def __init__(self, fname, lname, age):
        self.fname = fname
        self.lname = lname
        self.age = age
        
    def fullname(self):
        self.fname = input("Enter your first name: ")
        self.lname = input("Enter your last name: \n")
        self.age = input("Enter your age: \n")
    
    def nput(self):
        print("Your name is {} {} and your age is {}")
    
print(nput.Hello())
