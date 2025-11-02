# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
class R:
 def init(self, l, w):
 self.__l = l
 self.__w = w
 def display(self):
 print(self.__l)
 print(self.__w)
 rect = R(5,3)
 rect.display()
 Thus ,the program executed successfully.
 
## Output
<img width="394" height="203" alt="image" src="https://github.com/user-attachments/assets/97542ad1-d4fa-441b-be7d-375e38497dc0" />

## Result
Thus, the program has been successfully executed.
