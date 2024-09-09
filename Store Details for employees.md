<img width="688" alt="Screenshot 2024-09-09 at 5 20 36 PM" src="https://github.com/user-attachments/assets/bede075c-e657-4ae8-b033-ae767992ab0b"># Store Details for Employees
create  a class called employee as main template
create many instances or objects from that template for each employee
```
class Employee:
  count=0
  def __init__(self,name,position,salary):
      self.name=name
      self.position=position
      self.salary=salary
      Employee.count+=1
def displayCount(self):
      print("There are %d employees" % Employee.count)
def displayDetails(self):
      print("Name:",self.name,",Position:",self.position,",Salary:",self.salary)

emp1=Employee("Employee1","HR",30000)
emp1=Employee("Employee2","Manager",90000)
emp1=Employee("Employee3","Programmer",50000)
emp1=Employee("Employee4","Engineer",65000)
emp1.displayCount()  
emp2.displayCount()  
emp3.displayCount()  
emp4.displayCount()

emp1.displayDetails()  
emp2.displayDetails()  
emp3.displayDetails() 
emp4.displayDetails()

  ```


 ![Uploading Screenshot 2024-09-09 at 5.20.36 PM.png…]()
