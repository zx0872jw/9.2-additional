# 9.2-additional

class Employee:
    def __init__(self, name, ID_number, Department, Job_Title):
        self.name = name
        self.ID_number = ID_number
        self.Department = Department
        self.Job_Title = Job_Title
emp_1 = Employee("Susan Meyers", "47899", "Accounting", "Vice President")
emp_2 = Employee("Mark Jones", "39119", "IT", "Programmer")
emp_3 = Employee("Joy Rogers", "81774", "Manufacturing", "Engineer")

print(emp_1.name, emp_1.ID_number, emp_1.Department, emp_1.Job_Title)
print(emp_2.name, emp_2.ID_number, emp_2.Department, emp_2.Job_Title)
print(emp_3.name, emp_3.ID_number, emp_3.Department, emp_3.Job_Title)
