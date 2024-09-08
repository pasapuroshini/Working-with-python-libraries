# Store Details for Employees
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
