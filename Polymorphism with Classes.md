# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```
class Beans(): 
    def f(self):
        print("Vegetable")
        print("Green")
class Mango(): 
    def d(self):
        print("Fruit")
        print("Yellow")
     #Add your code here      
def func(obj): 
    pass
       #Add your code here
#creating objects
o = Beans() 
o.f()
ob = Mango() 
ob.d()
```
## Output
<img width="741" height="322" alt="Screenshot 2025-10-21 125544" src="https://github.com/user-attachments/assets/7f3ab0c0-89f5-47a6-b492-c31919a0a09d" />

## Result
successfully  created two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.
