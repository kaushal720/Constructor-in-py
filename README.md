# Constructor-in-py
class employee:
    language = "python" # this is a class attribute
    salary = 1200000
    
    def __init__(self, name, salary, language): # dunder method which is automatically called
        self.name = name
        self.salary = salary
        self.language = language
        print("i am creating an object")
        
    def getinfo(self):
        print(f"the language is{self.language}. the salary is {self.salary}") 
    
    @staticmethod
    def greet():
        print("good morning")   
        
kaushal = employee("kaushal", 13000000, "javascript")
#kaushal.name = "kaushal"
print(kaushal.name, kaushal.salary, kaushal.language)
