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
- To define the class, ** class ** keyword is used.

ex:
 class Employee{
         
         data members 
         method Declarations and method definations 
         
 }

`Object`
- Object is an instance of class i.e., it is the real entity.
- Object allocate memory and it can call as many times  as per requirement.
- **new** keyword is to define object of class.
ex:
 Employee emp = new Employee()
 
 `static keyword`
 - static keyword acts as a modifier on attritbutes, methods and inner class.
 - static keyword declares that the attributes or methods is associated with the class as the whole rather than any particular instance of class.
 - The static member are often called as the "class attritbute" or "class method".
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
 - Data member can be access using class name and following the attirbutesName.
 
 `Method`
 - Method contains :
 1. Method Declaration 
 2. Method Defination 
 
 1. Method Declaration 
 - Beside method name it also contains access modifier , return type and list of parameters.
 
  <<access Modifier>> <<return type>> <<Method name>> ( <<list of parameters>> )
  ex :
   public String empDisplay()

2. Method Definition 
- It is the body of method.
- It contains bussiness logic.
ex:
   public String empDisplay(){
          
          // bussiness logic

   }
   
   
`Access Modifier`
- Access modifiers are used to set the accessibility (visibility) of classes.Visibility(Scope) can be within the class, 
  outside the class, within the package and outside the package.  
- Accessbility can be change of the attributes, constructor, setter, method.
- Types:
1. public - scope of public modifier is everywhere i.e., within and outside of package. 
2. protected - scope of protected modifier is within the package but we can access outside of the package if the class is derived class.
3. default - scope of default modifier is with the package.
4. private - scope of the private modifier is within  the class we cannot access outside the class even if it having same package.

![AccessModifier]()




 
 
 
 
 
 
 
