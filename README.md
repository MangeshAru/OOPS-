# OOPS-
- There are 4 pillar of oops.
### Inheritance
### Polymorphism
### Abstraction
### Encapsulation

## Basic Terminology in oops
`Class`
- Class is a blueprint from which object are created.
- Class is a group of similar objects.
- Class is logical entity. Class doesn't allocate memory when it is created.
- To define the class, class keyword is used.

ex:
 class Employee{
         
         data members 
         method Declarations and method definations 
         
 }

`Object`
- Object is an instance of class i.e., it is the real entity.
- Object allocate memory and it can call as many times as per requirement.
- new keyword is to define object of class.
ex:
 Employee emp = new Employee()
 
 `static keyword`
 - static keyword acts as a modifier on attritbutes, methods and inner class.
 - static keyword declares that the attributes or methods is associated with the class as the whole rather than any particular instance of class.
 - The static member are often called as the "class attribute" or "class method".
 - Attribute and Method are access using className.
 
 
 `Data Member(Attributes)`
 - Two type 
 1. Instance Data Member
 2. Static Data Member
 
 `Instance Data Member(Attributes)`
 - Memory will be allocated every time when object is created also called object level attrubutes.
 - It stores specific value.
 - This variable is access by instance reference. i.e., emp.nameofAttributes
 
 `static Data Member`
 - static keyword is used with data member(Attributes).
 - It allocate memory only once also called class level attributes.
 - It store common value.
 - Data member can be access using class name and following the attirbutesName. ex: Employee.empid
 
 `Method`
 - Method contains :
 1. Method Declaration 
 2. Method Defination 
 
 1. Method Declaration 
 - Beside method name it also contains access modifier , return type and list of parameters.
 
  access_Modifier return_type Method_name ( list of parameters )
  ex :
   public String empDisplay()

 2. Method Definition 
 - It is the body of method.
 - It contains bussiness logic.
ex:
   public int calculateSalary(){
          
          // bussiness logic

   }
   
`Concrete class`
 - A concrete class is a class that has an implementation for all of its methods.
`Non-Concrete class`
 - A non-concrete class is a class that has minimum one abstract method.
   
`Access Modifier`
- Access modifiers are used to set the accessibility (visibility) of classes.Visibility(Scope) can be within the class, 
  outside the class, within the package and outside the package.  
- Accessbility can be change of the attributes, constructor, setter, method.
- Types:
1. public - scope of public modifier is everywhere i.e., within and outside of package. 
2. protected - scope of protected modifier is within the class but we can access outside of the class if the class is derived class.
3. default - scope of default modifier is with the package.
4. private - scope of the private modifier is within  the class we cannot access outside the class even if it having same package.

![AccessModifier](https://github.com/MangeshAru/OOPS-/blob/main/AccessModifier.jpg)

 `non-access modifier`
 - static
 - final
 - abstract
 - synchronized
 - transient
 - volatile
 - native
 
 `final`
 - final modifier are for finalizing the implementation of class,methods and attributes.
 - It cannot applied to interface,constructor and enum.
 - final class cannot extend and overriden.
 
 `abstract`
 - Abstract method is method having method declaration but implemented by other class method.
 - If even one method is abstract then class is also abstract.
 - An interface is by default abstract.
 
 `synchronised`
 - A synchronized modifier in java can be applied only with method and block.
 -  In the synchronized method block, only one thread is allowed to execute at a time. It makes thread-safe.
 
 `volatile`
 `native`
 `transient`
 
### static block
 - static block is generally used to initialize the static variable.
 - static block executes only once when the class is loaded (even before the instance is created).
 ex:
  class Employee {
  
  
    stact int empid;
    static{
         empid = empid + 1;
    }
  }
 
### constructor
- constructor is used to create instance of the class.
- It is used to initialize the data member of the class.
- It is similar to method but it has name same as class name and no return type.
- types of constructor:
  - default constructor 
  - no argument constructor 
  - parameterised constructor</br>
  
`default constructor`
  - If the programmer doesn't provide the constructor then compiler provide the default constructor.It is implicitly done by compiler.
 ex:
   class Employee {
   
   
      private int id;
      Employee()  // default constructor
      
  }
 
`parameterised constructor`
  - The explicit constructor that is created by programmer with one or more parameter to initialize instance variable of class.
 ex:
 
  class Employee {
   
   
     int empid;
     int ename;
     employee( int empid, int ename){
          this.empid = empid;
          this.ename = ename;
     }
  }

 `this keyword`
 - refers to the current object in a method or constructor.
## Basic Structure of oops


  <Access_Modifier> class class_name {
                      
                      // data member(argument)
                      Access_Modifier data_type nameOfArgument;
                      //constructor
                      public class_name(no_of_parameter){
                                  // initializing data member
                      }
                      //method
                      access_modifier return_type method_name ( list_of_parameter ){
                                //bussiness logic--implementation 
                      }
   }
 
### Inheritance
 
 `super`
 
### polymorphism
 `Method overloading`
 `Method overriding`
### Abstraction
 `interface`
### Encapsulation
 
 
 
 
 
 
 
 
 





 
 
 
 
 
 
 
