# OOP Lab 

* Create project called `School` it has the main method 

* Create two classes named `Teacher` and `Student`. Each class should contain:
    * At least five attributes
    * A constructor
    * A toString method to display the values of all the attributes of each class

* Edit `Main.java` to check the toString methods you’ve created for each of the classes above. To test the toString methods, create three instances of each class (each with different attribute values) and display them as was done for the Student class.


* Create a class diagram for the following classes:
    * Student
    * Teacher

Example of class diagram 

```
public class Person {
    private String name;
    private int age;

    public Person(String initialName) {
        this.name = initialName;
        this.age = 0;
    }

    public void printPerson() {
        System.out.println(this.name + ", age " +   this.age + " years");
    }
}
```

![UML](UML.webp)
