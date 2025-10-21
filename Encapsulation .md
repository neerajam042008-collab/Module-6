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
```
class Rectangle:
  __length = 0 #private variable
  __breadth = 0#private variable
  def _init_ (self,length,breadth):
    #constructor
    self.__length = 5
    self.__breadth = 3
  def show(self):
    print(self.__length)
    print(self.__breadth)
 
rect = Rectangle('5','3')
rect.show()
```
## Output
<img width="352" height="234" alt="Screenshot 2025-10-21 125001" src="https://github.com/user-attachments/assets/13b1c01f-dfa7-4869-97f2-f3f34a849c5d" />

## Result
successfully implemented **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.
