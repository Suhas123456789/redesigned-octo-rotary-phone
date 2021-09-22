#creating a class employee
class employee:
 
    # class variable same for all the instances ( objects )
    Company ="Career Dream Education"
 
    def __init__(self,name,age,position):
 
        # instance variable different for different instances.
        self.name = name
        self.age = age
        self.position = position
 
     # class method 
    def get_details(self):
 
        return f"My name is {self.name} and i am {self.age} year old and
                 i am a {self.position} at {self.Company}. "
 
 
#creating an object and passing argument and it taken by init() method automatically
emp1 = employee("John",22,"Software Developer")
 
emp2 = employee("Suhas",22,"Python and Machine learning engineer")
 
