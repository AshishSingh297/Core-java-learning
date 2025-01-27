// interface 

// Online Java Compiler
// Use this editor to write, compile and run your Java code online
interface Animal
{
    void sleep();
    void eat();
}

class Dog implements Animal
{
    public void sleep()
    {
        System.out.println("Sleeping");
    }

    public void eat()
    {
        System.out.println("Eating");
    }
}

public class Main
{
    public static void main(String args[])
    {
        Dog obj = new Dog();
        obj.sleep();
        obj.eat();
    }
}
