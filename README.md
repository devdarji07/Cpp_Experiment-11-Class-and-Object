# Experiment: Objects and Classes in C++

## Aim
To understand the concept of **Objects and Classes in C++** and calculate the **Volume of a Cuboid** using different approaches such as direct initialization, user input, and member functions.

---

## Objectives
- To learn the use of **class and object** in C++.
- To explore the role of **data members and member functions**.
- To implement volume calculation using different methods:
  1. Class with user input method.  
  2. Class with direct values assigned inside object.  
  3. Class with a member function for volume.  
  4. Class with encapsulation (private data and public method).  
- To compare different approaches and understand the advantages of **encapsulation and abstraction**.

---

## Theory

### Object-Oriented Programming (OOP) in C++
In C++, OOP allows us to design programs using objects that represent real-world entities.  
The main pillars of OOP are **Classes, Objects, Encapsulation, Abstraction, Inheritance, and Polymorphism**.  
In this experiment, we focus on **Classes, Objects, Encapsulation, and Abstraction**.

### Class and Object
- **Class**: Blueprint or template that defines the structure and behavior of objects.  
- **Object**: Instance of a class (each object has its own data but uses the same functions).  
- Example: In the Cuboid class, `length`, `width`, and `height` are data members, and `volume()` is a member function.

### Encapsulation
- Wrapping data and functions together in a class.  
- Protects data using **access specifiers** (public, private, protected).  
- Example: Private dimensions with a public `volume()` method.

### Abstraction
- Hides unnecessary details and exposes only essential methods.  
- Example: `getVolume()` returns the result without showing calculation details.

### Reusability & Modularity
- Member functions can be reused across multiple objects.  
- Modular code improves readability, maintainability, and reduces redundancy.

---

## Data Members and Member Functions
- **Data Members**: Variables (length, width, height).  
- **Member Functions**: Functions to take input, process data, and return results.  

Examples in this experiment:
- `input()` → Takes user input.  
- `volume()` → Calculates volume.  
- `display()` → Shows result.  

---

## Observations from Different Approaches
- **Public data members**: Simple, but not secure.  
- **Methods for input & calculation**: More modular and user-friendly.  
- **Private members with public methods**: Best practice, ensures encapsulation.  

---

## Importance of Classes in Real-World Programming
- Models real-world entities.  
- Multiple objects coexist with different states but shared behaviors.  
- Foundation for advanced OOP concepts (Inheritance, Polymorphism).  

---

## Key Concepts Learned
- **Encapsulation** → Wrapping of data and functions together.  
- **Access Specifiers** → Control access (`public`, `private`).  
- **Reusability** → Methods reused across objects.  
- **Abstraction** → Hides implementation details.  

---

## Comparison of Programs

| Program Version | Input Method | Data Members Access | Volume Calculation Method | Output Example |
|-----------------|--------------|----------------------|----------------------------|----------------|
| User_Input_Volume_using_ClassMethod | User enters values via method | Public | Member method `volume()` | Volume displayed after input |
| Volume_using_Class_Cuboid | Direct assignment to object | Public | Formula in `main()` | Direct calculation |
| Vol_of_Cuboid_Class_Method | Values initialized in object | Public | Member function `volume()` | Volume returned by method |
| Cuboid with Encapsulation | Private members | Private | Public method `volume()` | Secure calculation |

---

## Program Descriptions

### 1. User Input of Volume using Class and Method
- Takes dimensions from user input.  
- Volume calculated inside class method.  
- Demonstrates interaction between user and object.

### 2. Volume using Class Cuboid
- Values directly assigned to public members.  
- Volume calculated in `main()`.  
- Simple but not secure.

### 3. Vol of Cuboid (Class Method)
- Values initialized directly.  
- Volume returned by a member function.  
- Cleaner than method 2.

### 4. Cuboid with Encapsulation (Private Data)
- Data members private, only accessed through public method.  
- Demonstrates **data hiding** and **best practice**.

---

## Concepts Used
- **Class and Object** → Basic OOP building blocks.  
- **Data Members** → Store dimensions.  
- **Member Functions** → Operate on data.  
- **Encapsulation** → Restricts direct access.  
- **Access Specifiers** → `public` and `private`.  
- **Abstraction** → Hides internal details.  
- **Modularity** → Reusable and readable code.  

---

## Overall Observations
- Public data → Easy but insecure.  
- Input methods → Interactive.  
- Member functions → Improve modularity.  
- Encapsulation → Best method for safety and clarity.  

---

## Conclusion
This experiment helped us understand:  
- The concept of **Objects and Classes** in C++.  
- Different approaches for volume calculation.  
- That **Encapsulation** ensures maximum security and good coding practice.  
- Using classes and objects makes programs more **organized, reusable, and professional**.
